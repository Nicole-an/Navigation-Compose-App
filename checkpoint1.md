# App Navigation Compose

## Explicação Completa do Projeto

Explicação da MainActivity e da navegação no aplicativo

A classe MainActivity é o ponto de entrada do aplicativo Android e herda de ComponentActivity, sendo responsável por inicializar a interface utilizando Jetpack Compose. Dentro do método onCreate, ocorre toda a configuração inicial da aplicação.

É utilizado o método enableEdgeToEdge() para permitir que o layout ocupe toda a tela. Em seguida, o setContent define a interface com Compose.

Dentro desse bloco, é aplicado um tema para padronizar o visual do aplicativo. O Scaffold é utilizado como estrutura base, organizando o layout e fornecendo controle de espaçamentos através do innerPadding.

O navController é criado para gerenciar a navegação entre as telas. O NavHost define as rotas do aplicativo, começando pela tela de login. Cada rota representa uma tela e pode receber parâmetros, permitindo a troca de informações entre diferentes partes do sistema.

Assim, a MainActivity centraliza toda a navegação e estrutura do aplicativo.

Explicação da tela de Login

A função LoginScreen representa a tela inicial do aplicativo. A interface é construída utilizando um Box, que ocupa toda a tela, possui uma cor de fundo e um espaçamento interno.

No topo, é exibido o título "LOGIN". No centro, há um botão que, ao ser clicado, navega para a tela de menu utilizando o NavController.

Essa tela inicia o fluxo do aplicativo de forma simples e direta.

Explicação da tela de Menu

A função MenuScreen representa a tela principal após o login. Ela utiliza um Box como estrutura base e uma Column para organizar os elementos verticalmente.

No topo, é exibido o título "MENU". No centro, há três botões organizados verticalmente.

O primeiro botão navega para a tela de perfil, enviando nome e idade como parâmetros. O segundo botão leva para a tela de pedidos, enviando o nome do cliente. O terceiro botão retorna à tela de login.

Essa tela funciona como um ponto central de navegação entre as funcionalidades.

Explicação da tela de Pedidos

A função PedidosScreen representa a tela onde são exibidos os pedidos. Ela recebe um parâmetro opcional chamado cliente, que é utilizado para personalizar o conteúdo.

A tela ocupa todo o espaço disponível, possui uma cor de fundo e um espaçamento interno. No topo, é exibido o texto "PEDIDOS" junto com o nome do cliente recebido.

No centro, há um botão que permite voltar para o menu. Essa navegação é feita através do NavController.

Essa tela demonstra o uso de parâmetros opcionais na navegação.

Explicação da tela de Perfil

A função PerfilScreen é responsável por exibir informações do usuário. Ela recebe como parâmetros o nome e a idade, que são obrigatórios e enviados durante a navegação.

A interface é construída utilizando um Box, que ocupa toda a tela, com uma cor de fundo e espaçamento interno.

No topo, é exibido um texto que combina as informações recebidas, mostrando o nome do usuário e sua idade. Isso demonstra como dados podem ser passados entre telas e utilizados dinamicamente.

No centro da tela, há um botão que permite retornar ao menu principal. Ao ser clicado, ele utiliza o NavController para realizar a navegação.

De forma geral, essa tela exemplifica o uso de parâmetros obrigatórios na navegação e a personalização da interface com base nesses dados.

## Funcionalidades
- Navegação entre telas
- Uso do NavController
- Passagem de parâmetros entre telas

## Prints do Aplicativo

### Tela de Login
[Captura de tela 2026-03-21 020554.png](../../Users/nicol/OneDrive/Imagens/Capturas%20de%20tela/Captura%20de%20tela%202026-03-21%20020554.png)

### Tela de Menu
[Captura de tela 2026-03-21 020602.png](../../Users/nicol/OneDrive/Imagens/Capturas%20de%20tela/Captura%20de%20tela%202026-03-21%20020602.png)

### Navegação funcionando
[Captura de tela 2026-03-21 020609.png](../../Users/nicol/OneDrive/Imagens/Capturas%20de%20tela/Captura%20de%20tela%202026-03-21%20020609.png)
[Captura de tela 2026-03-21 020617.png](../../Users/nicol/OneDrive/Imagens/Capturas%20de%20tela/Captura%20de%20tela%202026-03-21%20020617.png)

## Desenvolvido por
Nicole Alves Nogueira

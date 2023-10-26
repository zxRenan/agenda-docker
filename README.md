Aproposta em questão se concentra na criação de um ambiente de desenvolvimento ou implantação usando Docker Compose. Esse ambiente consistirá em três contêineres distintos, cada um desempenhando um papel específico:

Contêiner PHP: Este contêiner é responsável por hospedar e executar o código da aplicação PHP. Ele fornece um ambiente no qual os scripts e aplicativos PHP podem ser executados de maneira isolada, facilitando o desenvolvimento e a implantação de aplicativos baseados em PHP.

Contêiner Nginx: O contêiner Nginx é utilizado como servidor web e atua como um intermediário entre os clientes que acessam o aplicativo e o contêiner PHP. Ele gerencia as solicitações HTTP, fornece roteamento e balanceamento de carga, além de servir arquivos estáticos. Isso é essencial para tornar o aplicativo acessível na web.

Contêiner MySQL: O terceiro contêiner é responsável por hospedar o sistema de gerenciamento de banco de dados MySQL. Ele armazena, gerencia e fornece acesso aos dados do aplicativo, permitindo que o PHP interaja com o banco de dados para armazenar e recuperar informações.

O uso do Docker Compose permite que esses contêineres sejam facilmente configurados, conectados e implantados em conjunto, garantindo que a aplicação PHP, o servidor web Nginx e o banco de dados MySQL funcionem em harmonia. Essa abordagem simplifica o processo de desenvolvimento e implantação de aplicativos, garantindo a consistência do ambiente, independentemente do sistema em que é executado.

O site usado para fins de teste neste exemplo foi obtido a partir do repositório público mantido por Gláucia Lemos, com a devida autorização dela. O repositório em questão está disponível em: https://github.com/glaucia86/projeto.crud.php. O site em questão é um aplicativo de CRUD simples, que funciona como uma espécie de agenda online.
# resumo-do-lab3
Configurando uma instância de Banco de Dados na Azure
Resumo sobre Configuração de uma Instância de Banco de Dados no Azure

Durante o laboratório, aprendi como configurar uma instância de banco de dados no Azure, utilizando o Azure SQL Database, um serviço gerenciado que facilita o processo de criação, administração e escalabilidade de bancos de dados na nuvem.

Primeiro, acessei o Portal do Azure (portal.azure.com), onde posso gerenciar todos os recursos da minha conta. No painel inicial, cliquei em "Criar um recurso" e selecionei a opção "Banco de Dados SQL" para iniciar a configuração da minha instância.

O Azure oferece várias opções de banco de dados, como SQL Database, MySQL, PostgreSQL e outros, mas escolhi SQL Database, que é um banco de dados relacional totalmente gerenciado e baseado no SQL Server. Esse serviço é ideal para aplicações que necessitam de alta disponibilidade, escalabilidade e segurança.

Após selecionar o Banco de Dados SQL, comecei a configurar os detalhes da instância, como o nome do banco de dados, assinatura e grupo de recursos. O grupo de recursos serve para organizar meus recursos dentro do Azure, e por isso, selecionei um grupo já existente ou criei um novo.

Em seguida, configurei o plano de preço da minha instância de banco de dados. O Azure SQL Database oferece diferentes camadas de desempenho, como Basic, Standard, Premium, dependendo das necessidades de desempenho e escala. Eu selecionei a camada que melhor atendia ao meu projeto, levando em consideração a quantidade de armazenamento e o número de DTUs (Database Transaction Units) ou vCores para definir a capacidade da instância.

Para garantir a segurança do banco de dados, configurei as configurações de firewall, permitindo que apenas determinados endereços IPs ou redes possam acessar a instância. Além disso, configurei o Azure Active Directory para autenticação, caso fosse necessário gerenciar o acesso de usuários através de identidades corporativas.

Configurei também as opções de backup, que são fundamentais para garantir a integridade dos dados. O Azure SQL Database realiza backups automáticos e permite configurar pontos de recuperação, além de Geo-Replication, caso fosse necessário criar réplicas do banco de dados em diferentes regiões para alta disponibilidade.

Uma vez criada a instância, aprendi a monitorar o desempenho da instância de banco de dados utilizando o Azure Monitor e o SQL Analytics, onde posso acompanhar métricas importantes como uso de CPU, armazenamento, latência de consultas, entre outras. Também é possível configurar alertas para me avisar caso algo esteja fora dos parâmetros esperados.

Por fim, pude conectar minha aplicação ao banco de dados utilizando strings de conexão fornecidas pelo portal. As strings de conexão contêm os detalhes necessários, como nome do servidor, usuário e senha, para que minha aplicação consiga acessar o banco de dados e realizar operações.

O Azure torna a criação e gerenciamento de bancos de dados extremamente simples e eficiente, proporcionando uma instância de banco de dados escalável, segura e altamente disponível. Com as configurações que fiz, pude garantir que minha instância de banco de dados estivesse bem protegida, com backups automáticos e monitoramento constante, permitindo que eu focasse no desenvolvimento sem me preocupar com a administração da infraestrutura.

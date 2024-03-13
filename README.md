# ponderada_s5

Após seguir as instruções do tutorial fornecido, configurei uma instância EC2 na AWS e a implementei um banco de dados MariaDB na RDS. A aplicação, desenvolvida em PHP, estabelece uma conexão segura com o banco de dados MariaDB para gerenciar informações referentes a empregados. Esta atividade facilitou a interação direta com o banco de dados através de uma interface web, proporcionando uma maneira eficiente e eficaz de armazenar, acessar e manipular dados em tempo real.

### Código desenvolvido

O código PHP é parte de uma aplicação web simples que interage com um banco de dados MySQL para gerenciar dados de empregados. A primeira parte do código estabelece uma conexão com o banco de dados usando credenciais definidas em um arquivo externo (dbinfo.inc). Após estabelecer a conexão, o código verifica a existência da tabela EMPLOYEE, e esta tabela é destinada a armazenar informações sobre os empregados


A segunda parte do código é um formulário HTML que permite ao usuário inserir informações sobre um novo empregado, como nome, endereço, data de nascimento, email e área de trabalho. Após o preenchimento, o formulário pode ser submetido para adicionar os dados fornecidos à tabela EMPLOYEES no banco de dados. Após a submissão, a página é recarregada e os novos dados podem ser processados e adicionados ao banco.

A última parte do código exibe os dados atualmente armazenados na tabela EMPLOYEES, realizando uma consulta ao banco de dados para buscar todas as linhas existentes e exibindo-as em uma tabela HTML. Para cada linha retornada pela consulta, os dados de cada empregado são mostrados em linhas separadas da tabela. Este conjunto de operações demonstra a eficácia da aplicação em gerenciar dados de forma dinâmica, evidenciando a integração bem-sucedida entre a instância EC2, o MariaDB na RDS e a aplicação web desenvolvida.
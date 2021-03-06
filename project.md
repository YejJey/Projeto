# CONTEXTO DE APLICAÇÃO
Uma empresa que atua na área de vendas de produtos e utilidades em geral,
tendo como foco satisfazer os clientes com as vendas de produtos da empresa. É
uma empresa que atende a comunidade local e vizinhanças. Atualmente não possui
qualquer sistema para atender as atividades operacionais ou gerenciais dos seus
processos internos e externos. Os controles de cadastro de cliente, produto e
vendas são feitos manualmente por intermédio de fichas de cadastros.

As formas de armazenamento são feitas da seguinte maneira: a empresa
coloca na ficha de cadastro de cliente o nome da pessoa, produto vendido, valor
total e armazena em uma gaveta, a ficha de cadastro de produtos contém nome do
produto, quantidade, valor de entrada e valor de saída, na qual é armazenada da
mesma forma. Não tem uma ficha em especial para o controle de vendas, pois ela é
registrada na mesma ficha do cliente, contendo o nome do produto, quantidade e
valor da venda.

## 1 Levantamento de Requisitos e Riscos
Será abordado também além dos requisitos, os riscos apresentados sob o
domínio do problema da empresa. Estes riscos devem ser levantados e apontados,
para contra pôr a não utilização de nenhum software que controle os processos e
informações relevantes, além das necessidades apresentadas pelos usuários. Ou
seja, o que você poderá apresentar como riscos?

### 1.1 Problemas Existentes
A empresa possui apenas o sistema manual para o controle de cadastro de
cliente, produto e estoque. Esse cenário dificulta a gerência da empresa e gera
perdas de tempo no atendimento dos clientes e dificuldades de controle das vendas.
Todos os produtos vendidos são anotados na ficha do cliente ou em qualquer outro
rascunho disponível, caso não exista uma ficha com seus dados cadastrais. Em
determinados momentos, os funcionários esquecem-se de anotar as transações,
tornando vulnerável a organização dos produtos da loja. Após a entrada e a saída de
produtos, funcionários atualizam o estoque manualmente, havendo dificuldades para
realizar esse controle e desperdício de tempo na execução das tarefas.

Os problemas existentes na empresa podem ser resumidos em:
- Falta de controle de estoque: a empresa vende um produto e tem a
dificuldade de saber quantos produtos tem no estoque.
- Falta de controle de clientes: o cadastro é feito em fichas de papel,
tendo assim, dificuldade para organizá-las. A possível perda de fichas é
uma preocupação.
- Falta de controle com as transações dos produtos: não existe controle
preciso de produtos no estoque no momento da compra ou venda.
- Falta de relatórios: não existem formas de visualização de relatórios,
com isso, a empresa fica vulnerável com relação às suas informações.

### 1.2 Desejos do Cliente
Durante o processo de levantamento de requisitos, o cliente manifestou
alguns desejos, entre eles implantar um sistema que possa disponibilizar com maior
facilidade a realização dos cadastros de clientes e produtos e ter um controle de
estoque, para saber o que existe na empresa de produtos. O cliente também
gostaria de um sistema que gerasse relatórios da movimentação da empresa, de
modo a fornecer maior confiança às suas negociações.
Além de obter relatórios mais precisos e ágeis, esse sistema forneceria maior
apoio aos processos de vendas da empresa, visto que controlará todas as
movimentações de compras e vendas, aumentando assim a clareza de informações
e auxiliando para o contínuo crescimento da empresa. 

A lista seguinte aponta um conjunto de desejos manifestados pelos usuários:
- Ter um controle de cadastro de clientes
- Ter um controle de cadastro de produtos
- Ter um controle de estoque
- Ter um controle nas transações de compra e venda
- Melhorar organização da empresa com relatórios precisos
- Tornar o trabalho mais fácil e rápido

### 1.3 Soluções Alternativas
A melhor solução para este problema seria a criação um software de sistema de controle financeiro, capaz de atender as demandas da empresa sem a necessidade de ser operada por um funcionário especializado em excel e geração de relatórios de maneira simplificada e prática de ser lida e reutilizada

### 1.4 Solução Escolhida
O software que seria criado para esse propósito organizaria todas as informações da empresa como os usuários (Cliente e funcionário), fornecedores, o produto em relação ao controle de entradas, saídas, notas fiscais, estoque e ate mesmo os contratos da empresa em relação a todos os anteriores citados. Seria gerado relatórios impressos e online em tempo real com todas essas informações de maneira rápida e prática, sem a necessidade de muito conhecimento em excel por parte do responsável pela empresa.

### 1.5 Impactos do Sistema na Organização
Com esse software serão gerados relatórios a respeito do controle de estoque através do controle de entrada e saída, irá alertar ao responsável se haverá a necessidade de contato com o fornecedor para o preenchimento de mais produtos, notas fiscais serão geradas automaticamente para o cliente no ato da compra e será tudo devidamente registro em sistema para futuras análises ou impressão de relatórios. A empresa ficará ciente da situação de todos os funcionários, como registro de ponto, se estão trabalhando de maneira efetiva mediante a sua função. Em casos de faltas sem justificativa, atrasos ou saídas antecipadas sem a autorização do responsável do setor, será gerado relatórios a respeito do débito de horas do funcionário.

## 2 Elaboração e Especificação


### 2.1 Definição dos Atores
As pessoas que vão interagir com a aplicação, são as partes interessadas, ou seja, quem solicitou a aplicação. Como também o sistema terá que ter suporte e possíveis atualizações, também será utilizado por nossa empresa que é quem ficará responsável por esse tipo de serviço. Futuramente, com a expansão do sistema, a meta é produzir um site onde que o cliente final também possa interagir com o sistema, assim podendo fazer um cadastro, atualizar suas informações e verificar possíveis descontos disponíveis.

### 2.2 Lista de Requisitos
O sistema em si terá uma tela inicial que dará as opções:

* Cadastrar nova compra, onde estará listados todos os produtos comprados por um cliente específico; 

* Opção de cadastrar cliente, que será utilizado tanto pelo caixa, que será realizado um cadastro rápido com o Nome e CPF por praticidade, quanto pelos terminais, que terá as opções de atualizar o cliente; 

* Opção de cadastrar produto, onde será realizado a inserção de produtos no estoque;

* Opção de solicitar pedido para que seja feita a solicitação de pedido para um fornecedor especifico;

* Opção de gerar relatório, onde que nessa opção a administração da empresa terá como extrair e visualizar os relatórios da quantidade de compras que foram realizadas no mês, valor total faturado dentro de um período, quais produtos saíram mais dentro de um período, falta de produto em estoque, quantos pedidos de produtos para os fornecedores foram realizados, todo tipo de nota fiscal para melhorar o controle dos contadores.

### 2.3 Diagrama de Caso de Uso

![Diagrama de caso de uso - Projeto Carlos](https://user-images.githubusercontent.com/64055734/81449840-85ba9000-9157-11ea-88f1-c12fc78804b7.png)

### 2.4 Diagrama de Classes (Em construção)

![Projeto - Diagrama de classe](https://user-images.githubusercontent.com/64055734/81449898-ac78c680-9157-11ea-9446-30c8182d26e6.png)

### 2.5 Diagrama de Telas (Em construção)

![DIagrama de TElas](https://user-images.githubusercontent.com/64055734/81008175-e335a080-8e28-11ea-9e69-7e3790fff2af.png)


### 2.6 Diagramas de Atividade (Em construção)

#### - Realizar Pedido

![Diagrama de Atividade - Realizar Pedido](https://user-images.githubusercontent.com/64055734/82265101-9bd90500-993c-11ea-8a70-5baa46eb990c.png)

#### - Pesquisa de Produtos e Pedidos

![Diagrama de Atividade - Pesquisa de Produtos e Pedidos](https://user-images.githubusercontent.com/64055734/82265198-cf1b9400-993c-11ea-9619-9a1ea657282b.png)

#### - Realizar Compras

![Diagrama de Atividade - Realizar Compras](https://user-images.githubusercontent.com/64055734/82843444-82433a80-9eb3-11ea-843d-8c36230114a2.png)

#### - Gerar Relatórios

![Diagrama de atividade - Gerar Relatórios](https://user-images.githubusercontent.com/64055734/82845985-22519180-9ebd-11ea-80c3-be0f32a1657a.png)

### 2.7 Diagramas de Sequência (Em construção)

#### - Realizar Pedido

![Diagrama de Sequência - Realizar Pedido](https://user-images.githubusercontent.com/64055734/82843619-0ac1db00-9eb4-11ea-8e2a-f604c4c83097.png)

#### - Pesquisar Produto

![Diagrama de Sequência - Pesquisar Produto](https://user-images.githubusercontent.com/64055734/82843598-01387300-9eb4-11ea-9c1d-b11549620882.png)

#### - Realizar Compras

![Diagrama de Sequência - Realizar Compras](https://user-images.githubusercontent.com/64055734/82843584-f41b8400-9eb3-11ea-860c-58a8edff855f.png)

### 2.7 Protótipo Interativo

https://www.figma.com/proto/jUkv5MCvoXKSSowIB5uyaa/Prot%C3%B3tipo-mercado?node-id=9%3A2&viewport=462%2C341%2C0.56033855676651&scaling=min-zoom

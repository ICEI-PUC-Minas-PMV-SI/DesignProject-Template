
# 3 DOCUMENTO DE ESPECIFICAÇÃO DE REQUISITOS DE SOFTWARE

Nesta parte do trabalho você deve detalhar a documentação dos requisitos do sistema proposto de acordo com as seções a seguir. Ressalta-se que aqui é utilizado como exemplo um sistema de gestão de cursos de aperfeiçoamento.


### 3.1 Objetivos deste documento

Descrever e especificar as necessidades da Coordenação do Curso de Sistemas de Informação da PUC Minas que devem ser atendidas pelo projeto SCCA – Sistema de Cadastro de Cursos de Aperfeiçoamento.

### 3.2 Escopo do produto

3.2.1 Nome do produto e seus componentes principais
O produto será denominado SCCA – Sistema de Cadastro de Cursos de Aperfeiçoamento. Ele terá somente um componente (módulo) com os devidos elementos necessários à gestão de cursos.

3.2.2 Missão do produto
Gerenciar informações sobre a oferta de cursos de aperfeiçoamento, gerenciar a composição das turmas, alunos, professores e matrículas. 

3.2.3 Limites do produto
O SCCA não fornece nenhuma forma de avaliação de alunos, pagamento de parcelas do curso, pagamento a professore e agendamentos. O SCCA não contempla o atendimento a vários cursos de Sistemas de Informação de outras unidades da PUC Minas.

3.2.4 Benefícios do produto

|#|Benefício|	Valor para o Cliente|
|------|-----------------------------------------|----| 
|1	| Facilidade no cadastro de dados	|Essencial|
|2 | Facilidade na recuperação de informações	|Essencial|
|3	| Segurança no cadastro de matrículas	|Essencial|
|4 |	Melhoria na comunicação com os alunos	|Recomendável|

### 3.3 Descrição geral do produto

3.3.1 Requisitos Funcionais

|Código	|Funcionalidade|	Descrição|
|------|-----------------------------------------|----| 
|RF1|	Gerenciar Curso de Aperfeiçoamento|	Processamento de Inclusão, Alteração, Exclusão e Consulta de Cursos de Aperfeiçoamento|
|RF2|	Gerenciar Professor|	Processamento de Inclusão, Alteração, Exclusão e Consulta de professores|
|RF3|	Gerenciar Matrícula |	Processamento de Inclusão, Alteração, Exclusão e Consulta de Matrículas de alunos em Cursos de Aperfeiçoamento|
...	...	...

### 3.3.1 Requisitos Não Funcionais

|Código| 	Restrição|	Descrição|
|------|-----------------------------------------|----| 
|RNF1|	Ambiente|	O ambiente operacional a ser utilizado é o Windows XP|
|RNF2|	Ambiente|	O sistema deverá executar em um computador configurado com uma impressora de tecnologia laser ou de jato de tinta, a ser usada para impressão dos relatórios|
|RNF3|	Segurança|	O produto deve restringir o acesso por meio de senhas individuais para o usuário|
...	...	...

### 3.3.2 Usuários 

Descrição
|#|	Ator	|Definição|
|------|-----------------------------------------|----|
|1|	Coordenador|Usuário gerente do sistema responsável pelo cadastro e manutenção de cursos de aperfeiçoamento. Possui acesso geral ao sistema|
|2|	Secretaria|	Usuário responsável por registros de alunos, professores, turmas e gerência de matrículas|
...	...	...

...	...	...



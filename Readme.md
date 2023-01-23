# SQLPowerArchitect-ModelagemDeDados-ClubeDoLivro
Projeto de Modelagem de Dados com intuito de montar e preparar um banco de dados eficiente para operar no _SGBD (Sistema Gerencial de Banco de Dados) SQL.


<h2 style="color:red">Ferramentas Utilizadas no Projeto:</h2>
- Word: Como forma de descrever e simular uma entrevista com a área, de forma que possamos entender as regras de negócio.<br>
- brModelo: Elaboração do modelo conceitual e lógico.<br>
- SQL Power Architect: Elaboração do modelo físico.


<br>O objetivo inicial, antes iniciar as praticas no SGBD relacional SQL, é a elaboração dos projetos que irão realizar a contrução do Mini-Mundo. Para isso, passaremos por 4 etapas fundamentais para a construção de um banco de dados eficiente e organizado.

<br>

1 - Criação do mini-mundo: O recorte do mundo real que possui o processo de abstração, focando em tudo que for relevante para a área de negócio. A área de negócio, por sua vez, irá descrever de forma detalhada o processo e regras de negócio envolvidas no projeto. Com esse entendimento entre as equipes, é feito o MER ( Modelo Entidade Relacional) cujo o objetivo é determinar as ligações, entidades e carácteristicas.
Com a criação do MER, é feito o DER (Diagrama Entidade Relacionamento) que tem como foco pegar a decrição do MER e representar graficamente para melhorar o entedimento das relações.

<br>

2 - Modelo Conceitual: O modelo conceitual será feito na ferramenta brModelo onde iremos melhorar o DER, utilizando uma linguagem de alto nível, para descrever visualmente as entidades fortes e fracas, atributos, chaves primarias/identificadores, associações relativas, especializações, valores atómicos ou multivalorados e a relação entre eles.
<br>
![modeloconceitual](https://user-images.githubusercontent.com/88864793/214097111-15208fbd-865c-4938-a6fc-5953102b8303.png)

3 - Modelo Lógico: Os modelos lógicos se preocupam com os tipos, atributos e relacionamentos das entidades (as informações em si) que habitarão o sistema.
<br>
![modelologico](https://user-images.githubusercontent.com/88864793/214096641-4c5bdade-8225-4335-a19f-f9677db4a7b6.png)


4 - Modelo Físico: Representa o 3º estágio da modelação, onde o modelo físico enriquece modelo lógico com detalhes que são extremamente importantes para a implementação, como por exemplo, o tipo de dado, o numero de caracteres suportados, se aceita valores nulos ou não, etc. 

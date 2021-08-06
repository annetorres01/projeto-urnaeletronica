# Trabalho de PI: Urna eletrônica
Trabalho desenvolvido durante a disciplina de projeto integrador

# Sumário
### 1. COMPONENTES<br>
Integrantes do grupo<br>
Anne Louise Silva Torres: annelouise1106@gmail.com<br>
Fernanda Pereira de Assis: fernandap.deassis@gmail.com<br>
Milena Silva Loureiro: milenaloureirosilva@gmail.com<br>

### 2.INTRODUÇÃO E MOTIVAÇAO<br>
Este documento contém a especificação do projeto integrador urna eletrônica 
<br> O objetivo desse sistema é facilitar a escolha de candidatos a um cargo por meio de uma votação eletrônica <br>
### 2.MINIMUNDO<br>

O programa desenvolvido é a simulação de uma urna eletrônica, que poderá ser usada de diversas maneiras, seja em uma votação para cargos em uma empresa, ou na escolha de um diretor em escolas. A simulação tem o intuito de facilitar as concorrências, e proporcionar mais segurança aos usuários. Para a urna eletrônica ter 100% de aproveitamento é preciso informar alguns dados, como: Nome do candidato, CPF do candidat, número eleitoral, data de nascimento,idade do candidato,matrícula do candidato, nome dos votante, cpf do votante, edereço do votante, matrícula do votante, função exercida pelo votante e a escolha do candidato de cada eleitor.Após a  inserção dos dados a urna irá calcular a quantidade de votos que cada candidato teve e informar o resultado ao responsável pela votação. É importante lembrar que cada eleitor votará apenas uma vez em 1 único candidato.
Após escolher o seu candaidato o sistema retornará os dados do escolhido para confirmação do voto como forma de auditar a eleição.


### 3.RASCUNHOS BÁSICOS DA INTERFACE (MOCKUPS)<br>

![image](https://user-images.githubusercontent.com/88466893/128277278-63d57460-af82-4c30-9dbb-a473070448ba.png)


#### 3.1 QUAIS PERGUNTAS PODEM SER RESPONDIDAS COM O SISTEMA PROPOSTO?
* Relatório que informe quais são os candidatos ao cargo incluido as seguintes informações: nome do candidato, cpf do candidato, matrícula do candidato, idade do candidato e número do candidato.
* Relatório que informe os dados dos votantes incluindo as seguintes informações: nome do votante, cpf do votante, endereço do votante, matrícula do votante, função exercida pelo votante e a escolha do candidato do votante.


### 4 TABELA DE DADOS DO SISTEMA:
   https://docs.google.com/spreadsheets/d/1aT2AxWSsNnTO1J_Ju3kJGb8jjKlWov5A3LmBYEtSwl8/edit#gid=0
    
 ### 5.PMC<br>
![image](https://user-images.githubusercontent.com/88466893/128278510-bdc8c61a-22d4-4398-9f94-9e68c4c2a690.png)


### 6.MODELO CONCEITUAL<br>
  ![image](https://user-images.githubusercontent.com/88466893/128507446-0c2f9dcb-efbb-4e83-86b7-513ccaefa138.png)

      
    
#### 6.1 Descrição dos dados 
    [objeto]: [descrição do objeto]
    
    Eleitor: Tabela que armazena as informações relativas ao funcionário<br>
    CPF: campo que armazena o número de Cadastro de Pessoa Física para cada funcionário da empresa.<br>
    Endereço: campo que armazena o endereço do funcionário.<br>
    Nome: campo que armazena o nome do funcionário<br>
    Matrícula: identificador do funcionário<br>
    Escolha do funcionário: campo que armazena o número referente ao candidato escolhido pelo funcionário<br>
    
    Candidato: Tabela que armazena as informações relativas ao candidato<br>
    CPF: campo que armazena o número de Cadastro de Pessoa Física para cada candidato da empresa.<br>
    Idade: campo que armazena a idade do candidato.<br>
    Nome: campo que armazena o nome do candidato<br>
    Matrícula: identificador do candidato<br>
    Número: campo que armazena o número do candidato<br>
    
    
    Empresa: Tabela que armazena as informações relativas a empresa<br>
    Endereço: campo que armazena o endereço da empresa.<br>
    Razão social: campo que armazena o nome da empresa<br>
    CNPJ : Campo que armazena o número do Cadastro Nacional de Pessoa Jurídica da empresa<br>
    Cargo ofertado: vaga que o candidato está concorrendo na empresa<br>
### 7	MODELO LÓGICO<br>
        a) inclusão do esquema lógico do banco de dados
        b) verificação de correspondencia com o modelo conceitual 
        (não serão aceitos modelos que não estejam em conformidade)
### 8	MODELO FÍSICO<br>
        a) inclusão das instruções de criacão das estruturas em SQL/DDL 
        (criação de tabelas, alterações, etc..) 
        

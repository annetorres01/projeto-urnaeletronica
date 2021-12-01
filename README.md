# Trabalho de PI: Urna eletrônica
Trabalho desenvolvido durante a disciplina de projeto integrador

# Sumário
### 1. COMPONENTES<br>
Integrantes do grupo<br>
Anne Louise Silva Torres: annelouise1106@gmail.com<br>
Fernanda Pereira de Assis: fernandap.deassis@gmail.com<br>
Milena Silva Loureiro: milenaloureirosilva@gmail.com<br>

### 2.INTRODUÇÃO E MOTIVAÇAO<br>
Este documento contém a especificação do projeto integrador do tema votoção eletrônica 
<br> O objetivo desse sistema é facilitar a votação de ideias/candidatos por meio de uma votação eletrônica <br>
### 2.MINIMUNDO<br>

O sistema desenvolvido é uma votação eletrônica, que poderá ser acessado via Web ou Aplicativo (VOTE AQUI), o intuito é que seja usado para votação de uma eleição de pequeno porte (sindicatos,grêmios estudantis, cargo de empresas, etc) ou para votação de ideias (obras em um bairro - associações comunitárias, palestrante que deve ser convidado para um evento - grêmio estudantil). O objetivo desse sistema é tornar o processo de votação dinâmico, intuito, prático, reduzir custos e propocionar maior segurança aos usuários. Para a votação eletrônica ter 100% de aproveitamento é preciso que haja um organizador que insira no banco de dados as informações dos candidatos (número, cpf, nome) ou propostas (imagem, título, descrição) além dos dados dos votantes (cpf e nome). Após a  inserção dos dados a votção será iniciada e cada eleitor fará o login para poder votar, quando receber a permissão irá escolher seu candidato ou decisão. Cada eleitor só poderá fazer uma escolha. Depois de todos votarem o sistema calculará o candidato/decisão vencedora e exibirá na tela.

### 3.RASCUNHOS BÁSICOS DA INTERFACE (MOCKUPS)<br>

![image](https://user-images.githubusercontent.com/88466893/128277278-63d57460-af82-4c30-9dbb-a473070448ba.png)


#### 3.1 QUAIS PERGUNTAS PODEM SER RESPONDIDAS COM O SISTEMA PROPOSTO?
* Relatório que informe quais são os candidatos ao cargo incluido as seguintes informações: nome do candidato, cpf do candidato e número do candidato.
* Relatório que informe os dados dos votantes incluindo as seguintes informações: nome do votante, cpf do votante, email do votante  e a escolha do candidato do votante.


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
        

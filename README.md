<!-- PROJECT LOGO -->
<div align="center">
   <a href="https://github.com/othneildrew/Best-README-Template">
      <img src="https://github.com/Dev-Team-04/Sistema-de-Gerenciamento-de-Ferramentas/blob/versao_final/estacio_sem_nome.ico" alt="estacio logo" width="80"                  height="80">
   </a>
    <h1 align="center">FACULDADE ESTÁCIO</h1>
     <hr>
</div> 

* DESENVOLVIMENTO FULL STACK
* PROJETO INTEGRADOR - MUNDO 02
* DISCIPLINA: Projeto Front-End om Framework e CRUD
* MISSÃO CERTIFICAÇÃO – PROGRAMADOR FRONT-END

<hr>

 <h1 align="center"> DEV TEAM 02 </h1>
 <hr>

* [ANDRE LUIZ FERREIRA DE SOUZA](https://github.com/adventureandre) - MATRICULA: 202208604943
* [JEFFERSON PONTE PESSOA](https://github.com/jeffersonkako) - MATRICULA: 202208291228
* [MARCO BAROZZI](https://github.com/msbzz) - MATRICULA: 202211381232
* [AMANDA DUQUE KAWAUCHI](https://github.com/madukisp) - MATRICULA: 202209170254
* [EMERSON GREGORIO ALVES](https://github.com/Gregdev22) - MATRICULA: 202209084986
* [NELSON CARVALHO DE LIMA JUNIOR](https://github.com/MamboDark) - MATRICULA: 202208353568

 <h1 align="center"> ⚙️Descrição da Missão  </h1>
 <hr>


<h3>Seu desafio será criar uma aplicação web de lista de afazeres (“to-do list”). Os requisitos que a aplicação deve ter, são: </h3>

* Incluir título na aba do navegador, para que o usuário encontre a sua aplicação no meio das várias abas que constantemente mantém abertas; 

* Incluir um cabeçalho dentro da página, para que o usuário saiba facilmente em que página se encontra e do que se trata o conteúdo; 

* Inserir um ícone na aba do navegador; 

* Disponibilizar um campo de texto para digitar o nome de uma nova atividade a ser adicionada à lista; 

* Disponibilizar um botão para adicionar uma nova atividade à lista; 

* Disponibilizar uma lista contendo as atividades já inseridas; 

* Cada linha da lista deve conter:  

    - o texto que o usuário digitou ao cadastrar a atividade; 
    - checkbox ou botão para o usuário marcar que a atividade já foi realizada;  
    - um botão para excluir a atividade da lista caso desejado. 

* Quando o usuário marcar uma tarefa como realizada, o texto daquela linha deve ser tachado (line-through); 
* Disponibilizar um README documentando racional, e qualquer coisa que queira documentar sobre o sistema e principalmente como iniciá-lo. 

 <h1 align="center"> 🌟 Bônus da Missão Certificação (Não obrigatórios)  </h1>
 <hr>

* A lista deve ser salva no "localStorage" do navegador (incluindo quais itens já foram realizados), e deve ser carregada sempre que a página for reaberta. 

* Categorizar os itens da lista. 

* Ser possível reordenar os itens da lista. 

* Guardar os dados em um banco de dados. 

* Incluir/remover anexo as tarefas. 

* Disponibilizar um Dockerfile ou compose com instruções de como iniciar o sistema. 

 <h1 align="center"> ⚒ APLICAÇÃO ⚒ </h1>
 <hr>

## Configuração do Ambiente
   
   #Porta do app
   
    A porta da aplicação esta configurada para 3000 (padrão).

##Persistência dos dados

   O projeto foi desenvolvido para persistir seus dados tanto para Localstorage (modo default) assim como para o banco MongoDb estando instalado , para isso bastaria configurar as informações pertinentes ao banco em .env  e ativar a opção ATIVE_DB= true em 'setDB.ts'
porem devido a problemas tecnicos com mudança de versão do NextJs de ultima hora, não foi possível concluir a adaptação do acesso ao mongoDB a tempo.     
  
## Tecnologias

. NextJs

. TailWindcss

. Java Script

. MongoDb

. Type Script

### Instalação utilizando docker
Siga as etapas abaixo para configurar o ambiente:

1. Clone este repositório:
   ```shell
   git clone https://github.com/adventureandre/missao-mundo2

2. Execute o Docker:
   ```shell
   docker-compose up -d

### Instalação
Siga as etapas abaixo para configurar o ambiente:

1. Clone este repositório:
   ```shell
   git clone https://github.com/adventureandre/missao-mundo2

2. Execute o NPM INSTALL:
   ```shell
   npm i
   

3. Rode o projeto :
   ```shell
   npm run dev

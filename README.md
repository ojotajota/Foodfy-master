<h1 align="center">
  <a href="https://github.com/abner-starkasty/Foodfy/raw/master/readme-assets/chef.png">
  <img 
    src="/readme-assets/chef.png"
    width="200px"
    alt="Logo do LaunchBase">
</h1>

<h4 align="center">
  🍕🍗  FoodFy 🚀
</h4>

<p align="center">
  <a href="https://www.linkedin.com/in/juscelino-j%C3%BAnior-19aab5113/">
    <img 
      alt="Made by Juscelinio Júnior" 
      src="https://img.shields.io/badge/MADE%20BY-Juscelino%20Junior-%230077b5?style=flat-square&logo=linkedin">
  </a>
  
  <a href="https://rocketseat.com.br/">
    <img 
      alt="Instituição de Ensino" 
      src="https://img.shields.io/badge/-Rocketseat-%237159c1?style=flat-square&logo=apache-rocketMQ&logoColor=White">
  </a>

  <a href="https://www.javascript.com/">
    <img 
      alt="JavaScript" 
      src="https://img.shields.io/badge/STACK-JavaScript-%23F7DF1E?style=flat-square&logo=JAVASCRIPT">
  </a>

  <a href="https://www.postgresql.org/">
    <img 
      alt="Postgresql" 
      src="https://badgen.net/badge/icon/postgresql?icon=postgresql&label">
  </a>
  
  
### 🔖 Sobre

O projeto **Foodfy** é um site de receitas culinárias. Esse projeto foi proposto como desafio durante o **Bootcamp LaunchBase** lecionado pela **Rocketseat**, com o intuito de colocar em prática todo o conhecimento adquirido. O projeto foi desenvolvido em várias etapas conforme a evolução no curso.


------
### 🛠 Tecnologias utilizadas

<p align="center">
As seguintes ferramentas foram usadas na solução dos desafios:

<p align="center">
    <a href="https://www.javascript.com/">
        <img 
            src="/readme-assets/icon-javascript.svg" 
            alt="logo JavaScript"
            width="50px"
            style="border-radius: 8px;">
    </a>
    <a href="http://www.ecma-international.org/ecma-262/6.0/">
        <img 
            src="/readme-assets/icon-ecmascript6.svg" 
            alt="logo ECS6"
            width="50px"
            style="border-radius: 8px;">
    </a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/CSS">
        <img 
            src="/readme-assets/icon-css3.svg" 
            alt="logo CSS3"
            width="50px"
            style="border-radius: 8px;">
    </a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML">
        <img 
            src="/readme-assets/icon-html5.svg" 
            alt="logo HTML5"
            width="50px"
            style="border-radius: 8px;">
    </a>
    <a href="https://mozilla.github.io/nunjucks/">
        <img 
            src="/readme-assets/icon-nunjucks.svg" 
            alt="logo HTML5"
            width="52px"
            style="border-radius: 8px;">
    </a>
    <a href="https://nodejs.org/en/">
        <img 
            src="/readme-assets/icon-nodejs.svg" 
            alt="logo Node.js"
            width="50px"
            style="border-radius: 8px;">
    </a>
    <a href="https://expressjs.com/">
        <img 
            src="/readme-assets/icon-express2.png" 
            alt="logo framework express"
            width="85px">
    </a>
    <a href="https://git-scm.com/">
        <img 
            src="/readme-assets/icon-git.svg" 
            alt="logo git"
            width="50px">
    </a>
    <a href="https://github.com/">
        <img 
            src="/readme-assets/icon-gitHub2.svg" 
            alt="logo git"
            width="50px">
    </a>
    <a href="https://www.postgresql.org/">
        <img 
            src="/readme-assets/icon-postgresql.svg" 
            alt="logo postgreSQL"
            width="50px">
    </a>
    <a href="https://code.visualstudio.com/">
        <img 
            src="/readme-assets/icon-vscode.svg" 
            alt="logo vsCode"
            width="50px">
    </a>
</p>

##### 👉 Ferramentas necessárias:
- Editor:
    - [Vscode](https://code.visualstudio.com/) foi utilizado nesse projeto; 
- [Node.Js](https://nodejs.org/en/) - Instalado em sua máquina;
- [Git](https://git-scm.com/downloads) - Instalado em sua máquina;

##### 👉 Após instalar as ferramentas:

## `Como Utilizar:`

1. Baixe [o projeto] com:
    * `git clone()`
    # Clonar repositório
    $ git clone https://github.com/ojotajota/Foodfy-master
    
    **ou**
    
    * Baixe o projeto como _zip_.

2. Execute **`npm install`** no terminal para instalar as dependências deste projeto.

3. Configure o acesso ao Banco de dados (utilizando o Postgres), no arquivo __src/config/db.js__

4. Caso não possua o banco foodfy com suas tabelas criado, execute os comandos presente no arquivo foodfy.sql.

5. Após configurar o arquivo _db.js_ e criar o banco, execute o arquivo seed.js (`node seed.js`) para popular alguns dados e testar a aplicação.

6. Execute `npm start` para iniciar a aplicação. Abra o navegador em (**http://localhost:5000/**)
    * Obs: ***Tome Cuidado*** ao __excluir__ as entidades, pois _**a grande maioria das imagens**_ serão compartilhadas entre si, caso exclua algum chefe, usuário ou receita, reponha uma imagem como padrão no caminho **public/images/recipes-and-chefs/**, sendo __chefs.jpg__ para chefes e __recipes.png__ para receitas.

### Um pouco mais de arroz

Para utlizar o serviço de email, configure o [mailtrap] no arquivo **src/lib/mailer.js**, colocando suas credenciais.

Todas as senhas do seed.js são padronizadas ('123'), pegue um email da tabela users e utilize um usuário na rota de login (`/users/login`).

Considere em limpar o banco eventualmente, executando os comandos finais do arquivo **foodfy.sql** (está na tag `--restart to run seed.js`).


### 👨‍💻 Desenvolvedor

<p align="center">
    <a href="https://app.rocketseat.com.br/me/juscelino-de-melo-costa-junior-1585162196">
        <img 
            style="border-radius: 50%;" 
            src="https://avatars2.githubusercontent.com/u/50853522?s=460&u=683e8a27c25840fc488651ba112accb3e74a75fa&v=4" 
            width="120px;" 
            alt="Foto">
        <br/>
        <sub><b>Juscelino Júnior🚀</b></sub>
    </a>
</p>
</br>
<h6 align="center">
    Feito com 💜 por Juscelino Júnior 🙌 
</h6>

<p align="center">
    <a href="https://www.linkedin.com/in/juscelino-júnior-19aab5113/">
        <img 
            alt="Linkedin Juscelino Junior" 
            src="https://img.shields.io/badge/-Juscelino%20Junior-%230077b5?style=flat-square&logo=linkedin">
    </a>
    <a href="https://www.facebook.com/juscelinomcjunior/">
        <img 
            alt="facebook Abner Willys" 
            src="https://img.shields.io/badge/-Juscelino%20Junior-%234267b2?style=flat-square&logo=facebook&logoColor=white">
    </a>
    
</p>

# doeaki-senac
**Projeto Integrador 2ª Entrega**

**GRUPO:13**

Fabio Yoshihara Suehara

Julio Martini Marcelo Soares

Mariana Moraes Costa

Rafael Rodrigues Amaro Nunes

Robson Aparecido Ramos


# Projeto DoeAki
Portal que reúne ONGs que prestam auxílio em desastres ambientais e voluntários em potencial.

# O MVP foi desenvolvido como mobile-first
Para visualizá-lo como foi projetado, ao abrir a página inicial, clicar com botão direito > Inspecionar > Clicar no ícone de celular para ter a visão mobile


## Ferramentas utilizadas:
### Front:
* HTML, CSS, Javascript
* Biblioteca Axios
### Back:
* Node.js,
* Bibliotecas Express, Sequelize, Nodemon
### Dados:
* MySQL



Para rodar o projeto localmente é necessário ter instalado:
Criar um banco de dados vazio e executar o arquivo app.js sem o "brute force" comentado para criar as tabelas com os campos vazios. 
Em seguida comentar a linha: “models.js:43” novamente.
Inserir os dados cadastrais no arquivo signup.js:http://localhost:5000/cadastro

* Node.js (pode ser necessário adicionar o node à variável de ambiente PATH)
* MySQL Server e o serviço rodando (no Windows > Iniciar+R > services.msc > MySql > Botão direito e Iniciar)
* Rodar a query do arquivo doeaki.sql no terminal do MySql para criar o banco de dados e as tabelas
* Abrir o terminal na pasta com os arquivos e digitar: npm start
* 


### Melhorias
Algumas melhorias já foram mapeadas e tornariam o código mais eficiente:
* Implementação de uma template engine, como Handlebars, para diminuir a repetição de código HTML
* SCSS para diminuir a repetição de código e otimizar a renderização
* Rotina que cria o banco de dados e as tabelas apenas ao inicializar o npm, sem ser necessário rodar uma query

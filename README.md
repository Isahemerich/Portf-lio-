# Portfolio
Este projeto consiste em um site de portfólio desenvolvido utilizando HTML, CSS e JavaScript.

O sistema possui um formulário de contato, armazenamento de mensagens e uma área administrativa para gerenciamento dos dados.



A ferramenta escolhida para a automação foi o EmailJS.

Ela foi utilizada para automatizar o envio de e-mails sem a necessidade de desenvolver um servidor próprio para essa função.

O sistema realiza duas ações:

Envia um e-mail para a responsável pelo site quando alguém envia uma mensagem.

Envia um e-mail de confirmação para a pessoa que preencheu o formulário.

A comunicação é realizada por meio da biblioteca JavaScript do EmailJS.



O projeto utiliza o LocalStorage do navegador para armazenar as mensagens.

Os dados são organizados no formato JSON, permitindo salvar, consultar, editar e excluir mensagens.

O sistema também possui 20 mensagens de teste para facilitar a verificação das funcionalidades.



Para acessar a área administrativa:

Abra o arquivo contato.html.

Clique no botão Área administrativa.

O painel será exibido na própria página.

No painel é possível realizar as operações CRUD:

Create: cadastrar novas mensagens por meio do formulário.

Read: visualizar as mensagens recebidas.

Update: editar nome, e-mail e conteúdo das mensagens.

Delete: excluir mensagens cadastradas.



Abra a pasta do projeto no Visual Studio Code.

Execute o arquivo index.html utilizando o Live Server.

Acesse a página de contato.

Preencha o formulário e envie uma mensagem.

Verifique o recebimento dos e-mails.

Acesse a área administrativa para testar a visualização, edição e exclusão das mensagens.

Tecnologias utilizadas

HTML

CSS

JavaScript

LocalStorage

JSON

EmailJS

Bootstrap



As mensagens ficam armazenadas no navegador utilizado. Portanto, os dados do LocalStorage não são compartilhados automaticamente entre diferentes dispositivos ou navegadores.

O painel administrativo está inicialmente oculto e é exibido ao clicar no botão correspondente.

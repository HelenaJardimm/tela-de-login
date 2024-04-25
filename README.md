FUNCIONALIDADE DA PAGINA WEB

A primeira pagina trata-se de uma pagina para login de um usuario, a segunda e utilizada para caso este usuario tenha esquecido a sua senha de login atual, ajudando e realizando uma recuperação de senha.E também temos a pagina de cadastro caso o usuário ainda não tenha realizado seu cadastro.

# tela-de-login

Esse código é uma página HTML que cria uma interface simples de login. Vou explicar as diferentes partes do código:

<!DOCTYPE html>: Define o tipo de documento como HTML5.
<html lang="en">: Abertura da tag <html> indicando o início do documento HTML, com o atributo lang especificando o idioma como inglês.
<head>: Esta seção contém metadados e informações sobre o documento, como o título da página, a codificação de caracteres e o viewport para dispositivos móveis.
<meta charset="UTF-8">: Define a codificação de caracteres como UTF-8.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Define a largura da tela como largura do dispositivo e escala inicial como 1.0, importante para a responsividade em dispositivos móveis.
<title>Tela de Login</title>: Define o título da página como "Tela de Login".
<style>: Define estilos CSS internos para a página.
<body>: Esta seção contém o conteúdo visível da página.
<div class="login-container">: Um contêiner para o formulário de login.
<form action="#" method="post" id="login-form">: Um formulário de login que envia os dados para um destino não especificado (#) usando o método POST.
<label for="username">Usuário:</label>: Rótulo para o campo de entrada de usuário.
<input type="text" id="username" name="username" required>: Campo de entrada de texto para o nome de usuário, com o atributo required indicando que é obrigatório preencher este campo.
<label for="password">Senha:</label>: Rótulo para o campo de entrada de senha.
<input type="password" id="password" name="password" required>: Campo de entrada de senha, com o atributo required.
<input type="submit" value="Entrar">: Botão de envio do formulário.
<div class="forgot-password">: Uma seção para o link "Esqueceu a senha de novo cara ?".
<a href="http://127.0.0.1:5500/2login.html" id="forgot-password-link">Esqueceu a senha de novo cara ?</a>: Um link para uma página externa ou local (neste caso, 2login.html) para redefinir a senha.
<script src="script.js"></script>: Referência a um arquivo JavaScript externo chamado script.js, que provavelmente contém funcionalidades adicionais para o formulário de login.
  

  # esqueceu a senha

  Este código é uma página HTML para recuperação de senha. Aqui está uma explicação das partes do código:

<!DOCTYPE html>: Declaração do tipo de documento como HTML5.
<html lang="en">: Tag HTML que define o idioma do documento como inglês.
<head>: Esta seção contém metadados e informações sobre o documento.
<meta charset="UTF-8">: Define a codificação de caracteres como UTF-8.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Define a largura da tela como largura do dispositivo e escala inicial como 1.0, importante para a responsividade em dispositivos móveis.
<title>Recuperação de Senha</title>: Define o título da página como "Recuperação de Senha".
<style>: Define estilos CSS internos para a página.
<body>: Esta seção contém o conteúdo visível da página.
<div class="login-container">: Um contêiner para o formulário de recuperação de senha.
<h2>Ultima vez que eu recupero em se liga</h2>: Um título para o formulário de recuperação de senha.
<form action="#" method="post" id="forgot-password-form">: Um formulário que envia os dados para um destino não especificado (#) usando o método POST.
<label for="email">E-mail:</label>: Rótulo para o campo de entrada de e-mail.
<input type="email" id="email" name="email" required>: Campo de entrada de e-mail, com o atributo required indicando que é obrigatório preencher este campo.
<input type="submit" value="Recuperar Senha">: Botão de envio do formulário.
<script>: Não há scripts incluídos nesta página. 

# cadastro

Este é um código HTML básico para criar um formulário de cadastro. Vou explicar as principais partes:

<!DOCTYPE html>: Declara o tipo de documento como HTML5.
<html lang="pt-br">: Define o idioma do documento como português do Brasil.
<head>: Esta seção contém metadados e referências a recursos externos, como folhas de estilo e scripts.
<meta charset="UTF-8">: Define o conjunto de caracteres como UTF-8 para suportar caracteres especiais.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Define a largura da viewport como o largura do dispositivo e escala inicial como 1.
<title>Cadastro</title>: Define o título da página como "Cadastro".
<style>: Define as regras de estilo CSS embutidas para estilizar a página.
<body>: Esta seção contém o conteúdo visível da página.
<div class="container">: Define um contêiner com uma largura máxima de 400px, centrado horizontalmente na página e com um fundo rosa claro.
<h2>Cadastro</h2>: Um título de nível 2 que diz "Cadastro".
<form action="processa_cadastro.php" method="post">: Um formulário HTML com o atributo action definido como "processa_cadastro.php", indicando para onde os dados do formulário serão enviados quando o formulário for submetido, e o método post, que envia os dados de forma que não são visíveis na URL.
<label for="nome">Nome:</label>: Um rótulo para o campo de entrada de nome, indicado pelo atributo for correspondente ao id do campo de entrada.
<input type="text" id="nome" name="nome" required>: Um campo de entrada de texto para o nome, com o id "nome" e o name "nome". O atributo required indica que este campo é obrigatório.
O mesmo padrão se repete para os campos de email e senha.
<input type="submit" value="Cadastrar">: Um botão de envio do formulário com o valor "Cadastrar".
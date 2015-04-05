# Drupal 7
//Aqui neste repositório mostrará todas as falhas e soluções e aprendisagem do drupal.
`OBS: Tudo aqui é sobre o Drupal 7`

A video aula está no link : [Como Instalar o Drupal 7](http://youtube.com)

1 - Baixe a versão mas atualizada do Drupal 7 : [neste link](https://www.drupal.org/start)

2 - Agora extraia todo conteudo no seu servidor depois renomeie para o nome do seu site

### Instalação do drupal

1 - Baixe a versão de tradução de acordo com a versão do seu Drupal : [neste link](https://localize.drupal.org/translate/languages/pt-br) ; e faça o download

2 - Mova o arquivo de tradução para a pasta `/sites/profiles/starndard/translations`

3 - Crie um banco de dados para seu site, e deixe-o em branco.

4 - Agora abra no navegador a pasta do seu site

5 - Mostrará a página de instalação do Drupal a opção STANDARD estará ativa clique em SAVE E CONTINUE

6 - Agora selecione a lingua que deseja instalar, no meu caso é o PORTUGUÊS, selecione e clique em SAVE E CONTINUE

7 - No campo DATABASE NAME escreva o nome do banco de dados que você criou. Em DATABASE USER escreva o nome do usuário, servidor local sempre é `root` e em DATABASE PASSWORD no servidor local nao precisa de senha.
depois clique em SAVE E CONTINUE

8 - Normalmente em portugues sempre ocorre um erro, Clique em PÁGINA DE ERROS ou THE ERROR PAGE

9 - Agora vai mostra o formulário de preenchimento de dados pessais. preencha-os: NOMES, EMAIL, ESTADO, USERNAME, PASSWORD. depois clique em SAVE E CONTINUE

10 - Clique no link VISITE SEU SITE ou VISIT YOUR SITE.

11 - Caso a tradução nao funcione, no final da instalação vá até o menu configurações > traduzir a interface > na aba importar, importe o arquivo de tradução que está na pasta "/profiles/starndard/translations" (a tradução fica por volta de 91% à 93%)


### Drupal 7+ Gulp

Para a instalação do Gulp na plataforma Drupal é preciso criar uma pasta com o ponto na frente ex: `.npm` e inclua o package.json e o gulpfile.js na pasta.
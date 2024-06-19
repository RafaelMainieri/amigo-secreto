# Amigo Secreto 👥

<div align="center">
  <h3>Técnologias Utilizadas:</h3>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" width="25" height="25" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg" width="25" height="25"" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-original.svg" width="25" height="25" />
</div>

## Sobre
Projeto criado no curso da Alura [Lógica de Programação: praticando com desafios](https://cursos.alura.com.br/course/logica-programacao-praticando-desafios), disponibilizado pelo programa [Geração Caldeira](https://www.geracaocaldeira.org/) do [Instituto Caldeira](https://institutocaldeira.org.br/), do qual fui selecionado para participar da etapa online.<br>

Este é um projeto de uma aplicação que facilita o sorteio para um jogo de amigo secreto. Você pode adicionar o nome de todos os seus amigos e fazer um sorteio aleatório para que a brincadeira fique mais divertida e dinâmica! O sistema conta com algumas validações como conferir a repetição dos nomes inseridos, confere se de fato foi escrito algum nome no campo para inseri-lo e pede um mínimo de 4 integrantes para o sorteio.

## Funcionalidades
- Adicionar nomes na lista = O usuário insere o nome do amigo no campo "Nome do Amigo" e clica no botão adicionar;
- Botão Adicionar = O programa cria um array na abertura do site e adiciona o nome digitado nesse array;
- Validações<br>
  → Texto Vazio = O programa valida se realmente foi escrito algum texto no campo. Caso nao tenha sido, exibe um alerta informando o usuário;<br>
  → Mínimo Pessoas = O programa valida o tamanho do array, só sendo possivel sortear os nomes com no mínimo 4 integrantes, alertando o usuário;<br>
  → Nome Repetido = O programa analisa o array e não permite a adesão de um nome que ja pertence a lista do sorteio, alertando o usuário;<br>
- Botão Sortear = São embaralhados os nomes adicionados na lista de sorteio e apresentados na tela do usuário;
- Botão Reiniciar = O sistema reinicia o sorteador, zerando todos os campos preenchidos

## Como Executar
1. Acesso ao site: [Clique Aqui](https://rafaelmainieri.github.io/carrinho-compras/);
2. O usuario deve adicionar os nomes à lista do sorteio (sempre se atentando às validações);
3. Clicar no botão "Adicionar";
4. Após conferir os nomes da lista do sorteio, clicar no botão "Sortear";
5. Caso esteja insatisfeito com a lista do sorteio, clique no botão "Reiniciar";

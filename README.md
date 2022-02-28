# Boas vindas ao repositório do projeto de Receitas!

Nessa aplicação é possível pesquisar receitas  com diversos filtros como País de origem, ingredientes, categorias e etc, Também é possível favoritar, iniciar receita, e acessar histórico de receitas feitas.
Todo o desenvolvimento do projeto foi feito em grupo, focado apenas no front end e em dispositivos móveis.
Foram utilizados 2 API's diferentes para acessar os dados da receitas, o [TheMealDB](https://www.themealdb.com/api.php) e [TheCockTailDB](https://www.thecocktaildb.com/api.php).

## Sumário

 - [Equipe de desenvolvimento](#equipe-de-desenvolvimento)
- [Tecnologias utilizadas](#tecnologias-utilizadas)
- [Requisitos](#requisitos-para-o-desenvolvimento)
- [Testes automatizados](#testes-automatizados)
-  [Aplicação funcionando](#aplicação-funcionando)


## Equipe de desenvolvimento
O projeto inteiro foi desenvolvido em grupo, decisões como quais tecnologias utilizar, estruturação de componentes e divisão de tarefas sempre foi um consenso entre toda a equipe.

### Integrantes da equipe
- [Cristhyane Araldi](https://github.com/CristhyaneAraldi)
- [Gabriel Ferreira](https://github.com/Gabrielferreirasl)
- Matheus Alves (https://github.com/malves224)
- [Saulo Lima](https://github.com/saulolima-c)
- [Victor Hugo Souza](https://github.com/victoraster2010)

## Tecnologias utilizadas

 - React.js
 - JavaScript
 - React Hooks
 - Context API
 - Jest, Reacting Testing Library (RTL)

## Requisitos para o desenvolvimento

A estrutura de telas e requisitos listados foram criadas pela escola de desenvolvimento [Trybe](https://www.betrybe.com/), 100% dos requisitos foram concluído.
   <details>
     <summary>Testes unitários</summary>

- [x] 1 - Desenvolva os testes unitários de maneira que a seja de, no mínimo, 90%
   </details>
    <details>
    <summary>Tela de Login</summary>
    
  - [x] 2 - Crie todos os elementos que devem respeitar os atributos descritos no protótipo para a tela de login
  - [x] 3 - Desenvolva a tela de maneira que a pessoa deve conseguir escrever seu email no input de email
  - [x] 4 - Desenvolva a tela de maneira que a pessoa deve conseguir escrever sua senha no input de senha
  - [x] 5 - Desenvolva a tela de maneira que o formulário só seja válido após um email válido e uma senha de mais de 6 caracteres serem preenchidos
  - [x] 6 - Salve 2 tokens no localStorage após a submissão, identificados pelas chaves mealsToken e cocktailsToken
  - [x] 7 - Salve o e-mail da pessoa usuária no localStorage na chave user após a submissão
  - [x] 8 - Redirecione a pessoa usuária para a tela principal de receitas de comidas após a submissão e validação com sucesso do login
  </details>
  <details>
    <summary>Header</summary>

  - [x] 9 - Implemente os elementos do header na tela principal de receitas, respeitando os atributos descritos no protótipo
  - [x] 10 - Implemente um ícone para a tela de perfil, um título e um ícone para a busca, caso exista no protótipo
  - [x] 11 - Redirecione a pessoa usuária para a tela de perfil ao clicar no botão de perfil
  - [x] 12 - Desenvolva o botão de busca que, ao ser clicado, a barra de busca deve aparecer. O mesmo serve para escondê-la
  </details>
  <details>
    <summary>Barra de busca</summary>

- [x] 13 - Implemente os elementos da barra de busca respeitando os atributos descritos no protótipo
- [x] 14 - Posicione a barra logo abaixo do header e implemente 3 radio buttons: Ingrediente, Nome e Primeira letra
- [x] 15 - Busque na API de comidas caso a pessoa esteja na página de comidas e na de bebidas caso esteja na de bebidas
- [x] 16 - Redirecione para a tela de detalhes da receita caso apenas uma receita seja encontrada, com o ID da mesma na URL
- [x] 17 - Mostre as receitas em cards caso mais de uma receita seja encontrada
- [x] 18 - Exiba um `alert` caso nenhuma receita seja encontrada
  </details>
  <details>
    <summary>Menu inferior</summary>
- [x] 19 - Implemente os elementos do menu inferior respeitando os atributos descritos no protótipo
- [x] 20 - Posicione o menu inferior de forma fixa e apresente 3 ícones: um para comidas, um para bebidas e outro para exploração
- [x] 21 - Exiba o menu inferior apenas nas telas indicadas pelo protótipo
- [x] 22 - Redirecione a pessoa usuária para uma lista de cocktails ao clicar no ícone de bebidas
- [x] 23 - Redirecione a pessoa usuária para a tela de explorar ao clicar no ícone de exploração
- [x] 24 - Redirecione a pessoa usuária para uma lista de comidas ao clicar no ícone de comidas
  </details>
  <details>
    <summary>Tela principal de receitas</summary>

 - [x] 25 - Implemente os elementos da tela principal de receitas respeitando os atributos descritos no protótipo
 - [x] 26 - Carregue as 12 primeiras receitas de comidas ou bebidas, uma em cada card
 - [x] 27 - Implemente os botões de categoria para serem utilizados como filtro
 - [x] 28 - Implemente o filtro das receitas através da API ao clicar no filtro de categoria
 - [x] 29 - Implemente o filtro como um toggle, que se for selecionado de novo, o app deve retornar as receitas sem nenhum filtro
- [x] 30 - Implemente o filtro de categoria para que apenas um seja selecionado por vez
- [x] 31 - Desenvolva o filtro de categorias com a opção de filtrar por todas as categorias
- [x] 32 - Redirecione a pessoa usuária, ao clicar no card, para a tela de detalhes, que deve mudar a rota e conter o id da receita na URL
  </details>
  <details>
    <summary>Tela de detalhes de uma receita</summary>

 - [x] 33 - Implemente os elementos da tela de detalhes de uma receita respeitando os atributos descritos no protótipo
 - [x] 34 - Realize uma request para a API passando o `id` da receita que deve estar disponível nos parâmetros da URL
 - [x] 35 - Desenvolva a tela de forma que contenha uma imagem da receita, o título, a categoria (ou se é ou não alcoólico), uma lista de ingredientes seguidos pelas quantidades, instruções, um vídeo do youtube "embedado" e recomendações
- [x] 36 - Implemente as recomendações, para receitas de comida, a recomendação deverá ser bebida e vice-versa
- [x] 37 - Implemente os cards de recomendação, onde serão 6 cards, mas mostrando apenas 2 e o scroll é horizontal, similar a um `carousel`
- [x] 38 - Desenvolva um botão de nome "Iniciar Receita" que deve ficar fixo na parte de baixo da tela o tempo todo
- [x] 39 - Implemente a solução de forma que caso a receita já tenha sido feita, o botão "Iniciar Receita" deve sumir
- [x] 40 - Implemente a solução de modo que caso a receita tenha sido iniciada mas não finalizada, o texto do botão deve ser "Continuar Receita"
- [x] 41 - Redirecione a pessoa usuário caso o botão "Iniciar Receita" seja clicado, a rota deve mudar para a tela de receita em processo
- [x] 42 - Implemente um botão de compartilhar e um de favoritar a receita
- [x] 43 - Implemente a solução de forma que, ao clicar no botão de compartilhar, o link da receita dentro do app deve ser copiado para o clipboard e uma mensagem avisando que o link foi copiado deve aparecer
- [x] 44 - Implemente o ícone do coração (favorito) de maneira que, deve vir preenchido caso a receita esteja favoritada e "despreenchido" caso contrário
- [x] 45 - Implemente a lógica no botão de favoritar, caso seja clicado, o ícone do coração deve mudar seu estado atual, caso esteja preenchido deve mudar para "despreenchido" e vice-versa
 - [x] 46 - Salve as receitas favoritas no `localStorage` na chave `favoriteRecipes`
  </details>
  <details>
    <summary>Tela de receita em progresso</summary>

  - [x] 47 - Desenvolva a tela de maneira que contenha uma imagem da receita, seu titulo, sua categoria (ou se a bebida é alcoólica ou não) uma lista de ingredientes com suas respectivas quantidade e suas instruções
  - [x] 48 - Desenvolva um checkbox para cada item da lista de ingredientes
  - [x] 49 - Implemente uma lógica que, ao clicar no checkbox de um ingrediente, o nome dele deve ser "riscado" da lista
 - [x] 50 - Salve o estado do progresso, que deve ser mantido caso a pessoa atualize a página ou volte para a mesma receita
 - [x] 51 - Desenvolva a lógica de favoritar e compartilhar, a lógica da tela de detalhes de uma receita se aplica aqui
 - [x] 52 - Implemente a solução de maneira que o botão de finalizar receita só pode estar habilitado quando todos os ingredientes estiverem _"checkados"_ (marcados)
 - [x] 53 - Redirecione a pessoa usuária após clicar no botão "Finalizar receita", para a página de receitas feitas, cuja rota deve ser `/receitas-feitas`
  </details>
  <details>
    <summary>Tela de receitas feitas</summary>

- [x] 54 - Implemente os elementos da tela de receitas feitas respeitando os atributos descritos no protótipo
 - [x] 55 - Desenvolva a tela de maneira que, caso a receita do card seja uma comida, ela deve possuir: a foto da receita, o nome, a categoria, a area, a data em que a pessoa fez a receita, as 2 primeiras tags retornadas pela API e um botão de compartilhar
- [x] 56 - Desenvolva a tela de maneira que, caso a receita do card seja uma bebida, ela deve possuir: a foto da receita, o nome, se é alcoólica, a data em que a pessoa fez a receita e um botão de compartilhar
- [x] 57 - Desenvolva a solução de maneira que o botão de compartilhar deve copiar a URL da tela de detalhes da receita para o clipboard
- [x] 58 - Implemente 2 botões que filtram as receitas por comida ou bebida e um terceiro que remove todos os filtros
- [x] 59 - Redirecione para a tela de detalhes da receita caso seja clicado na foto ou no nome da receita
  </details>
  <details>
    <summary>Tela de receitas favoritas</summary>

 - [x] 60 - Implemente os elementos da tela de receitas favoritas (cumulativo com os atributos em comum com a tela de receitas feitas) respeitando os atributos descritos no protótipo
- [x] 61 - Desenvolva a tela de maneira que, caso a receita do card seja uma comida, ela deve possuir: a foto da receita, o nome, a categoria, a area, um botão de compartilhar e um de "desfavoritar"
- [x] 62 - Desenvolva a tela de maneira que, caso a receita do card seja uma bebida, ela deve possuir: a foto da receita, o nome, se é alcoólica ou não, um botão de compartilhar e um de "desfavoritar"
 - [x] 63 - Desenvolva a solução de maneira que o botão de compartilhar deve copiar a URL da tela de detalhes da receita para o clipboard
 - [x] 64 - Desenvolva a solução de maneira que o botão de "desfavoritar" deve remover a receita da lista de receitas favoritas do `localStorage` e da tela
- [x] 65 - Implemente 2 botões que filtram as receitas por comida ou bebida e um terceiro que remove todos os filtros
- [x] 66 - Redirecione a pessoa usuária ao clicar na foto ou no nome da receita, a rota deve mudar para a tela de detalhes daquela receita
  </details>
  <details>
    <summary>Tela de explorar</summary>

- [x] 67 - Implemente os elementos da tela de explorar respeitando os atributos descritos no protótipo
- [x] 68 - Desenvolva a tela de maneira que tenha 2 botões: um para explorar comidas e o outro para explorar bebidas
- [x] 69 - Redirecione a pessoa usuária ao clicar em um dos botões, a rota deve mudar para a página de explorar comidas ou de explorar bebidas
  </details>
  <details>
    <summary>Tela de explorar bebidas ou comidas</summary>

 - [x] 70 - Implemente os elementos da tela de explorar bebidas ou comidas respeitando os atributos descritos no protótipo
  - [x] 71 - Desenvolva 3 botões: um para explorar por ingrediente, um para explorar por local de origem e um para pegar uma receita aleatória
 - [x] 72 - Redirecione a pessoa usuária ao clicar em "Por Ingredientes", a rota deve mudar para a tela de explorar por ingredientes
- [x] 73 - Redirecione a pessoa usuária ao clicar em "Por Local de Origem", a rota deve mudar para tela de explorar por local de origem
- [x] 74 - Redirecione a pessoa usuária ao clicar em "Me Surpreenda!", a rota deve mudar para a tela de detalhes de uma receita, que deve ser escolhida de forma aleatória através da API
  </details>
  <details>
    <summary>Tela de explorar ingredientes</summary>

- [x] 75 - Implemente os elementos da tela de explorar ingredientes respeitando os atributos descritos no protótipo
- [x] 76 - Desenvolva cards para os 12 primeiros ingredientes, de forma que cada card contenha o nome do ingrediente e uma foto
- [x] 77 -  Redireciona a pessoa usuária ao clicar no card do ingrediente, a rota deve mudar para tela principal de receitas mas mostrando apenas as receitas que contém o ingrediente escolhido
  </details>
  <details>
    <summary>Tela de explorar por local de origem/area</summary>

- [x] 78 - Implemente os elementos da tela de explorar por local de origem respeitando os atributos descritos no protótipo
- [x] 79 - Desenvolva as mesmas especificações da tela de receitas principal, com a diferença de que os filtros de categoria são substituídos por um dropdown
- [x] 80 - Implemente o dropdown de maneira que devem estar disponíveis todas as áreas retornadas da API, incluindo a opção "All", que retorna as receitas sem nenhum filtro
- [x] 81 - Implemente a rota que deve ser apenas `/explorar/comidas/area`
  </details>
  <details>
    <summary>Tela de perfil</summary>

- [x] 82 - Implemente os elementos da a tela de perfil respeitando os atributos descritos no protótipo
- [x] 83 - Implemente a solução de maneira que o e-mail da pessoa usuária deve estar visível
- [x] 84 - Implemente 3 botões: um de nome "Receitas Feitas", um de nome "Receitas Favoritas" e um de nome "Sair"
- [x] 85 - Redirecione a pessoa usuária que, ao clicar no botão de "Receitas Favoritas", a rota deve mudar para a tela de receitas favoritas
- [x] 86 - Redirecione a pessoa usuária que, ao clicar no botão de "Receitas Feitas", a rota deve mudar para a tela de receitas feitas
- [x] 87 - Redirecione a pessoa usuária que, ao clicar no botão de "Sair", o `localStorage` deve ser limpo e a rota deve mudar para a tela de login
  </details>
## Testes automatizados

Testar a aplicação foi muito importante devido ao tamanho do projeto ser relativamente grande, Garantindo a segurança da aplicação conforme o crescimento, Um dos principais desafios foi garantir uma aplicação testável.

#### O Projeto contempla 90% de cobertura de linhas

![90% de cobertura de testes](https://raw.githubusercontent.com/malves224/app-recipes/app-matheus-alves/testCoverage.png)


## Aplicação funcionando

![Aplicação funcionando](https://raw.githubusercontent.com/malves224/app-recipes/main/app-funcionando.gif)

[Acesse a aplicação](https://app-recipes-six.vercel.app/)

### Rode a aplicação em sua maquina
Entenda melhor como a aplicação funciona rodando na sua maquina,
Execute o comando `git clone git@github.com:malves224/app-recipes.git && cd app-recipes && npm install
`, Após compilar execute o comando `npm start` e acesse em seu navegador `localhost:3000`.

OBS: Por favor não envie nenhum pull request não espero contribuições, Fique a vontade para fazer um Fork.

<h2> Duvidas entre em contato </h2>
  <a href="https://www.linkedin.com/in/mthsalves//">
    <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?&style=flat-square&logo=linkedin&logoColor=white">
  </a>
  <br>
<a href = "mailto: Malves224@gmail.com">Malves224@gmail.com</a>

# [EVNTS] DESAFIO BACK-END NODEJS

- [SUMÁRIO](#evnts-desafio-back-end-nodejs)
  - [1 Introdução](#1-introdu%C3%A7%C3%A3o)
  - [2 Descrição](#2-descri%C3%A7%C3%A3o)
  - [3 API - UAIFOOD](#3-api---uaifood)
    - [3.1 Descrição](#31-descri%C3%A7%C3%A3o)
    - [3.2 EndPoints](#32-endpoints)
    - [3.3 Pontos Extras](#33-pontos-extras)
  - [4 Desafios de Lógica](#4-desafios-de-l%C3%B3gica)
    - [4.1 Descrição](#41-descri%C3%A7%C3%A3o)
    - [4.1 INICIANTE (1 ponto cada)](#41-iniciante-1-ponto-cada)
    - [4.2 INTERMEDIÁRIO (3 pontos cada)](#42-intermedi%C3%A1rio-3-pontos-cada)
    - [4.3 DIFICIL (7 pontos cada)](#43-dificil-7-pontos-cada)
  - [5 Considerações Finais](#5-considera%C3%A7%C3%B5es-finais)

## 1 Introdução

Olá! 😁

Se você recebeu um convite para estar aqui você faz parte de um grupo de pessoas que acreditamos serem bons candidatos!

Fizemos este teste com muito carinho e esperamos que você consiga se sair bem 👍

O teste consiste em testar suas habilidades em construir soluções para o _Back-end_.


Todo o seu código deve ser disponibilizado em um repositório em seu _github_ ou _bitbucket_ pessoal. Envie o link para o email que te enviamos (vagas@evnts.com.br).

Boa sorte!

## 2 Descrição


Este desafio tem duas etapas. Em cada uma delas é possível fazer atividades extras para ganhar uns pontinhos a mais com a gente 😉

Na primeira queremos entender como você arquitetura um sistema e além do seu domínio das tecnologias, legibilidade de código, entre outras coisas.

A segunda etapa consiste de exercícios de programação. Queremos ver sua lógica de programação, como você aborda as situações que surgirão no dia-a-dia, e sua capacidade para resolver problemas incomuns.


## 3 API - UAIFOOD


### 3.1 Descrição

A Evnts é uma empresa mineira, cheia de mineiros, então nada melhor que um teste no que fazemos de melhor: __comer__. Para isto, neste teste, você vai ter que nos ajudar e criar o ~~disruptivo~~ site __UaiFood__.
<center>

![BUSCA](https://github.com/evnts-dev/teste-front-react/blob/master/imgs/documentation/search.jpg?raw=true)
</center>


A única restrição de tecnologia é o ```NodeJs```. Utilize qualquer framework, ferramenta e serviço que quiser. O mesmo serve para o banco de dados, relacional ou não relacional (```MySQL```, ```Firebase```, ```Mongo```, etc. Você quem manda!. Não se esqueça de elaborar sua solução, os detalhes de arquitetura e a escolha de frameworks e padrões de projeto.

Pontos extras se usar GraphQL``` 😁

Não se esqueça de fazer de uma forma que seja simples para rodar o seu serviço localmente e, como este serviço será um SUCESSO MUNDIAL ele deve ser a prova de erros!


### 3.2 EndPoints

Para isso, precisaremos das seguintes rotas:

1. **Cadastrar Restaurante**

Receber as informações relevantes do restaurante e criar um novo cadastro do mesmo na base. Verificar se já não existe o mesmo antes de inserir. Além de todos os dados que julgar pertinente, o restaurante deve ter um **tipo de cozinha** (Árabe, Brasileira, Chinesa, Francesa, frutos do mar, Vegetariana, Italiana, Pizza, Hambúrguer, Lanches, etc..).

2. **Cadastrar Item**

Dado um restaurante, cadastrar um novo item ao cardápio daquele restaurante. Este item deve conter toda e qualquer informação pertinente e, obrigatoriamente, um **preço**.


3. **Atualizar Item**

Dado um restaurante e um Item, atualizar o preço e os demais dados para os novos passados.


4. **Listar restaurantes**

Dado os parâmetros, trazer apenas os restaurantes que tiverem um match. Os parâmetros podem ser:
  - **Cidade:** Recebe uma cidade e retorna os restaurantes cadastrados naquela cidade
  - **Distância:** Recebe _lat_ e _lng_ e um raio (em quilômetros) e retorna apenas os restaurantes dentro da região
  - **Tipo de cozinha:** recebe o **tipo de cozinha** e retorna os restaurantes daquele tipo
  - **Prato:** recebe qualquer coisa que o cliente digitar relacionado aos pratos cadastrados (ex.: strogonoff) e traz os restaurantes que tiverem itens relacionados

A consulta pode conter um ou mais destes parâmetros e deve trazer a junção de todos.



### 3.3 Pontos Extras

Se você quiser mostrar o quanto você é fera, nos ajude a desenvolver um __frontend__ para o nossos sistema! Crie telas para os endpoints de cadastro e atualização citados acima. Você pode encontrar um exemplo de _layout_ [aqui](https://github.com/evnts-dev/teste-front-react/blob/master/README.md); use a sua criatividade para desenvolve-las, confiamos em você! :)

Você também pode ganhar pontos extras implementando um sistema de autenticação, permitindo apenas que o restaurante cadastre/atualize itens se estiver logado (obviamente, permitindo apenas que altere/adicione seus itens).


## 4 Desafios de Lógica

### 4.1 Descrição

Esta etapa consiste em testar sua lógica de programação! Para isso utilizamos a ferramenta [URI](https://www.urionlinejudge.com.br), uma plataforma com diversos problemas de maratona de programação, onde você pode utilizar diversas linguagens para resolvê-los (```Java```, ```Python```, ```C```, entre outras). Utilize o ```Javascript``` para esta atividade!

Os exercícios tem um valor (pontos), quanto mais pontos você fizer melhor!

Faça no mínimo **12 PONTOS**

Tutorial de como utilizar o URI: https://www.loom.com/share/1a7b7b00c41e4975aca013ef0814410b

### 4.1 INICIANTE (1 ponto cada)
  - Área do circulo: https://www.urionlinejudge.com.br/judge/pt/problems/view/1002
  - Salário com bônus: https://www.urionlinejudge.com.br/judge/pt/problems/view/1009
  - Cédulas: https://www.urionlinejudge.com.br/judge/pt/problems/view/1018


### 4.2 INTERMEDIÁRIO (3 pontos cada)
  - Positivos e média: https://www.urionlinejudge.com.br/judge/pt/problems/view/1064
  - Média 3: https://www.urionlinejudge.com.br/judge/pt/problems/view/1040
  - Soma de Impares Consecutivos I: https://www.urionlinejudge.com.br/judge/pt/problems/view/1071


### 4.3 DIFICIL (7 pontos cada)
  - A Lenda de Flavious Josephus: https://www.urionlinejudge.com.br/judge/pt/problems/view/1030
  - Colônia de Formigas: https://www.urionlinejudge.com.br/judge/pt/problems/view/1135


## 5 Considerações Finais

Sinta-se a vontade para entrar em contato com a gente para o que precisar! Estaremos a disposição.

Feedbacks também são bem vindos

Boa sorte!

<p align="center">
  <img align="center" src="https://raw.githubusercontent.com/evnts-dev/teste-front-react/master/imgs/uaifood/potato/potato.jpg" alt="batatinha" />
  <br/>
  mandavê 😘
</p>

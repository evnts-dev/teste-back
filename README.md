# [EVNTS] DESAFIO BACK-END NODEJS

- [SUMÁRIO](#evnts-desafio-back-end-nodejs)
  - [1 Introdução](#1-introdu%C3%A7%C3%A3o)
  - [2 API - UAIFOOD](#2-api---uaifood)
    - [2.1 Descrição](#21-descri%C3%A7%C3%A3o)
    - [2.2 EndPoints](#22-endpoints)
  - [3 Pontos Extras](#3-pontos-extras)
  - [4 Considerações Finais](#4-considera%C3%A7%C3%B5es-finais)

## 1 Introdução

Olá! 😁

Se você recebeu um convite para estar aqui você faz parte de um grupo de pessoas que acreditamos serem bons candidatos!

Fizemos este teste com muito carinho e esperamos que você consiga se sair bem 👍

O teste consiste em testar suas habilidades em construir soluções para o _back-end_.

Todo o seu código deve ser disponibilizado em um repositório em seu _github_ ou _bitbucket_ pessoal. Envie o link para o email que te enviamos (vagas@evnts.com.br).

Boa sorte!

## 2 API - UAIFOOD


### 2.1 Descrição

A Evnts é uma empresa mineira, cheia de mineiros, então nada melhor que um teste no que fazemos de melhor: __comer__. Para isto, neste teste, você vai ter que nos ajudar e criar o ~~disruptivo~~ site __UaiFood__.
<center>

![BUSCA](https://github.com/evnts-dev/teste-front-react/blob/master/imgs/documentation/search.jpg?raw=true)
</center>


A única restrição de tecnologia é o ```NodeJs```. Utilize qualquer framework, ferramenta e serviço que quiser. O mesmo serve para o banco de dados, relacional ou não relacional (```MySQL```, ```Firebase```, ```Mongo```, etc). Você quem manda! Não se esqueça de elaborar sua solução, os detalhes de arquitetura e a escolha de frameworks e padrões de projeto.


### 2.2 Endpoints

Para isso, precisaremos das seguintes rotas:

1. **Cadastrar Restaurante**

Receber as informações relevantes do restaurante e criar um novo cadastro do mesmo na base. Verificar se já não existe o mesmo antes de inserir. Além de todos os dados que julgar pertinente, o restaurante deve ter um **tipo de culinária** (Árabe, Brasileira, Chinesa, Francesa, frutos do mar, vegetariana, Italiana, pizza, hambúrguer, lanches, etc..).

2. **Cadastrar Item**

Dado um restaurante, cadastrar um novo item ao cardápio daquele restaurante. Este item deve conter toda e qualquer informação pertinente e, obrigatoriamente, um **preço**.


3. **Atualizar Item**

Dado um restaurante e um Item, atualizar o preço e os demais dados para os novos dados informados.


4. **Listar restaurantes**

Dado os parâmetros, trazer apenas os restaurantes que tiverem um match. Os parâmetros podem ser:
  - **Cidade:** Recebe uma cidade e retorna os restaurantes cadastrados naquela cidade
  - **Tipo de cozinha:** recebe o **tipo de cozinha** e retorna os restaurantes daquele tipo
  - **Prato:** recebe qualquer coisa que o cliente digitar relacionado aos pratos cadastrados (ex.: strogonoff) e traz os restaurantes que tiverem itens relacionados
  - [OPCIONAL] **Distância:** Recebe _lat_ e _lng_ e um raio (em quilômetros) e retorna apenas os restaurantes dentro da região

A consulta pode conter um ou mais destes parâmetros e deve trazer a junção de todos.


## 3 Pontos Extras

Se você quiser mostrar o quanto você é fera e ganhar uns pontos extras nos ajude a desenvolver um sistema de autenticação, permitindo apenas que o restaurante cadastre/atualize itens apenas se estiver logado (obviamente, permitindo apenas que altere/adicione seus itens).

Qualquer acréscimo em tecnologias não obrigatórias será levado em consideração também (testes automatizados, microserviços, etc).

## 4 Considerações Finais

Sinta-se a vontade para entrar em contato com a gente para o que precisar! Estaremos a disposição.

Feedbacks também são bem vindos

Boa sorte!

<p align="center">
  <img align="center" src="https://raw.githubusercontent.com/evnts-dev/teste-front-react/master/imgs/uaifood/potato/potato.jpg" alt="batatinha" />
  <br/>
  mandavê 😘
</p>

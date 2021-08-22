# Introdução a automação web com Selenium e Java
Vamos fazer cadastro e login em um site de forma automatizada.

## Pré-requisitos
- Java 8
- IDE 
- Maven
- [Selenium Webdriver](https://www.selenium.dev/documentation/webdriver/) (adicionado no `pom.xml`)
- [JUnit](https://junit.org/junit5/docs/current/user-guide/) (adicionado no `pom.xml`)

## Observação
- Neste projeto eu uso um `chromedriver` da versão compatível com o meu navegador. Então clique [aqui](https://chromedriver.chromium.org/downloads) para achar a versão específica do seu Chrome, mas antes disso clique [aqui](https://br.ccm.net/faq/29343-como-verificar-a-versao-do-google-chrome) para descobrir a versão do seu navegador. 
- Agora basta substituir o arquivo `chromedriver` do path `selenium\src\test\resources\drivers` pelo arquivo da sua versão. 
- A automação foi feita em um site, onde seus nomes de seletores podem mudar com o tempo, porém se isso acontecer, basta adicionar o nome do seletor atual do site.

## Como executar os testes?
>mvn clean compile test

## Guia
1) É necessário instanciar o Driver para poder usá-lo
2) Adicionar as annotations do JUnit, exemplo: `@Before`: código executado antes do teste, `@Test`: código teste, `@After`: código executado depois do teste. 
3) A classe `Utils.java` no projeto foi criada para ser uma classe auxiliar que contêm métodos que vão se repetir várias vezes. Obs: Essas annotations mudaram no JUnit5.

## Dicas adicionais
Aprofundar conhecimentos em debug de código, orientação a objeto, [PageObject](https://testinworld.wordpress.com/2012/02/22/padrao-de-projeto-page-objects/) e Java.

## Sobre a Autora
Oi, eu sou a Fernanda! Estou aqui para contribuir com meu conhecimento e espero poder ajudar no desenvolvimento profissional de cada um de vocês.

[![Linkedin Badge](https://img.shields.io/badge/-Fernanda_Maki_Hirose-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/fernanda-maki-hirose-801117208/)](https://www.linkedin.com/in/fernanda-maki-hirose-801117208/)  [![Gmail Badge](https://img.shields.io/badge/-femahi2020@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:femahi2020@gmail.com)](mailto:femahi2020@gmail.com)

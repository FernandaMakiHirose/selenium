# Introdução a automação web com Selenium e Java

## Pré-requisitos
- Java 8
- IDE
- Maven
- [Selenium Webdriver](https://www.selenium.dev/documentation/webdriver/) (adicionado no `pom.xml`)
- [JUnit](https://junit.org/junit5/docs/current/user-guide/) (adicionado no `pom.xml`)

## Guia
1) É necessário instanciar o Driver para poder usá-lo
2) Adicionar as annotations do JUnit, exemplo: `@Before`: código executado antes do teste, `@Test`: código teste, `@After`: código executado depois do teste. 
3) A classe `Utils.java` no projeto foi criada para ser uma classe auxiliar que contêm métodos que vão se repetir várias vezes. Obs: Essas annotations mudaram no JUnit5.

## Dicas adicionais
Aprofundar conhecimentos em debug de código, orientação a objeto, [PageObject](https://testinworld.wordpress.com/2012/02/22/padrao-de-projeto-page-objects/) e Java.

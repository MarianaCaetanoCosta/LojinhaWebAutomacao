## 🛒 Lojinha Web — Automação de Testes com JUnit e Selenium

Projeto de automação de testes Web da aplicação Lojinha, desenvolvido utilizando Java, JUnit e Selenium WebDriver.

O projeto tem como objetivo demonstrar a criação e execução de testes automatizados para validação de regras de negócio, utilizando técnicas de Partições de Equivalência e Valores Limite, além dos padrões Page Object Model e Fluent Page Object Model.

## 🎯 Objetivo

Automatizar testes funcionais da aplicação Lojinha Web, validando as regras de negócio relacionadas ao cadastro, edição, exclusão e consulta de produtos e componentes.

O projeto também demonstra a utilização de boas práticas para organização, reutilização e manutenção do código de automação.


## 🧪 Testes automatizados

💰 Cenários de teste
O plano de testes contempla as principais operações da aplicação:

1. 🔐 Entrar
2. 📦 Cadastro de produto
3. 🔧 Cadastro de componente
4. 📋 Listagem de produtos
5. 🚪 Sair

## Imagens

<img width="773" height="489" alt="image" src="https://github.com/MarianaCaetanoCosta/JL_LojinhaWebAutomacao/blob/main/imagens/Login.JPG" />

<img width="773" height="488" alt="image" src="https://github.com/MarianaCaetanoCosta/JL_LojinhaWebAutomacao/blob/main/imagens/ListaProdutos.JPG" />

<img width="765" height="484" alt="image" src="https://github.com/MarianaCaetanoCosta/JL_LojinhaWebAutomacao/blob/main/imagens/CadastrarProdutos.JPG" />

<img width="773" height="488" alt="image" src="https://github.com/MarianaCaetanoCosta/JL_LojinhaWebAutomacao/blob/main/imagens/EditarProdutos.JPG" />

<img width="765" height="484" alt="image" src="https://github.com/MarianaCaetanoCosta/JL_LojinhaWebAutomacao/blob/main/imagens/AdicionarComponente.JPG" />

<img width="765" height="484" alt="image" src="https://github.com/MarianaCaetanoCosta/JL_LojinhaWebAutomacao/blob/main/imagens/ComponenteAdicionado.JPG" />

## Notas Gerais

- Utilizado as notações:
    - **Before Each**: para capturar o usuário e senha que será utilizado posteriormente nos métodos de teste.
    - **DisplayName** para dar descrições em português para nossos testes.

## 🏛️ Design Patterns
- **Page Object Model :** O Page Object Model é usado em testes de automação, onde cada página da web em um aplicativo da web é representada como uma classe. A classe contém os elementos e ações que podem ser realizados na página. Isso torna o código de teste mais sustentável, pois as alterações na página podem ser feitas em um só lugar, em vez de em vários testes.

- **Fluent Page Object Model :** O Fluent Page Object Model é uma extensão do Page Object Model, onde métodos são encadeados para formar uma interface fluente. Isso torna o código de teste mais legível e conciso, pois várias ações podem ser executadas na página em uma única linha de código.

## ▶️ Como executar

### 1. Preparar o ambiente

Antes de executar o projeto, instale e configure:

* [**Java JDK**](https://www.oracle.com/java/technologies/downloads/)
* [**Intellij**](https://www.jetbrains.com/idea/download/?section=windows)
* [**Maven**](https://maven.apache.org/download.cgi)

## 2. Dependências

* [Api Junit Jupter](https://mvnrepository.com/artifact/org.junit.jupiter/junit-jupiter-api/5.11.0-M2)
* [Selênio Java](https://mvnrepository.com/artifact/org.seleniumhq.selenium/selenium-java/4.23.0)


## 3. Driver dos navegadores

* [Chrome Driver](https://developer.chrome.com/docs/chromedriver/downloads?hl=pt-br)
* [Firefox Driver](https://github.com/mozilla/geckodriver)
* [Edge Driver](https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/?form=MA13LH)

### 4. Clonar o projeto

Clone o repositório para sua máquina local:

```bash
git clone <URL_DO_REPOSITORIO>
```

### 5. Abrir o projeto

Abra o projeto no **IntelliJ IDEA**.

O Maven realizará o carregamento das dependências configuradas no `pom.xml`, incluindo:

* JUnit Jupiter;
* Selenium Java.

### 6. Configurar o navegador

Selecione o navegador em que os testes serão executados e verifique se o respectivo WebDriver está disponível:

* **ChromeDriver** → Google Chrome
* **GeckoDriver** → Mozilla Firefox
* **EdgeDriver** → Microsoft Edge

### 7. Configurar a aplicação

Verifique se a **Lojinha Web** está disponível para execução dos testes e se as informações necessárias para autenticação estão configuradas no projeto.

### 8. Executar os testes

No IntelliJ IDEA, localize a classe de testes e execute os cenários automatizados utilizando o **JUnit**.

Os testes irão abrir o navegador configurado e executar automaticamente os fluxos definidos na automação.

### 9. Validar os resultados

Após a execução, verifique o resultado dos cenários automatizados e as validações realizadas pela aplicação.



## 👩‍💻 Sobre o projeto

Projeto desenvolvido como parte do meu portfólio de Qualidade de Software e Automação de Testes, com foco na aplicação prática de Java, JUnit e Selenium WebDriver para criação e execução de testes automatizados em aplicações Web.

O projeto demonstra desde a configuração do ambiente e dos WebDrivers até a automação dos cenários de teste, aplicação de técnicas de Partições de Equivalência e Valores Limite e utilização dos padrões Page Object Model e Fluent Page Object Model.

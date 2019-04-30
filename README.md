# continuous-integration
An example of a CI/CD gitlab with golang and mongoDB. It will help work with 
automated tests.

# CI/CD - version: English
  Continuous Integration (CI) and Continuous Delivery (CD) will allow your team to accelerate the process of developing your project. You will be able to provide faster results for customers and stakeholders.So how does CI/CD work? It's simple, CI integrates your team's code into a shared repository. Each merge (pull) request will pass by three phases: build, test, and deploy, who triggers a pipeline. CD will delivery your code validated to your aplication.
  There is a lot of reasons for you and your team use CI/CD in your application. CI/CD will help to:
    * fix problems quickly
    * allow the team to work(develop) faster
    * fast delivery of results to your customers and stakeholders
    * test your application automatically several times a day
    * fast feedbacks
  I use the gitlab for work with CI/CD because it offers a CI/CD serive to your application if you add a .gitlab-ci.yml file. It's very simple to use and understand. You have to add the .gitlab-ci.yml file in your shared repository and configure a Runner(https://docs.gitlab.com/ee/ci/runners/README.html) for the CI pipelines work. The .gitlab-ci.yml file lives in the root of your repository. You have to configure what CI does with project. In this repository you will find my example of .gitlab-ci.yml file using golang and mongodb.

# CI/CD - version: Portuguese
  A Continuous Integration (CI) and Continuous Delivery (CD) permitirão que sua equipe acelere o processo de desenvolvimento do seu projeto. Você sera capaz de entregar resultados mais rápidos para os clientes e as partes interessadas. Então, como o CI / CD funciona? É simples, o CI integra o código da sua equipe em um repositório compartilhado. Cada solicitação de merge (pull) request passará por três fases: build, test e deploy, que acionará o pipeline. O CD entregará seu código validado para a sua aplicação.
  Há muitas razões para você e sua equipe usarem o CI / CD em sua aplicação. Irá ajudar em:
    * corrigir problemas rapidamente
    * permitir que a equipe trabalhe (desenvolva) mais rapidamente
    * entrega rápida de resultados para seus clientes e partes interessadas
    * testar sua aplicação automaticamente várias vezes ao dia
    * feedbacks rápidos
  Eu uso o gitlab para trabalhar com CI / CD porque ele oferece um serviço de CI / CD para sua aplicação se você adicionar um arquivo .gitlab-ci.yml no diretório. É muito simples de usar e entender. Você precisa adicionar o arquivo .gitlab-ci.yml no seu repositório compartilhado e configurar o Runner (https://docs.gitlab.com/ee/ci/runners/README.html) o CI pipelines funcionar. O arquivo .gitlab-ci.yml vive na raiz do seu repositório. Você precisa configurar o que o CI faz com o projeto. Neste repositório você encontrará meu exemplo de arquivo .gitlab-ci.yml usando golang e mongodb.
  



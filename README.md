# Angular-control-navigation-flow

Angular: controle o fluxo de navegação :

https://cursos.alura.com.br/course/angular-controle-fluxo-navegacao

Projeto: gatitobook

>cd /api

>npm i

>npm start

>cd /gatitobook

>ng serve

login: cesar

senha: 123


Módulo 1:

* Como criar um componente reutilizável, recebendo atributos utilizando o decorator @Input
* Aprendemos a projetar um conteúdo externo no nosso componente utilizando a diretiva ng-content
* Criamos um serviço e enviamos além dos parâmetros, o header da requisição utilizando o objeto HttpHeaders
* Centralizamos a configuração do endereço da API utilizando o arquivo de environment.

Módulo 2:

* Como criar uma página utilizando diversos componentes reutilizáveis utilizando a composição.
* Aprendemos a utilizar o operador switchMap para concatenar dois fluxos de informações e não realizar um subscribe dentro de outro subscribe.
* Aprendemos a utilizar guarda de rotas para controlar o fluxo de navegação do usuário em nossa aplicação.

Módulo 3:

* Como parametrizar a rota da aplicação e utilizar essa informação com o serviço ActivatedRoute
* Aprendemos como anexar o token a todas as requisições ao backend criando um serviço do tipo Interceptor
* Criamos as funções de curtir e excluir e aprendemos mais sobre os operadores mapTo e catchError

Módulo 4:

* Como carregar informações do servidor enquanto a rota é carregada utilizando o serviço do tipo Resolver
* Criamos o componente de comentários e anexamos ele ao nosso componente de detalhe do animal
* Aprendemos a como resetar o formulário após a requisição utilizando o operador tap

Módulo 5:

* Como criar CSS para um componente específico, criando a animação do Menu da aplicação
* Criamos um serviço de upload e aprendemos como enviar uma foto para nosso backend
* Aprendemos a utilizar o HttpClient do Angular para monitorar o progresso da operação de upload.
* Como criar o pacote do nosso projeto de front-end para ser enviado para a produção através do comando ng build.

_________________________________________________________________________________________________________________

Angular: control the navigation flow:

https://cursos.alura.com.br/course/angular-controle-fluxo-navegacao

Project: gatitobook

>cd /api

>npm i

>npm start

>cd /gatitobook

>ng serve

login: cesar

password: 123

Module 1:

* We started a project using angular/cli as a support tool throughout our workflow. Using the --strict option, we turn on more type checking in our project, improving our code quality right from the start.
* We learned how to configure Bootstrap as the global CSS framework for our application.
* We also started structuring our application using the Angular module. With the lazy loading technique, we improve the initial loading of our application.
* We also studied how an Angular component is composed and what files angular/cli generates for us.
* We started to develop our first functionality: the Login form.

Module 2:

* How to interact with our backend using Angular's HttpClient service.
* How to use Angular's Dependency Injection mechanism to create our own services and inject them into our components.
* We also saw how to create a Template Driven form, in which all the assembly and the business rule are in the template file, and Angular controls the data model using the ngModel component.
* We created a generic messaging component and learned how to receive parameters using @Input and how to display dynamic content using Angular's interpolation.
* Finally, we implement the validations of our HTML form using the ngModel to get the field reference to evaluate if it is valid or not.

Module 3:

* How to create a form using the reactive forms technique, in which we have a little more settings, but we gain more possibilities and control over the form.
* We studied the routerLink directive and how Angular parses the passed path, evaluating first the component module route and then the global route.
* We created the new user registration service and used the good practice of creating an interface for the return of the backend so that we have better productivity and fewer errors.

Module 4:

* How to load information from the server while the route is loaded using the Resolver type service
* We create the comments component and attach it to our animal detail component
* We learned how to reset the form after the request using the tap operator

Module 5:

* How to create CSS for a specific component, creating the application Menu animation
* We created an upload service and learned how to upload a photo to our backend
* We learned how to use Angular's HttpClient to monitor the progress of the upload operation.
* How to package our front-end project to be sent to production using the ng build command.

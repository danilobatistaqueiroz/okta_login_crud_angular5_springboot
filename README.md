# Login and CRUD with Angular 5 and Spring Boot

### This project uses Authentication, Angular Material, Giphy, H2 database, JPA

This project uses:  

In Angular  
* NgForm (@angular/forms)
* rxjs/Subscription
* rxjs/Observable
* ActivatedRoute (@angular/router)
* HttpClient (@angular/common/http)
* GiphyService
* OktaAuthService
* OktaAuthModule
* BrowserAnimationsModule
* Angular Material
* HttpInterceptor

In Java  
* Lombok
* JPA
* JpaRepository
* CrossOrigin (CORS)
* FilterRegistrationBean
* CorsFilter


**Steps to use**
To install this application, run the following commands:

`git clone git@github.com:danilobatistaqueiroz/okta_login_crud_angular5_springboot.git`  
`cd okta_login_crud_angular5_springboot`  
This will get a copy of the project installed locally.   
To install all of its dependencies and start each app, follow the instructions below.  

To run the server, cd into the server folder and run:  
`./mvnw spring-boot:run`  

To run the client, cd into the client folder and run:  
`npm install && npm start`  


**Project Structure**

![angular5_crud_structure](https://user-images.githubusercontent.com/32627919/36615945-d30541dc-18c0-11e8-9dfc-5f7ea2ba3cee.PNG)



**Screenshots**

![login](https://user-images.githubusercontent.com/32627919/36645200-e11be210-1a43-11e8-8cc7-c4acddadfa78.PNG)

![okta](https://user-images.githubusercontent.com/32627919/36645201-e13fbc8a-1a43-11e8-8bb8-2e6c02c3f872.PNG)

![home](https://user-images.githubusercontent.com/32627919/36645204-e19c850a-1a43-11e8-8119-ec5f6cc04adc.PNG)

![list](https://user-images.githubusercontent.com/32627919/36645199-e0f84396-1a43-11e8-8428-f2fce402d8be.PNG)

![car-list](https://user-images.githubusercontent.com/32627919/36645203-e17d908c-1a43-11e8-9bed-043f3fb5d165.PNG)

![car-add](https://user-images.githubusercontent.com/32627919/36645202-e15f3056-1a43-11e8-8d78-fe1427fd9096.PNG)



**Some steps to create the application**

http://start.spring.io  
choose: Web, JPA, Actuator, H2, Rest Repositories, Lombok

**Create a Client with Angular Cli**
https://cli.angular.io
npm install -g @angular/cli
ng new client
cd client
npm install --save @angular/material @angular/cdk
npm install --save @angular/animations
https://material.angular.io
ng g s car
mkdir -p src/app/shared/car
mv src/app/car.service.* src/app/shared/car/.
ng g c car-list
ng serve
http://localhost:4200
ng g c car-edit
https://www.npmjs.com/package/@okta/okta-angular
npm install --save @okta/okta-angular
ng g c home



___



Links:

https://gist.github.com/danilobatistaqueiroz/2eb727d7ca164b97552cff7ffaa78d3a

https://developer.okta.com/blog/2017/12/04/basic-crud-angular-and-spring-boot

https://dev-121524-admin.oktapreview.com/dev/console

https://developer.okta.com/quickstart/#/angular/nodejs/express


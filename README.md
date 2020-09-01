Angular setup:-
==============
Note : we need vs code IDE for angular project

1.install node js.
  Confirm node : node -v
               : npm -v
2.install angular cli 
	npm install -g @angular/cli   (g stands for global install)
  Confirm angular : ng -version
  NPM- Node Packager Manager
  
 3.navigate to project directory
 
 4.create project by hiting
	 ng new demo-app
 
 Integrtion with Git
 ===================
 1.checkout angular project from Github:-
 	a.	Go to View --> Command paletee..--> Git Clone --> enter url and press enter button
	b.	select parent directory to save angular project in local drive.
	c. 	If we get any exception or any issues hit bellow command.
		npm install --save-dev @angular-devki/build-angular.
Note : to run app use "ng serve" or to stop app use "CTRL + C - Y".
	
Refrences:-
=========
https://nodejs.org/en/download/?utm_source=blog

vs code install
https://github.com/Java-Techie-jt/     -----hit hub url
https://www.javainuse.com/spring/ang7-crud

routing-demo application:
https://www.freakyjolly.com/angular-8-what-is-routing-and-how-to-add-in-angular-application-very-quick/

Add Navigation Links in Application
For navigation in the application, we can use routerLink directive.

There is also another useful directive routerLinkActive, which adds a specified class when that path is opened/ active.

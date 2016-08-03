The majority of the samples you see here involves mixed projects (net451) that will run only in Windows. For most of us .NET developers, this is the reality for forseeable future. We ain't gonna port multi years systems to run on Linux. We want to improve the creaky .NET MVC 3.0 that we had lying around and bring it to aspnetcore MVC.

* [Hello World with reload](https://github.com/dodyg/practical-aspnetcore/tree/master/hello-world-with-reload)

  Setup your most basic web app and enable the change+refresh development experience. 
  
  We are using ```IApplicationBuilder Run```, an extension method for adding terminal middleware.

* [Hello World with middlewares](https://github.com/dodyg/practical-aspnetcore/tree/master/hello-world-with-middleware)

  ASPNetCore is built on top of pipelines of functions called middleware. 
  
  We are using ```IApplicationBuilder Use```, an extension method for adding middleware and ```IApplicationBuilder Run```.
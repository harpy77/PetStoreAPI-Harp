Read Me Notes - by Harp Singh 2019
==================================
The solution contained herein, is an API built using the ASP.NET Web Application framework. It is based on the requirements specified at https://petstore.swagger.io

Its target framework is .NET 4.6.1 and has been developed using the C# language, MVC design model, Entity Framework, Linq & NuGet packages.

The solution is neither 100% complete or functional in its entirety. The was due to technical issues I had in generating a database context and entity classes. Nevertheless the structure and approach I attempted to use can be seen the C# classes that created in Models & Controllers folders (uncommenting required) 

The operational endpoints provided with this solution act to service GET requests. This can be performed by running the solution within a valid Visual Studio IDE (2017 or 2019) and browsing to the any of the following locations:


Pets
-----
http://<<server or localhost>>/api/pet/
http://<<server or localhost>>/api/user/{petid}


Users
-----
http://<<server or localhost>>/api/user/
http://<<server or localhost>>/api/user/{id}


Orders
------
http://<<server or localhost>>/api/order/
http://<<server or localhost>>/api/order/{id}

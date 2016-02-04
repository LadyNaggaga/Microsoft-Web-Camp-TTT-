# Microsoft Web Camp Train The Trainer Repo 

## Suggested Agenda 
|Time	|Session|
|---	|---	|
| 8:30 AM  	| 	Welcome and keynote	|
| 9:00 - 10:00 AM  	|  [Intro to ASP.NET Core 1.0, MVC 6 and Visual Studio 2015 Web Tooling](https://github.com/Microsoft-Web/WebCampTrainingKit/tree/aspnet-5-updates/Presentation/ASPNET-and-VS-Web-Tooling/GettingStartedASPNET5)	|
| 10:00 -11:00 AM  	| [Instructor led/hands-on labs on ASP.NET Core 1.0 & MVC 6 & VS 2015 Tooling](https://github.com/Microsoft-Web/WebCampTrainingKit/tree/aspnet-5-updates/HOL/IntroToASPNET5) 	|
| 11:00 -11:15 AM  	| Break	|
| 11:15 -11:45 AM  	| [Demo - Building and deploying an ASP.NET application](https://github.com/Microsoft-Web/WebCampTrainingKit/tree/aspnet-5-updates/Presentation/Build-and-deploy-ASPNET/GeekQuiz-Build-and-deploy-ASP)|
| 11:45 AM - 12:30 PM 	|[Building web front ends for both desktop and mobile using the latest web standards](https://github.com/Microsoft-Web/WebCampTrainingKit/blob/aspnet-5-updates/Presentation/Modern-Web-Front-Ends/GeekQuiz-SPA-Interface)	|
| 12:30 - 1:00 PM  	| Lunch  	|
| 1:00 PM - 2:00 PM 	| [Instructor led / hands-on labs ASP.NET MVC 6 & SPA](https://github.com/Microsoft-Web/WebCampTrainingKit/blob/aspnet-5-updates/HOL/AspNetApiSpa)  	|
| 2:00 PM - 3:00 PM 	| API Services for both [web](https://github.com/Microsoft-Web/WebCampTrainingKit/tree/aspnet-5-updates/Presentation/HTTP-Services/GeekQuiz-Web-API-backend) and [devices](https://github.com/Microsoft-Web/WebCampTrainingKit/tree/aspnet-5-updates/Presentation/HTTP-Services/GeekQuiz-Web-API-Universal-Windows)	|
| 3:00 PM - 4:00 PM 	| Running, improving and maintaining a site in the real world.[Scaling](https://github.com/Microsoft-Web/WebCampTrainingKit/tree/aspnet-5-updates/Presentation/ASPNET-in-Production/Scaling-a-production-website), [EF & Deployment](https://github.com/Microsoft-Web/WebCampTrainingKit/tree/aspnet-5-updates/Presentation/ASPNET-in-Production/Handling-change-EF-migrations), &[AAD](https://github.com/Microsoft-Web/WebCampTrainingKit/tree/aspnet-5-updates/Presentation/ASPNET-in-Production/Handling-change-EF-migrations) 	|
| 4:30 PM - 5 PM  	| Wrap-up(Q&A) / Evaluations / Raffle   	|

#Sessions Descriptions

###Introduction to  ASP.NET Core 1.0  & MVC 6 & VS 2015 Tooling

- Start by explaining the One ASP.NET experience in VS2015. There’s no MVC project type or Web Forms project any longer, there’s just ASP.NET.  Make sure that the audience is aware that they can mix Web Forms and Web API, or MVC and SignalR.  It is all supported. 
- One ASP.NET Demo: In this demo create a new one ASP.NET Tool in VS 2015. Start with  Web Forms app and create a simple model "Person", and use the new scaffold an MVC & Web API .
    Goal of the demo is to 
    - Create a new ASP.NET 4.5 site 
    - Create a simple model person
    - scaffold an MVC controller for person 
    - scaffold a web api controller for person 
Introduce ASP.NET Core 1.0
- Introduce the VS 2015 web dev features including Grunt, Gulp, Bower, and NPM integration 
- Jump into the demo on [VS and web tool essentials](https://github.com/Microsoft-Web/WebCampTrainingKit/tree/master/Presentation/02-ASPNET-and-VS-Web-Tooling/Visual-Studio-and-Web-Essentials) and [Tag Helpers](https://github.com/Microsoft-Web/WebCampTrainingKit/tree/master/Presentation/02-ASPNET-and-VS-Web-Tooling/TagHelpers)

### Building web front ends for both desktop and mobile using the latest web standards

This session gives an overview of modern web standards and modern JavaScript libraries such jQuery, Knockout.js, AngularJS, and Ember.js. [Training video](https://channel9.msdn.com/events/Windows-Azure-DevCamps/WebCamp/WEB4)

### API Services for both web and devices

This session will begin by explaining what HTTP services are and some HTTP API design principles like REST and Hypermedia.
[Training video](https://channel9.msdn.com/Events/Windows-Azure-DevCamps/WebCamp/WEB5)
This  video covers the basics. The demo at the end is Ember.js (and a bit dated at this point). Consider holding off on the documented Angular demo (Building the GeekQuiz front end) to have time for the [HOL for Api & SPA](https://github.com/Microsoft-Web/WebCampTrainingKit/tree/master/HOL/AspNetApiSpa)
Also consider an example of bower (either in the existing templates or from a new command line) to install jQuery
bower init
bower install jQuery --save

Note the added files in bower_components/jquery/dist folder. We've seen lots of attendees lately not having any experience with npm or bower.

### Running, improving and maintaining a site in the real world
Talk about running, improving, and maintaining a site in the real world in the context of three different scenarios: scale, change, and environments.
[Training Video](https://channel9.msdn.com/Events/Windows-Azure-DevCamps/WebCamp/WEB6)



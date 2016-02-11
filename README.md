# Microsoft Web Camp Train The Trainer Repo 

### Table of Content
- [Requirements](https://github.com/LadyNaggaga/Microsoft-Web-Camp-TTT-#requirements)
- [Suggested Agenda](https://github.com/LadyNaggaga/Microsoft-Web-Camp-TTT-#suggested-agenda):  Please make sure to [review original content](https://github.com/Microsoft-Web/WebCampTrainingKit) and make it your own.
- [Session Descriptions](https://github.com/LadyNaggaga/Microsoft-Web-Camp-TTT-#requirements) 
- [FAQ](https://github.com/LadyNaggaga/Microsoft-Web-Camp-TTT-/blob/master/README.md#faq)

## Requirements
|||
|---	|---	|
| Tools 	| 	[ASP.NET Core RC](https://go.microsoft.com/fwlink/?LinkId=627627) |
| Content	| [Web Camp Installer](https://github.com/Microsoft-Web/WebCampTrainingKit/releases/tag/v2016.02.09).  |
| Nice to haves 	| USBs with 	[ASP.NET Core RC](https://go.microsoft.com/fwlink/?LinkId=627627)	|

## Suggested Agenda 
|Time	|Session|
|---	|---	|
| 8:30 AM  	| 	Welcome and [keynote](https://github.com/Microsoft-Web/WebCampTrainingKit/tree/master/Presentation/01-Keynote)	|
| 9:00 - 10:00 AM  	|  [Intro to ASP.NET Core 1.0, MVC and Visual Studio 2015 Web Tooling](https://github.com/Microsoft-Web/WebCampTrainingKit/tree/master/Presentation/02-ASPNET-and-VS-Web-Tooling)	|
| 10:00 -11:00 AM  	| [Instructor led/hands-on labs on ASP.NET Core 1.0 & MVC 6 & VS 2015 Tooling](https://github.com/Microsoft-Web/WebCampTrainingKit/tree/master/HOL/IntroToASPNETCore) 	|
| 11:00 -11:15 AM  	| Break	|
| 11:15 -11:45 AM  	| [Demo - Building and deploying an ASP.NET application](https://github.com/Microsoft-Web/WebCampTrainingKit/tree/master/Presentation/03-Build-and-deploy-ASPNET)|
| 11:45 AM - 12:30 PM 	|[Building web front ends for both desktop and mobile using the latest web standards](https://github.com/Microsoft-Web/WebCampTrainingKit/tree/master/Presentation/04-Modern-Web-Front-Ends)	|
| 12:30 - 1:00 PM  	| [Lunch](http://img1.joyreactor.com/pics/post/gif-lunch-food-bun-373379.gif)  	|
| 1:00 PM - 2:00 PM 	| API Services for both [web](https://github.com/Microsoft-Web/WebCampTrainingKit/tree/master/Presentation/05-HTTP-Services/GeekQuiz-Web-API-Universal-Windows) and [devices](https://github.com/Microsoft-Web/WebCampTrainingKit/tree/master/Presentation/05-HTTP-Services/GeekQuiz-Web-API-backend)	|
| 2:00 PM - 3:00 PM 	| [Instructor led / hands-on labs ASP.NET MVC 6 & SPA](https://github.com/Microsoft-Web/WebCampTrainingKit/tree/master/HOL/AspNetApiSpa)  	|
| 3:00 PM - 4:00 PM 	| [Running, improving and maintaining a site in the real world](https://github.com/Microsoft-Web/WebCampTrainingKit/tree/master/Presentation/06-ASPNET-in-Production). 	|
| 4:30 PM - 5 PM  	| Wrap-up(Q&A) / Evaluations / Raffle   	|

#Suggested Sessions & Descriptions

###Introduction to  ASP.NET Core 1.0  & MVC & VS 2015 Tooling

- Start by explaining the One ASP.NET experience in VS2015. There’s no MVC project type or Web Forms project any longer, there’s just ASP.NET.  Make sure that the audience is aware that they can mix Web Forms and Web API, or MVC and SignalR.  It is all supported. 
- One ASP.NET Demo: In this demo create a new one ASP.NET Tool in VS 2015. Start with  Web Forms app and create a simple model "Person", and use the new scaffold an MVC & Web API .
    Goal of the demo is to 
    - Create a new ASP.NET 4.5 site 
    - Create a simple model person
    - scaffold an MVC controller for person 
    - scaffold a web api controller for person 

### Introduce ASP.NET Core 1.0
- Must reads on name change and release timing: 
 - http://www.hanselman.com/blog/ASPNET5IsDeadIntroducingASPNETCore10AndNETCore10.aspx
 - https://blogs.msdn.microsoft.com/webdev/2016/02/01/an-update-on-asp-net-core-and-net-core/
- Introduce the VS 2015 web dev features including Grunt, Gulp, Bower, and NPM integration 
- Jump into the demo on [VS and web tool essentials](https://github.com/Microsoft-Web/WebCampTrainingKit/tree/master/Presentation/02-ASPNET-and-VS-Web-Tooling/Visual-Studio-and-Web-Essentials) and [Tag Helpers](https://github.com/Microsoft-Web/WebCampTrainingKit/tree/master/Presentation/02-ASPNET-and-VS-Web-Tooling/TagHelpers)

### Building web front ends for both desktop and mobile using the latest web standards

This session gives an overview of modern web standards and modern JavaScript libraries such jQuery, Knockout.js, AngularJS, and Ember.js. [Intro to the basics](https://channel9.msdn.com/events/Windows-Azure-DevCamps/WebCamp/WEB4)

### API Services for both web and devices

This session will begin by explaining what HTTP services are and some HTTP API design principles like REST and Hypermedia.
[Intro to the basics](https://channel9.msdn.com/Events/Windows-Azure-DevCamps/WebCamp/WEB5)
This  video covers the basics. 

The demo at the end is Ember.js (and a bit dated at this point). Consider holding off on the documented Angular demo (Building the GeekQuiz front end) to have time for the [HOL for Api & SPA](https://github.com/Microsoft-Web/WebCampTrainingKit/tree/master/HOL/AspNetApiSpa)


Also consider an example of bower (either in the existing templates or from a new command line) to install jQuery

-bower init

-bower install jQuery --save

Note the added files in bower_components/jquery/dist folder. We've seen lots of attendees lately not having any experience with npm or bower.

### Running, improving and maintaining a site in the real world
Talk about running, improving, and maintaining a site in the real world in the context of three different scenarios: scale, change, and environments.  Goal of the talk and demo is to give the attendees a sense of the tooling and support for adapting to the change in a real world environrment.

- Cover the issues that are introduced once your site is in production. [This](https://channel9.msdn.com/Events/Windows-Azure-DevCamps/WebCamp/WEB6) video shows the deck and demos.
- Consider swapping demos that are presented in the slides for the EF Migrations, Deploying and Preforming a RollBack in Produciton demos from the [HOL](https://github.com/Microsoft-Web/WebCampTrainingKit/tree/master/HOL/WebSitesInProduction#Exercises) (Exercises 1,2,3).

### FAQ 
##### Web Forms 
- Are Web Forms going away ?  No Web Forms are not going way. 
- How do I integrate MVC with my currnet Web Form application?

##### WCF
- Will WCF be supported in the future ?
- Can I migrate from WCF to Web APIs?
### Content Ideas
If you have any content ideas, demos and demos scripts please link them below.
- Getting Started on Mac (Maria to add demo script)
- [Docker](https://github.com/aspnet/aspnet-docker)
- Dashboards, Web APIs , MVC & SPA (work in progress)


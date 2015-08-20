# Monona
Project Monona

Welcome to the first draft of the first syllabus for the first apps training course! 

What we'll cover: 
Who we are & Why we're doing this
General time line
Example Apps
Introduction to the Apps Framework  
Resources 

What we'll cover: Zendesk Apps framework, how to build an app, how to troubleshoot an app, how you should handle app related tickets, what to do if you are interested and want to learn more.

Who we are and why we are doing this: James Peterson & Jordan Wheelock. We're doing this because it's imperative to not write off all apps questions as "custom coding" when it is in our scope of knowledge to provide documentation and assistance regarding Zendesk Apps.  You are Tier 2 and will see a variety of App questions, from the basic (do you have an app that does), to the more philosophical (can an app do this), to the investigative (I'm using this method, I expect result A, but I'm seeing result B, why?), to the explanatory (how do I set a field?). 

Timeline: We'll work together to create a Zendesk App, meeting two or three times per month on Fridays. This workshop could last for several months depending on the aptitude and interest of the participants. 

How: We will provide explanations of common App methods, troubleshooting strategies, insight, and good resources.  This will be interactive with the participants expected to build their own app.  We will have the group divided into teams.


Example Apps: Pop Pop, ZCC, Out of Office. 

Introduction to the Apps Framework: 
Framework: A layered structure indicating what kind of programs can or should be built and how they would interrelate. 
Zendesk App: A Zendesk app is most commonly thought of as a ticket sidebar app, such as the time tracking app that we use on support.zendesk.com. However a Zendesk app may also be a top bar app, or navigation bar app (left side bar). 

The framework was developed along with the New Zendesk interface as a way to allow for extensibility without damaging the core product.  With classic Zendesk, we often see custom widgets changing core functionality of Zendesk interface or preventing us from troubleshooting easily (hidden Settings page).

Basic app files: 
manifest.json
app.css
app.js
translations
assets
templates
README.md

Resources: 
Apps Framework Documentation - https://developer.zendesk.com/apps/docs/agent/introduction
Github Demo Apps Repo - https://github.com/zendesk/demo_apps/
Zendesk Labs Repo - https://github.com/zendesklabs
ZCC - https://github.com/zendeviancup/ghost-triggers
Out of Office - https://github.com/zendesklabs/out_of_office_app
Developer Diary - https://support.zendesk.com/hc/en-us/articles/203691326-Developer-diary-Building-a-Zendesk-app-Part-1-
Zendesk Apps Framework Section in HC - https://support.zendesk.com/hc/en-us/sections/200625656-Zendesk-Apps-framework

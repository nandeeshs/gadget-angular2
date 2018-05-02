# gadget-angular2
scaffold for angularj2 using yeoman



# An OpenSocial Gadget Written In Angular2

## Intro
This is an example project for creating an opensocial gadget for hosting in an opensocial container.This project is embedded with angular2 lib
with simple "Hello World" app.

## Steps 
First install the necessary dependencies, this may take a few minutes.
```
npm install
```
Start a Development Server
```
npm run serve
```
You can now access the gadget or execute standalone from http://localhost:3000 and can see "Welcome to Angular App!" getting displayed.

## Adding to an Open Social Container (dashboard)
copy and place gadget.xml present under public directory to .tmp directory (untill we automate this).
To add this gadget to an open social container, specify the URL to the gadget.xml file served by this Angular application, e.g.
http://localhost:3000/gadget.xml
If you change the host/port, make sure you edit the gadget.xml accordingly.

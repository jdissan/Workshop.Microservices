# Demos

This folder contains all the demos available during the Microservices Workshop

## ASP.Net MVC - demo

The `ASP.Net MVC` solution demoes UI Composition techniques when using regular ASP.Net MVC 5. To run the demo ensure that the following projects are set as startup projects:

* `Divergent.Sales.API.Host`
* `Divergent.Shipping.API.Host`
* `Divergent.Frontend`

## Vanilla TypeScript - demo

The `Vanilla TypeScript` solution demoes UI Composition techniques hosting the composition engine directly in the Single Page Application, that is build using plain Typescript and no UI/Presentation frameworks. To run the demo ensure that the following projects are set as startup projects:

* `Divergent.Sales.API.Host`
* `Divergent.Shipping.API.Host`
* `Divergent.Frontend`

The demo depends on `Node.js` and `npm` that need to be installed on the user machine. Ensure also that `Grunt` npm package is installed globally by running the following command at a command prompt:

> npm install -g grunt-cli

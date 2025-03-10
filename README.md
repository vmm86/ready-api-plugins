ReadyAPI Plugin Development Kit
==================================

Here you'll find everything needed to get started with building plugins for SmartBear's ReadyAPI Platform.

* Go to http://readyapi.smartbear.com/dev/start for documentation, samples, etc
* Check out and build this project locally (with ```mvn install```) to get access to the [maven archetype](https://github.com/SmartBear/ready-api-plugins/tree/master/ready-api-plugin-archetype) and [plugin template](https://github.com/SmartBear/ready-api-plugins/tree/master/ready-api-plugin-template) for getting started
  quickly with building plugins.
    
We've also included documentation on how to build different plugin components.

* [Actions](actions-basic.md) - how to add menu and toolbar items
* [Listeners](listeners.md) - how to handle events occurring during the usage of ReadyAPI, for example test-executions,
project changes, etc.                                      
* [Import and Discovery methods](import-and-discovery.md) - how to add new ways of creating ReadyAPI projects from 
 external data

And some general guidelines for ReadyAPI plugin development.

* [General Guidelines](dev-guidelines.md) (Logging, Analytics, etc...)
* [Creating dialogs](creating-dialogs.md)

If you're looking for some specific content - please don't hesitate to 
[open an issue](https://github.com/SmartBear/ready-api-plugins/issues/new)!

##Existing Plugins

Many of the existing plugins are open-sourced here at GitHub and make use of the above outlined extension points and 
concepts. Have a look at them to get an understanding of how to add similar features to your plugins:

 * [Swagger Plugin](https://github.com/olensmar/soapui-swagger-plugin) Adds functionality for importing and exporting
 Swagger definitions to/from REST APIs,
 * [RAML Plugin](https://github.com/olensmar/soapui-raml-plugin) Adds functionality for importing and exporting RAML
 definitions to/from REST APIs. Also has an action to browser the Mulesoft ApiHub API directory and import API definitions
 directly from there.
 * [API Blueprint Plugin](https://github.com/olensmar/soapui-blueprint-plugin) Adds functionality for importing and exporting
 API-Blueprint definitions to/from REST APIs. 
 * [Groovy Console Plugin](https://github.com/olensmar/soapui-groovy-console-plugin) Adds an interactive Groovy Console for 
 trying out groovy scripts dynamically within ReadyAPI
 * [3Scale Plugin](https://github.com/SmartBear/ready-3scale-plugin) Allows you to import APIs directly from a 3Scale hosted developer portal.


 

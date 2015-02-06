# EmberJS

EmberJS samples and some full applications

## About
Ember is a MVC javascript framework who allows to create scalable single-page applications.

## Elements
#### Routes
A route object corresponds to a URL that synthesize the state of the application. Routes are defined in the singleton Router object (the core concept of Ember)

#### Models
Every route has an associated model, containing the data of the application.

#### Controllers
Controllers are used for add logic to the application and is used to present the model's properties to the template. If the template is associated with a single model record, the controller generally inherits from ObjectController; inherits from ArrayController if the model has a list of records.

#### Templates
Ember use the Handlebars templating library to describe the user interface. Templates are used to build the HTML tags and embed expressions that update dynamically.

#### Views
Views are used typically to add sophisticated handling of user events, JavaScript animationsm, custom graphics not made with CSS or create a re-usable component.

#### Components
Components are specialized views for creating custom elements (application-specific HTML tag) in acording with the W3C, that can be easily reused in other templates. 

## Requirements:

Ember v1.2.*+

Ember-data v1.0*+

Bootstrap v3.0.*+

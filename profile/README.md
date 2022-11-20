# Hermes-Flutter

Private repository of flutter packages that meet all of the generic needs of a mobile app.

These packages allow a developer to, once cloned, inject each layer of each package into the apps DI container providing them with a range of services and default pages to provide a basic app flow.

All classes implementations for classes that are registered on the DI container are overridable so if the developer is required to implement certain functions differently or override pages in the app flow then they are able to do so by extending the existing implementation class and re-registering the new implementation to the super class type on the DI container during bootstap faze.

Each package is fully tested and functions as expected with all exceptions handled with helpful data structures to provide this information back to the developer when exceptions are thrown.

# Contact

For more information about this project please contact: 

josheverett02@gmail.com
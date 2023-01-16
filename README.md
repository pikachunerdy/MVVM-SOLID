# Blazor MVVM
Blazor MVVM pattern with SOLID principles

# Why?
I have seen many examples of Web developments trying to apply MVVM but none is based on applying robust SOLID principles.
There are many examples of MVVM binding models directly in the view, Models with services, VM with business logic/initialization, etc...

# SOLID MVVM

MVVM architecture to introduce between VM and Model the following components with different responsibilities:

- Creation - Have control of the creation of the infrastructure through factories
- Initialization - VM initializers
- Syncronization - DataSource component to synchronize VM and Model
- Business Logic - Commands/CommandManager/EventManager with the responsibility of containing the delegates that execute the business logic.


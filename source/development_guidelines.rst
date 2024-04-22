===============
Design Document
===============

Overview
------------

The Design Document builds directly upon the Software Architecture and refines the decisions made in the architecture phase. The transition between Software Architecture and Software Design is fluid. In contrast to the Software Architecture, Software Design involves decisions related to implementation.

Modeling Core Structures of the Application
--------------------------------------------

Important recurring structures of the application are modeled using a class diagram. If a framework is utilized, document the interaction and integration of the framework into the application.

Patterns Used
----------------

The following patterns are employed within the application:

    - [List the patterns used and describe how they are implemented within the application]

Domain Model
----------------

The domain model encompasses the classes and objects of the domain, excluding technical classes such as DAOs or UI classes. It can be modeled using a class diagram or an EER diagram.

Exception Handling
---------------------

Describe the exception handling concept of the application:

    - Types of Exceptions Used: [Checked or Runtime Exceptions]
    - Application-Specific Exceptions: [Specify any application-specific exceptions used]

REST Specification
----------------------

Define the URLs under which the individual server functions are reachable. Documentation can be provided using Swagger UI.

Logging
--------

Specify the log levels used:

    - Log Levels: [List the log levels used]
    - Definition of Log Messages: [Define which log messages are output at each log level]

Security Aspects
-----------------

Describe the authentication and authorization mechanisms within the application:

    - Authentication and Authorization: [Explain how authentication and authorization are implemented]
    - Security Techniques: [Describe the techniques used to prevent security vulnerabilities in the application]

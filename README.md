# NServiceBus-RetailDemo-project

The solution contains four projects. The ClientUI, Sales, Billing and Shipping endpoints that communicate with each other using NServiceBus messages. The ClientUI endpoint is implemented as a web application and is the entry point to our system. The Sales, Billing and Shipping endpoints are implemented as console applications, contain business logic related to processing and fulfilling orders. Each endpoint references the Messages assembly, which contains the definitions of messages as simple class files. 


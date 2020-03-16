# Model-View-Controller

## Why Model-View-Controller? 

Many applications start from something small, such as several hundred lines of code prototype of a toy application written in one evening. When you add new features and the application code clutters, it becomes much harder to understand how it works and to modify it, especially for a newcomer. The Model-View-Controller \(MVC\) pattern serves as the basis for software architecture that will be easily maintained and modified

## What are the parts of MVC?

The main idea of MVC is about separating an application into three parts: **model**, **view**, and **controller**. There is an easy way to understand MVC—the model is the data and its business logic, the view is the window on the screen, and the controller is the glue between the two.

## What is Model?

The model is a foundation of the application because, while the view and controller depend on the model, the model is independent of the presentation or the controller.

The model provides knowledge: data, and how to work with that data. The model has a state and methods for changing its state but does not contain information on how this knowledge can be visualized.

This independence makes working independently, covering the model with tests and substituting the controllers/views without changing the business logic of an application.

## What is View?

View receives data from the model through the controller and is responsible for its visualization. It should not contain complex logic; all such logic should go to the models and controllers.

## What Controller?

The responsibility of the controllers is to receive data from the request and send it to other parts of the system. Only in this case, the controller is "thin" and is intended only as a bridge \(glue layer\) between the individual components of the system.




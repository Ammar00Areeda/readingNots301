## what is Component

A Component is one of the core building blocks of React. In other words, we can say that every application you will develop in React will be made up of pieces called components. Components make the task of building UIs much easier. You can see a UI broken down into multiple individual pieces called components and work on them independently and merge them all in a parent component which will be your final UI.

## What are the charactistics of a component?

Path. A location in the folder in which to store components. Use folders to organize components in a hierarchical manner.

Component name. The name of the component.

* Component type name. The name of the component type that is associated with a component. See Component Type Concepts.

*The provisioning system includes some component types that support generic models, such as files and directories. Additional component types can be added to the system by importing plug-ins that are specific to application domains, such as Microsoft Windows and WebLogic.

* Version number. The version number of the component. Each time a component is modified, the version number increments.

* At check-in time, you choose how to increment the version number. You can increment by the major number, which is to the left of the decimal point, or by the minor number, which is to the right of the decimal point.

* Platform. The operating system on which this component can be installed.

* Check-in date. The date and time when the component was checked in.

* Check-in user. The user ID of the person who checked in the component. This attribute is useful when you want to audit provisioning system processes.

* Label. An optional string that you can use to categorize or group components.

* Category. An optional object that you can use to filter the component list. After you create a category object, you can subsequently use it to group components.

* Description. An optional string that describes the component. Use this attribute to provide meaningful information about the component.

* Source. The resource that has been included in this component. The source can be a single file resource or a list of other components.

* Component variables. A list of variables and their values (name-value pairs) that are required to deploy a component resource. See Component Variables.

* Procedures. A set of instructions that specifies what to do with the resources and variables.

* Hidden. A characteristic that indicates whether you can view the component in a list of components. By default, components are not hidden.

## What are the advantages of using component based architecture?

Advantages. Ease of deployment − As new compatible versions become available, it is easier to replace existing versions with no impact on the other components or the system as a whole. Reduced cost − The use of third-party components allows you to spread the cost of development and maintenance.


## What is props short for?

all know that React Components allow you to split the application interfaces into reusable, independent segments. “Props” stands for properties. It is a special keyword in React which is used for passing data from one component to another. Logically, components are just like JavaScript functions.

## How are props used in React?

Props” is a special keyword in React, which stands for properties and is being used for passing data from one component to another. Furthermore, props data is read-only, which means that data coming from the parent should not be changed by child components.

## What is the flow of props?

There are basically two ways that data gets handled in React: props and state (available through this.state ). A third is context, not discussed here, which is more advanced and not currently guaranteed stable (React Docs: Context).
While a component can’t change its own props, it can change its state…Props and state are used as input for the render() method to determine its output. The render() method also calls the diff algorithm which recognizes any changes in the component and logs them for batching to the “real” DOM.
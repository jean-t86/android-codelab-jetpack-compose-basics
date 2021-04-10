# Jatpack Compose Basics Codelab

Jetpack Compose is a modern toolkit designed to simplify UI development. It combines a reactive 
programming model with the conciseness and ease of use of the Kotlin programming language. It is 
fully declarative, meaning you describe your UI by calling a series of functions that transform data 
into a UI hierarchy. When the underlying data changes, the framework automatically recalls these 
functions, updating the view hierarchy for you.

A Compose app is made up of composable functions - just regular functions marked with @Composable, 
which can call other composable functions. A function is all you need to create a new UI component. 
The annotation tells Compose to add special support to the function for updating and maintaining 
your UI over time. Compose lets you structure your code into small chunks. Composable functions are 
often referred to as "composables" for short.

By making small reusable composables - it's easy to build up a library of UI elements used in your 
app. Each one is responsible for one part of the screen and can be edited independently.

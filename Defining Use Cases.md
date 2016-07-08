# Defining the Use Cases
The first thing we need to do is to start describing the application that we want to build. This could just be a big long text with everything that we can think of and sometimes that is a helpful first step, but we're going to put a little bit of structure into our use cases so that it will aid us in designing and developing the software later on. The reason why we want a certain structure to the use cases is so that we can run tests against them to verify if our application satisfies the use cases. To do that, we'll use Gherkin syntax to describe the system that we want to build. By using Gherkin we gain a couple of advantages. They can be read by non-developers because it's just plain language and not source code. Also there are testing tools that know how to read Gherkin syntax and turn it into executable code that can be used to test our application.

If we were to define every use case right now we would quickly get bored and lose momentum so instead we are going to define the most obvious use case that we can deliver and we'll grow the system using an iterative planning, development, testing, deployment process.

## Use Case Structure
TODO: Reference Gherkin Specification Book

At the most basic level, the Gherkin syntax is written in a "Given-When-Then" template. The Given part defines the context of the use case. The When part of the template describes one or more events that occur within the system. The Then part ensures or validates that the expected outcome(s) take place. It is important to keep the use cases written in the vocabulary of the bussines and not the developers. They should be easy to read and understand by non-developers.

## Use Case 1: Create a Tenant
The most straightforward thing we can do is to create a new Tenant because it is the container that holds it's Customers so it is a natural starting point.



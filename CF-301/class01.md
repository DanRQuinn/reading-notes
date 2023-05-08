# Introduction to React and Components

## Component-Based Architecture

### Components

A component is a software object, intended to interact with other components, encapsulating certain functionality or a set of functionalities. It has an obviously defined interface and conforms to a recommended behavior common to all components within an architecture.

A component can have three different views − object-oriented view, conventional view, and process-related view.

Object-oriented view

A component is viewed as a set of one or more cooperating classes. Each problem domain class (analysis) and infrastructure class (design) are explained to identify all attributes and operations that apply to its implementation. It also involves defining the interfaces that enable classes to communicate and cooperate.

Conventional view

It is viewed as a functional element or a module of a program that integrates the processing logic, the internal data structures that are required to implement the processing logic and an interface that enables the component to be invoked and data to be passed to it.

Process-related view

In this view, instead of creating each component from scratch, the system is building from existing components maintained in a library. As the software architecture is formulated, components are selected from the library and used to populate the architecture.

Characteristics of Components
Reusability − Components are usually designed to be reused in different situations in different applications. However, some components may be designed for a specific task.

Replaceable − Components may be freely substituted with other similar components.

Not context specific − Components are designed to operate in different environments and contexts.

Extensible − A component can be extended from existing components to provide new behavior.

Encapsulated − A A component depicts the interfaces, which allow the caller to use its functionality, and do not expose details of the internal processes or any internal variables or state.

Independent − Components are designed to have minimal dependencies on other components.

- What is a “component”?

A component is a modular, portable, replaceable, and reusable set of well-defined functionality that encapsulates its implementation and exporting it as a higher-level interface.

- What are the characteristics of a component?

Reusability, Replacable, Not context specific, Extensible, Encapsulated, Independant

- What are the advantages of using component-based architecture?

Ease of deployment, Reduced cost, Ease of development, Reusable

## What is Props and How to Use it in React

### Props

React is a component-based library that divides the UI into little reusable pieces. In some cases, those components need to communicate (send data to each other) and the way to pass data between components is by using props.

I will be explaining how to use Props step by step.

1. Firstly, define an attribute and its value(data)
2. Then pass it to child component(s) by using Props
3. Finally, render the Props Data
`
class ParentComponent extends Component {  
  render() {
    return (
      <h1>
        I'm the parent component.
        <ChildComponent />
      </h1>
    );
  }
}
`
- What is “props” short for?

Properties

- How are props used in React?

They are used to pass data from one component to another

- What is the flow of props?

From parent to child and not the other way around

## Bookmarks

[Tutorial: Tic-Tac-Toe](https://react.dev/learn/tutorial-tic-tac-toe)

[Hello World](https://legacy.reactjs.org/docs/hello-world.html)

[Introducing JSX](https://legacy.reactjs.org/docs/introducing-jsx.html)

[Rendering Elements](https://legacy.reactjs.org/docs/rendering-elements.html)

[Components and Props](https://legacy.reactjs.org/docs/components-and-props.html)

# React: State and Props

## React: Component Lifecycle Events

from: [Component Lifecycle Events](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

What are component lifecycle events?
React lets you define components as classes or functions. The methods that you are able to use on these are called lifecycle events. These methods can be called during the lifecycle of a component, and they allow you to update the UI and application states.

Mounting
When an instance of a component is being created and inserted into the DOM it occurs during the mounting phase. Constructor, static getDerivedStateFromProps, render, componentDidMount, and UNSAFE_componentWillMount all occur in this order during mounting.

Updating
Anytime a component is updated or state changes then it is rerendered. These lifecycle events happen during updating in this order.

static getDerivedStateFromProps, shouldComponentUpdate, render,
getSnapshotBeforeUpdate, componentDidUpdate, UNSAFE_componentWillUpdate, UNSAFE_componentWillReceiveProps

Unmounting
The final phase of the lifecycle if called when a component is being removed from the DOM. componentWillUnmount is the only lifecycle event during this phase.

constructor()
The constructor for a React component is called before it is mounted.If the component is a subclass you should call super(props), or the props will be undefined. constructors can be used to assign state using this.state or to bind event handle methods to an instance. Let’s take a look at some example code.

- Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

The 'Render'.

- What is the very first thing to happen in the lifecycle of React?

The constructor is called.

- Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

Constructor, Render, componentDidMount, React Updates, componentWillUnmount.

- What does componentDidMount do?

It is a lifecycle method in React that is called immediately after a component is mounted

## React State Vs Props

from: [React State Vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)

- What types of things can you pass in the props?

Strings, numbers, booleans, objects, arrays, functions and react elements.

- What is the big difference between props and state?

Props is passed into a component and updated inside, while state is handeled inside of the component and updated outside.

- When do we re-render our application?

When the user does something like interacts with the page or if there is a change in props or state.

- What are some examples of things that we could store in state?

Forms, UI States, loading status

## Bookmarks

[State and Lifecycle](https://legacy.reactjs.org/docs/state-and-lifecycle.html)
[Handling Events](https://legacy.reactjs.org/docs/handling-events.html)
[Tutorial: Tic-Tac-Toe](https://react.dev/learn/tutorial-tic-tac-toe)
[React Bootstrap](https://react-bootstrap.github.io/)
[Cheatsheet](https://getbootstrap.com/docs/5.0/examples/cheatsheet/)
[All Bootstrap CSS classes](https:https://bootstrapshuffle.com/classes//canvas.instructure.com/courses/6694774/discussion_topics/17993163)
[Ship the future faster](https://www.netlify.com/)

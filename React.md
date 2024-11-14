# Interview Questions & Answers

### Questions

| No. | Questions                                                                                                                                                                                                                        |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|     | **Behavioural Questions**                                                                                                                                                                                                                   
| 1   | [What is React?](#what-is-react) 
| 2   | [How does React differ from other front-end frameworks? What are the key concepts in React?](#how-differ-react-from-other-frameworks)                                                                                                
| 3   | [How to create components in React?](#how-to-create-components-in-react)



## Answers
1. ### What is React?
   
React is an open-source JavaScript library created by Facebook for building complex, interactive UIs in web and mobile applications.
    **[⬆ Back to Top](#questions)**
    
2.  ### How does React differ from other front-end frameworks? What are the key concepts in React?

React is a popular front-end JavaScript library that differs from other front-end frameworks in several key ways. One of the primary distinctions is React's focus on building user interfaces by breaking them down into reusable components. This component-centric approach provides a modular and efficient way to create complex UIs.

Key Concepts in React:

Component-Based Architecture: React revolves around the concept of components, which are self-contained, reusable building blocks for UI elements. Components encapsulate their own logic and state, making them easier to manage and test.

Virtual DOM: React uses a virtual representation of the actual DOM to efficiently update only the necessary parts of the UI. When the state of a component changes, React calculates the minimal set of changes needed and updates the real DOM accordingly, improving performance.

Unidirectional Data Flow: React follows a unidirectional data flow, meaning that data flows in a single direction: from parent components to child components. This makes it easier to understand how data changes propagate and helps prevent unexpected side effects.

JSX (JavaScript XML): React introduces JSX, a syntax extension that allows developers to write HTML-like code directly within JavaScript. JSX makes it more intuitive to define component structures and interactions.

Reconciliation: React efficiently updates the DOM by reconciling changes between the previous and current states of components. This minimizes DOM manipulations and leads to better performance.

State and Props: React components can have both state and props. State represents mutable data that can change over time, while props are immutable data passed from parent components to child components.

Lifecycle Methods: React components have a lifecycle that includes various methods that are called at different stages of a component's existence. These methods allow developers to perform actions such as initialization, updating, and cleanup.

Hooks: Introduced in React 16.8, hooks provide a way to add state and lifecycle features to functional components. They offer a more concise and organized approach to managing component state and behavior.

Context: React's Context API allows data to be passed through the component tree without having to pass props manually at each level. This is useful for sharing data that is needed by many components.

Server-Side Rendering (SSR) and Client-Side Rendering (CSR): React supports both SSR and CSR. SSR renders components on the server before sending them to the client, improving SEO and initial load times. CSR renders components on the client side, providing a more dynamic and interactive experience.

In summary, React's focus on component reusability, virtual DOM, unidirectional data flow, and JSX syntax sets it apart from other front-end frameworks. Its key concepts enable developers to build efficient, maintainable, and interactive user interfaces.
    **[⬆ Back to Top](#questions)**
3. ### How to create components in React?
   
Components form the fundamental building blocks of a React application.

React provides two ways to create a component – function components and class components.

Function Components is the simplest way to create a component. It uses pure JavaScript functions that accept props and returns a React element.

function Welcome({ message }) {
  return <h1>{`Hello, ${message}`}</h1>
}

Class Components, on the other hand, uses ES6 class to define a component. The same function component can be rewritten as the following class component:

class Welcome extends React.Component {
  render() {
    return <h1>{`Hello, ${this.props.message}`}</h1>
  }
}
    **[⬆ Back to Top](#questions)**



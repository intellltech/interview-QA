# Solidity Interview Questions & Answers

### Questions

| No. | Questions                                                                                                                                                                                                                        |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|     | **Behavioural Questions**                                                                                                                                                                                                                   
| 1   | [What is Solidity?](#what-is-solidity) 
| 2   | [What are some important features of Solidity?](#What-are-some-important-features-of-Solidity)                                                                                                
| 3   | [How to create components in React?](#how-to-create-components-in-react)



## Answers
1. ### What is Solidity?
   
Solidity is a high-level language used in the blockchain ecosystem for implementing smart contracts. Designed specifically for targeting the Ethereum Virtual Machine, Solidity was influenced by several programming languages, such as JavaScript, Python, and C++.
    **[⬆ Back to Top](#questions)**
    
2.  ### What are some important features of Solidity?

Solidity has some salient features, which include libraries, contracts, and inheritance support. With Solidity, users can also create custom data types which can be a crucial part of smart contract development.
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



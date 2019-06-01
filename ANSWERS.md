## Self-Study/Essay Questions

- [ ] What are PropTypes used for? Please describe why it's important to type check our data in JavaScript.

*PropTypes are used to continuously validate datatypes, that are passed around from different components within an app. This is a debugging process that happens during development. This is to help prevent any additional debugging once the app is in production.   

- [ ] Describe a life-cycle event in React?

*The life-cycle events in React are the diffferent stages an app or component eveolves through. Birth/Mount, Growth/Updates, Death/Unmounting.

- [ ] Explain the details of a Higher Order Component?

*HOC is an advanced technique for reusing component logic. These are not part of Reacts API but rather patterns that emerge from Reacts compositional nature.  Higher-Order Component is a function that takes a component in as one parameter and returns a new component. HOCs are commonly used in third-party React libraries. If composed properly, this replaces the need to use mixins for cross-cutting between components of an application. 

- [ ] What are three different ways to style components in React? Explain some of the benefits of each.

*Styled-components = a library for writing CSS in our JS files using a tagged template literals, which are essentially invoking functions that pass strings with styles in them. With this method, we can actually pass in props that will impact the color of our elements or components such as a button. 

*Reactstrap = bootstrap modified for React to implement pre-built components that are already styled, from the Reactstrap library. 

*CSS = traditional styling sheet that uses a separate file to controls styles throughout a component or entire application. 
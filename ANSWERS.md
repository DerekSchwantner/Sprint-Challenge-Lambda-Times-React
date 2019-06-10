- [ ] What are PropTypes used for? Please describe why it's important to type check our data in JavaScript.

ANSWER: PropTypes are used to let the developer know if the right type of props are beign passed down between the components. If the prop is supposed to be a string and is instead coming in as an array, the PropTypes will notify the developer that the proptype is wrong and was expecting a different type of prop.

- [ ] Describe a life-cycle event in React?

ANSWER: ComponentDidMount(): once the elements of the page are rendered, this method is called. Allows developers to do things like state changes after the initial render, fetching data, and making the experience more dynamic overall.

- [ ] Explain the details of a Higher Order Component?

ANSWER: A high order component is a function that takes in a component and returns a new component. Similar to a high order function which takes in a callback function.

- [ ] What are three different ways to style components in React? Explain some of the benefits of each.

ANSWER:

CSS/SASS/LESS:Very convneient and easy to use. Can nest the styling and other developers will be able to easily overwrite/change styling.

Libraries(Reactstrap etc.): the components in the libraries will already be styled for you. the downside is that they are very hard to overwrite and often use the important tag.

Styled Components: can be a modular way to style, and has the benefit of reusability.

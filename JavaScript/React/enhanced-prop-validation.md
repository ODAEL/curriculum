# Enhanced Prop Validation 
author: catalin

levels:

  - basic

  - advanced

  - medium

type: normal

category: best practice

parent: prop-validation

---
## Content

In addition to standard *prop validations* for *JavaScript* primitives there are other types available through `React.PropTypes`.

Validate for anything that can be rendered (e.g. numbers, strings, elements or even an array containing these types):

```jsx
myNode: React.PropTypes.node,
```
Validate for a React element:
```jsx
myElem: React.PropTypes.element,
```
Validate for an instance of a class (using `instanceof` operator):
```jsx
myEnki: React.PropTypes.instanceof(Enki),
```

Validate for specific values treating it as an `enum`:
```jsx
myEnum: React.PropTypes.oneOf(['a', 'b']),
```
Validate for multiple types simultaneously:
```jsx
myProp: React.PropTypes.oneOfType([
 React.PropTypes.string,
 React.PropTypes.instanceOf(Enki),
]),

```
Validate for an array of a certain type:
```jsx
myArray: React.PropTypes.arrayOf(
  React.PropTypes.bool),
```
Validate for an object with prop values of a certain type:
```jsx
myObjOf: React.PropTypes.objectOf(
  React.PropTypes.number),
```

---
## Practice

Validate if your prop is an instance of the `Enki` class:
```jsx
MyClass = React.createClass({
  propTypes: {
    myProp = React.???
             .???(???),
  },
// other code
});
```
* `PropTypes`
* `instanceOf`
* `Enki`
* `enki`
* `ObjectOf`
* `PropType`
* `propType`
* `oneOf`

---
## Revision

Validate if your prop is an instance of the `Enki` class:
```jsx
MyClass = React.createClass({
  propTypes: {
    myProp = React.???
             .???(???),
  },
// other code
});
```
* `PropTypes`
* `instanceOf`
* `Enki`
* `enki`
* `ObjectOf`
* `PropType`
* `propType`
* `oneOf`
# README #

React Introduction

## Installation

Clone this repository and use `npm start` in your terminal to make it start

## Activities and Objectives

You are tasked to further develop your Container component.

Let it accept a `circles` props that tells it how many `Circle`s components should be rendered inside its belly.

Examples:

```
//just one, Container would most likely be a square if you allow it with his CSS
ReactDOM.render(
  <Container circles={5}>
  </Container>,
  document.getElementById('app')
);
//should render 5 circles inside your Container
```

## Extra notes and tips

Have you thought about validating the value of `circles`? Which values and types should/would you allow your component to accept?

A `for` loop might be fine for now, but consider a more functional approach, generating a quick array of `n` elements with

```javascript
let baseArray = Array.from({length: n},(a,i) => i);
```

Would it possible for you now to get some kind of user input to decide how many `Circle`s add to (or, why not, remove from) the container?
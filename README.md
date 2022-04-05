# Redux Quiz

<img src="https://chriscourses.com/img/blog/redux/redux.jpg" height="400px"/>

## Getting Started

- Fork and Clone

## Questions

1. What is Redux?

```
It is a standalone library that can be used with any UI layer. It is a predictable state container for JS Apps
```

2. What packages do we install to use Redux?

```
redux and react-redux
```

3. In your own words, describe the flow of how Redux is used to manage state.

```
You got the store with reudcers, then combine the reducers, then you update states for react components, then dispatch an action for the reducers
```

4. What do we use in order to manage different pieces of state?

```
Reducers
```

5. What do we use to perform an update to state?

```
Components from react
```

6. How do we access state from Redux?

```
props.todoState
```

7. In your own words, describe how to set up Redux for a React App.

```

first npm install react redux react-redux

second create store directory with an actions directory and reducers directory

third wrap <App/> in idex.js with provider with store = {store} and import store from store directory and import provider from react-redux
```

## Submission

Pull Request due by **9AM EST** following the [PR Submission Guidelines](https://github.com/SEI-R-2-22/template_pull_request).

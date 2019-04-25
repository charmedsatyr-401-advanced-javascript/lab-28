![CF](http://i.imgur.com/7v5ASc8.png) LAB
=================================================

## Lab 28: Props and State

### Author: Joseph Wolfe

### Links and Resources
* [repo](https://github.com/charmedsatyr-401-advanced-javascript/lab-28)
* Travis: N/A (Code Sandbox)
* [Props Practice](https://codesandbox.io/s/7wkron08oq)
* [Internal State Practice](https://codesandbox.io/s/8l4nznl5ql)
* [External State Practice](https://codesandbox.io/s/94w9jrn8qw)


### Modules
* `Props Practice`: `App` passes a `text` prop to `Message`, which renders it. `index.js` renders a `Main` entry point.

* `Internal State Practice`: `App` renders its own state and a form that can be manipulated by handler functions. The application has a single dynamic module because that is how I thought it was to be distinguished from `External State Practice`. `index.js` renders a `Main` entry point.

* `External State Practice`:  `App` renders its own state. `App` passes `handleInput` and `bumpCounter` functions to a `Form` component as `handleInput` and `handleSubmit` props, respectively. The passed functions allow `App` state to be modified from within `Form`.

#### Tests
* What assertions were made?
  * Tests ensure each element renders without crashing. Each dynamic element has functional tests. Snapshot tests don't seem to run well on codesandbox.
* What assertions need to be / should be made?
  * Snapshot tests could be made locally and used to update the repo.

#### UML
![UML](assets/uml.jpg)

# Single Page Applications with Vue
01. What is the entrypoint of an application?

  > The place where the execution of a program begins.

02. What is the difference between a vue `component` and `page`?

  > Both are used to display information but you could say a page is the hub or the base of what will be displayed and components are pieces that you bring in to display whatever information is held in the component.

03. What is ***Component-Based Architecture***?

  > Component based architecture is seperating objects into individual components. Where the view and the functions the view needs are tied into one space.

04. What are the three tags that make up a Vue component?

  > Script, Template and Style

05. What are ***lifecycle hooks***? What are lifecycle hooks used for?

  > Lifestyle hooks are how the library you're using is working behind the scenes. Hooks are used for knowing when certain pieces of what you're using are called in so that you can understand when pieces of your code are being brought in.

06. Which component in Vue does the vue-router use to mount pages onto?

  > The router-link

07. What is the difference between the `AppState` and the state object within a component?

  > The `AppState` is holding and is the main reference for our variables, where the state object in the component is a reference to that "main" variable.

08. What is the responsibility of `Services` in our Vue projects?

  > Services is performing all of our C.R.U.D. functionality for us. 

09. What are ***props*** and how are they used? Provide an example

  > Props are references to variables/objects that we pass down from parent to child. An example is when we call a component in a page, we pass an object referene as a prop down to the component to be used to display information about that object.

10. What is the Vue method used to create watchable objects such as `state` or `AppState`?

  > watch() or we have also been using computed to "watch" values for changes.

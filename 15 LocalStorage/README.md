# LocalStorage and Event Delegation Project

The aim of this project is using **Local Storage** in the browser and how to use something called **Event Delegation** to handle events on elements created in the future. 

**Local storage** : data with no expiration date that will persist after the browser window is closed.

**Event Delegation** : The event delegation uses specifics of *event propagation* mechanism.

Using the event delegation requires 3 steps:

**Step 1.** Determine the parent of elements to watch for events.

**Step 2** Attach the event listener to the parent element.

**Step 3** Use **event.target** to select the target element.

**Demo [here](https://neslinbaydar.github.io/15%20LocalStorage/index.html)**

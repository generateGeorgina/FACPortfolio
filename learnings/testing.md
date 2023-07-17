Deployed site: [https://cazanelena.github.io/to-do-list/](https://cazanelena.github.io/to-do-list/)

## 1. Check that passing a given input into our tests returns the expected output
Here, I implemented test helpers using vanilla JavaScript to test the expected result against the actual return.

![testing helpers](../images/testing/Screenshot%202023-07-17%20at%2010.40.50.png)
## 2. Write tests to mimic the behaviour of a user performing different actions
On line 14, I use `.click()` to simulate a user clicking the delete button on a task to test if it successfully removes the task (child li element) from the parent (ul element).

![delete task test](../images/testing/Screenshot%202023-07-17%20at%2011.09.27.png)
## 3. Write testable, modular functions
Here, I imported a module `deleteTask` that will be run at a click event at the bottom of `addDeleteButton`.

![add delete button](../images/testing/Screenshot%202023-07-17%20at%2010.52.41.png)
## 4. Write functions that add, remove or modify DOM nodes
I created a delete function that removes a task from the `.parentNode` (line 4).

![delete function](../images/testing/Screenshot%202023-07-17%20at%2011.01.18.png)
## 5. Apply event listeners to HTML form elements
The `addNewTask()` callback function is triggered by a 'click' (line 9) or 'keydown' (line 13) event for the form element.

![main js](../images/testing/Screenshot%202023-07-17%20at%2011.02.39.png)
## 6. Use scope to control what variables are accessible inside functions and blocks
In this test, `deleteTask` is imported, making it avaliable in this module to check if the function is working as a callback funtion on line 13.

![delete task test](../images/testing/Screenshot%202023-07-17%20at%2011.09.27.png)

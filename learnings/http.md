## 1. Write code that executes asynchronously
Here is an an example of code that executes asynchronously using promises.

![bored api promise](../images/http/Screenshot%202023-06-22%20at%2015.07.42.png)
## 2. Use callbacks to access values that aren’t available synchronously
You can see this callback function in use on line 39.

![handle form submit callback](../images/http/Screenshot%202023-06-22%20at%2015.24.04.png)
## 3. Use promises to access values that aren’t available synchronously
On line 120, I use `json.data.type` to access the data the promise returned.

![bored data render](../images/http/Screenshot%202023-06-22%20at%2015.07.42.png)
## 4. Use the fetch method to make HTTP requests and receive responses
You can see an example of a fetch request on line 111.

![fetch request](../images/http/Screenshot%202023-06-22%20at%2015.07.42.png)
## 5. Configure the options argument of the fetch method to make GET and POST requests
On lines 55 to 58, I configured a GET request.

![get request](../images/http/Screenshot%202023-06-22%20at%2015.32.51.png)
## 6. Use an array method to iterate through an array containing values
On line 28, I used `forEach` to iterate through the `weatherHistory` array from local storage.

![forEach](../images/http/Screenshot%202023-06-22%20at%2015.39.59.png)
## 7. Use the filter array method to create a new array with certain values removed
The filter array method was used to filter out a random activity type that had already been suggested to the user on line 85.

![filter array](../images/http/Screenshot%202023-06-22%20at%2015.44.56.png)
## 8. Access DOM nodes using a variety of selectors
Lines 11 and 12 are examples of accessing DOM nodes.

![DOM nodes](../images/http/Screenshot%202023-06-22%20at%2016.16.55.png)
## 9. Add and remove DOM nodes to change the content on the page
On line 20, the abstracted function adds content to the page when executed.

![append child](../images/http/Screenshot%202023-06-22%20at%2016.32.50.png)
## 10. Use consistent layout and spacing
The home page was laid out with consistent styles.

![home page](../images/http/Screenshot%202023-06-22%20at%2016.22.38.png)
## 11. Follow a spacing guideline to give our app a consistent feel
The history page also followed the same layout as the home page.

![history page](../images/http/Screenshot%202023-06-22%20at%2016.24.05.png)
## 12. Debug client side JS in our web browser
I frequently used Chrome's dev tools to debug my code, including accessing local storage via the application tab to check my work.
## 13. Use console.log() to help us debug our code
Whenever the was a type error, I used `console.log()` to find out what value variables hold at different points in the code.
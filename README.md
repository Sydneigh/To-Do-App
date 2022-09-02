https://sydneigh.github.io/To-Do-App/
# To-Do App Annotations
I built three different features into the app:
1.	The ability to add tasks to your HTML
2.	The ability to mark tasks completed and alter the look of your element
3.	The ability to delete tasks off your list

1) Creating Tasks 
First, I created a click function that targets the id of enter.	Inside the newly created event listener, I created a var named task.
Next, I created a jQuery selector that targets the id of todoItem: $("your selector here").Then, I added the jQuery function .val(); at the end of your jQuery selector.	Beneath the newly created var, I created another jQuery selector that targets the id of todoList.
![code line 1](https://user-images.githubusercontent.com/96391154/188043369-ca3e54af-0736-444f-99de-2b27b60b5fbc.jpg)

2) Deleting Tasks
I created  a jQuery selector that targets the document. Then attached a click event listener to it with three parameters: the type of function, the element we are selecting, and an anonymous function. Inside the newly created event listener, I added a jQuery selector. 

3) Completing Tasks
I created another jQuery selector that targets the document. I attached a click event listener to it with three parameters—a click, the class of task, and an anonymous function. Under the new selector, I created an if-else statement

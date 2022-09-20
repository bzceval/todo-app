## Project About
*Actually, when starting the project, I didn't want it to progress by keeping the data in localStorage. But but when I designed it in **Figma**  my muses came and asked me to do this. I hope you like it. Oh, by the way, I added the steps I followed below and of course my `Pseudocode`. Thanks* 🤸‍♀️

## Use Technologies
I used **HTML** in my index page and applied the **JavaScript** language to give it dynamism. And of course **CSS** is indispensable to make it look beautiful on the eye. **Bootstrap** framework helped me a lot in grid structure.

## Design
- [Figma Design](https://www.figma.com/file/Po79NBfsNv6HeDX5ov9KON/Todo-App-%7C-JS?node-id=0%3A1)


## Pseudo Code
- BEGIN
- OUTPUT "Please Add Todo List"
- INPUT input.value </br>
    IF ( !input.value ) </br>
    OUTPUT "Please Enter A Todo Item" </br>
    ELSE </br>
    SET innerHTML += input.value </br>    

## Step by Step Coding
[x] Get Document Elements With JS </br> 
[x] Add AddButon and a listen event to it. </br> 
[x] Check if task item input value is entered with console log but you shouldn't take a space as a task.</br> 
[x] Check if task description input value is entered with console log but you shouldn't take a space as a task.</br> 
[x] Else create a new dataset. 
[x] Call the function that creates the new li element for task input item data. 
[x] Call the function that creates the new li element for description input data. 
[x] And empty the of both input.</br>
[x] Empty the input if no task item input value and task descripton input value. </br>
*Finish this function for now. Because I will add localStorage after finishing Dom activities.*</br>
[x] Created a function that takes a dynamic data parameter that the li element element for task input item will be in.
[x] Create a new li element and assign it the object's id and the completed class.</br>
[x] Create control icon and connect to li</br>
[x] Create edit icon and connect to li</br>
[x] Create a p element for the description and task, connect it to the li element by creating a text node.</br>
[x] Create delete icon and connect to li</br>
[x] The same steps are done in the annotation function.</br>
[x] Assign the resulting li elements to the ul element as a child. </br>
[x] If an event comes from any of the children of the ul, detect it and take action with addEventListener. (Capturing)</br>
[ ] If the event came from a delete button, delete the parent of the delete button from the DOM.</br>







[x] Create your todo list when event click. </br>


 







[ ] Delete related element of array</br>
[ ] Store the final version of the set array in localStorage</br>
[ ] If the event came from an okey button, if it has a class named checked in the relevant li element, delete it, otherwise add it (DOM)</br>
[ ] Adding is possible with the enter key</br>
[ ] Let the input be active at the start</br>
[ ] Add DeleteButton and a listen event to it. </br> 
[ ] Delete last added item when event click </br> 
[ ] Inject the same things on the keyboard with the enter key to insert and the spacebar to delete. </br> 
[ ]
[ ]
[ ]
[ ]
[ ]
[ ]
[ ]it should push the data from the li function with the parameter to the parsed array for localStorage, set data for DOM.

[ ] update todos array with data from localStorage </br>
[ ] If there is no item named todos in localStroge, assign an empty array. </br>
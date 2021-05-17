##  lists and keys


1. **What does .map() return?**

      ***The map() method returns an entirely new array with transformed elements and the same amount of data. In the case of forEach() , even if it returns undefined , it will mutate the original array with the callback.***


2. **If I want to loop through an array and display each value in JSX, how do I do that in React?**

     ***we loop an array using the JavaScript map() function***


3. **Each list item needs a unique *Key*.**
4. **What is the purpose of a key?**

     ***Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity***
---------------------------------------
## The Spread Operator


1. ***What is the spread operator?***

     **The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.**

2. ***List 4 things that the spread operator can do.***

    - *Copying an array*
    - *Concatenating or combining arrays*
    - *Using Math functions*
    - *Using an array as arguments*


3. ***Give an example of using the spread operator to combine two arrays.***

    - **const objectOne = {hello: "🤪"}**
    - **const objectTwo = {world: "🐻"}**
    - **const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}**


4. ***Give an example of using the spread operator to add a new item to an array.***
    - **const ourArray = […myArray,’🐻’, ‘🍍’]**

5. ***Give an example of using the spread operator to combine two objects into one.***

    **const objectOne = {hello: "🤪"}**

    **const objectTwo = {world: "🐻"}**
    
    **const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}**

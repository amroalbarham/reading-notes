
- **Describe what Array.map() does**

    *function iterates over an array and runs a call back for each element. The callback receives the value and the index of the array element as a parameter.*

- **Describe what Array.reduce() does**
    
    *iterates over an array and returns the last version of the “accumulator” … in each iteration, based on the value and/or idx of the current element in the array, you have the opportunity to modify and return the accumulator. After the last iteration of the array, that accumulator value is returned to the caller. **initialvalue** represents the value of the accumulator in the first iteration.*

- **Provide code snippets showing how to use superagent() to fetch data from a URL and log the result**

    -   *With normal Promise **.then()** syntax*

    ```
      superagent.get(`https://swapi.dev/api/people`).then(data=>{
           data.body.results.forEach(item=>{
           console.log({[item.name] : item.url})
             })
          }).catch(error=>console.log(error));
  ```

    - *Again with **async** / **await** syntax*

    ```
         try{
             let data=await superagent.get(`https://geocode.xyz/${city}?json=1`);
             console.log(city,data.body.longt,data.body.latt)
             }catch(error){console.log(error)}
    ```


- **Explain promises as though you were mentoring a Code 301 level student**


    * *A Promise is a proxy for a value not necessarily known when the promise is created. It allows you to associate handlers with an asynchronous action's eventual success value or failure reason. This lets asynchronous methods return values like synchronous methods: instead of immediately returning the final value, the asynchronous method returns a promise to supply the value at some point in the future*

    * *A Promise is in one of these states:*

        - ***pending:** initial state, neither fulfilled nor rejected.*

        - ***fulfilled:** meaning that the operation was completed successfully.*

        - ***rejected:** meaning that the operation failed.*


- **Are all callback functions considered to be Asynchronous? Why or Why Not?**


    *callbacks don't have anything to do with the async concept at all. They're just regular functions, and they don't know or care whether they're going to be called asynchronously or not.so a callback can be used synchronously or asynchronously.*
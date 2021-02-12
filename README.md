A solution to the Hoxhunt 2021 Backend/Frontend summer intern [task](https://hunters.hoxhunt.com/#/challenge).
Made by: Samuel Granvik.
  

### About
I built the solution with JavaScript, and used Node.js to test out the code. (`node algorithm.js`)

My solution uses separate arrays that get their data *pushed* to them from the initial `emails` array. I then loop through the `emails` array to handle the logic. 

The `includes();` method gets used in the `if-statement` logic to handle what email *rule* to follow , and then add it to the final `villainArray` if the `if-statement` logic is true. 

If the first rule of the task is false (i.e. does the last name contain the letter *r*), then I break the for-loop with a `continue;` and move on to the next loop iteration. 

I also take advantage of a Reg-ex to check whether there are two or more *t*'s in a string for the last email *rule*. 

One can of course improve the solution to maybe use more regular expressions, or to use a less resource tense `if-statement` logic and add some unit tests. One could also create another function or method to check if the number of the algorithm is actually a prime number. But all in the solution works and I'm okay with the current code.
### Solution to the Hoxhunt 2021 Backend/Frontend Summer internship [task](https://hunters.hoxhunt.com/#/challenge)
Made by: Samuel Granvik 👋

I built the solution with JavaScript, and used Node.js to test out the code. `node algorithm.js`

------------
#### Execution

My solution uses a `for-loop` to go through all the email addresses in the initial emails array. I then split the email addresses into a set of separate arrays to be used later in the `if-statement` logic.

##### The logic of the rules

The `includes();` method gets used in the `if-statement` logic to handle what email *rule* to follow, and then add it to the final `villainArr`.

If the first first rule of the `if-statement` logic is true (i.e. If the last name **does**  containt a letter: **r**), then I break the `for-loop` with a `continue;` and move on to the next loop iteration.

The next `if-else` statements takes care of the lesser rules, and adds the corresponding emails to the `villainArr` if they are true.

The last rule takes advantage of a Reg-ex to check whether the current itterations email address's last name contains two or more **t**s. 

------------
#### Conclusion

One can of course improve the solution to maybe use more regular expressions, or to use a less resource tense `if-statement` logic, and add some unit tests. 
One could also create another function or method to check if the number of the algorithm is actually a prime number. 

But all in the solution works and I'm okay with the current code. 
Thanks for checking it out! 🙏

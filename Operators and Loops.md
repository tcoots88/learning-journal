#### Comparison Operators
- You can evaluate a situation by comparing one value in the script to what you expect it might be. The result will be a Boolean: true or false

| Input      | Output | 
| :---        |    :----:   |
| ==      | is equal to       | 
| !=   | is not equal to        |      |
| ===      | strict equal to | 
| !==        |    strict not equal to   | 
| >      | greater than       |   |
| <   | less than        | 
| >=      | greater than or equal to | 
| <=      | less than or equal to | 

#### Logical Operators
- Comparison operators usually return **true** or **false**.  Logical operators allow you to compare the results of more than one comparison operator. 

| Input      | Meaning | 
| :---        |    :----:   |
| &&      | Logical AND       | 
| `||`   | Logical OR        |      |
| !      | Logical NOT | 

#### Loops
- Loops check a condition. If it returns true, a code block will run.  Then the condition will be checked again and if it still returns as true, the code block will run again.  It repeats until condition returns false.  There are three common types of loops:
    1. FOR: In a FOR loop, the condition is usually a counter, which is used to tell how many times the loop should run
    2. WHILE: If you do not know how many times the loop should run, you could use a WHILE loop.  Here the condition can be something other than a counter, and the code will continue to loop for as long as the condition is true
    3. DO WHILE: The do...while loop is very similar to the while loop, but has one key difference.  It will always run the same statements inside the curly braces at least once, even if the condition evaluates it to false. 

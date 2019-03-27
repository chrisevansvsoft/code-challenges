Language: golang
Challenge: create a function that expects a string of eight coordinates of a chess board.
The program will then work out if the coordinates all have queens on them and return true if all the queens are safe.
Otherwise return the first of the locations of queens attacking each other

Sample Test Cases
Input:[]string {"(2,1)", "(4,3)", "(6,3)", "(8,4)", "(3,4)", "(1,6)", "(7,7)", "(5,8)"}
Output:"(2,1)"

Input:[]string {"(2,1)", "(5,3)", "(6,3)", "(8,4)", "(3,4)", "(1,8)", "(7,7)", "(5,8)"}
Output:"(5,3)"

Points
0: No attempt
3: extra output of chess board
3: correct output
3: no errors with 2 examples
3: return all attacking queens instead of just the first
3: use proper chess coordinates instead of 2,1 etc
-9: use php 

Sandbox: https://play.golang.org/

Template:

```go
package main
import "fmt"

func EightQueens(strArr []string) string { 

  // code goes here   
  // Note: feel free to modify the return type of this function 
  return strArr[0]
            
}

func main() {

  // do not modify below here, readline is our function
  // that properly reads in the input for you
  fmt.Println(EightQueens(readline()))

}
```

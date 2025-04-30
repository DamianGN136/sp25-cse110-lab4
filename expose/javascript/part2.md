1. line 12 prints out "3" which is the length of the list of prices and the last last iteration of the for loop before it terminates. This variable can be accessed because it is declared using 'var'
2. line 13 prints out '150'. This discountedPrice variable can be accessed because it was declared using 'var'.
3. line 14 prints out '150'. The finalPrice variable can be accessed because it was declared using 'var'.
4. the return value is calculated as [50, 100, 150] but nothing it output because we do not log it in the console
5. should return an error since i is out of scope
6. should return an error since 'discountedPrice' is out of scope i.e. we are trying to access it outside the for loop its defined in
7. should print out 150 since it is defined outside of all individual code blocks
8. the return value is calculated as [50, 100, 150] but nothing it output because we do not log it in the console
9. should output an error because we are trying to modify the 'discounted' list which is declared as 'const'
10. should return 3
11. the return value is calculated as [50, 100, 150] but nothing it output because we do not log it in the console

12. Parts A-E:
    ```js
    - A: student.name
    - B: student["Grad Year"]
    - C: student.greating()
    - D: student["Favorite Teacher"].name
    - E: student.courseLoad[0]

    
13. Arithmetic:
    ```js
    -A: '3' + 2 = '32'
    //This is because the '+' operator with a string performs string contatenation. '3' is a string which cause 2 to be converted to a string as well
    -B: '3' - 2 = 1
    //The '-' operator triggers numeric coercion. The string '3' gets converted to an integer
    -C: 3 + null = 3
    //null becomes coerced to 0 in numeric addition
    -D: '3' + null = 3null
    //Here the '+' sign with a string causes string concatenation. null becomes a string
    -E: true + 3 = 4
    //true is coerced to 1 due to the '+' operation
    -F: false + null = 0
    //both false and null are coerced to 0
    -G: '3' + undefined = 3undefined
    // the '+' operation causes undefined to be converted to a string and concatenation is performed
    -H: '3' - undefined = NaN
    //The '-' operation attempts numeric coercion: null becomes NaN and hence 3 - NaN = NaN

  14. Comparison:
      ```js
      -A: '2' > 1 -> true
      //'2' is coerced to an integer and 2 > 1 is true
      -B: '2' < '12' -> false
      //This is comparing strings. Since '2' comes after '1' lexicographically we get false
      -C: 2 == '2' -> true
      //'==' allows type coercion. '2' becomes a string and it is in fact true that 2 == 2
      -D: 2 === '2' -> false
      //'===' checks both value and type. We get false because 2 is an int and '2' is a string
      -E: true == 2 -> false
      //true is coerced to 1 because of '=='. 1 == 2 is false
      -F: true === Boolean(2) -> true
      //Boolean(2) returns true. So true === true is true


  15. The difference betweeen '==' and '===':
      - '==' is a loose equality operator. Before comparing values it first performs type coercion if their are differing types
      - '===' is a stricy equality operator. It performs no type conversions and it compares both type and value.
     

  16. Loops
      ```js
      for(let property in statistics){
          if(property.startsWith('r') || statistics[property] % 2 !== 0){
              console.log(statistics[property]);
          }
      }

  17. Functions
      ```js
      [2,4,6]
      ```
      The function creates an empty array newArr. It iterates through the original array and applies the callback function to each element giving:
        - doSomething(1) -> 2
        - doSomething(2) -> 4
        - doSomething(3) -> 6
     It then pushes each result into newArr and returns newArr.
      

  18. setInterval(), setTimeout(), clearTimeout()
      ```js
      setInterval(() => {
        let d = new Data();
        let time = d.toLocaleTimeString();
        console.log(time);
      }, 1000)

  19. The output is 1, 4, 3, 2
      

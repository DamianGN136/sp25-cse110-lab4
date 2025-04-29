1. line 9 will print: "values added: 20"
2. line 13 will print: "final result: 20"
3. You shouldn't use var because that means the variable can be accessed anywhere even outside its code block. This opens up possibility of naming and scoping errors.
4. line 9 prints: "values added: 20"
5. we get an error when we reach line 13. This is because we declared result using 'let' which means that result can only be accessed inside the if statement it was declared in.
6. we get an error. This is because we are trying to modify as variable that was declared as 'const', which means once its declared and assigned a value it can no longer be changed.
7. Similarily to 6, we get an error because we are trying to modify a const variable.

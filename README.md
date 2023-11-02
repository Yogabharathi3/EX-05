# EX-05-5b-FUNCTIONS AND STORAGE CLASS
## AIM:
Write a C program to calculate the Product of first 12 natural numbers using Recursion
## ALGORITHM:
1. Define a recursive function calculateProduct that takes an integer parameter n.
2. Return n multiplied by the result of the calculateProduct function called with n - 1.
3. Declare an integer variable n and an unsigned long long variable product.
4. Initialize n with the value 12 (for the first 12 natural numbers).
5. Call the calculateProduct function with n and store the result in the product variable.
6. Print the result, indicating it is the product of the first 12 natural numbers.
## PROGRAM:
```
#include <stdio.h>
int Product(int n){
  if (n == 1)
    return 1;
else
    return n * Product(n - 1);
}
int
  main(){ int
  n = 12;
  int product = Product(n);
  printf("Product is = %d\n", product);
  return 0;
}  
```
## OUTPUT:
![image](https://github.com/Yogabharathi3/EX-05-5a-POINTERS/assets/118899387/9bc9b9ed-2748-4b74-acb5-83ee20b6b45a)

## RESULT:
Thus the program  has been executed successfully.

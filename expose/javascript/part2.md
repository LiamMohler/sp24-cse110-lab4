1) Prints 12 because in scope of var variable type.

2) Prints 150 because in scope of var variable type. (last being iterated through)

3) Prints 150 because in scope of var variable type. (last being iterated through)

4) Returns [50, 100,150] because discount if 50%. (all in scope, no errors)

5) Error, let declaration of i is not inside the scope (only in the for loop)

6) Error, let declaration of discountedPrice is not inside the scope (only in the for loop)

7) 150, the let declaration of finalPrice is within the scope. (last being iterated through)

8) Returns [50, 100,150] because discount if 50%. (discounted var is in the scope)

9) Error, let i is not declared in the scope outside of the forloop.

10) Prints 3, const is not re-assigned anywhere and nothing is accessed outside of it's scope.

11) Returns [50, 100,150] because discount if 50%. (no const variables re-assigned or anything accessed outside of scope) 

12) 
A. student.name  <br>
B. student['Grad Year']   <br>
C. student.greeting()  <br>
D. student['Favorite Teacher'].name  <br>
E. student.courseLoad[0]  

13) 
A. '32' -> 2 is cast to string because + operand using with string <br>
B. 1 -> 3 is cast to int because - operand  <br>
C. 3 -> null treated as 0 in numeric  <br>
D. '3null' -> null treated as string with + opperand (concat)  <br>
E. 4 -> true converted to 1 is numeric context  <br>
F. 0 -> false converted to 0 in numeric and so is null  <br>
G. '3undefined' -> undefined converted to string because + operand with '3'  <br>
H. NaN -> undefined because arithmatic operation (- operand) involves undefined  <br>

15) 
A. true -> convert string to number and compare  <br>
B. false -> perform character by character comparison with strings based on unicode  <br>
C. true -> string 2 converted to number 2 then compared.  <br>
D. false -> no converstion in ===  <br>
E. false -> true converts to 1 due to type coercion  <br>
F. true -> boolean converts arguement to boolean value (2 is true because non-zero)  <br>

16) == compares two values for equality after performing type coercion, while === compares two values without performing type coercion. === is STRICTLY equal (must be same type)

17) done

18) returns [2,4,6] -> newArr is initialized and for loop iterates over every elemnt of array. For each element doSomething is called which multiplies the number by two, then after gets pushed into the newArr. Then newArr is returned.

19) done

20) 
1  <br>
4  <br> 
3  <br>
2

# Embedded Software Interview Question and Answer
Below are the questions and answers that I did during my interview review.

**1. What is Static variable?**

**Answer:** Static variables are allocated at compile time, and remain in memory throughout the program's lifetime. 
- If static variable declares within a function. Now, It is local static variable -> It retain the value between function calls.
- If static variable declares for a function name. Now, it is static function -> It only visible in the file where it is declares.
- If global static variable -> Can only accessed in the file where it is created.

**2. What is Pointer?**

**Answer:** Pointer is variable that stores the address or location of other variable, constant, function or data object. 
By using pointer, embedded C program can perform operation such as:
- Accessing array or string element. 
- Dynamic memory allocation. 
- Call by reference.
- And implementing tree, graphs, linked list and many other data structure. 

**3. What is use Const keyword?**

**Answer:** Const keyword is used to declares a variable as read-only. Its value cannot be changed once it has been initialized. 
Const keyword:
- Can help prevent accidental programing change to important variable. 
- And help optimize program memory usage.

**4. What is Pointer to constand and Constant Pointer?**

**Answer:**
- **Pointer to constant:** This is a pointer can point to an address. This pointer can be change the addresss it point to. But, cannot change the value at the address it is pointing to. 
- **Constant pointer:** This is a pointer 

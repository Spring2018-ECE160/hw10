## Question 3

(Eckel, 11.17) Create a class that contains a double*. The constructor initializes the double* by calling new double and assigning a value to the resulting storage from the constructor argument. The destructor prints the value that’s pointed to, assigns that value to -1, calls deletefor the storage, and then sets the pointer to zero. Now create a function that takes an object of your class by value, and call this function in main( ). What happens? Fix the problem by writing a copy-constructor.

Compile Steps:

Output:

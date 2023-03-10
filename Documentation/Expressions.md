# Expressions

Lumina is designed to make programming as simple and intuitive as possible, using a wide range of expressions and functions that are easy to learn and use. In addition to the basic calculation operators like <code>+, -, /, *</code>, Lumina also includes a variety of conditional expressions such as <code>==, !=, <, ></code> for use in loops and other constructs.

The provided code also uses a number of specialized functions, including:

<code>define()</code>: Create and initialize variables. For example, <code>define(arr, array(1,2,3,4))</code> initializes the variable <code>arr</code> as an array with the specified values. Similarly, <code>define(n, len(arr))</code> sets the variable <code>n</code> to the length of the array.

<code>array()</code>: Creates an array with the specified values.
  
<code>len()</code> is a function that returns the length of an array. To use it, simply call the function with the array as the argument. For example, if you have an array called "my_array", you can find its length by calling <code>len(my_array)</code>.
  
<code>element()</code>: Retrieves the value of an element in an array at a given index. Example: <code> out(element(arr, 2))</code>
  
<code>replace()</code>: Replaces the value of an element in an array at a given index with a new value. For example: <code> define(arr, replace(arr, 3, "test"))</code>
  
<code>out()</code>: Outputs a value to the console.

Overall, Lumina is a powerful and versatile programming language that can be used for a wide range of applications, from simple calculations to complex data processing and analysis. With its intuitive syntax and rich set of functions, it is an excellent choice for both novice and experienced programmers alike.

# Tumy is a new programming language that combines the best of Python, C++, and Rust

## About

Tumy is a cutting-edge programming language designed to bring together the simplicity of Python, the performance optimizations of C++, and the memory safety features of Rust. The primary goal of Tumy is to provide developers with a language that is both easy to read and write, while delivering high-performance and memory safety.

Tumy adopts Python's clean and readable syntax, making it approachable for developers of all experience levels. By leveraging the performance optimizations of C++, Tumy enables developers to write efficient and speedy code. Furthermore, inspired by Rust's memory safety model, Tumy incorporates features like ownership and borrowing to ensure secure memory management and prevent common memory-related errors.

Under the hood, Tumy utilizes the powerful parsing capabilities of PLY (Python Lex-Yacc) to define its formal grammar and parsing rules. This allows for precise and reliable parsing of source code, aiding in the creation of robust and error-free applications.

With Tumy, developers can expect a powerful and user-friendly programming environment. By combining the strengths of Python, C++, and Rust, Tumy opens up new possibilities for software development across various domains.

# How to use

Here are some examples of the syntax in the Tumy programming language.

### 1. Variable declaration:

```cs
int x = 10
string &y = "Hello world!"
```

### 2. Conditional structures:

```cs
if condition:
    // Code to execute if condition is true
else:
    // Code to execute if condition is false

for item in iterable:
    // Iterate over each item in the iterable

while condition:
    // Repeat until the condition is false

```

Example:

```cs
//int16 x = 10
int x = 10 //int32

if x > 5:
    print("x is greater than 5")
elif x == 5:
    print("x is equal to 5")
else:
    print("x is less than 5")

```

### 3. Functions:

```cs

int add(int a, int b):
    return a + b

void greet(string message):
    print("Hello, " + message + "!")

add(3,4)
greet("Tumy")

```

### 4. Class:

```cs
class Person:
    string name
    int age

    Person(string name, int age):
        self.name = name
        self.age = age

    string get_name():
        return self.name

    void set_name(string name):
        self.name = name

    int get_age():
        return self.age

    void set_age(int age):
        self.age = age

void main():
    person = Person("John", 30)
    print(person.get_name())  // Output: John

    person.set_name("Jane")
    print(person.get_name())  // Output: Jane

```

### 5. Importing libraries:

```cs
import math

print(math.sqrt(16))  # Kết quả: 4.0
```

### 6. The main execution function:

```cs
void main():
    // Main tasks and logic of the program

main()  // Call the main() function to start the program execution

```

### 7. Closures:

```cs
type closure_function(param1, param2) {
    // Closure execution statements
    // Can access variables from the outer scope
    // Use param1, param2, and other variables
}
```

```cs
int add(a, b):
    return a + b

int result = add(3, 5)
print(result) // Output: 8


```

```cs
int closure():
    int x = 10

    int inner_function(int y):
        return x + y

    return inner_function

int my_closure = closure()
int result = my_closure(5)  // Output: 15
```

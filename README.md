# Tumy is a new programming language that combines the best of Python, C++, and Rust

## Introduction

Tumy is an innovative programming language that combines the simplicity of Python, the performance optimizations of compiled languages like C++, the memory safety features inspired by Rust, and the analytical power of R. With Tumy, developers can enjoy a language that is both easy to read and write, while delivering high-performance, memory safety, and data analysis capabilities.

Tumy adopts Python's clean and readable syntax, making it accessible to developers of all skill levels. However, unlike traditional interpreted languages, Tumy introduces a compilation step to enhance performance. The code is initially interpreted, and then the commands are stored as precompiled data, allowing for faster execution times. If any changes are made to the code, the affected parts are re-interpreted and recompiled, ensuring up-to-date performance optimizations.

Taking inspiration from Rust's memory safety model, Tumy incorporates features like ownership and borrowing, ensuring secure memory management and eliminating common memory-related errors. This allows developers to write code with confidence, knowing that memory safety is enforced by the language itself.

In addition, Tumy leverages the performance optimizations of C++. By utilizing the power of C++ under the hood, Tumy enables developers to write efficient and high-performance code. The ability to leverage C++ optimizations provides Tumy with the speed and efficiency needed for computationally intensive tasks and resource-constrained environments.

Moreover, Tumy integrates the analytical capabilities of R, allowing developers to seamlessly perform data analysis and statistical computations. The combination of C++ performance optimizations and R's analytical power makes Tumy a versatile language for both general-purpose programming and data analysis tasks.

Internally, Tumy utilizes the robust parsing capabilities of PLY (Python Lex-Yacc) to define its formal grammar and parsing rules. This ensures accurate and reliable parsing of the source code, enabling the creation of robust and error-free applications.

With Tumy, developers can enjoy a powerful and user-friendly programming experience, combining the strengths of Python, C++'s performance optimizations, Rust's memory safety, and R's analytical power. Tumy opens up new possibilities for software development and data analysis, providing a comprehensive solution for various domains.

# Authors
- Tung Nguyen (Ryan - Acala)

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
let multiplier = let (factor) = {
    return let (x) = {
        return factor * x;
    };
};

let multiplyByTwo = multiplier(2);
let result = multiplyByTwo(5);
print(result);  // Kết quả: 10

```

# Tumy is a new programming language that combines the best of Python, C++, and Rust

## About

Tumy is a cutting-edge programming language designed to bring together the simplicity of Python, the performance optimizations of C++, and the memory safety features of Rust. The primary goal of Tumy is to provide developers with a language that is both easy to read and write, while delivering high-performance and memory safety.

Tumy adopts Python's clean and readable syntax, making it approachable for developers of all experience levels. By leveraging the performance optimizations of C++, Tumy enables developers to write efficient and speedy code. Furthermore, inspired by Rust's memory safety model, Tumy incorporates features like ownership and borrowing to ensure secure memory management and prevent common memory-related errors.

Under the hood, Tumy utilizes the powerful parsing capabilities of PLY (Python Lex-Yacc) to define its formal grammar and parsing rules. This allows for precise and reliable parsing of source code, aiding in the creation of robust and error-free applications.

With Tumy, developers can expect a powerful and user-friendly programming environment. By combining the strengths of Python, C++, and Rust, Tumy opens up new possibilities for software development across various domains.

# How to use

Dưới đây là một số ví dụ về cú pháp của ngôn ngữ Tumy

### 1. Khai báo biến:

```cs
int32 x = 10
string &y = "Hello world!"
```

### 2. Cấu trúc điều khiển:

```cs
if condition:
    // Thực hiện khi điều kiện đúng
else:
    // Thực hiện khi điều kiện sai

for item in iterable:
    // Lặp qua từng phần tử trong iterable

while condition:
    // Lặp cho đến khi điều kiện sai
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

### 3. Hàm:

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

### 5. Import thư viện:

```cs
import math

print(math.sqrt(16))  # Kết quả: 4.0
```

### 6. Hàm thực thi chính **main()**:

```cs
void main():
    // Các tác vụ và logic chính của chương trình Tumy

main()  // Gọi hàm main() để bắt đầu thực thi chương trình
```

### 7. Closures:

```cs
type closure_function(param1, param2) {
    // Các lệnh thực thi của closures
    // Có thể truy cập các biến từ phạm vi bên ngoài
    // Sử dụng param1, param2 và các biến khác
}
```

```cs
int add(a, b):
    return a + b


int result = add(3, 5)
print(result) // Kết quả: 8

```

```cs
int closure():
    int x = 10

    int inner_function(int y):
        return x + y

    return inner_function

int my_closure = closure()
int result = my_closure(5)  # Kết quả: 15
```

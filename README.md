# How to run or compile a Hello world ( simple programming) with a terminal 

# languages

- [C](#c-object-oriented-programming-language) C programming
- [C++](#c-1) C++ programming
- [Go](#go-language) Go lang
- [python](#python) Python programming
- [php](#php) PHP programming
- [Typescript](#typescript) Typescript programming
- [NodeJS](#nodejs) Node.js - JavaScript runtime environment

## C (object-oriented programming language)
**Step 1**: First you have to make sure available **gcc**  to compile a c code. <br>
open the terminal and run the following command to check **gcc** is already installed or not
```sh
gcc --version
```
**Step 2**: Create a new file e.g.  hello.c or example.c
**Step 3**: Simple code for testing c programming language
```c
#include<stdio.h>
int main(void){
 printf("Hello, I am C programming language!\n");
 return 0;
}
```
**Step 4**: run the following command on the terminal to compile the code
```sh
gcc hello.c -o output && ./output
```
remember to change hello to your file if you have a different name  and if you must run the terminal in the same directory where is the file (hello.c)


## C++
Step 1: first need to available **g++**  to compile a c code.
open the terminal and run the following command **g++** is already available on your computer if it doesn't exist install g++
```sh
g++ --version
```
Step 2: Create a file like **hello.cpp** or example.cpp <br>

Step 3: Simple code for a test run
```c
#include <iostream>
using namespace std;

int main() {
    cout << "Hello, I am C++ programming language!" << endl;
    return 0;
}
```
Step 4: run the following command on the terminal
```sh
g++ hello.cpp -o output && ./output
```
remember to change hello to your file if you have a different name  and if you must run the terminal in the same directory where is the file (hello.c)




## go language
Step 1: Make sure **go lang**  is available in your system.
if you have already installed Go language then go ahead.
to check the go language is available in your system run the following command
```sh
gcc --version
```

step 2: We need to create a file you can choose any name (hello.go e.g.) or example.go

step 3: write a simple code or past this code in your file hello.go
```go
package main

import "fmt"

func main() {
    fmt.Println("Hello, I am GO programming language!")
}
```
Step 4: Finally the the following command in your terminal to get the output of the code
```sh
go run hello.go
```
remember to change hello to your file if you have a different name  and if you must run the terminal in the same directory where is the file (hello.c)



## python
Step 1: Make sure **python or python3**  is available in your system.
if you don't have already installed then install it.
to check the go language is available in your system run the following command
```sh
python --version
```
or
```sh
python3 --version
```

step 2: We need to create a file you can choose any name e.g. (hello.py)

step 3: write a simple code or past this code in hello.py 
```py
print("Hello, I am python programming language! ")
```
Step 4: Finally run the following command in your terminal to get the output of the code
```sh
python hello.py
```
or
```sh
python3 hello.py
```
remember to change hello to your file if you have a different name  and if you must run terminal in same directory where is the file (hello.c)



## php
Step 1: Make sure **php**  is available in your system.
if you don't have already installed php language then install [php](http://php.net).
to check the go language is available in your system run the following command
```sh
php --version
```
step 2: We need to create a file you can choose any name (hello.php e.g.).
create with terminal
```sh
touch hello.go
```

step 3: write a simple code or past this code in your file hello.go
```php
<?php
echo "Hello, I am php programming language!";
```
Step 4: Finally the the following command in your terminal to get the output of the code
```sh
php hello.php
```


## rust

```sh
rustc --version
```
rust code 

```rust
fn main() {
    println!("Hello, I am Rust Programming Language");
}
```

```sh
rustc hello.rs -o output && ./output
```


# typescript

```sh
tsc -v
```
hello.ts file code

```ts
console.log("Hello, I am typescript");
```

```sh
tsc hello.ts
```

# nodejs

```sh
node -v
```

```js
console.log("Hello, I am nodejs");
```

```sh
node hello.js
```


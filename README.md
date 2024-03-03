# How to run or compile a Hello world ( simple programming) with terminal 

# languages

- [C](#c-object-oriented-programming-language) C programming
- [C++](#c-1) C++ programming
- [Go](#go-language) Go lang
- [python](#python) Python programming
- [php](#php) PHP programming
- [typescript](#typescript) Typescript programming
- [nodejs](#nodejs) Node.js programming

## C (object-oriented programming language)
Step 1: first need to available **gcc**  to compile a c code.
open terminal and run the following command to check if could not found then install **gcc**
```sh
gcc --version
```
Step 2: Create a file like hello.c or use terminal to create a file
```sh
touch hello.c
```
Step 3: Simple code for test run
```c
#include<stdio.h>
int main(void){
 printf("Hello, I am C programming language!\n");
 return 0;
}
```
Step 4: run the following command on terminal
```sh
gcc hello.c -o output && ./output
```
remember to change hello to your file if you have different name  and if you must be run terminal as same directory where is the file (hello.c)


## C++
Step 1: first need to available **g++**  to compile a c code.
open terminal and run the following command to check if could not found them install **g++**
```sh
g++ --version
```
Step 2: Create a file like **hello.cpp** 
or use terminal to create a file
```sh
touch hello.cpp
```
Step 3: Simple code for test run
```c
#include <iostream>
using namespace std;

int main() {
    cout << "Hello, I am C++ programming language!" << endl;
    return 0;
}
```
Step 4: run the following command on terminal
```sh
g++ hello.cpp -o output && ./output
```
remember to change hello to your file if you have different name  and if you must be run terminal as same directory where is the file (hello.c)




## go language
Step 1: Make sure **go lang**  is available in your system.
if you dont have already installed go language then install.
to check the go language is available in your system run the following command
```sh
gcc --version
```
then the output should look like this :
```sh
go version go1.13.5 linux/amd64
```
step 2: We need to create a file you can chose any name (hello.go e.g.).
if you would like to create the file with terminal type the following command
```sh
touch hello.go
```

step 3: write a simple code or past this code in your file hello.go
```go
package main

import "fmt"

func main() {
    fmt.Println("Hello, I am GO programming language!")
}
```
Step 4: finally the the following command in your terminal to get output of code
```sh
go run hello.go
```
remember to change hello to your file if you have different name  and if you must be run terminal as same directory where is the file (hello.c)



## python
Step 1: Make sure **python or python3**  is available in your system.
if you dont have already installed then install.
to check the go language is available in your system run the following command
```sh
python --version
```
or
```sh
python3 --version
```

step 2: We need to create a file you can chose any name (hello.py e.g.).
to create the file by terminal
```sh
touch hello.py
```

step 3: write a simple code or past this code in your file hello.go
```py
print("Hello, I am python programming language! ")
```
Step 4: finally run the following command in your terminal to get output of code
```sh
python hello.py
```
or
```sh
python3 hello.py
```
remember to change hello to your file if you have different name  and if you must be run terminal as same directory where is the file (hello.c)



## php
Step 1: Make sure **php**  is available in your system.
if you dont have already installed php language then install [php](http://php.net).
to check the go language is available in your system run the following command
```sh
php --version
```
step 2: We need to create a file you can chose any name (hello.php e.g.).
create with terminal
```sh
touch hello.go
```

step 3: write a simple code or past this code in your file hello.go
```php
<?php
echo "Hello, I am php programming language!";
```
Step 4: finally the the following command in your terminal to get output of code
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


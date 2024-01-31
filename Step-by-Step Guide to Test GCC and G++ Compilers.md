# **Step-by-Step Guide to Test GCC and G++ Compilers:**

### **1. Open Terminal:**

Press Ctrl + Alt + T to open a Terminal window.

 

### **2. Test GCC (C Compiler):**

Create a new file named hello.c using a text editor like Nano:

```cmd
nano hello.c
```

Write the following C code into the hello.c file:

```c
#include <stdio.h>

int main() {

  printf("Hello, World!\n");

  return 0;

}
```

Save the file and exit the text editor (in Nano, press Ctrl + O to save, then Enter, and Ctrl + X to exit).

Compile the hello.c file using the gcc compiler:

```cmd
gcc hello.c -o hello
```

Run the compiled executable:

```cmd
./hello
```

You should see the output:

```cmd
Hello, World!
```

**3. Test G++ (C++ Compiler):**

Create a new file named hello.cpp using a text editor:

```cmd
nano hello.cpp
```

Write the following C++ code into the hello.cpp file:

```c++
#include <iostream>

using namespace std;

int main() {

  cout << "Hello, World!" << endl;

}
```

Save the file and exit the text editor.

Compile the hello.cpp file using the g++ compiler:

```cmd
g++ hello.cpp -o hello_cpp
```

Run the compiled executable:

```cmd
./hello_cpp
```

You should see the output:

```cmd
Hello, World!
```

Final Output:

The output of both programs should be:

```cmd
Hello, World!
```

By following these steps, you can verify the installation of gcc and g++ compilers on your Ubuntu system and compile/run C and C++ programs successfully.
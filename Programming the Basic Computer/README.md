# Introduction 
The knowledge in computer architecture must to be interstand in the both software and hardware, because the two branches influence each other.

#### Table
- In this Table we notice how code will turned from high-level language such as `Java` or `C++` to `Machine Language` and understoodable by a computer.

| Language Level         | Description / Examples                              |
|------------------------|------------------------------------------------------|
| **High-level language** | Examples: C / C++ / Java / Python / Fortran         |
| **Compiler**            | Translates from high-level language to assembly     |
| **Assembly language**   | Symbolic code                                       |
| **Assembler**           | Translates from assembly to machine language        |
| **Machine language**    | Binary code, Octal or Hexadecimal code              |

### Program
A list of instructions or statements for directing the computer to perform a required task.

```cpp
#include <iostream>

using namespace std;

int main() {
    cout << "Hello, world!" << endl;

    
    return 0;
}
```
This will be turned to `Assembly Language` by **Assembler**.

Then Assembler will turn the code to `Machine Language`. Thats is different between languages , Some language like `Python` , `Java` and `C#` is Application languages not a System languages so it's turn first to something named **Bytecode**.
## Chapter 1:

### Title: Diving in C++

> This documents illustrates the basic structure of C++ program or main (.cpp) file that executes during compilation

> It doesn't tell you about deep understanding of how C++ compiler works because it will be held in other topic in this chapter, which is specifically the 6th topic.

> :memo: Let's start

```C++
#include <iostream>
```

> The first line of the C++ code, this is the library that runs C++ main features, basically it's meaning is simple: input & output stream.

```C++
#include <iostream>

int main() {
    return 0;
}
```

> This is the next lines of code and this function is the main function which means it runs the program, and without this main function, your C++ code won't compile. It is recommended to place it in the end, because logically it compiles and runs your C++ code, so it should be placed in the end. And also main function returns 0 because the function itself should return value and 0 stands for True, and 1 stands for False. You can run your C++ code without returning 0, but it is preferable to write it in the end of function body.

```C++
#include <iostream>

int main() {
    std::cout << "C++ is fast and powerfull programming language" << std::endl;
    return 0;
}
```

> So, in the 4th line of code we output the string using std namespace and cout, cout basically is an object of ostream class. And std::endl stands for \n or escape character. You can use either std::endl nor \n, depends on you.








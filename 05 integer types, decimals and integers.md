```cpp
#include <iostream>
#include <string>

int main() {
 int i{}; //if var doesn't have {}, 
          //it'll give garbage numbers AKA gives random number.
          //this is so cool btw
 int x{14};
 int y{6};

 std::cout << i << std::endl;
 std::cout << x << std::endl;
 std::cout << x + y << std::endl;

 std::cout << "------------------" << std::endl;// virtual line break here~

 int q(3.4); //info lost. less safe than {}

 std::cout << q << std::endl; 

 std::cout << "------------------" << std::endl;// virtual line break here~

 int w = 2.9; //info lost. less safe than {}

 std::cout << w << std::endl; 

 std::cout << "------------------" << std::endl;// virtual line break here~

 std::cout << sizeof(int) << std::endl; // bytes
 std::cout << sizeof(i) << std::endl; // bytes

 return 0;
}
```

output:
```
0
14
20
------------------
3
------------------
2
------------------
4
4
```
so the whole point is to show that vscode is a good ide. if you use {} on a decimal (`int{2.9}`), there's an error that says you should use a double before trouble (i came up with that on the spot btw). also this is the start of my brain damage AKA not properly naming variables.

also this is when memory things started. i honestly have no idea what that means or why it's important because i've only written small programs.

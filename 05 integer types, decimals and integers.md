```cpp
#include <iostream>
#include <string>

int main() {

    int i{}; //if var doesn't have {}, 
             //it'll give garbage numbers AKA gives random number.
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

}
```

result:
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
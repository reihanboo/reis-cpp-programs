```cpp
#include <iostream>
#include <string>

int main() {
 // all of these numbers equates to 15
 int num1 = 15; //decimal
 int num2 = 017; //octal. '0' in the beginning signals that this number is an octal
 int num3 = 0x0f; //hexadecimal. '0x' in the beginning signals that this number is a hexadecimal
 int num4 = 0b00001111; //binary. guess

 std::cout << num1 << std::endl << num2 << std::endl << num3 << std::endl << num4 << std::endl;

 return 0;
}
```

returns:
```
15
15
15
15
```

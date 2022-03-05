```cpp
#include <iostream>
  
int addition(int first_param, int second_param) {
 int result = first_param + second_param;
 return result;
}

int main()
{

 int firstNumber{3};
 int secondNumber{4};
  
 std::cout << firstNumber << std::endl;
 std::cout << secondNumber << std::endl;

 int sum = firstNumber + secondNumber;
 std::cout << "sum:" << sum << "\n";

 sum = addition(42,9000);
 std::cout << "sum:" << sum << "\n";

 sum = addition(5829,358092);
 std::cout << "sum: " << sum << "\n";

 std::cout << "sum: " << addition(4,6) << "\n";

 return 0;

}
```

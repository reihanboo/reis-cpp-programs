```cpp
#include <iostream>

int main() {
 int firstNumber{3};
 int secondNumber{4};

 std::cout << firstNumber << std::endl;
 std::cout << secondNumber << std::endl;
 
 return 0;
}
```
output:
```
3
4
```
---
```cpp
#include <iostream>

int main() {
 int firstNumber{3};
 int secondNumber{4};

 int sum = firstNumber + secondNumber;
 std::cout << "sum: " << sum << "\n";

 return 0;
}
```
output:
```
sum: 7
```
---
```cpp
#include <iostream>
  
int addition(int first_param, int second_param) {
 int result = first_param + second_param;
 return result;
}

int main() {
 int sum;
 sum = addition(42,9000);
 std::cout << "sum: " << sum << "\n";

 sum = addition(5829,358092);
 std::cout << "sum: " << sum << "\n";

 std::cout << "sum: " << addition(4,6) << "\n";

 return 0;
}
```
output:
```
sum: 9042  
sum: 363921
sum: 10  
```

```cpp
#include <iostream>
#include <string>

int main() {
 std::string sentence;

// this will repeat any sentence
 std::cout << "write something: ";
 std::getline(std::cin,sentence);
 std::cout << sentence << "\n";
}
```
output:
```
write something: {you write something. more than 2 words for extra effects}
{the repeat of that sentence}
```
the reason for choosing `std::getline` is so that you can input more than 2 words. while with `std::cin`, you can only input a single word

---
```cpp
#include <iostream>

 std::cerr << "error: something wrong" << "\n";
 std::clog << "log: something happened??" << "\n";
 
 return 0;
}
```
output:
```

```
i'm like actually confused. this is probably useless for small programs like mine, but may be useful for bigger ones. but using gcc 11.2.0 it acts as a `std::cout`. correct me if i'm wrong.

---
```cpp
#include <iostream>
#include <string>

int main() {
int age;
std::string full_name;

// the way
std::getline(std::cin,full_name);
std::cin >> age;
std::cout << "name: " << full_name << " age: " << age << std::endl;
    return 0; 
}
```

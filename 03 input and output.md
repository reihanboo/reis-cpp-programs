```cpp
#include <iostream>
#include <string>

int main()
{
int age;
std::string full_name, name;

// this will repeat any sentence
std::getline(std::cin,full_name);
std::cout << full_name << "\n";

// this block is for cError and cLog. idk what that is tho
std::cerr << "error: something wrong" << "\n";
std::clog << "log: something happened??" << "\n";

/* the wrong way
std::string name;
std::cout << "ur name: ";
std::cin >> name; */

/* just calling name
std::cout << "hello, " << name << "\n"; */

// the way
std::getline(std::cin,full_name);
std::cin >> age;
std::cout << "name: " << full_name << " age: " << age << std::endl;
    return 0; 
}
```
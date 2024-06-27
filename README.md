# Hi, I'm Maha!

```cpp
#include <iostream>
#include <vector>
#include <string>

struct Maha {
    std::string pronouns[2] = {"she", "her"};
    std::vector<std::string> languages = {"c++", "c#", "c"};
    std::string university = "fast nuces";
};

int main() {
    Maha maha;
    std::cout << "Hi, I'm Maha!" << std::endl;
    return 0;
}

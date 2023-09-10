# ФИО
Яблоков Денис Евгеньевич

# Специальность (направление)
ФИИТ

# Курс
2

# Увлечения, хобби и т.д.
```
#include <string>
#include <iostream>
#include <algorithm>

int main()
{
    auto i{ 0xC };
    std::string x{ "FIIT" };
    while(i--)
        std::next_permutation(x.begin(), x.end());   
    std::cout << x;
    return 0;
}
```

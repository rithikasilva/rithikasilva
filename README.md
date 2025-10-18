<!-- # Hi there 👋, I'm Rithika
-->
```C++
#ifndef RITHIKA_SILVA_H
#define RITHIKA_SILVA_H

#include <string>
#include <vector>
#include <iostream>

class RithikaSilva {
public:
    std::string alias = "r1tz";
    std::string status = "4th Year CS Student @ UW";
    
    std::vector<std::string> laptops = {
        "Quasar (M4 MacBook Pro)",
        "Tachyon (Asus G14, 2022)"    // Portable space heater
    };
    
    std::vector<std::string> languages = {"C++", "C", "Python", "Rust", "Go"};
    
    void now() const {
        std::cout << "Locked in." << std::endl;
    }
    
    // TODO: Stop adding TODOs
};

#endif // RITHIKA_SILVA_H
```

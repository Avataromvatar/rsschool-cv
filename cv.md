# Pankratov Aleksandr
## Contact information:
**Phone:** +79225052806  
**E-mail:** avataromvatar@gmail.com  
**Telegram:** @avataromvatar  
## About myself:
Husband and father of two girls aged 15 and 18. Curious, sociable, teachable and self-taught.  
I have passed an interesting life path from a plumber to a software developer, family and women's wardrobe are very motivating for growth.  
Now I want to strengthen my skills in JS, Dart, Backend.
## Skills and Proficiency:
- 5 years in C/C++ software development for domestic and imported microcontrollers (1986BE92, 1986BE1, STM32);
- 10 years in the development of PLC programs in LD, FBD, ST, C/C++, Lua;
- software development in C/C++ (Qt, boost, asio), Dart/Flutter, JavaScript;
- development of various devices based on microcontrollers for solving tasks on automated control systems and robotics;
- management of a small project team (4 people) according to the Agile methodology.

## General list of technologies used and available knowledge:
**Programming languages:** C, C++, Dart, JavaScript, LD, FBD, ST, Script, Lua.  
**Libraries and frameworks:** Rx Data, Block, Radius, Have, SQLite, stl, thread, Qt, boost.asio, Protothread, MQT, jQuery, NodeJS, websockets.  
**Web:** HTML5,CSS, JavaScript, RestApi, FastCGI, RPC-Json.  
**Version control system:** Git.   
## Code Example:
### Codewars task:
Implement the function which takes an array containing the names of people that like an item. It must return the display text as shown in the examples:
```
[]                                -->  "no one likes this"
["Peter"]                         -->  "Peter likes this"
["Jacob", "Alex"]                 -->  "Jacob and Alex like this"
["Max", "John", "Mark"]           -->  "Max, John and Mark like this"
["Alex", "Jacob", "Mark", "Max"]  -->  "Alex, Jacob and 2 others like this"
```
Note: For 4 or more names, the number in "and 2 others" simply increases.
### Code:
```
function likes(names) {

    if (names instanceof Array && names.length != 0) {
        if (names.length >= 4) {
            return `${names[0]}, ${names[1]} and ${names.length - 2} others like this`;
        }
        else
            if (names.length == 3)
                return `${names[0]}, ${names[1]} and ${names[2]} like this`;
            else
                if (names.length == 2)
                    return `${names[0]} and ${names[1]} like this`;
                else
                    return `${names[0]} likes this`;
    }
    return "no one likes this";
}
```
## Languages:
 - **Russian** - Native
 - **English** - B1


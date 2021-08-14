# Notes from tutorials

[Date => 14/08/2021]

it is bad practice to be using 
```c++
using namespace std;
```
instead use
```c++
using std::cout;
cout << "Hello\n";
```
or
```c++
std::cout << "Hello\n";
```
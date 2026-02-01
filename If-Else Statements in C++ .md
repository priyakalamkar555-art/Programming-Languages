# If-Else Statements in C++

*If-Else statements* in C++ are used for *decision-making*.  
They allow your program to *execute different code based on conditions*.

![Image](https://github.com/user-attachments/assets/7aa80050-e24b-4633-a5ce-bd45e0b02560)

## Real-Life Analogy

- If the light is *green*,  you go.  
- Else (red or yellow), you stop.  


## Syntax
```c++
if (condition) {
    // code to execute if condition is true
} else {
    // code to execute if condition is false
}
```
## Example

#include &lt;iostream&gt;
```
using namespace std;
int main() 
{
    int number;
    cout << "Enter a number: " ;
    cin >> number ;
 if (number % 2 == 0)      //checking condition if condition is true then even statement will execute
      {
           cout << number << " is even." ;
      } 
else       // otherwise else (odd ) statement wil execute
    {                            
        cout << number << " is odd." ;
    }
    return 0;
}```

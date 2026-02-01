# cin & cout in C++ Easy Way to Remember

### C++ uses cin & cout :

1) cin = Used to **Take Input from the User**  
2) cout =  Used to **Display Output to the Screen**

![Image](https://github.com/user-attachments/assets/df714579-b699-4ea9-95e5-d1c4921d3070)

# Real Life Analogy:
- cin = Listening Music 🎵
- cout = Reading Lyrics Aloud  🗣️

so simply, cin Listens, cout Speak

# Example:

#include &lt;iostream&gt;
using namespace std;

int main() {
    int age;
    cout << "Enter your age: ";   // Ask user to enter value
    cin >> age;                 // User input goes IN
    cout << "Your age is " << age;  // Display OUT
    return 0;
}

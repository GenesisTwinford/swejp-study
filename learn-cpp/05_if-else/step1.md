```cpp
#include <iostream>
using namespace std;

int main()
{
    int age[] = {16,48,72,66,23};
    
    for(int i = 0; i < 5; i++)
    {        
        // your code goes here. 
        // use a if else block to classify the person as Child / Adult / Retired
        if(age[] < 20)
        {
            cout << "Child" << endl;
        }
        else if(age[] >= 20 and age[] < 60)
        {
            cout << "Adult" << endl;
        }
        else
        {
            cout << "Retired" << endl;
        }
    }
    return 0;
}
```
- 問題
  https://www.learn-cpp.org/en/if-else
- メモ
  - ❌ ... age[]  
    ⭕️ ... age[i]  

  - 🔺 ... and  
    ⭕️ ... &&  
    &はビット演算子の操作のみで用いることができる。ほとんど使わない。
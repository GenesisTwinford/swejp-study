```c++
#include <iostream>
using namespace std;

int main() {
  int a = 3;
  float b = 4.5;
  double c = 5.25;
  double sum;

  /* Your code goes here */
sum = a + b + c;

  cout << "The sum of a, b, and c is " << sum << endl;
  return 0;
}
```
- 解いた問題
https://www.learn-cpp.org/en/Variables_and_Types
- 次回
https://www.learn-cpp.org/en/Arrays
- メモ
  - Cではstdio.hと書いたが、C++ではiostreamと書く。  
  stdio.hは型安全性が低いが速い。printf()で出力。  
  iostreamは型安全性が高いが遅い。cout <<で出力。
  - floatは約6~7桁、doubleは約15～16桁の小数含む有効数字に使う。
  - <<は、情報を右から左に流す（挿入・結合）という意味合いがある。

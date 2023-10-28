# Hello World

We will begin by teaching you guys how to print characters to the console!

```cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
    cout << "Hello World!\n";
}
			
```

This might look like some ancient runes but bear with us! We'll explain what each line of code does.

```cpp
#include <bits/stdc++.h>
```

What the first line does is include a library of code that has previously been written by other programmers. This library is called bits/stdc++.h . No one wants to write hundreds of lines of code in a time-constrained environment. Programmers reuse other code to save time and not reinvent the wheel.&#x20;

<figure><img src="../../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>

```cpp
using namespace std;
```

However, there are some annoying disadvantages including such a huge library in our code and we want to avoid this problem by including the block of code above in our program which prevents the function that we want to use from overlapping another family of functions, by including the keyword **namespace** to differentiate to the **compiler** organization in C++.&#x20;




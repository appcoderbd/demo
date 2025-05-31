# Demo Git Code
___

**Text Bold**

*Text Italic*

~~Delete Text~~

> This is new code


```js
let a = 10;
let b = 20;
console.log(a+b);
```

```c++
#include <stdio.h>
int main() {    

    int number1, number2, sum;
    
    printf("Enter two integers: ");
    scanf("%d %d", &number1, &number2);

    // calculate the sum
    sum = number1 + number2;      
    
    printf("%d + %d = %d", number1, number2, sum);
    return 0;
}
```

---

| Item   | Work   | Learn  |
|--------|--------|--------|
| Git    | Init   | Learn  | 
| Github | Commit | branch | 
| push   | pull   | head   | 
| recet  | -d     | hello  | 

---

`File > New > New Module` এ যান।

```java

    // MyUtils.java (mylibrary module)
    package com.moni.mylibrary;
    
    public class MyUtils {
        public static String sayHello() {
            return "Hello from Library!";
        }
    }

```

---

```git
cd path/to/your/project
git init
git remote add origin https://github.com/yourusername/MyAndroidLibrary.git
git add .
git commit -m "Initial library commit"
git push -u origin master
```
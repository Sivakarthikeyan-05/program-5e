# program-5e
# 🧪 C Programming Lab
## 📘 Experiment No: 5e
### 🔹
**Date:** 31/3/2026  
**Name:** Sivakarthikeyan .V
**Register No:** 25017090 

---

## 🎯 AIM
To write a C program to check ahether the givern character is digit or not.
---

## 🧠 ALGORITHM
1.Get a character as input from the user.
2.Check whether the given character is digit or not using ASCII value.
3.print the result using printf() function.
---

## 💻 PROGRAM
```
#include<stdio.h>
#include<ctype.h>
#include<string.h>
int main()
{
    char str[100];
    int count=0;
    fgets(str,sizeof(str),stdin);
    for(int i=0;str[i]!='\0';i++)
    {
        if((str[i]>=60&&str[i]<=90)||(str[i]>=97&&str[i]<=122))
        count++;
    }
    printf("Number of Alphabets in the string is : %d",count);
}
```

## 🖼️ OUTPUT SCREENSHOT

<img width="815" height="151" alt="image" src="https://github.com/user-attachments/assets/3209e2a1-8511-4463-adc0-7db61f8f7aef" />


---

## ✅ RESULT
Thus the C program to check whether the given character is digit or not is executed successfully.

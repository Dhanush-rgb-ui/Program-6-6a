# Module-6 Day-1 SEB
## AIM:
To write a c program to read and display an array of any 3 integer elements using pointer.

## For example:
<img width="225" height="136" alt="image" src="https://github.com/user-attachments/assets/6980225e-8feb-4d0c-8ff6-f11e8f6beca1" />

## Program:
```c
#include<stdio.h>
int main(){
    int n;
    int*p=&n;
    scanf("%d",p);
    int a[*p];
    int i;
    for(i=0;i<*p;i++){
        scanf("%d",&a[i]);
    }
    for(i=0;i<*p;i++){
        printf("the elements are %d\n",a[i]);
    }
    return 0;
}
```
## Result:
<img width="470" height="220" alt="image" src="https://github.com/user-attachments/assets/6151df78-36f2-47af-91cc-e6e923b7fd41" />

# Module-6 Day-1 SEB
## AIM:
To write a c program to read and display an array of any 3 integer elements using pointer.

## For example:

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

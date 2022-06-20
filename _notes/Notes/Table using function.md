```c
#include <stdio.h>

#include <conio.h>

void table(int n); // paramter

int n;

int main(){

  printf("Enter the number");

  scanf("%d",&n);

  table(n); // argument

  return 0;

}

void table(int n){

  for (int i = 1; i <=10 ; i++)

  {

    printf("%d\n",n*i);

  }

}
```
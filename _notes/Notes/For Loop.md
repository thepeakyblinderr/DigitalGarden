![[Pasted image 20220321183412.png|400]]

![[Pasted image 20220321183450.png|1000]]
once it initializes then it wont again initialize

___

# Example 1

```c
int main()

{

 for (int i = 0; i < 5; i++)

 {

 printf("kya chal raha bhai \n" );

 }

  

return 0;

}
```

# Print first 100 number
```c
#include <stdio.h>

#include <math.h>

  

 int main()

 {

 for (int i = 1; i <=100 ; i++)

 {

 printf("%d \n", i  );

 }

  

return 0;

}
```

# Increment and decrement

> 
> i++ means use i value first then increment it **post-increment**
> ++i means increment i value first and then use **pre-increment**
> 


## example 1
```c
int main()

 { 

 int i=1;

 printf("%d \n", i++);

 printf("%d", i);

  

return 0;

} 

here output will be 
1 
2
```


## example 2

```c
int main()

  {
 
  int i=1;

  printf("%d \n", --i);

  printf("%d", i);

  return 0;

 
  here output wil be 
  0
  0
```

> Loop counter can be float or even character

## example 3 - all alphabet in order

```c
int main()

 {

for (char ch='a'; ch <='z'; ch++)

 {

 printf("%c \n",ch );

}

return 0;

}
```

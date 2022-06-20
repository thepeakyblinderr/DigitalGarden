#  Function
- Remote buttons are example of function
- Block of code that performs certain task
- **Thumb Rule**
	- If we are using certain block of code more than three times then go make function of it


# syntax 1 Function Prototype/Declaration 
Ex - void printhello( );
it is void because it is not returning any value

# syntax 2 Function definition
```c
void printf(){
printf("Hello");
}
```

# syntax 3 Function call
```c
int main(){
printhello()
return 0; 
}
```

- Generally function are written below the int main function
- even if we dont right below the main function its okay but if we decide to right it above the int main function we dont need to declare function seperately 
```c
#include <stdio.h>

#include <conio.h>

  

void namaste();

void bonjour();

char ch;

  

int main(){

   printf("if you are indian press i and if you are french press f");

   scanf("%c", &ch);

  

   if(ch =='i'){

     namaste();

   }else {

     bonjour();

   }

  return 0;

}

  

void namaste(){

  printf("Namaste");

}

void bonjour(){

printf("Bonjour");

}
```

# [[Types of function]]
# [[Sum using function]]
# [[Table using function]]
# Difference between argument and parameter
![[Pasted image 20220414223302.png|300]]

___

![[Pasted image 20220414223809.png]]

```c

#include <stdio.h>

#include <conio.h>

  

int price(float value);

  

int main(){

  float value = 1000 ;

  price(value);

  printf("value is %f", value);

  return 0;

}

  

int price(float value){

  value = value + (0.18*value);

  printf( "final value is : %f", value);

}
```

**Output**
![[Pasted image 20220414225438.png]]

this happens because only copy of argument is passed  to the function
___

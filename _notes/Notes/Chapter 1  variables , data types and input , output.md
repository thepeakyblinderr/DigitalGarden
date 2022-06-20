.c is extension of c language
*gcc hello.c* , gcc is compiler to invoke the file
*./a.exe* - for windows and for mac *./a.out*

---  

# [[Variable in c|Variable]]
# First Program
```c
#include<stdio.h>

int main() 
{ printf("Hello World"); 
return 0;
}
```
 
 # Variables & Data Types + Constants & Keywords
```c
#include<stdio.h>
int main()
{ int number; 
int age; 
int price; 
return 0;
}
```

```
#include<stdio.h>
int main() 
{ int age = 22;
float pi = 3.14; 
char percentage = '%';
return 0;
}
```

---



# [[Keywords]]



# [[Comments]]


```
CASES 
integers
printf(" age is %d ", age);

real number
printf(" value of pi is %f ", pi);

characters
printf(" star looks like this %c ", star);

```



# [[Input]]



= is assignment operator

### sum program

```c
#include <stdio.h>
int main()
{
 int a,b;
 printf("enter a");
 scanf("%d", &a);
 printf("enter b");
 scanf("%d", &b);
int sum = a + b;
printf("sum is = %d", sum);
return 0;
}
```


---


# **Compilation** :
   A computer program that translates C code into machine code
![[Pasted image 20220320172134.png]]




# Area of circle program
```
include <stdio.h>
int main()
{
 int radius;
 float pi=3.14;
 float area;
 printf("enter radius");
 scanf("%d", &radius);
 area= (pi/4)*radius*radius;
 printf("are of circle is = %f", area );
return 0;
}
```
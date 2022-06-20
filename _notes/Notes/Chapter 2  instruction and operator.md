# [[Type Declaration Instructions]]

# [[Arithmetic Instructions]]

# [[Type Conversion]]

---


- invalid since product contains float 
```c

#include <stdio.h>
#include <math.h>
int main()
{
 printf("%d",2.0*9);
return 0;
}
```

- Valid

```c
#include <stdio.h>
#include <math.h>
int main()
{
 printf("%f",2.0*9);
return 0;
}
```

```c
int main()
{
 printf("%d",9/2);
return 0;
}
 
```

---

here output will be 4 not 4.5 since %d
in order to get 4.5 use %f

---

```
int a= 1.999;
output will be 1 only
 ```


---

![[Pasted image 20220320221859.png|500]]
![[Pasted image 20220320222053.png|500]]
![[Pasted image 20220320222635.png]]


---


## Control Instruction
   Used to determine flow of program
- **Relational operator** 

![[Pasted image 20220321104426.png|200]]



```c
{
 printf("%d",4==4);

return 0;
}

```

output will be 1 hence it is true
if outpput is 0 then it is false 

!= --> means not equal


---

- **Logical operator**

![[Pasted image 20220321105509.png|200]]

```c
int main()

{

 printf("%d",4>3 && 5>2);

return 0;

}

```

 output will be 1 hence true
___
![[Pasted image 20220321110157.png]]
 here output is 1
___
- **Operator precedence**
![[Pasted image 20220321110407.png|300]]
***relational > logical***
___
- **short hand operator**

![[Pasted image 20220321110643.png|200]]
 *when same variable i both left and right side use short hand*
 following example:
```c
int main()

{
 int a = 5;
 int c = 6;
 a+=c;
 printf("%d", a);
return 0;
}


OR

int main()

{

 int a = 5;
 int c = 6;
 a=a+c;
 printf("%d", a);
return 0;

}

```

___
# Divisible by 2 program / number is even or odd

```c
int main()

{
 int a;
float b;
printf("enter the number");
scanf("%d", &a);
printf("%d", a%2==0);
return 0;
}
```

if it returns 1 then it is divisible by 2

___

![[Pasted image 20220321113256.png|500]]

![[Pasted image 20220321113233.png|500]]
___

# Two digit number program
![[Pasted image 20220321113635.png|500]]

___
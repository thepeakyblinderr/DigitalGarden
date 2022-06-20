![[Pasted image 20220321183107.png|400]]

# [[For Loop]]
# [[Infinite loop]]
# [[While loop]]
# [[Do while loop]]

### [[C programming#^a99418]]
```c
#include <stdio.h>

#include <conio.h>

  

int main(){

    int n ;

    int sum=0;

    printf("enter the number you want sum for");

    scanf("%d",&n);

    for (int i = 0; i <=n; i++)

    {

       sum=sum+i;

    }

    printf("%d\n",sum);

  

    for (int i = n; i >=0; i--)

    {

        printf("%d\n",i);

    }
```

### Both sum and reversed

We can initialize multiple variables in For loop

```c
int main(){

    int n ;

    int sum=0;

    printf("enter the number you want sum for");

    scanf("%d",&n);

    for (int i = 0,  j=n; i <=n && j>=0; i++ , j--)

    {

       sum=sum+i;

       printf("%d\n",j);

    }

    printf("sum is %d\n",sum);

    return 0;

}

```

### Alternate way
sum --> 1+2+3
or sum --> 3+2+1 it is same
hence following program

```c
int main(){

    int n ;

    int sum=0;

    printf("enter the number you want sum for");

    scanf("%d",&n);

    for (int j=n;j>=0; j--)

    {

       sum=sum+j;

       printf("%d\n",j);

    }

    printf("sum is %d\n",sum);

    return 0;

```

### Printing table of number
```c
#include <stdio.h>

#include <conio.h>

  

int main(){

    int n ;

    printf("enter the number for table");

    scanf("%d",&n);

    for (int i=1; i<=10 ; i++)

    {

       printf("%d\n",n*i);

    }

    return 0;

}

```

# [[Break statement]] 

# [[Continue statement]]

# Print the factorial of number n
```c
#include <stdio.h>

#include <conio.h>

  

int main(){

    int n;

    int fact=1;

    printf("enter the number");

    scanf("%d",&n);

   for (int i = 1; i <=n ; i++)

   {

      fact=fact*i;

   }

   printf("factorials is %d\n",fact);

  

  return 0;

}
```

# Print table in reverse
```c
#include <stdio.h>

#include <conio.h>

  

int main(){

    int n;

    printf("enter the number");

    scanf("%d",&n);

   for (int i = 10; i >=1 ; i--)

   {

     printf("%d\n",n*i);

   }

  return 0;

}
```

# Calculate  sum from 5 to 50
```c
#include <stdio.h>

#include <conio.h>

  

int main(){

    int sum=0;

    for (int i = 5; i <=50; i++)

    {

        sum=sum+i;

    }

    printf("%d",sum);

  return 0;

}
```

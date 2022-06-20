for **exiting** the loop
```c
  
int main(){

    for (int i = 1; i <= 5; i++)

    {

        if (i==3)

        {

         break;

        }

     printf("%d\n",i);

    }

    printf("End");

    return 0;

```

###  Infinite loop
```c
int main(){

    int n;

    do {

    //    printf("enter the number");

    //    scanf("%d",&n);

    } while (1);
here 1 means true hence it will always be true
```

### Keep taking numbers till user input odd number
```c
#include <stdio.h>

#include <conio.h>

  

int main(){

    int n;

    do

    {

       printf("enter the number");

       scanf("%d",&n);

       printf("Entered number is %d\n",n);

if (n%2!=0 )

{

   break;

}

    } while (1);

printf("You have entered odd");    

    return 0;

}
```


### keep taking number until user enter number which is multiple of 7

```c
#include <stdio.h>

#include <conio.h>

  

int main(){

   int n ;

  do

  {

       printf("Enter the number\n");

       scanf("%d",&n);

      printf("You have entred : %d\n",n);

  

      if (n%7==0)

      {

         break;

      }

  

  } while (1);

 printf("entered number is multiple of 7");

  

  return 0;

}
```

- **Break takes you  out of even nested loops**
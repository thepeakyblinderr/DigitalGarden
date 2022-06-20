- Skips to the next iteration 
- *(aage wali cheez ko karo jo abhi karne vale wo chhod to)*
```c
#include <stdio.h>

#include <conio.h>

  

int main(){

   for (int i = 1; i <=5 ; i++)

   {

       if (i==3)

       {

           continue; // Skip

       }

      printf("%d\n",i);

   }
 
  return 0;

}
```

### Print all number from 1 to 10 except 6
```c

#include <stdio.h>

#include <conio.h>

  

int main(){

   for (int i = 1; i <11 ; i++)

   {

       if (i==6)

       {    

           continue;

       }

      printf("%d\n",i);

   }

  

  return 0;

}
```

 ### Print all the odd number from 5 to 50
```c
#include <stdio.h>

#include <conio.h>

  

int main(){

   for (int i = 5; i <=50; i++)

   {

       if (i%2!=0 )

       {    

           continue;

       }

      printf("%d\n",i);

   }

  

  return 0;

}
```

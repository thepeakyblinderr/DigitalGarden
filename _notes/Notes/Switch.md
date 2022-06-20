![[Pasted image 20220321161221.png|400]]

### Weekday example 
```c
int main()

{

 int day ;

 printf("enter number ");

 scanf("%d",&day);

 switch (day)

 {

 case 1 : printf("monday");

 break;

 case 2 : printf("tuesday");

 break;

 case 3 : printf("wednesday");

 break;

 case 4 : printf("thursday");

 break;

 case 5 : printf("friday");

 break;

 case 6 : printf("saturday");

 break;

 case 7 : printf("sunday");

 break;

 default: printf(" wrong info");

 }

return 0;

}
```


 here break is comment in this case so it will execute all cases
![[Pasted image 20220321162525.png|500]]

> 
> switch Properties b. Nested switch (switch inside switch) are allowed
> a. Cases can be in any order
> 

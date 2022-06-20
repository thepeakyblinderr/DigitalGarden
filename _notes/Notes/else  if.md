![[Pasted image 20220321155418.png|400]]

___


*if we dont want anything to do with above condition we just want all condition to run then use "if" repetitively*
![[Pasted image 20220321155709.png]]
___
### else if example
```c
int main()

{

 int age ;

 printf("what is your age");

 scanf("%d", &age);

 if (age >=18)

 {

 printf("you are a stupid adult \n");

 }

 else if (age >=13 && age <18){

 printf("teemager hai shanti me rahe");

 }

 else if (age <13){

 printf("ghar me ghusa rahe bahar mat nikal \n");

 }

 printf("ho gaya bhai chalo nhiklo");

return 0;

}
```

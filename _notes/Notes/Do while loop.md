
> A loop that runs at least once

![[Pasted image 20220321201645.png|400]]
___

![[Pasted image 20220321204518.png]]

> this i value is limited to that particular loop only
> "i" cant be used outside of ***for*** loop
>
>same i can be used for two or more loops 

^a99418



inside DO loop { jo bhi kaam karvana hai }

### Example of infinte loop if we don't put i++
```c
int main(){

    int i;

  do {

      printf("%d\n",i);

  } while (i<=5);

    return 0;

}
```

### Print in reverse
```c

int main(){

    int i=5;

  do {

      printf("%d\n",i);

      i--;

  } while (i>0);

    return 0;

}
```

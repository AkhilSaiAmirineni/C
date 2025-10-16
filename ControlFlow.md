### 1.WRITE A C PROGRAM TO ACCEPT TWO INTEGERS AND CHECK WHETHER THEY ARE EQUAL OR NOT?
~~~c
#include<stdio.h>
void main()
{
  int a,b;
  printf("enter two numbers");
  scanf("%d %d",&a,&b);
  if(a==b)
  printf("both are equal");
else
  printf("both are not equal");
}
~~~
### output
~~~c
enter 2 numbers:2 3
both are not equal
~~~


//# c-31
//with argument and return values
#include<stdio.h>
int mul(int a,int b)
{
    return a*b;
}
int main()
{
   int output=mul(11,22);
   printf("product %d \n",output);
    return 0;
}

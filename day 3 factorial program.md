

DAY 3 FACTORIAL PRAGRAM









\#include<stdio.h>

int main()

{

&nbsp;   int n,i;

&nbsp;   long long fact = 1;

&nbsp;   printf("Enter a number: ");

&nbsp;   scanf("%d",\&n);

&nbsp;   if(n<0)

&nbsp;   printf("Factorial is not defined for negative numbers.");

&nbsp;   else{

&nbsp;       for(i=1;i<=n;i++){

&nbsp;           fact\*=i;

&nbsp;       }

&nbsp;       printf("Factorial of %d\\n",fact);

&nbsp;   }

&nbsp;       return 0;

}


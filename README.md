#include<stdio.h>

int main ()

{

int num, sum = 0;

printf("Enter any num: "); scanf("%d",&num);

//loop to find sum of digits while(num!=0){

sum += num % 10;

num = num / 10;

}

printf("Sum: %d",sum);

return 0;

}

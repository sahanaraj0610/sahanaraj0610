#include <stdio.h>
void printFactor(int num)
{
print("Factors of %d are:\n",num);
for(int i=1;i<=num;i++)
{
if(num%i==0)
{
printf(%d',i);
}}
printf("\n");
}
int main(){
int number;
print("Enter a number");
scanf("%d",&number);
printFactors(number);
return 0;
}

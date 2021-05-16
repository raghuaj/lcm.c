#include<stdio.h>
int lcm(int a,int b,int i)
{  if((a*i)%b==0)
   return a*i;

   else
       {
           i=i+1;
        return lcm(a,b,i);
       }
}

int main()
{
    int n1,n2,z;
    printf("Enter Number 1: ");
    scanf("%d",&n1);

    printf("\nEnter Number 2: ");
    scanf("%d",&n2);

    if(n1>=n2)
        z=lcm(n1,n2,1);
    else
        z=lcm(n2,n1,1);

    printf("\nLCM of the given two numbers is %d \n",z);
return 0;
}

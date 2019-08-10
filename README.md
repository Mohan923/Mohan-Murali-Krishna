#include<stdio.h>
int main()
{
int i,x,p;
float m,s=0;
scanf("%d %d\n",&x,&p);
m=x;
if(x>0&&x<10000)
{
if(p>1&&p<100)
{
i=0;
while(i!=4)
{
s=s+m;
m=(m*p)/100;
i++;
}
}
}
printf("%f\n",s);
}

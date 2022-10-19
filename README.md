//# Net-and-gross-salary.c//
#include<stdio.h>
int main()
{
   float bs,da,hra,pf,gs,net;
   printf("Enter basic salary\n");
   scanf("%f",&bs);
   hra=0.2*bs;
   da=0.5*bs;
   pf=0.05*bs;
   gs=bs+da+hra+pf;
   net=gs-pf;
   printf("\n house rent allowance=%f",hra);
   printf("\n dearness allowance=%f",da);
   printf("\n personal finance=%f",pf);
   printf("\n gross salary=%f",gs);
   printf("\n net salary=%f",net);
   return 0;
}

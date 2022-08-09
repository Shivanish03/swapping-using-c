/*# swapping-using-c*/
/*swapping of integers values*/
#include<stdio.h>
#include<conio.h>
int main()
{
int a,b,temp ;
printf("enter the value of a=");
scanf("%d",&a);
printf("enter the value of b:-");
scanf("%d",&b);
// if a=2 and b=5 , and user want output swapping of numbers as a=5 and b=2 , using temp variable we store value of a in temp and then swap value of b in and then swap value of temo in b  
temp=a;
a=b;
b=temp;
printf("a=%d and b=%d", a,y);
getch();
}

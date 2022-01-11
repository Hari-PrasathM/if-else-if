#include<stdio.h>
void main()
{
int mark;
printf("Enter your mark :");
scanf("%d",&mark);
if(mark<=100 && mark>=85)
{
printf("Grade A");
}
else if(mark<=84 && mark>=70)
{
printf("Grade B");
}
else if(mark<=69 && mark>=55)
{
printf("Grade C");
}
else if(mark<=54 && mark>=40)
{
printf("Grade D");
}
else
{
printf("Grade F");
}
return 0;
}

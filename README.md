#include<stdio.h>
int main()
{
int a;
printf("Enter the marks of the student : ");
scanf("%d",&a); // scaning input
    //finding grade for entered marks
if(a>=85)                   //if marks are >=85 grade is A
    printf("Grade A \n");
else if(a<=84&&a>=70)      //if marks are >=70 and <=84 grade is B.
    printf("Grade B \n");
else if(a<=69&&a>=55)      //if marks are >=55 and <=69 grade is C.
    printf("Grade C \n");
else if(a<=54&&a>=40)      //if marks are >=40 and <=54 grade is D.
    printf("Grade D\n");
else if(a<=39&&a>=0).      //if marks are >=0 and <=39 grade is F.
    printf("Grade F \n");
  //we know marks can not be negative so if entry is -ve it will print invalid entry.
else
    printf("Invalid entry \n");
return 0;
}

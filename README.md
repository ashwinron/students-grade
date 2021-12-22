#include<stdio.h>

int main()
{
    float marks;
    char grade;
    printf("enter my marks:");
    scanf("%f",&marks);
    
    if(marks>=90)
    {
        grade = 'a';
    }
    else if(marks>=80 && marks<90)
    {
        grade='b';
    }
    else if(marks>=70 && marks<80)
    {
        grade = 'c';
    }
    else if(marks>=60 && marks<70)
    {
        grade = 'd';
    }
    else if(marks>=50 && marks<60)
    {
        grade = 'e';
    }
    else
    {
        grade='f';
    }
    printf("your grade is %c",grade);
    return 0;
    
}




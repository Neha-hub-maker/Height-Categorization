#include<stdio.h>
int main()
{
    float a;
printf("enter height of th person");
scanf("%f",&a);
if (a<150)
{
    printf("he is dwarf");
    
}
else
{
if(a>=150 && a<165)
{
    printf("he is average");
}
else{
        if(a>=165 && a<=195)
        {
            printf("he is tall");
        }
        else {
            printf("he has abnobmal height");
        }

    }
}









return 0;
}

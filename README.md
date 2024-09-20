# op-tester
#include <stdio.h>
int main()
{
    char firstname[50],secondname[50];
    //prompt the user to enter thier name 
    printf("enter your firstname:");
    scanf("%s", firstname);
    printf("enter your secondname:");
    scanf("%s", secondname);
    //Display the entered names
    printf("\nYour full name is: %s %s ", firstname,secondname);
    return 0;
}
    

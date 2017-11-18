#include <stdio.h>
int main()
{
    int number;
    printf("enter a number:");
    scanf("%d", &number);
    if (number < 0)
    {
       printf("you entered %d. \n", number);
    }
    return 0;
}

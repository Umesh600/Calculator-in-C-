# Calculator-in-C-
In this program use in switch case 

#include <stdio.h>

int main()
{
    float num1,num2,result;
    char op;

    printf("Enter the operation:");
    scanf("%c",&op);

    printf("Enter the two num:");
    scanf("%f %f",&num1,&num2);


    switch(op) {
    case '-':
        result = num1-num2;
        printf("%f",result);
        break;

    case '+':
        result=num1+num2;
        printf("%f",result);
        break;

    case '*':
        result=num1*num2;
        printf("%f",result);
        break;

    case '/':
        result=num1/num2;
        printf("%f",result);
        break;

    default :
        printf("\nthe opertor is not valid:");
    }
    return 0;
}

# guessthenumbergame
#include<stdio.h>
int main()
{
    int n,m=9,i=0;

    printf(" Welcome to the guess the number game\n");


    do
    {
        printf("Take your guess :");
        scanf("%d",&n);

    i++;
         if(n>m)
    {
        printf("Think of a smaller number\n");
    }
    else if (n<m)
    {
        printf("Think of a greater number\n");
    }
    else
    {
        printf("Right guess");
    }

    }
    while(n!=m);

return 0;
}

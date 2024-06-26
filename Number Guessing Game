#include <stdio.h>
#include <math.h>
#include <stdlib.h>
#include <time.h> 

int main()
{
    int lb,ub,n,m,i,c=0;
    
    printf("Enter Lower bound:- ");
    scanf("%d",&lb);
    printf("Enter Upper bound:- ");
    scanf("%d",&ub);
    srand(time(0)); 
    n=(rand()%(ub-lb+1))+lb; 
    //printf("%d",n);
    printf("\n\tYou have only 7 chances to guess the integer!\n");
    while(i<=7)
    {
        c++;
        printf("\nGuess a number:- ");
        scanf("%d",&m);
        if(m<=lb||m>=ub)
        {
            printf("Number out of bound.\n");
        }
        else
        {
            if(m==n)
            {
                printf("\tCongratulations you did it in %d chances!\n",c);
                exit(1);
            }
            else
            {
                if(m<n)
                {
                    printf("You guessed too small!\n");
                }
                else
                {
                    printf("You guessed too high!\n");
                }
            }
        }
        i++;
    }
    printf("\n\tThe number is %d",n);
    printf("\n\tBetter Luck Next time!");
    return 0;
}

#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() 
{
	/*0 -> Snake
	  1 -> Water
	  2 -> Gun*/
    srand(time(0)); // Seed the random number generator with the current time
    int player,computer = rand() % 3; // Generate random number between 0 and 2
    printf("Enter 0 -> Snake, 1 -> Water, 2 -> Gun\n");
    scanf("%d",&player);
    printf("Computer chose %d\n",computer);
    if(player==computer)
    printf("It's a Draw!\n");
    else if((player==0 && computer==1) || (player==1 && computer==2) || (player==2 && computer==0))
    printf("You Win!\n");
    else if((player==0 && computer==2) || (player==1 && computer==0) || (player==2 && computer==1))
    printf("You Lose!\n");
	else
	printf("Something went wrong!!");    
    return 0;
}

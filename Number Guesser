#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() 
{
    srand(time(0)); // Seed the random number generator with the current time
    int random_num = (rand() % 100) + 1; // Generate random number between 1 and 100
    int guess_num,guess=0;
    do
    {
    	printf("Guess a Number : ");
    	scanf("%d",&guess_num);
    	if(guess_num<random_num)
    	printf("Higher number please\n");
    	else if(guess_num>random_num)
    	printf("Lower number please\n");
    	else
    	printf("Congrats!!");
    	guess++;
	}while(guess_num!=random_num);
	printf("You've guessed the number in %d guesses\n",guess);
    return 0;
}

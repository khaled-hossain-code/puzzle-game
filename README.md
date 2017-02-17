#include "stdio.h"

int main(void) {
  char ch;
  int num;
  int guessedNum = 67;
  
  printf("Guess My Number between 1 to 100: ");
  scanf("%d",&num);
  
  
  //start your loop here
  //
  if(num > guessedNum)
  {
    printf("Too large");
  }
  
  //if nuber is not eqaul ask again
  //if number is equal then break;
  return 0;
}

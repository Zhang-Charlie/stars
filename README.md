# stars
Write a C program that reads an integer n from the console and displays a stars pattern as shown in the examples below.  Example runs of the program:  Enter a value for n: 1 *  Enter a value for n: 2 ** *  Enter a value for n: 4 **** *** ** *
#include <stdio.h>

int main(void){

int n,index, column, counter;

printf("Enter a value for n:\n");
scanf("%d", &n);
                //  index >= 3
              //3  
    // 3counter == 3 ; 3counter >= 1; 2counter 
    // 2counter == 3 ; 2counter >= 1; 1counter      \n
    // 1counter == 3 ; 1counter >= 1; 0counter      \n
    // 0counter == 3 ; 0counter >= 1 STOPS HERE     






    // 3counter == 3 ; 3counter >= 1; 2counter 

    // 1index == 1 ; 1index >= 3counter; 2counter   
    // 1index == 1 ; 1index >= 2counter; 1counter   
    // 1index == 1 ; 1index >= 1counter; 0counter   
    // 1index == 1 ; 1index >= 0counter  STOPS HERE ***
        
        \n
    
    // 2counter == 3 ; 2counter >= 1; 1counter      
    
    // 1index == 1 ; 1index >= 2counter; 1counter   
    // 1index == 1 ; 1index >= 1counter; 0counter   
    // 1index == 1 ; 1index >= 0counter  STOPS HERE **
        \n
        
    // 1counter == 3 ; 1counter >= 1; 0counter  
    
    // 1index == 1 ; 1index >= 1counter; 0counter   
    // 1index == 1 ; 1index >= 0counter  STOPS HERE  *
    
    
    // 0counter == 3 ; 0counter >= 1 STOPS HERE    
    
    
    
    
    
    
    
    
     // 1index == 1 ; 1index >= 3counter; 2counter   
    // 1index == 1 ; 1index >= 2counter; 1counter   *
    // 1index == 1 ; 1index >= 1counter; 0counter   **
    // 1index == 1 ; 1index >= 0counter  STOPS HERE ***
    
for(counter = n; counter >= 1 ; counter-- )
{   
    // 3counter == 3 ; 3counter >= 1; 2counter 

    // 1index == 1 ; 1index >= 3counter; 2counter   
    // 1index == 1 ; 1index >= 2counter; 1counter   
    // 1index == 1 ; 1index >= 1counter; 0counter   ***
    
    // 2counter == 3 ; 2counter >= 1; 1counter      \n
    
    // 1index == 1 ; 1index >= 2counter; 1counter   
    // 1index == 1 ; 1index >= 1counter; 0counter   **
    
    // 1counter == 3 ; 1counter >= 1; 0counter      \n

    
    // 1index == 1 ; 1index >= 0counter  STOPS HERE *
    
    // 0counter == 3 ; 0counter >= 1 STOPS HERE 
   
    
    for(index = 1;index <= counter ;index++ )
    {   
        printf("*");
    }  

    printf("1\n");
} 


return 0;

}


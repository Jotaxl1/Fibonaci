#include "stdio.h"

void main() { 
    unsigned long long int a, b, aux;
	unsigned int i, n;

    a = 0; 
    b = 1; 

    printf("Por favor digite um numero para iniciar : "); 

    
    scanf("%u", &n); 
    printf("Fibonacci:\n"); 
    printf("1: 1\n"); 


    for(i = 0; i < n-1; i++) { 
	    aux = a + b; 
	    a = b; 
	    b = aux; 

	    printf("%u: %llu\n", i+2, aux); 
    } 
}

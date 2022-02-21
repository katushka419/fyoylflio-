#include <iostream> 
# include <stdio.h> 
  
int main ( ) 
  { 
     float a, b; 
     float s; 
     printf ("Исходные данные: \n"); 
     printf ("Длина"); 
     scanf ("%f", & a); 
     printf ("Ширина"); 
     scanf ("%f", & b); 
     s=a* b; 
     printf ("Площадь:%10.2f\n", s); 
     system("Стоп"); 
     return 0; 
   }

# number-division
" A simple program to divide one number by another " .



#include <stdio.h>
int main ()
{
    int a , b ,rem;
    printf ("Enter dividend : " , a) ;
    scanf ("%d" , &a) ;

    printf ("Enter divisor : " , b) ;
    scanf ("%d" , &b) ;

    rem = a%b ;

    printf ("Remainder = %d " , rem) ;

    return 0 ;

}

// if cp and sp of item is input determine profit or loss the seller has incurred //
#include <stdio.h>

int main() {
   float cp, sp, loss, profit, a;
   printf("Enter the value of cp and sp \n");
   scanf("%f%f", &cp,&sp);
   a = sp - cp; // Calculate the difference between selling price and cost price
   if(sp > cp) {
       printf("The profit he made: %f", a);
   } else {
       printf("The loss he incurred: %f", a);
   }
   return 0;
}

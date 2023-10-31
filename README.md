

       
#include <stdio.h>

int main() {
    int hundreds, fifties, twenties, tens, fives, ones;
    double quarters, dimes, nickels, pennies;

    printf("Money Counting Application\n");

    printf("Enter the number of $100 bills: ");
    scanf("%d", &hundreds);

    printf("Enter the number of $50 bills: ");
    scanf("%d", &fifties);

    printf("Enter the number of $20 bills: ");
    scanf("%d", &twenties);

    printf("Enter the number of $10 bills: ");
    scanf("%d", &tens);

    printf("Enter the number of $5 bills: ");
    scanf("%d", &fives);

    printf("Enter the number of $1 bills: ");
    scanf("%d", &ones);

    printf("Enter the number of quarters: ");
    scanf("%lf", &quarters);

    printf("Enter the number of dimes: ");
    scanf("%lf", &dimes);

    printf("Enter the number of nickels: ");
    scanf("%lf", &nickels);

    printf("Enter the number of pennies: ");
    scanf("%lf", &pennies);

    // Calculate the total amount
    double totalAmount = (hundreds * 100.0) + (fifties * 50.0) + (twenties * 20.0) + (tens * 10.0) + (fives * 5.0)
            + ones + (quarters * 0.25) + (dimes * 0.1) + (nickels * 0.05) + (pennies * 0.01);

    printf("Total amount: $%.2f\n", totalAmount);

    return 0;
}
<!---
Pritimadake/Pritimadake is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

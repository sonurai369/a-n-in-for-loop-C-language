# a-n-in-for-loop-C-language
<a>
#include <stdio.h>

int main() {
    int a, n, result = 1;

    // Taking base and exponent input
    printf("Enter the base (a): ");
    scanf("%d", &a);
    printf("Enter the exponent (n): ");
    scanf("%d", &n);

    // Calculating a^n using a for loop
    for (int i = 1; i <= n; i++) {
        result *= a;
    }

    printf("%d^%d = %d\n", a, n, result);
    
    return 0;
}

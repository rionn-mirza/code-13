#include <stdio.h>

int main() {
    int num, i;
    
    printf("Kon sonkhar namta chaan? ");
    scanf("%d", &num);
    
    printf("\n%d er namta:\n", num);
    for(i = 1; i <= 10; i++) {
        printf("%d x %d = %d\n", num, i, num * i);
    }
    
    return 0;
}

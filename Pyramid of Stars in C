#include <stdio.h>

int main() {
    
    int rows;
    
    printf("Enter Rows: ");
    scanf("%d", &rows);
    
    for (int i = 1; i <= rows; i++) {
        for (int j = 1; j <= 2 * rows - 1; j++) {
            if (j >= rows - (i - 1) && j <= rows + (i - 1)) {
                printf("*");
            }
            else {
            printf(" ");
            }
        }
        printf("\n");
    }
    return 0;
}

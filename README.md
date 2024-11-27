# code-platinium
this is my first porject.
author= rohit maurya
// multiplication of 2 dimensional matrix in c program 
#include<stdio.h>
HERE
int main() {
    int A[2][2], B[2][2], C[2][2];

    
    printf("Enter the values for matrix A[2][2]:\n");
    for (int i = 0; i < 2; i++) {
        for (int j = 0; j < 2; j++) {
            printf("A[%d][%d]: ", i, j);
            scanf("%d", &A[i][j]);
        }
    }

    
    printf("Enter the values for matrix B[2][2]:\n");
    for (int i = 0; i < 2; i++) {
        for (int j = 0; j < 2; j++) {
            printf("B[%d][%d]: ", i, j);
            scanf("%d", &B[i][j]);
        }
    }

    
    printf("Resultant matrix C:\n");
    for (int i = 0; i < 2; i++) {
        for (int j = 0; j < 2; j++) {
            C[i][j] = A[i][j] * B[i][j];
                        printf("C[%d][%d] = %d\n", i, j, C[i][j]);
                    }
                }

                return 0;
            }





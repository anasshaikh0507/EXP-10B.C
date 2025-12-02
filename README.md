//SHAIKH MOHAMMED ANAS,UIN:251P085,Roll No:10
//Class:F.E,Div:D
#include <stdio.h>

int main() {
    int array[] = {10, 20, 30, 40, 50};
    int n = sizeof(array) / sizeof(array[0]);
    int *p = array;
for(int i = n - 1; i >= 0; i--) {
        printf("%d ", *(p + i)); }

    return 0;}

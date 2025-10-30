# C-Programming_Ezaan-Ejaz
#include <stdio.h>

int main()
{
    int size, min;
    printf("\n Enter the size of array :");
    scanf("%d", &size);
    int array[size];
    min = array[0];
    for (int i = 0; i < size; i++)
    {
        printf("\n Enter the value of %d array element :", i);
        scanf("%d", &array[i]);
        if (min > array[i])
        {
            min = array[i];
        }
    }
    printf("\n The minimum value in the array is %d", min);
    return 0;
}

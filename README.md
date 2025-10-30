# C-Programming_Ezaan-Ejaz
<<<<<<< HEAD
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
=======
 
>>>>>>> ea6914191abe318eb231b8c99c78cce0fb665f78

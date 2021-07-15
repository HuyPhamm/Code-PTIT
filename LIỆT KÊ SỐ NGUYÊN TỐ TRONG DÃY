#include <stdio.h>

int main()
{
    int n;
    scanf("%d", &n);
    int a[n];
    for (int i = 0; i < n; i++)
        scanf("%d", &a[i]);
    int flag = 0;
    int count = 0;
    for (int i = 0; i < n; i++)
    {
        int flag = 0;
        for (int j = 2; j < a[i]; j++)
        {
            if (a[i] % j == 0)
            {
                flag = 1;
                break;
            }
        }
        if (flag == 0 && a[i] > 1)
            count++;
    }
    printf("%d ", count);
    for (int i = 0; i < n; i++)
    {
        int flag = 0;
        for (int j = 2; j < a[i]; j++)
        {
            if (a[i] % j == 0)
            {
                flag = 1;
                break;
            }
        }
        if (flag == 0 && a[i] > 1)
            printf("%d ", a[i]);
    }
}

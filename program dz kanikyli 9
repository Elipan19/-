#include <iostream>//TODO:)))

int strange(int *arr, int size)
{
    if (size > 0)
        return arr[size-1] + strange(arr, size-1);
    else
        return 0;
}

int main()
{
    int n;
    std::cin >> n;
    int arr[n];
    for(int i =0; i < n; i++)
    std::cin >> arr[i];
    int sum = strange(arr, n);
    std::cout << sum;
    return 0;
}

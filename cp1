#include "iostream"
void delete_duplicates(int arr[], int &n){ // Зодача 1
  for(int i=0;i<n;i++){
     for(int j=i+1;j<n;) {
         if(arr[i]==arr[j])
         {
             for(int k=j;k<n;k++)
             {
                 arr[k]=arr[k+1];
             }
             n--;
         }
         else j++;
     }
   }
}
int main() {
  int n = 0;
  std::cin >> n;
  int m[n] = {-1};
  for(int i = 0; i<n; i++)
    std::cin >> m[i];
  delete_duplicates(m, n);
  for(int i=0;i<n;i++) std::cout <<m[i]<<" ";
  return 0;
}

#include "iostream"
bool isP(int n){
  if(n == 0) return false;
  bool isPrime = true;
  for(int i = 2; i <= n / 2; ++i)
  {
      if(n % i == 0)
      {
          isPrime = false;
          break;
      }
  }
  return isPrime;
}
void delete_annoying_primes(int arr[], int &n){ // Зодача 2
  for(int i=0;i<n;i++){
     for(int j=i+1;j<n;) {
         if(arr[i]==arr[j] && isP(arr[j]))
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
  delete_annoying_primes(m, n);
  for(int i=0;i<n;i++) std::cout <<m[i]<<" ";
  return 0;
}

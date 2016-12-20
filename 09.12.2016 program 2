#include <iostream>

int s = 12;
void printArr(int arr[], int n) {for(int i=0; i<n; i++) std::cout <<arr[i]<< " "; std::cout << std::endl;}

void brf(int arr[], int n){
  for(int i=0; i<10;i++) {
    if(arr[s-n] +1 < 10) arr[s-n]++;
    else {arr[s-n+1]++; arr[s-n] = 0; return;}
    if((arr[0]+arr[1]+arr[2])%2 == 0)
    if((arr[11]+arr[10]+arr[9])%3==0)
    if((arr[2]+arr[11]+arr[5]+arr[8])%11==0)
    if((arr[1]+arr[3]+arr[5]+arr[7]+arr[9]+arr[11])%21==0)
    printArr(arr, s);
    if(n != 1) brf(arr, n-1);
  }
}

int main (){
  int a[s]={1};
  a[0]=0;
  brf(a, s);
}

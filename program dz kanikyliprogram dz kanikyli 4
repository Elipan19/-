#include "iostream"
#include <stdio.h>
void dig_trench(int *mt, int n){// 4
  int i,j,x;
  for(j=0;j<n;j++){
    x = n-j-1;
    for(int i = x; i<(n+x);i++){
      *(mt+n*j+i-x)=((i<(n-1))?(n-i-1):(i-n+1));
    }
  }
}
int main(){
  int n = -1;
  scanf("%i", &n);
  int mt[n][n];
  dig_trench(mt[0],n);
  for(int i=0;i<n;i++){
    for(int j=0;j<n;j++)
      printf("%i ",mt[i][j] );
    printf("\n");
  }
}

#include "iostream"
#include <stdio.h>
void build_ziggurat(int *mt, int n){// 3
  for(int x = 0; x < n/2; x++)
    for(int i = x; i<n-x;i++)
      for(int j= x; j<n-x;j++)
        *(mt+n*i+j) = x+1;
}
int main(){
  int n = -1;
  scanf("%i", &n);
  int mt[n][n];
  build_ziggurat(mt[0],n);
  for(int i=0;i<n;i++){
    for(int j=0;j<n;j++)
      printf("%i ",mt[i][j] );
    printf("\n");
  }
}

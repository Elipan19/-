#include <iostream> //TODO: snake
#include <stdio.h>
void put_snake(int *mt, int n, int m){// 3
  int i=0, j=m-1;
  for(int i=0; i < n*m;i++) *(mt+i)=-1;
  for(int x = 1; x < n*m;) {
        for(int ii = 0; ii < n; ii++)
          if(*(mt+m*i+j-m) == -1)             {*(mt+m*i+j) = x++;i--;} // up
          else                                {*(mt+m*i+j) = x;break;}
        for(int ii = 0; ii < m; ii++)
          if(*(mt+m*i+j-1) == -1 && j-1 >= 0) {*(mt+m*i+j) = x++;j--;}// left
          else                                {*(mt+m*i+j) = x;break;}
        for(int ii = 0; ii < n; ii++)
          if(*(mt+m*i+j+m) == -1)             {*(mt+m*i+j) = x++;i++; }// down
          else                                {*(mt+m*i+j) = x;break;}
        for(int ii = 0; ii < m; ii++)
          if(*(mt+m*i+j+1) == -1 && j+1 < m)  {*(mt+m*i+j) = x++;j++; }// right
          else                                {*(mt+m*i+j) = x;break;}
      }
}

int main()
{
  int n = -1, m;
  scanf("%i", &n);
  scanf("%i", &m);
  int mt[n][m];
  put_snake(mt[0],n,m);
  for(int i=0;i<n;i++){
    for(int j=0;j<m;j++)
      printf("%i\t",mt[i][j] );
    printf("\n");
  }
  return 0;
}

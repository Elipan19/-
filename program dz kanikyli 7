#include "iostream"
int strange_multiply(int a, int n) {
	if (n == 0 && n == 0) return 0;
	if (n % 2 == 1)
		return strange_multiply (a, n-1) + a;
	else {
		int b = strange_multiply (a, n/2);
		return b + b;
	}
}
int main(){
  int a,b;
  std::cin >> a;
  std::cin >> b;
  int s = strange_multiply(a,b);
  std::cout << s;
  return 0;
}

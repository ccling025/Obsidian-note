### Format Input
Use:
- %d for int
- %c for char
- %s for string
- %f for float
#### Custom format
- %.1f
	- 取到小數後1位
***
#### Implement of a simple calculator
```C
#include<stdio.h>
int main(){
	int a, b;
	char c;
	scanf("%d%c%d", &a, &c, &b);
	printf("%d\n", (a+b)*(c=='+')+(a-b)*(c=='-')+(a*b)*(c=='*'));
}
```
Input:
```
10+20
10-20
10*20
```
Output:
```
30
-10
200
```
*** 
###
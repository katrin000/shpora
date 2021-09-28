# shpora
hell0
#include <stdio.h>

int main(void)
{
	//переменная;
		//x=p*e^m;
		//тип имя;
		//тип имя=значение;

	int a;
	int b = 32;

	char q;
	unsigned char w;
	short e;
	unsigned short f;
	int d;
	unsigned m;
	long n;
	unsigned long l;
	float s;
	double c;
	long double x;
	
	char A = 1;
	unsigned char W = 100;
	short E = 1000;
	unsigned short F = 65534;
	int D = 2147483646;
	unsigned M = 4294967294;
		long N = 2147483643;
		unsigned long L = 4294967293;
		float S = 2;
	double C = 1;
	long double X=1;

	q = 1;
	 w = 100;
	 e = 1000;
	 f = 65534;
	 d = 2147483646;
	 m = 4294967294;
	 n = 2147483643;
	 l = 4294967293;
	 s = 2;
	 c = 1;
	 x = 1;
	 printf("%d %d %d %d %d %d %d %d %l %lf %lf\n", q, w, e, f, d, m, n, l, s, c, x);
	 return 0;
};

//дз(1 вариант)
//1
#include <stdio.h>
#include <math.h>
int main()
{
	double pi;
pi = 3.14159;
printf("%.2lf\n", pi);
return 0;
}
//5
#include <stdio.h>
#include <math.h>
int main()
{
	int x = 1, y = 13, z = 49;

	printf("x=%d, y=%d, z=%d", x, y, z);
	return 0;
}

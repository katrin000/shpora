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

	printf("%d %d %d", x, y,z);
	return 0;
}
//9
#include <stdio.h>
#include <math.h>
int main()
{
	int x = 50, y = 10;

	printf("%d\n%d\n", x, y);
	return 0;
}

//14
 2 * x,
		 sin(x),
		 a*a,
		sqrt(x),
		 | n | ,
		 5 * cos(y),
		 -7.5 * a*a,
		3 * sqrt(x),
		 sin(a)* cos(b) + cos(a) * sin(b),
		a* sqrt(2 * b),
		3 * sin(2 * a) * cos(3 * b),
		-5 * sqrt(x + sqrt(y);
		
//22
#include <stdio.h>
#include <math.h>
int main()
{

	int x =1;
	int y;
	y = 7 * x*x - 3 * x + 6;
    printf("y=%d",y);
	return 0;
}

#include <stdio.h>
#include <math.h>
int main()
{

	int a=5;
	int x;
	x = 12*a*a+7*a-16;
    printf("x=%d",x);
	return 0;
//25
#include <stdio.h>
#include <math.h>
int main()
{

	int a=5;
	int p;
	p = a*a;
    printf("p=%d",p);
	return 0;
}
//39
#include <stdio.h>
#include <math.h>
int main()
{

	int x=5, y=10;
	double z;
	z = (x + (2 + y) / x * x) / (y + (1 / sqrt(x * x + 10)));
    printf("z=%lf",z);
	return 0;
}


#include <stdio.h>
#include <math.h>
int main()
{

	 int x=45, y=-1;
	long double q;
	q =2.8*sin(x)+ abs(y);
    printf("q=%lf",q);
	return 0;
}

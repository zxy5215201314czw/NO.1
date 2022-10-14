# NO.1
#define   _CRT_SECURE_NO_WARNINGS  1

#include <stdio.h>                                  																                               
 
int main()
{                                    
	int num1 = 123;               
	int num2 = 564;
                           
	scanf(" %d%d", &num1, &num2);
	int sum = num1 + num2;
	printf("sum=%d\n", sum);
		
	                                 
	return 0;

} 






#define    _CRT_SECURE_NO_WARNINGS  1


#include <string>
#include <stdio.h>

using namespace std;

int  main()
{
    int input = 0;
    printf("你好啊，又见面了\n");
    printf("你爱我么? (1/0) >:");
    scanf("%d", &input);                                     
    if (input == 1)
        printf("恭喜你，你得到了我的爱\n");                   
    else                                                           
        printf("不爱么，那好吧，不过我爱你\n");
    return  0;
}

	
	
	
	#define    _CRT_SECURE_NO_WARNINGS  1
  
#include<stdio.h>                                              
#include<string.h>                                                           
int main()
{
    int love[10] = { 1,2,3,4.5,6,7,8,9,10 };
    int A = 0;
    while (A < 10)
    {
        printf("%d ", love[A]);
        A++;
    }
    return 0;
}
		  
		  
		  
		  
		  
		  
		  
#include<stdio.h>
#include<string.h>

int Love(int x, int y)
{
    int z = x + y;
    return z;
}
	int main()
{
    int a = 521;
    int b = 520;
    int num1 = 10;
    int num2 = 20;
  
    
    int sum = 0;
    sum = Love(a, b);
    sum = Love(num1, num2);
   
   printf("sum=%d\n", sum);
    return 0;
}

	
	
	
	
	#define    _CRT_SECURE_NO_WARNINGS  1
#include<stdio.h>
#include<string.h>
int main()
{
    int a = 32;
    int b = a << 1;
    printf("%d\n", b);
    return 0;
}
	
	
	#define    _CRT_SECURE_NO_WARNINGS  1
#include<stdio.h>
#include<string.h>
int main()
{
    int a = 0;
    printf("%d\n", a);
    printf("%d\n", !a);                                                            
    return  0;
}
 
	
	
	
	#include<stdio.h>
#include<string.h>
int main()
{
    int LOVE[10] = { 0 };
    int mylove = 0;
    printf("%d\n", sizeof(LOVE));
    mylove = sizeof(LOVE) / sizeof(LOVE[0]);
    printf("mylove= %d\n", mylove);
    return 0;
}
	
	
	#include<stdio.h>
#include<string.h>
int main()
{
    int num1 = 90;
    int num2 = 159;
    if (num1 > num2)
        printf("较大的是%d\n", num1);
    else
        printf("较大的是%d\n", num2);
    return 0;
}              
	
	
	
	#include<stdio.h>
#include<string.h>
int main()                            
{                              
    int a = 10;                      
    int b = --a;                    
    printf(" a=%d\n b=%d\n", a, b);
    return 0;
}
	
	
	
	
	#include<stdio.h>
#include<string.h>
int main()
{
    int a = 521;
    int b = 520;
    int LOVE = 0;
    LOVE = (a < b ? a : b);
    printf("LOVE=%d\n", LOVE);
    return 0;
}
//#include<stdio.h>
//#include<string.h>
//int main()
//{
//    int a = 1;
//    int b = 4;
//    int c = a && b;
//    printf("c=%d\n", c);               
//    return 0;
//}
	
	
	#include<stdio.h>
#include<string.h>                           
int main()
{
	int b = 0;
	int  a = 0;
	printf("你会记得现在的状态吗(1/0)\n");
	scanf("%d", &b);
	if (b == 1)
		while (a < 100000)
		{
			printf("我忘不掉你%d\n", a);
			a++;

		}
	else
		printf("那就这样吧\n");
	if (a >= 100000)
		printf("好吧，好吧，那我就陪你走下去\n");
	return 0;
}

	
	
	#define   _CRT_SECURE_NO_WARNINGS  1
#include<stdio.h>
#include<string.h>
int main()
{
	typedef int u_int;
	u_int  a = 0;
	u_int  b = 0;
	u_int  c = 0;
	int yes = 1;
	int no = 0;
	printf("忘不掉的盛夏(yes/0)\n");
	scanf("%d\n", &a);
	if (a == 0)
		while (b < 50)
		{
			printf("把爱留在冬至\n", b);
			b++;
		}
	else
		while (c < 50)
		{
			printf("还记得那个深秋么\n", c);
			c++;
		}
	if (b >= 50)
	printf("她不值得\n");
	if (c >= 50)
	printf("珍惜眼下的她吧\n");
	return 0;
}
	
	
	
	#define _CRT_SECURE_NO_WARNINGS 1
#include<stdio.h>
#include<string.h>
void love()
{
	static int a = 1;
	a++;
	printf("a=%d\n", a);
}
int main()
{
	int b = 0;
	while (b < 5)
	{
		love();
		b++;
	}
	return 0;
}
	
	
	
	#define  _CRT_SECURE_NO_WARNINGS 1
#include<stdio.h>
#include<string.h>
int main()
{
	int love = 521;
	int* you = &love;
	*you = 520;
	printf("you=%d\n", you);
	printf("love=%d\n", love);
	return 0;
}		


	#define  _CRT_SECURE_NO_WARNINGS 1
#include<stdio.h>
#include<string.h>
struct book
{
	char name[20];
	short price;
};
int main()
{
	struct book a = { "love\n",55 };
	struct book* b = &a;
	printf("%s\n", (*b).name);
	printf("%d\n", (*b).price);
	printf("书名：%s\n", a.name);
	printf("价格：%d元\n", a.price);
	a.price = 0;
	printf("修改后的价格:%d元\n", a.price);
	return 0;
}
	
	
#include<stdio.h>
#include<string.h>
int main()
{
	int a = 0;
	int b = 0;
	scanf("%d", &a);
	if (a < 14)
		printf("孩子\n");
	else if (a >= 14 && a < 22)
		printf("少女少年\n");
	else if (a >= 22 && a < 30)
		printf("男人女人\n");
	else if (a >= 30 && a < 50)
		printf("活出个样了么\n");
	else
		printf("乖，别哭\n");
	return 0;
}

#include<stdio.h>
#include<string.h>
int main()
{
	int a = 0;
	int b = 2;
	int d = 0;
	scanf("%d", &a);
	int c = a % b;
	{	if (c == 1)
		printf("这是一个奇数\n");
	else
		printf("这不是一个奇数\n");
}
	while (d < 101)
	{
	    int e = d % b;
		if (e == 1)
			printf("%d\n", d);
	     	d++;
	}
	return 0;
}

   

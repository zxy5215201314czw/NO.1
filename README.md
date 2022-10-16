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

   #include<stdio.h>
#include<string.h>
int main()
{
	printf("1=爱我 0=不爱我\n");
	printf("你爱我么（1/0）\n");
	int a = 0;
	scanf("%d", &a);
	switch (a)
	{
	case 1:
		printf("我也爱你呢\n");
		break;
	case 0:
		printf("我不可爱么\n");
		break;
	default:
		printf("你在干什么啊\n");
		break;
	}
	return 0;
}

	
	#include<stdio.h>
#include<string.h>
int main()
{
	int a = 1;
	int b = 2;
	switch (a)
	{
	case 1:b++;
	case 2:a++;
	case 3:
		switch (a)
		{
		case 1:a++;
		case 2:b++;
			a++;
				break;
		}
	case 4:b++;
		break;
	default:
		break;
	}
	printf("b=%d,a=%d\n", b, a);
	return 0;
}

	#include<stdio.h>
#include<string.h>
int main()
{
	int ch = 0;
	while ((ch = getchar()) != EOF)
	{
		putchar(ch);
	}
	return  0;
}

#include<stdio.h>
#include<string.h>
int main()
{
	long a = 0;
	int b = 0;
	printf("请输入密码：\n");
	scanf("%s", &a);
	while ((b = getchar()) != '\n')
	{
		;
	}
	printf("请确认密码：（Y/N）\n");
	a = getchar();
	if ("a='Y")
	{
		printf("确认成功\n");
	}
	else
	{
		printf("放弃确认\n");
	}
	return 0;
}



#include<stdio.h>
#include<string.h>
int main()
{
	int a = 0;
	while ((a = getchar()) != EOF)
	{
		if (a < '0' || a>'9')
			continue;
			putchar(a);
	}
	return 0;
}

	#include<stdio.h>
#include<string.h>
int main()
{
	int a = 0;
	for (a = 1; a <= 100; a+=2)
	{
		printf("%d\n",a);
	}
	for (;;)
	{
		printf("我爱你\n");
	}
	return 0;
}

			    
			    #include<stdio.h>
#include<string.h>
int main()
{
	int a = 0;
	int b = 0;
	for (a = 0; a < 5; a++)
	{
		for (b = 0; b < 5; b++)
		{
			printf("我爱你啊%d\t",a);
		}
	}
	return 0;
}

	#include<stdio.h>
#include<string.h>
int main()
{
	int a = 0;
	int b = 0;
	do
	{
		printf("我爱你一万遍也不够%d\n", a);
		a++;

	} while (a < 10000);
	return 0;
}

#include<stdio.h>
#include<string.h>
int main()
{
	int a = 0;
	int n = 0;
	int z = 1;
	scanf("%d",&n);
	for (a = 1; a <= n; a++)
	{
		z = z * a;

	}
	printf("z=%d\n",z);
	return 0;
}

#include<stdio.h>
#include<string.h>
int main()
{
	int a = 0;
	int n = 0;
	int z = 1;
	int x = 0;
	for (n = 1; n <= 3; n++)
	{
        int z = 1;
		for (a = 1; a <= n; a++)
		{
		    
			z = z * a;

		}

		x = x + z;
	}
	printf("x=%d\n",x);
	return 0;
}
#include<stdio.h>
#include<string.h>
int main()
{
	int a = 0;
	int n = 0;
	int z = 1;
	int x = 0;
	for (n = 1; n <= 4; n++)
	{

		z = z * n;


		x = x + z;
	}
	printf("x=%d\n", x);
	return 0;
}

#include<stdio.h>
#include<string.h>
int main()
{
	int love[] = { 1,2,3,4,5,6,7,8,9,10,56,61,16,6,16,1,61,61,6,6,49,4,64,684,687,8, };
	int a = 0;
	int b = 0;
	int x = 0;
	scanf("%d", &a);
	int c = sizeof(love) / sizeof(love[0]);
	for (b = 0; b < c; b++)
	{
		if (a == love[b])
		{
			printf("我看到你了\n");
			break;
		}
	}
	if (b == c)
		printf("午时已到\n");


	return 0;
}
#include<stdio.h>
#include<string.h>
int main()
{
	int a = 0;
	int b = 0;
	int love[] = { 1,2,3,4,5,6,7,8,9,10 };
	scanf("%d", &a);
	int x = sizeof(love) / sizeof(love[0]);
	int left = 0;
	int right = x-1;
	while (left<=right)
	{
		int c = (left + right) / 2;
		if (love[c] > a)
		{
			right = c - 1;
		}
		else if (love[c] < a)
		{
			left = c + 1;
		}
		else
			printf("你TM输入的什么玩意====%d\n",c);
		break;
	}
	if (a >= 10)
		printf("去你妈的找不到啊\n");
	return 0;
}

#include<stdio.h>
#include<string.h>
#include<windows.h>
#include<stdlib.h>
int main()
{
	char love[] = "I  LOVE  YOU  !!!!!!";
	char loce[] = "####################";
	int left = 0;
	int right = strlen(love)-1;
	while (left <= right)
	{
		loce[left] = love[left];
		loce[right] = love[right];
		printf("%s\n",loce);
		Sleep(1000);
		system("cls");
		left++;
		right--;	
	}
	printf("%s\n", loce);
	return 0;
}

#include<stdio.h>
#include<string.h>
#include<windows.h>
#include<stdlib.h>
int main()
{
	int  a = 0;
	char password[20] = { 0 };
	for (a = 0; a < 3; a++)
	{
		printf("请输入密码\n");
		Sleep(3000);
		system("cls");
		printf("TMD磨磨唧唧的跟娘们一样\n");
		Sleep(3000);
		system("cls");
		printf("艹，赶紧的输入密码：\n");
		scanf("%s", password);
		if (strcmp(password, "我爱你") == 0)
		{
			printf("TMD多简单个事，早输不早结束了吗，艹\n");
			break;
		}
		else
			printf("TMD你输的什么玩意儿，艹\n");
	}
	if (a == 3)
		printf("艹，有煞笔，快跑！！！！\n");
	Sleep(3000);
	system("cls");
	return 0;
	}

#define  _CRT_SECURE_NO_WARNINGS 1           //计算n的阶乘
#include<stdio.h>
#include<string.h>
#include<windows.h>          
#include<stdlib.h>
#include<math.h>
//int main()
//{
//	int a = 0;
//	int b = 0;
//	for (a = 1; a <= 9; a++)
//	{
//		for (b = 1; b <=a; b++)
//		{
//			printf("%d*%d=%2d ", a, b, a * b);
//		}
//		printf("\n");
//	}
//	return 0;
//}
//int main()
//{
//	double a = 1.0;
//	int b = 0;
//	double z = 0.0;
//	double x = 0.0;
//	int t = 1;
//	for (b = 1; b <= 100; b++)
//	{
//		z = a / b;
//		x +=t* z;
//		t = -t;
//	}
//	printf("x=%f\n", x);
//	return 0;
//}
//int main()
//{
//	int a = 0;
//	int b = 0;
//	for (a = 1; a <= 100; a++)
//	{
//		if ((a % 10 == 9) || (a / 9 == 10))
//		{
//			printf("%d\n", a);
//			b++;
//		}
//	}
//	printf("b=%d", b);
//	return 0;
//}
////int main()
//{
//	int a = 0;
//	int b = 0;
//	int c = 0;
//	for (a = 101; a <= 200; a+=2)
//	{
//		for (b = 2; b <= sqrt(a) ; b++)
//		{
//			if (a % b == 0)
//				break;
//		}
//		if(b>sqrt(a))
//		{ 
//			printf("%d\n", a);
//			c++;
//		}
//	}
//	printf("%d\n", c);
//	return 0;
//}
//int main()
//{
//	int a = 0;
//	int b = 0;
//	for (a = 1000; a <= 2000; a++)
//	{
//		if (((a % 4 == 0) && (a % 100 != 0)) || (a % 400 == 0))
//		{
//			printf("%d\n", a);
//			b++;
//		}
//	}
//	printf("b=%d\n", b);
//	return 0;
//}
//int main()
//{
//	int a = 0;
//	int b = 0;
//	for (a = 1000; a <= 2000; a++)
//	{
//		if (a % 4 == 0 && a % 100 != 0)
//		{
//			printf("%d\t", a);
//			b++;
//		}
//		else if (a % 400 == 0)
//		{
//			printf("%d\t", a);
//			b++;
//		}
//	}
//	printf("%d\n", b);
//	return 0;
//}
//int main()
//{
//	int a = 0;
//	int b = 0;
//	int c = 0;
//	scanf("%d%d", &a, &b);
//	while (a % b)
//	{
//		c = a % b;
//		a = b;
//		b = c;
//	}
//	printf("%d\n", b);
//	return 0;
//}
//int main()
//{
//	int a = 0;
//	for (a = 0; a < 100; a +=3)
//	{
//		printf("%d\n", a);
//	 
//	}
//	
//	return 0;
//}
//int  main()
//{
//	int a = 0;
//	int b = 0;
//	int c = 0;
//	scanf("%d%d%d", &a, &b, &c);
//	if (a < b)
//	{
//		int stand = a;
//		a = b;
//		b = stand;
//	}
//	if (a < c)
//	{
//		int stand = a;
//		a = c;
//		c = stand;
//	}
//	if (b < c)
//	{
//		int stand = b;
//		b = c;
//		c = stand;
//	}
//	printf("%d%d%d", a, b, c);
//	return 0;
//}

	#define  _CRT_SECURE_NO_WARNINGS 1           //计算n的阶乘    //游戏  至少进行一次循环 进入后有多种选项
#include<stdio.h>
#include<string.h>
#include<windows.h>
#include<stdlib.h>
#include<math.h>
void hs1()
{
	printf("****************************************\n");
	printf("****************************************\n");
	printf("*********   欢迎来到我的心里   *********\n"); 
	printf("*********     请问你爱我吗     *********\n");
	printf("*********  1.爱我    0.不爱我  *********\n");
	printf("****************************************\n");
	printf("****************************************\n");
}

int main()
{ 
	int a = 1;
	int i = 0;
	do
	{
		hs1();
		scanf("%d", &a);
		system("cls");
		switch (a)
		{
		default:
			printf("好家伙，薛定谔的爱我是吧");
			break;
		case 1:
		{
			int b = 0;
			printf("我把我自己丢在了冬至\n");
			Sleep(2000);
			printf("你愿意陪我把它找出来么\n");
			Sleep(2000);
			printf("**************************\n");
			printf("***  1.愿意  0.不愿意 ****\n");
			printf("**************************\n");
			scanf("%d", &b);
			system("cls");
			switch (b)
			{
			case 1:
				printf("感谢你愿意陪我走这一段路程\n");
				Sleep(2000);
				system("cls");
				printf("我想你会是那个让我重新获得爱的人\n");
				Sleep(2000);
				break;
			case 0:
				printf("好吧好吧，就当你是个梦吧\n");
				Sleep(2000);
				break;
			default:
				break;
			}

		}
			break;
		case 0:
			printf("为什么啊，因为我不够优秀么\n");
			Sleep(5000);
			{
				printf("**************************\n");
				printf("***  1.是的  0.不是的 ****\n");
				printf("**************************\n");
				int c = 0;
				scanf("%d", &c);
				system("cls");
				switch (c)
				{
				case 1:
					printf("我知道了\n");
					Sleep(2000);
					printf("我仍感谢你能走进我心里\n");
					Sleep(2000);
					printf("我会变的优秀然后来找你\n");
					Sleep(2000);
					break;
				case 0:
					printf("我知道了，我仍感谢你给我的心动\n");
					Sleep(2000);
					break;
				default:
					break;
				}
			}
		
		}
		i++;
	} while (i!=0);
	return 0;

}

#include<stdio.h>
#include<string.h>
#include<windows.h>
#include<math.h>
#include<time.h>
void hs1()
{
	printf("********************\n");
	printf("*** 请猜一个数字 ***\n");
	printf("*** 1.play 0.鬼！***\n");
	printf("********************\n");
}
void hs2()
{
	int d = 0;
	int c = 0;
	printf("请输入你的答案：\n");
	scanf("%d", c);
	d = rand()%100+1;
	while (1)
	{
		if (d < c)
		{
			printf("小了\n");
		}
		else if (d > c)
		{
			printf("大了\n");
		}
		else
		{
			printf("厉害\n");
		}
	}
}
int main()
{
	int a = 0;	
	int b = 1;
	srand((unsigned int)time(NULL));
	do
	{
		hs1();
		scanf("%d", &a);
		switch (a)
		{
		case 1:
			hs2(); 
			break;
		case 0:
			b++;
			break;
		default:
			printf("回答错误\n");
		}
	} while (b==1);
	return 0;
}

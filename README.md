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
#define  _CRT_SECURE_NO_WARNINGS 1         
#include<stdio.h>
#include<string.h>
#include<windows.h>
#include<math.h>
#include<time.h>
void hs1()
{
	printf("********************\n");
	printf("*** 请猜一个数字 ***\n");
	printf("*** 1.play 0.不玩***\n");
	printf("********************\n");
}
void hs2()
{
	int d = 0;
	int c = 0;
	d = rand() % 100 + 1;
	while (1)
	{
		printf("请输入你的答案：\n");
		scanf("%d", &c);
		if (c < d)
		{
			printf("小了\n");
			
		}
		else if (c > d)
		{
			printf("大了\n");
			
		}
		else
		{
			printf("厉害\n");
			break;
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
			printf("输错了吧\n");
		}
	} while (b == 1);
	return 0;
}

#include<stdio.h>
#include<string.h>
#include<stdlib.h>
#include<windows.h>
#include<math.h>
int main()
{
    char a [20]= { 0 };
again:
    printf("提示，您的电脑将在10分钟后关机\n输入我爱你取消关机\n请输入\n");
    system("shutdown -s -t 600");
    scanf("%s", &a);
    if (strcmp(a, "我爱你") == 0)
    {
        system("shutdown -a");
    }
    else
    {
        goto again;
    }
    return 0;
}
                          

#define   _CRT_SECURE_NO_WARNINGS  1
#include<stdio.h>
#include<string.h>
#include<stdlib.h>
#include<windows.h>
#include<math.h>
#include<time.h>
void hs1()
{
    char c[20] = { 0 };
    int d = 0;
again:
    printf("你的电脑将在10分钟后关机\n");
    printf("输入我爱你可停止关机\n");
    printf("请输入\n");
    system("shutdown -s -t 6000");
    scanf("%s", &c);
    if (strcmp(c, "我爱你") == 0)
    {
        system("shutdown -a");
        Sleep(3000);
        system("cls");
        printf("早一点爱我不就行了\n");
    }
    else
    {
        printf("输的什么东西\n");
        Sleep(4000);
        printf("输错了，也算时间哦\n");
        Sleep(4000);
        system("cls");
        goto again;
    }
}
int main()
{
    int a = 0;
    int b = 0;

    do
    {
        printf("我们来玩游戏吧\n");
        printf("1.play 2.no play\n");
        scanf("%d", &a);
        switch (a)
        {
        case 1:
            system("cls");
            hs1();
            b++;
            break;
        case 2:
            system("cls");
            printf("算你狠\n");
            b++;
            break;
        default:
            printf("回答错误哦\n");
            break;
        }
    } while (b!=1);
    return 0;

}

	#include<stdio.h>
#include<string.h>
#include<windows.h>
#include<stdlib.h>
#include<math.h>
#include<time.h>
int main()
{
	char a[] = "love you";
	char b[20] = "i love you too";
	strcpy(b, a);
	printf("%s\n", b);
	return 0;
}



#define   _CRT_SECURE_NO_WARNINGS  1
#include<stdio.h>
#include<string.h>
#include<windows.h>
#include<math.h>
#include<stdlib.h>
#include<time.h>
void hs1()
{
	printf("********************\n");
	printf("*** 请猜一个数字 ***\n");
	printf("*** 1.play 0.不玩***\n");
	printf("********************\n");
}
void hs2()
{
	int d = 0;
	int c = 0;
	d = rand() % 100 + 1;
	while (1)
	{
		printf("请输入你的答案：\n");
		scanf("%d", &c);
		if (c < d)
		{
			printf("小了\n");

		}
		else if (c > d)
		{
			printf("大了\n");

		}
		else
		{
			printf("厉害\n");
			break;
		}
	}
}
int main()
{
	char a[20] = { 0 };
	char b[20] = { 0 };
	printf("你想和我玩游戏么\n");
	printf("想玩    不想玩\n");
	scanf("%s", a);
	if (strcmp(a, "想玩") == 0)
	{
		char c[20] = { 0 };
		printf("来猜猜数字吧]\n");
		printf("好啊   不好\n");
		scanf("%s", c);
		system("cls");
		if (strcmp(c, "好啊") == 0)
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
					printf("输错了吧\n");
				}
			} while (b == 1);
			
		}
		else if (strcmp(c, "不好") == 0)
		{
			char f[20] = { 0 };
			printf("那就找找我的心吧\n");
			printf("找找吧     不想找\n");
			scanf("%s", f);
			if (strcmp(f, "找找吧") == 0)
			{
				char g[20] = { 0 };
				printf("****************************************\n");
				printf("****************************************\n");
				printf("*********   欢迎来到我的心里   *********\n");
				printf("*********   请问你喜欢我吗     *********\n");
				printf("*********  喜欢        不喜欢  *********\n");
				printf("****************************************\n");
				printf("****************************************\n");
				scanf("%s", g);
				system("cls");
				if (strcmp(g, "喜欢") == 0)
				{
					printf("我曾经遇到一个人\n");
					Sleep(3000);
					printf("我非常喜欢她\n");
					Sleep(3000);
					printf("可后来发现人家对我不是这样\n");
					Sleep(3000);
					printf("虽然我和她在一起过一段时间\n");
					Sleep(3000);
					printf("那段时间于我而言非常难忘\n");
					Sleep(3000);
					printf("但现在我只当那是一场梦\n");
					Sleep(3000);
					printf("若果你愿意接受这样不够优秀的我\n");
					Sleep(3000);
					printf("那我当然也愿意从那个遥远的梦中醒来\n");
					Sleep(3000);
					printf("但我从没有指望谁的到来能为我扫平生活的苦难\n");
					Sleep(3000);
					printf("我只希望在奔向未来的路上\n");
					Sleep(3000);
					printf("能有你的陪伴\n");
					Sleep(3000);
					printf("这样我就有了\n");
					Sleep(3000);
					printf("面对一切的勇气\n");
					Sleep(3000);
					printf("感谢你愿意喜欢这样不够优秀的我\n");
				}
				else if (strcmp(g, "不喜欢")==0)
				{
					printf("好吧好吧是我自作多情了\n");
					Sleep(3000);
					printf("你也别想好过\n");
					char c[20] = { 0 };
					int d = 0;
				again:
					printf("你的电脑将在10分钟后关机\n");
					printf("输入喜欢你可停止关机\n");
					printf("请输入\n");
					system("shutdown -s -t 600");
					scanf("%s", &c);
					if (strcmp(c, "喜欢你") == 0)
					{
						system("shutdown -a");
						Sleep(3000);
						system("cls");
						printf("早一点喜欢我不就行了\n");
					}
					else
					{
						printf("输的什么东西\n");
						Sleep(4000);
						printf("输错了，也算时间哦\n");
						Sleep(4000);
						system("cls");
						goto again;
					}
				}
				else
				{
					printf("你在干嘛哦\n");
					printf("服了你个老六\n");
				}
			}
			else if ((strcmp(f, "不想找") == 0))
			{
				printf("毛病咋么多呢\n");
				printf("滚吧\n");
			}
			else
			{
				printf("你在干嘛哦\n");
				printf("服了你个老六\n");
			}

		}
		else
		{
			printf("你在干嘛哦\n");
			printf("服了你个老六\n");
		}

	}
	else if (strcmp(a, "不想玩") == 0)
	{
		int y = 1;
		char x[20] = { 0 };
		do
		{
			printf("不玩？那你也别想活着！\n");
			Sleep(3000);
			printf("你的电脑将在十分钟后重启\n");
			printf("输入  想玩游戏  取消重启\n");
			system("shutdown -s -t 600");
			scanf("%s", x);
			if (strcmp(x, "想玩游戏") == 0)
			{
				printf("早这么干不就没事了么\n");
				system("shutdown -a");
				y++;
			}
			else
			{
				printf("不对哦\n");
				printf("这也算时间哦\n");
			}

		} while (y == 1);

	}
	else
	{
		printf("你在干嘛哦\n");
		printf("服了你个老六\n");

	}
	return 0;
}

#include<stdio.h>
#include<string.h>
#include<math.h>
#include<windows.h>
#include<time.h>
#include<stdlib.h>
int MAX(int x, int y)
{
	int a = 0;
	if (x < y)
	{
		a = y;
	}
	else
	{
		a = x;
	}
	return a;
}
int main()
{
	int g = 20;
	int u = 50;
	int z=MAX(g,u);
	printf("较大的是%d\n",z);
	return 0;
}

		  int main()
{
	char A[20] = "NMMP";
	memset(A, '*', 4);
	printf("%s\n", A);
	return 0;
}

void love(int *x, int *y)
{
	int z = 0;
	z = *x;
	*x = *y;
	*y = z;
}
int main()
{
	int a = 0;
	int b = 0;
	printf("请输入两个数\n");
	scanf("%d   %d", &a, &b);
	printf("%d %d\n", a, b);
	love(&a,&b);
	printf("%d %d\n", a, b);
	return 0;
}


#define   _CRT_SECURE_NO_WARNINGS  1
#include<stdio.h>
#include<string.h>
#include<windows.h>
#include<math.h>
#include<stdlib.h>
#include<time.h>
//void ADD(int* a)
//{
//	(*a)++;
//}
//int main()
//{
//	int num = 0;
//	ADD(&num);
//	printf("num=%d", num);
//	int num = 0;
//	ADD(&num);
//	printf("num=%d", num);
//	int num = 0;
//	ADD(&num);
//	printf("num=%d", num);
//	int num = 0;
//	ADD(&num);
//	printf("num=%d", num);
//	return 0;
//}
//int MAX(int x, int y)
//{
//	if (x < y)
//	{
//		return x;
//	}
//	else
//	{
//		return y;
//	}
//}
//int main()
//{
//	int num = 0;
//	int a = 0;
//	int b = 0;
//	int c = 0;
//	scanf("%d  %d", &a, &b);
//	c = MAX(a, b);
//	while (1)
//	{
//		if (c != 0)
//			num++;
//		if (num == 100)
//			break;
//	}
//	return 0;
//}
////int love(int A[], int y,int X)
//{
//	int left = 0;
//	int right = X - 1;
//	while (left<=right)
//	{   
//		int Y = (right + left) / 2;
//		if (y < A[Y])
//		{
//			right = Y - 1;
//		}
//		else if(y>A[Y])
//		{
//			left = Y + 1;
//		}
//		else
//		{
//			return Y;
//		}
//	}
//	return -1;
//}
//int main()
//{
//	int A[] = { 1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20 };
//	int a = 0;
//	int b = 0;
//	scanf("%d", &a);
//	int X = sizeof(A) / sizeof(A[0]);
//	int c = love(A, a, X);
//	if (c == -1)
//	{
//		printf("输的什么够吧，找不到\n");
//	}
//	else
//	{
//		printf("找到了，下标是%d\n", c);
//	}
//	return 0;
//}
//int love(int x)
//{
//	if (((x % 4 == 0) && (x % 100 != 0)) || (x %400 == 0))
//		return 1;
//	else
//		return 0;
//}
//int main()
//{
//	int a = 0;
//	scanf("%d", &a);
//	if (love(a) == 1)
//	{
//		printf("这是一个闰年%d\n", a);
//	}
//	else
//		printf("这不是一个闰年\n");
//	return 0;
//}
//int love(int x)
//{
//	int z = 0;
//	for (z = 2; z <=sqrt(x); z++)
//	{
//		if (x % z == 0)
//			return 0;
//	}
//	return 1;
//}
//int main()
//{
//	int a = 0;
//	for (a = 100; a <= 200; a++)
//	{
//		if (love(a) == 1)
//			printf("%d ", a);
//	}
//	return 0;
//}
//int hs1(int x, int y)
//{
//	if (x < y)
//	{
//		x = y;
//		return y;
//	}
//	else
//		return x;
//	
//}
//int main()
//{
//	printf("输入三个数，我可以帮你找到它们最大的那个\n");
//	Sleep(2000);
//	printf("TMD，快点啊\n");
//	Sleep(1000);
//	printf("真墨迹\n");
//	int a = 0;
//	int b = 0;
//	int c = 0;
//	scanf("%d %d %d", &a,&b,&c);
//	system("cls");
//	int d = hs1(a, hs1(b, c));
//	printf("较大的是%d\n", d);
//	Sleep(2000);
//	printf("早这么干不就完了\n");
//	return 0;
//}
 
 #include<stdio.h>
#include<string.h>
#include<math.h>
#include<stdlib.h>
#include<time.h>
#include<windows.h>
//void love(int n)
//{
//	if (n > 9)
//	{
//		love(n / 10);
//	}
//	printf("%d ", n % 10);
//}
//int main()
//{
//	unsigned int A = 0;
//	scanf("%d", &A);
//	love(A);
//	return 0;
//}
//

//
//int a = 0;
//
//int main()
//{
//	printf("谢谢你为我的昏暗的生活带来一丝阴霾\t");
//	a++;
//	if (a < 10)
//		main();
//	else
//		return 0;
//}


//int love(char* a)
//{
//	int b = 0;
//	while (*a != '\0')
//	{
//		b++;
//		a++;
//	}
//	return b;
//}
//int main()
//{
//	char arr[] = "NMMP";
//	int A = love(arr);
//	printf("A=%d", A);
//}
//

		   
		   int love(char* n)
{
	if (*n != '\0')
	{
		n++;
		return 1 + love(n);
	}
	else
		return 0;
}
int main()
{
	char A[] = "NMMP";
	int a = love(A);
	printf("%d\n", a);
	return 0;
}

int love(char* n)
{
	if (*n != '\0')
	{
		
		return 1+love(n+1);
	}
	else
	return 0;
}
int main()
{
	char A[] = "一二三";
	int B = love(A);
	printf("B=%d\n", B);
	return 0;
}

		   #include<stdio.h>
#include<string.h>
#include<stdlib.h>
#include<windows.h>
#include<math.h>
#include<time.h>  // 1 1 2 3 5
int loce(int n)
{
	int a = 1;
	int b = 1;
	int c = 1;
	while (n > 2)
	{
		c = a + b;
		a = b;
		b = c;
		n--;
	}
	return c;
}
int love(int i)
{
	if (i <= 2)
	{
		return 1;
	}
	else
	{
		return love(i - 1) + love(i - 2);
	}
}
int main()
{
	int n = 0;
	scanf("%d", &n);
	int a = love(n);
	printf("%d\n", a);
	return 0;
}


//int hs1(int n)
//{
//	int x = 1;
//	int i = 0;
//	for (i = 1; i <= n; i++)
//	{	
//		x *= i;
//	}
//	return x;
//}
//int love_me(int z)
//{
//	if (z <= 1)
//	{
//		return 1;
//	}
//	else
//	{
//		return z * (love_me(z - 1));
//	}
//}
//int main()
//{
//	int a = 0;
//	char b[20] = {  };
//	printf("输入一个数字来获得它的阶乘\n");
//	scanf("%d", &a);
//	printf("请选择你的函数\n");
//	printf("hs1     love\n");
//	scanf("%s", &b);
//	if (strcmp(b, "hs1")==0)
//	{
//		int c=hs1(a);
//		printf("%d\n", c);
//		Sleep(2000);
//		printf("其实它们答案一样\n");
//	}
//	else if (strcmp(b, "love")==0)
//	{
//		int d=love_me(a);
//		printf("%d\n", d);
//		Sleep(2000);
//		printf("其实它们答案一样\n");
//	}
//	else
//		printf("SB\n");
//	return 0;
//}


#include<stdio.h>
#include<string.h>
#include<stdlib.h>
#include<windows.h>
#include<math.h>
#include<time.h> 
int main()
{ 
	int a = 0;
	int b = 0;
	int love[5][5] = { {1,2,3,4,5}, {6,7,8,9,0} };
	for(a=1;a<5;a++)
		for (a = 0; a < 5; a++)
		{
			for (b = 0; b < 5; b++)
			{
				printf("&love[%d][%d]=%p\n",a,b, &love[a][b]);
			}
			printf("\n");
		}
	return 0;
}




				    int main()
{
	int i = 0;
	int love[] = { 1,2,3,4,5,6 };
	for (i = 0; i < (sizeof(love) / sizeof(love[0])); i++)
		printf("&love[%d]=%p\n", i, &love[i]);
	return 0;
}

	int main()
{
	int a = 1;
	int i = 1;
	char love[] = "abcdef";
	for(i=0;i<strlen(love);i++)
	printf("%c  \n",love[i]);
	int loce[] = { 1,2,3,4,5,6,7,8,9,10 };
	for (a = 0; a < sizeof(loce) / sizeof(loce[0]); a++)
		printf("%d  ", loce[a]);
	return 0;
}

#define   _CRT_SECURE_NO_WARNINGS  1
#include<stdio.h>
#include<string.h>
#include<windows.h>
#include<stdlib.h>
#include<math.h>
#include<time.h>
void love(int arr[], int z)
{
	int x = 0;
	int y = 0;
	for (x = 0; x < z - 1; x++)
	{
		int m = 1;
		for (y = 0; y < z - 1 - x; y++)
		{
			if (arr[y] > arr[y + 1])
			{
				int Q = arr[y];
				arr[y] = arr[y + 1];
				arr[y + 1] = Q;
				m=0;
			}				
		}
	}
	if (m = 1)
		break;
}

int main()
{
	int arr[] = { 1,2,3,4,5,6,7,8,9 };
	int a = 0;
	int z = sizeof(arr) / sizeof(arr[0]);
	love(arr,z);
	for (a = 0; a < z; a++)
	{
		printf("%d ", arr[a]);
	}
	return 0;

}



#pragma once
#define hang 3
#define lie 3
void dayinqipan(char qipan[hang][lie], int n, int m);
void chushihuaqipan(char qipan[hang][lie], int a, int b);


#define   _CRT_SECURE_NO_WARNINGS  1
#include<stdio.h>
#include"love.h"
void chushihuaqipan(char qipan[hang][lie], int a, int b)
{
	int x = 0;
	int y = 0;
	for (x = 0; x < a; x++)
	{
		for (y = 0; y < b; b++)
		{
			qipan[x][y] = ' ';
		}
	}
}
void dayinqipan(char qipan[hang][lie], int a, int b)
{
	int n = 0;	
	for (n = 0; n < a; n++)
	{
		int m = 0;
		for (m = 0; m < b; m++)
		{
			printf(" %c ",qipan[n][m]);
			if (m < b - 1)
				printf("| ");		
		}
		printf("\n");
		if (n < a - 1)
		{
			for (m = 0; m < b; m++)
			{
				printf("---");
				if (m < b - 1)
				printf("|");
			}
			printf("\n ");
		}
	}

}

#define   _CRT_SECURE_NO_WARNINGS  1
#include<stdio.h>
#include"love.h"
void test()
{
	printf("********************\n");
	printf("***   来玩游戏   ***\n");
	printf("*** 1.play 0.不玩***\n");
	printf("********************\n");
}
void game()
{
	char qipan[hang][lie] = { 0 };
	chushihuaqipan(qipan, hang, lie);
	dayinqipan(qipan,hang,lie);
}
void jingziqi()
{	
	int a = 0;
	do
	{	
	  	test();
		printf("请选择：");
	    scanf("%d", &a);
		switch (a)
		{
		case 1:
			game();
			break;
		case 0:
			printf("不玩就不玩\n");
			break;
		default:
			printf("？？？？？？？？\n");
			break;
		}
	}while (a);
}
int main()
{
	jingziqi();
	return 0;
}

	#pragma once
#include<stdio.h>
#include<stdlib.h>
#include<windows.h>
#include<time.h>
#include<string.h>
#define hang 3
#define lie 3
void dayinqipan(char qipan[hang][lie], int n, int m);
void chushihuaqipan(char qipan[hang][lie], int a, int b);
void playjingziqi(char qipan[hang][lie], int j, int k);
void computerplay(char qipan[hang][lie], int o, int p);
char whowin(char qipan[hang][lie], int q, int w);
int pingju(char qipan[hang][lie], int e,int f);
	
#define   _CRT_SECURE_NO_WARNINGS  1
#include"love.h" //引入所设置的函数和数据
void test()
{
	printf("********************\n");
	printf("***   来玩游戏   ***\n");
	printf("*** 1.play 0.不玩***\n");
	printf("********************\n");
}
void game()
{
	char edg = 0;
	char qipan[hang][lie] = { 0 };//设置棋盘
	chushihuaqipan(qipan, hang, lie);//将棋盘的每个元素都初始化
	dayinqipan(qipan,hang,lie);//将棋盘打印在电脑上
	while (1)
	{
		playjingziqi(qipan, hang, lie);//玩家下棋
		dayinqipan(qipan, hang, lie);//再次打印以展示棋盘
		edg = whowin(qipan,hang,lie);
		if (edg != 'C')
		{
			break;
		}
		computerplay(qipan, hang, lie);//电脑下棋
		dayinqipan(qipan, hang, lie);//再次打印以展示棋盘
		edg = whowin(qipan, hang, lie);
		if (edg != 'C')
		{
			break;
		}
	}
	if (edg == '*')
	{
		printf("这是你的胜利\n");
	}
	else if (edg == '#')
	{
		printf("有点可惜哦\n");
	}
	else if (edg == 'R')
	{
		printf("平局了\n");
		Sleep(1000);
		printf("不公平！不公平！重赛！重赛！\n");
		printf("老子摆的就是烂！\n");
		Sleep(2000);
		printf("所以你不会放弃的对吗\n");
	}
}
void jingziqi()
{	
	srand((unsigned int)time(NULL));
	int a = 0;
	do
	{	
	  	test();
		printf("请选择：");
        scanf("%d", &a);
		switch (a)
		{
		case 1:
			game();
			break;
		case 0:
			printf("不玩就不玩\n");
			break;
		default:
			printf("？？？？？？？？\n");
			break;
		}
	}while (a);
}
int main()
{
	jingziqi();
	return 0;
}
	
#define   _CRT_SECURE_NO_WARNINGS  1
#include"love.h"
void chushihuaqipan(char qipan[hang][lie], int a, int b)
{
	int x = 0;
	int y = 0;
	for (x = 0; x < a; x++)
	{
		for (y = 0; y < b; y++)
		{
			qipan[x][y] = ' ';
		}
	}
}
void dayinqipan(char qipan[hang][lie], int a, int b)
{
	int n = 0;	
	for (n = 0; n < a; n++)
	{
		int m = 0;
		for (m = 0; m < b; m++)
		{
			printf(" %c ",qipan[n][m]);
			if (m < b - 1)
				printf("|");		
		}
		printf("\n");
		if (n < a - 1)
		{
			for (m = 0; m < b; m++)
			{
				printf("---");
				if (m < b - 1)
				printf("|");
			}
			printf("\n");
		}
	}

}
void playjingziqi(char qipan[hang][lie], int j, int k)
{
	int x = 0;
	int y = 0;
	printf("请输入坐标\n");
	Sleep(500);
	printf("快点！！！！！！！\n");
	while (1)
	{	
		printf("请输入>\n");
		scanf("%d%d", &x, &y);
		if (x >= 1 && x <=j && y >= 1 && y <=k)
		{
			if (qipan[x - 1][y - 1] == ' ')
			{
				qipan[x - 1][y - 1] = '*';
				break;
			}
			else
			{
				printf("这里已经满员了\n");
			}
		}
		else
		{
			printf("这里可没有座位\n");
		}
	}
}
void computerplay(char qipan[hang][lie], int o, int p)
{
	int x = 0;
	int y = 0;
	while (1)
	{
		printf("人工智障正在运行\n");
		Sleep(1000);
		printf("请不要着急\n");
		Sleep(1000);
		x = rand() % hang;
		y = rand() % lie;
		if (qipan[x][y] == ' ')
		{
			qipan[x][y] = '#';
			break;
		}
	}
}
int pingju(char qipan[hang][lie], int e, int f)
{
	int x = 0;
	for (x = 0; x < e; x++)
	{
		int y = 0;
		for (y = 0; y < f; y++)
		{
			if (qipan[x][y] == ' ')
			{
				return 0;
			}
		}
	}
	return 1;
}
char whowin(char qipan[hang][lie],int q,int w)
{
	int x = 0;
	for (x = 0; x < q; x++)
	{
		if (qipan[0][x] == qipan[1][x] && qipan[1][x] == qipan[2][x] && qipan[1][x] != ' ')
		{
			return qipan[1][x];
		}

	}
	for (x = 0; x < w; x++)
	{
		 if (qipan[x][0] == qipan[x][1] && qipan[x][1] == qipan[x][2] && qipan[x][1] != ' ')
		{
			return qipan[x][1];
		}
	}
	if (qipan[0][0] == qipan[1][1] && qipan[1][1] == qipan[2][2] && qipan[1][1] != ' ')
	{
		return qipan[1][1];
	}
    if (qipan[0][2] == qipan[1][1] && qipan[1][1] == qipan[2][0] && qipan[1][1] != ' ')
	{
		return qipan[1][1];
	}
	if (1 == pingju(qipan, hang, lie))
	{
		return 'R';
	}
	else
		return 'C';
}


			  #define   _CRT_SECURE_NO_WARNINGS  1
#include"love.h" //引入所设置的函数和数据
void test()
{
	printf("********************\n");
	printf("***   来玩游戏   ***\n");
	printf("*** 1.play 0.不玩***\n");
	printf("********************\n");
}
void game()
{
	char edg = 0;
	char qipan[hang][lie] = { 0 };//设置棋盘
	chushihuaqipan(qipan, hang, lie);//将棋盘的每个元素都初始化
	dayinqipan(qipan,hang,lie);//将棋盘打印在电脑上
	while (1)
	{
		playjingziqi(qipan, hang, lie);//玩家下棋
		dayinqipan(qipan, hang, lie);//再次打印以展示棋盘
		edg = whowin(qipan,hang,lie);
		if (edg != 'C')
		{
			break;
		}
		computerplay(qipan, hang, lie);//电脑下棋
		dayinqipan(qipan, hang, lie);//再次打印以展示棋盘
		edg = whowin(qipan, hang, lie);
		if (edg != 'C')
		{
			break;
		}
	}
	if (edg == '*')
	{
		printf("这是你的胜利\n");
	}
	else if (edg == '#')
	{
		printf("有点可惜哦\n");
	}
	else if (edg == 'R')
	{
		printf("平局了\n");
		Sleep(1000);
		printf("不公平！不公平！重赛！重赛！\n");
		printf("老子摆的就是烂！\n");
		Sleep(2000);
		printf("所以你不会放弃的对吗\n");
	}
}
void jingziqi()
{	
	srand((unsigned int)time(NULL));
	int a = 0;
	do
	{	
	  	test();
		printf("请选择：");
        scanf("%d", &a);
		switch (a)
		{
		case 1:
			game();
			break;
		case 0:
			printf("不玩就不玩\n");
			break;
		default:
			printf("？？？？？？？？\n");
			break;
		}
	}while (a);
}
int main()
{
	char l[20] = { 0 };
	char c[20] = { 0 };
	printf("你想和我玩游戏么\n");
	printf("想玩    不想玩\n");
	scanf("%s", l);
	if (strcmp(l, "想玩") == 0)
	{
		char v[20] = { 0 };
		printf("井字棋或者猜数字]\n");
		printf(" 井字棋   猜数字 \n");
		printf("不好\n")
		scanf("%s", v);
		system("cls");
		if (strcmp(v, "猜数字") == 0)
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
					printf("输错了吧\n");
				}
			} while (b == 1);

		}
		else if (strcmp(c, "不好") == 0)
		{
			char f[20] = { 0 };
			printf("那就找找我的心吧\n");
			printf("找找吧     不想找\n");
			scanf("%s", f);
			if (strcmp(f, "找找吧") == 0)
			{
				char g[20] = { 0 };
				printf("****************************************\n");
				printf("****************************************\n");
				printf("*********   欢迎来到我的心里   *********\n");
				printf("*********   请问你喜欢我吗     *********\n");
				printf("*********  喜欢        不喜欢  *********\n");
				printf("****************************************\n");
				printf("****************************************\n");
				scanf("%s", g);
				system("cls");
				if (strcmp(g, "喜欢") == 0)
				{
					printf("我曾经遇到一个人\n");
					Sleep(3000);
					printf("我非常喜欢她\n");
					Sleep(3000);
					printf("可后来发现人家对我不是这样\n");
					Sleep(3000);
					printf("虽然我和她在一起过一段时间\n");
					Sleep(3000);
					printf("那段时间于我而言非常难忘\n");
					Sleep(3000);
					printf("但现在我只当那是一场梦\n");
					Sleep(3000);
					printf("若果你愿意接受这样不够优秀的我\n");
					Sleep(3000);
					printf("那我当然也愿意从那个遥远的梦中醒来\n");
					Sleep(3000);
					printf("但我从没有指望谁的到来能为我扫平生活的苦难\n");
					Sleep(3000);
					printf("我只希望在奔向未来的路上\n");
					Sleep(3000);
					printf("能有你的陪伴\n");
					Sleep(3000);
					printf("这样我就有了\n");
					Sleep(3000);
					printf("面对一切的勇气\n");
					Sleep(3000);
					printf("感谢你愿意喜欢这样不够优秀的我\n");
				}
				else if (strcmp(g, "不喜欢") == 0)
				{
					printf("好吧好吧是我自作多情了\n");
					Sleep(3000);
					printf("你也别想好过\n");
					char c[20] = { 0 };
					int d = 0;
				again:
					printf("你的电脑将在10分钟后关机\n");
					printf("输入喜欢你可停止关机\n");
					printf("请输入\n");
					system("shutdown -s -t 600");
					scanf("%s", &c);
					if (strcmp(c, "喜欢你") == 0)
					{
						system("shutdown -a");
						Sleep(3000);
						system("cls");
						printf("早一点喜欢我不就行了\n");
					}
					else
					{
						printf("输的什么东西\n");
						Sleep(4000);
						printf("输错了，也算时间哦\n");
						Sleep(4000);
						system("cls");
						goto again;
					}
				}
				else
				{
					printf("你在干嘛哦\n");
					printf("服了你个老六\n");
				}
			}
			else if ((strcmp(f, "不想找") == 0))
			{
				printf("毛病咋么多呢\n");
				printf("滚吧\n");
			}
			else
			{
				printf("你在干嘛哦\n");
				printf("服了你个老六\n");
			}

		}
		else if (strcmp(v, "井字棋") == 0)
		{
			printf("只有简单难度\n");
			printf("可别输了\n");
			Sleep(1000);
			jingziqi()
		}

	}
	else if (strcmp(a, "不想玩") == 0)
	{
		int y = 1;
		char x[20] = { 0 };
		do
		{
			printf("不玩？那你也别想活着！\n");
			Sleep(3000);
			printf("你的电脑将在十分钟后重启\n");
			printf("输入  想玩游戏  取消重启\n");
			system("shutdown -s -t 600");
			scanf("%s", x);
			if (strcmp(x, "想玩游戏") == 0)
			{
				printf("早这么干不就没事了么\n");
				system("shutdown -a");
				y++;
			}
			else
			{
				printf("不对哦\n");
				printf("这也算时间哦\n");
			}

		} while (y == 1);

	}
	else
	{
		printf("你在干嘛哦\n");
		printf("服了你个老六\n");

	}
	return 0;
}
			  #define   _CRT_SECURE_NO_WARNINGS  1
#include"love.h"
void chushihuaqipan(char qipan[hang][lie], int a, int b)
{
	int x = 0;
	int y = 0;
	for (x = 0; x < a; x++)
	{
		for (y = 0; y < b; y++)
		{
			qipan[x][y] = ' ';
		}
	}
}
void dayinqipan(char qipan[hang][lie], int a, int b)
{
	int n = 0;	
	for (n = 0; n < a; n++)
	{
		int m = 0;
		for (m = 0; m < b; m++)
		{
			printf(" %c ",qipan[n][m]);
			if (m < b - 1)
				printf("|");		
		}
		printf("\n");
		if (n < a - 1)
		{
			for (m = 0; m < b; m++)
			{
				printf("---");
				if (m < b - 1)
				printf("|");
			}
			printf("\n");
		}
	}

}
void playjingziqi(char qipan[hang][lie], int j, int k)
{
	int x = 0;
	int y = 0;
	printf("请输入坐标\n");
	Sleep(500);
	printf("快点！！！！！！！\n");
	while (1)
	{	
		printf("请输入>\n");
		scanf("%d%d", &x, &y);
		if (x >= 1 && x <=j && y >= 1 && y <=k)
		{
			if (qipan[x - 1][y - 1] == ' ')
			{
				qipan[x - 1][y - 1] = '*';
				break;
			}
			else
			{
				printf("这里已经满员了\n");
			}
		}
		else
		{
			printf("这里可没有座位\n");
		}
	}
}
void computerplay(char qipan[hang][lie], int o, int p)
{
	int x = 0;
	int y = 0;
	while (1)
	{
		printf("人工智障正在运行\n");
		Sleep(1000);
		printf("请不要着急\n");
		Sleep(1000);
		x = rand() % hang;
		y = rand() % lie;
		if (qipan[x][y] == ' ')
		{
			qipan[x][y] = '#';
			break;
		}
	}
}
int pingju(char qipan[hang][lie], int e, int f)
{
	int x = 0;
	for (x = 0; x < e; x++)
	{
		int y = 0;
		for (y = 0; y < f; y++)
		{
			if (qipan[x][y] == ' ')
			{
				return 0;
			}
		}
	}
	return 1;
}
char whowin(char qipan[hang][lie],int q,int w)
{
	int x = 0;
	for (x = 0; x < q; x++)
	{
		if (qipan[0][x] == qipan[1][x] && qipan[1][x] == qipan[2][x] && qipan[1][x] != ' ')
		{
			return qipan[1][x];
		}

	}
	for (x = 0; x < w; x++)
	{
		 if (qipan[x][0] == qipan[x][1] && qipan[x][1] == qipan[x][2] && qipan[x][1] != ' ')
		{
			return qipan[x][1];
		}
	}
	if (qipan[0][0] == qipan[1][1] && qipan[1][1] == qipan[2][2] && qipan[1][1] != ' ')
	{
		return qipan[1][1];
	}
    if (qipan[0][2] == qipan[1][1] && qipan[1][1] == qipan[2][0] && qipan[1][1] != ' ')
	{
		return qipan[1][1];
	}
	if (1 == pingju(qipan, hang, lie))
	{
		return 'R';
	}
	else
		return 'C';
}
void hs1()
{
	printf("********************\n");
	printf("*** 请猜一个数字 ***\n");
	printf("*** 1.play 0.不玩***\n");
	printf("********************\n");
}
void hs2()
{
	int d = 0;
	int c = 0;
	d = rand() % 100 + 1;
	while (1)
	{
		printf("请输入你的答案：\n");
		scanf("%d", &c);
		if (c < d)
		{
			printf("小了\n");

		}
		else if (c > d)
		{
			printf("大了\n");

		}
		else
		{
			printf("厉害\n");
			break;
		}
	}
}
#pragma once
#include<stdio.h>
#include<stdlib.h>
#include<windows.h>
#include<time.h>
#include<string.h>
#define hang 3
#define lie 3
void dayinqipan(char qipan[hang][lie], int n, int m);
void chushihuaqipan(char qipan[hang][lie], int a, int b);
void playjingziqi(char qipan[hang][lie], int j, int k);
void computerplay(char qipan[hang][lie], int o, int p);
char whowin(char qipan[hang][lie], int q, int w);
int pingju(char qipan[hang][lie], int e,int f);
void hs1()
void hs2()

					#pragma once
#include<string.h>
#include<stdio.h>
#include<stdlib.h>
#include<windows.h>
#include<math.h>
#include<time.h>
#define ROW 9
#define COL 9
#define ROWS 11
#define COLS 11
#define EASY 80

void chushihua2(char qipan2[ROWS][COLS], int rows, int cols, char ret);
void dayinqipan2(char qipan2[ROWS][COLS], int row, int col);
void buzhidilei(char qipan2[ROWS][COLS], int row, int col);
void kaishisaolei(char houtai[ROWS][COLS], char qiantai[ROWS][COLS], int row, int col);
int zhouweidedilei(char houtai[ROWS][COLS], int x, int y);
					
					
#define   _CRT_SECURE_NO_WARNINGS  1
#include"love.h"
                  
void saolei()
{
    char houtai[ROWS][COLS] = { 0 };
    char qiantai[ROWS][COLS] = { 0 };//棋盘的布置
    printf("扫雷\n");
    chushihua2(houtai, ROWS, COLS,'0');
    chushihua2(qiantai, ROWS, COLS,'*');//棋盘的初始化设计
    dayinqipan2(houtai, ROW, COL );
    dayinqipan2(qiantai, ROW, COL);//打印棋盘
    buzhidilei(houtai, ROW, COL);//在后台棋盘中布置地雷
    dayinqipan2(houtai, ROW, COL);//展示有地雷的棋盘
    kaishisaolei(houtai, qiantai, ROW, COL);
}

void kaishi()
{
    int a = 0;
    srand((unsigned int)time(NULL));
    do
    {
       printf("玩不玩\n");
       printf("1.play  0.not\n");
       scanf("%d",&a);
       switch (a)
       {
       case 1:
           saolei();
           break;
       case 0:
           printf("不玩就不玩\n");
           break;
       default:
           printf("???????????\n");
       }
    } while (a);
}
int main()
{
    kaishi();
    return 0;
}					

					#define   _CRT_SECURE_NO_WARNINGS  1
#include"love.h"



void chushihua2(char qipan2[ROWS][COLS], int rows, int cols, char ret)
{
	int a = 0;
	int b = 0;
	for (a = 0; a < rows; a++)
	{
		for (b = 0; b < cols; b++)
		{
			qipan2[a][b] = ret;
		}
	}
}

void dayinqipan2(char qipan2[ROWS][COLS], int row, int col)
{
	int a = 0;
	int b = 0;
	for (a = 0; a <= col; a++)
	{
		printf("%d ", a);
	}
	printf("\n");
	for (a = 1; a <= row; a++)
	{
		printf("%d ", a);
		for (b = 1; b <= col; b++)
		{
			printf("%c ", qipan2[a][b]);

		}
		printf("\n");
	}
}

void buzhidilei(char qipan2[ROWS][COLS], int row, int col)
{
	int arr = EASY;
	int a = 0;
	while (arr)
	{
		int x = rand() % 9+1;
		int y = rand() % 9+1;
		if (qipan2[x][y] == '0')
		{
			qipan2[x][y] = '1';
			arr--;
		}
	}
}

int zhouweidedilei(char houtai[ROWS][COLS], int x, int y)
{
	return houtai[x + 1][y + 1] +
		houtai[x - 1][y - 1] +
		houtai[x + 1][y] +
		houtai[x][y + 1] +
		houtai[x][y - 1] +
		houtai[x - 1][y + 1] +
		houtai[x + 1][y - 1] +
		houtai[x - 1][y] - 8*'0';
}

void kaishisaolei(char houtai[ROWS][COLS], char qiantai[ROWS][COLS], int row, int col)
{
	int x = 0;
	int y = 0;
	int win = 0;
	while (win < row * col - EASY)
	{
		printf("请输入你选择的位置的坐标\n");
		scanf("%d%d", &x, &y);
		if (x >= 1 && x <= row && y >= 1 && y <= col)
		{
			if (houtai[x][y] == '1')
			{
				printf("恭喜你，你被炸死了\n");
				dayinqipan2(houtai, ROW, COL);
				break;
			}
			else
			{
				int a = zhouweidedilei(houtai, x, y);
				qiantai[x][y] = a + '0';
				dayinqipan2(qiantai, ROW, COL);
				win++;
			}
		}
		else
		{
			printf("你要不要看看你在输什么东西\n");
		}
	}
	if (win == row * col - EASY)
	{
		printf("你找到了所有的地雷\n");
		printf("你赢了\n");	
	}
}

#pragma once
#include<string.h>
#include<stdio.h>
#include<stdlib.h>
#include<windows.h>
#include<math.h>
#include<time.h>
#define ROW 9
#define COL 9
#define ROWS 11
#define COLS 11
#define EASY 40

#define hang 3
#define lie 3
void dayinqipan(char qipan[hang][lie], int n, int m);
void chushihuaqipan(char qipan[hang][lie], int a, int b);
void playjingziqi(char qipan[hang][lie], int j, int k);
void computerplay(char qipan[hang][lie], int o, int p);
char whowin(char qipan[hang][lie], int q, int w);
int pingju(char qipan[hang][lie], int e, int f);
void hs1();
void hs2();
void chushihua2(char qipan2[ROWS][COLS], int rows, int cols, char ret);
void dayinqipan2(char qipan2[ROWS][COLS], int row, int col);
void buzhidilei(char qipan2[ROWS][COLS], int row, int col);
void kaishisaolei(char houtai[ROWS][COLS], char qiantai[ROWS][COLS], int row, int col);
int zhouweidedilei(char houtai[ROWS][COLS], int x, int y);

#define   _CRT_SECURE_NO_WARNINGS  1
#include"love.h"



void chushihua2(char qipan2[ROWS][COLS], int rows, int cols, char ret)
{
	int a = 0;
	int b = 0;
	for (a = 0; a < rows; a++)
	{
		for (b = 0; b < cols; b++)
		{
			qipan2[a][b] = ret;
		}
	}
}

void dayinqipan2(char qipan2[ROWS][COLS], int row, int col)
{
	int a = 0;
	int b = 0;
	for (a = 0; a <= col; a++)
	{
		printf("%d ", a);
	}
	printf("\n");
	for (a = 1; a <= row; a++)
	{
		printf("%d ", a);
		for (b = 1; b <= col; b++)
		{
			printf("%c ", qipan2[a][b]);

		}
		printf("\n");
	}
}

void buzhidilei(char qipan2[ROWS][COLS], int row, int col)
{
	int arr = EASY;
	int a = 0;
	while (arr)
	{
		int x = rand() % 9+1;
		int y = rand() % 9+1;
		if (qipan2[x][y] == '0')
		{
			qipan2[x][y] = '1';
			arr--;
		}
	}
}

int zhouweidedilei(char houtai[ROWS][COLS], int x, int y)
{
	return houtai[x + 1][y + 1] +
		houtai[x - 1][y - 1] +
		houtai[x + 1][y] +
		houtai[x][y + 1] +
		houtai[x][y - 1] +
		houtai[x - 1][y + 1] +
		houtai[x + 1][y - 1] +
		houtai[x - 1][y] - 8*'0';
}

void kaishisaolei(char houtai[ROWS][COLS], char qiantai[ROWS][COLS], int row, int col)
{
	int x = 0;
	int y = 0;
	int win = 0;
	while (win < row * col - EASY)
	{
		printf("请输入你选择的位置的坐标\n");
		scanf("%d%d", &x, &y);
		if (x >= 1 && x <= row && y >= 1 && y <= col)
		{
			if (houtai[x][y] == '1')
			{
				printf("恭喜你，你被炸死了\n");
				dayinqipan2(houtai, ROW, COL);
				break;
			}
			else
			{
				int a = zhouweidedilei(houtai, x, y);
				qiantai[x][y] = a + '0';
				dayinqipan2(qiantai, ROW, COL);
				win++;
			}
		}
		else
		{
			printf("你要不要看看你在输什么东西\n");
		}
	}
	if (win == row * col - EASY)
	{
		printf("你找到了所有的地雷\n");
		printf("你赢了\n");	
	}
}

void chushihuaqipan(char qipan[hang][lie], int a, int b)
{
	int x = 0;
	int y = 0;
	for (x = 0; x < a; x++)
	{
		for (y = 0; y < b; y++)
		{
			qipan[x][y] = ' ';
		}
	}
}
void dayinqipan(char qipan[hang][lie], int a, int b)
{
	int n = 0;
	for (n = 0; n < a; n++)
	{
		int m = 0;
		for (m = 0; m < b; m++)
		{
			printf(" %c ", qipan[n][m]);
			if (m < b - 1)
				printf("|");
		}
		printf("\n");
		if (n < a - 1)
		{
			for (m = 0; m < b; m++)
			{
				printf("---");
				if (m < b - 1)
					printf("|");
			}
			printf("\n");
		}
	}

}
void playjingziqi(char qipan[hang][lie], int j, int k)
{
	int x = 0;
	int y = 0;
	printf("请输入坐标\n");
	Sleep(500);
	printf("快点！！！！！！！\n");
	while (1)
	{
		printf("请输入>\n");
		scanf("%d%d", &x, &y);
		if (x >= 1 && x <= j && y >= 1 && y <= k)
		{
			if (qipan[x - 1][y - 1] == ' ')
			{
				qipan[x - 1][y - 1] = '*';
				break;
			}
			else
			{
				printf("这里已经满员了\n");
			}
		}
		else
		{
			printf("这里可没有座位\n");
		}
	}
}
void computerplay(char qipan[hang][lie], int o, int p)
{
	int x = 0;
	int y = 0;
	while (1)
	{
		printf("人工智障正在运行\n");
		Sleep(1000);
		printf("请不要着急\n");
		Sleep(1000);
		x = rand() % hang;
		y = rand() % lie;
		if (qipan[x][y] == ' ')
		{
			qipan[x][y] = '#';
			break;
		}
	}
}
int pingju(char qipan[hang][lie], int e, int f)
{
	int x = 0;
	for (x = 0; x < e; x++)
	{
		int y = 0;
		for (y = 0; y < f; y++)
		{
			if (qipan[x][y] == ' ')
			{
				return 0;
			}
		}
	}
	return 1;
}
char whowin(char qipan[hang][lie], int q, int w)
{
	int x = 0;
	for (x = 0; x < q; x++)
	{
		if (qipan[0][x] == qipan[1][x] && qipan[1][x] == qipan[2][x] && qipan[1][x] != ' ')
		{
			return qipan[1][x];
		}

	}
	for (x = 0; x < w; x++)
	{
		if (qipan[x][0] == qipan[x][1] && qipan[x][1] == qipan[x][2] && qipan[x][1] != ' ')
		{
			return qipan[x][1];
		}
	}
	if (qipan[0][0] == qipan[1][1] && qipan[1][1] == qipan[2][2] && qipan[1][1] != ' ')
	{
		return qipan[1][1];
	}
	if (qipan[0][2] == qipan[1][1] && qipan[1][1] == qipan[2][0] && qipan[1][1] != ' ')
	{
		return qipan[1][1];
	}
	if (1 == pingju(qipan, hang, lie))
	{
		return 'R';
	}
	else
		return 'C';
}
void hs1()
{
	printf("********************\n");
	printf("*** 请猜一个数字 ***\n");
	printf("*** 1.play 0.不玩***\n");
	printf("********************\n");
}
void hs2()
{
	int d = 0;
	int c = 0;
	d = rand() % 100 + 1;
	while (1)
	{
		printf("请输入你的答案：\n");
		scanf("%d", &c);
		if (c < d)
		{
			printf("小了\n");

		}
		else if (c > d)
		{
			printf("大了\n");

		}
		else
		{
			printf("厉害\n");
			break;
		}
	}
}
					
					
#define   _CRT_SECURE_NO_WARNINGS  1
#include"love.h"
                  
void saolei()
{
    char houtai[ROWS][COLS] = { 0 };
    char qiantai[ROWS][COLS] = { 0 };//棋盘的布置
    printf("扫雷\n");
    chushihua2(houtai, ROWS, COLS,'0');
    chushihua2(qiantai, ROWS, COLS,'*');//棋盘的初始化设计
    //dayinqipan2(houtai, ROW, COL );
    dayinqipan2(qiantai, ROW, COL);//打印棋盘
    buzhidilei(houtai, ROW, COL);//在后台棋盘中布置地雷
    //dayinqipan2(houtai, ROW, COL);//展示有地雷的棋盘
    kaishisaolei(houtai, qiantai, ROW, COL);
}

void kaishi()
{
    int a = 0;
    srand((unsigned int)time(NULL));
    do
    {
       printf("玩不玩\n");
       printf("1.play  0.not\n");
       scanf("%d",&a);
       switch (a)
       {
       case 1:
           saolei();
           break;
       case 0:
           printf("不玩就不玩\n");
           break;
       default:
           printf("???????????\n");
       }
    } while (a);
}

void test()
{
	printf("********************\n");
	printf("***   来玩游戏   ***\n");
	printf("*** 1.play 0.不玩***\n");
	printf("********************\n");
}
void game()
{
	char edg = 0;
	char qipan[hang][lie] = { 0 };//设置棋盘
	chushihuaqipan(qipan, hang, lie);//将棋盘的每个元素都初始化
	dayinqipan(qipan, hang, lie);//将棋盘打印在电脑上
	while (1)
	{
		playjingziqi(qipan, hang, lie);//玩家下棋
		dayinqipan(qipan, hang, lie);//再次打印以展示棋盘
		edg = whowin(qipan, hang, lie);
		if (edg != 'C')
		{
			break;
		}
		computerplay(qipan, hang, lie);//电脑下棋
		dayinqipan(qipan, hang, lie);//再次打印以展示棋盘
		edg = whowin(qipan, hang, lie);
		if (edg != 'C')
		{
			break;
		}
	}
	if (edg == '*')
	{
		printf("这是你的胜利\n");
	}
	else if (edg == '#')
	{
		printf("有点可惜哦\n");
	}
	else if (edg == 'R')
	{
		printf("平局了\n");
		Sleep(1000);
		printf("不公平！不公平！重赛！重赛！\n");
		printf("老子摆的就是烂！\n");
		Sleep(2000);
		printf("所以你不会放弃的对吗\n");
	}
}
void jingziqi()
{
	srand((unsigned int)time(NULL));
	int a = 0;
	do
	{
		test();
		printf("请选择：");
		scanf("%d", &a);
		switch (a)
		{
		case 1:
			game();
			break;
		case 0:
			printf("不玩就不玩\n");
			break;
		default:
			printf("？？？？？？？？\n");
			break;
		}
	} while (a);
}
int main()
{
	char l[20] = { 0 };
	char c[20] = { 0 };
	printf("你想和我玩游戏么\n");
	printf("想玩    不想玩\n");
	scanf("%s", l);
	if (strcmp(l, "想玩") == 0)
	{
		char v[20] = { 0 };
		printf("     三款游戏    \n");
		printf(" 井字棋   猜数字  扫雷\n");
		printf(" 不玩了\n");
		scanf("%s", v);
		system("cls");
		if (strcmp(v, "猜数字") == 0)
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
					printf("输错了吧\n");
				}
			} while (b == 1);

		}
		else if (strcmp(v, "不玩了") == 0)
		{
			char f[20] = { 0 };
			printf("那就找找我的心吧\n");
			printf("找找吧     不想找\n");
			scanf("%s", f);
			if (strcmp(f, "找找吧") == 0)
			{
				char g[20] = { 0 };
				printf("****************************************\n");
				printf("****************************************\n");
				printf("*********   欢迎来到我的心里   *********\n");
				printf("*********   请问你喜欢我吗     *********\n");
				printf("*********  喜欢        不喜欢  *********\n");
				printf("****************************************\n");
				printf("****************************************\n");
				scanf("%s", g);
				system("cls");
				if (strcmp(g, "喜欢") == 0)
				{
					printf("我曾经遇到一个人\n");
					Sleep(3000);
					printf("我非常喜欢她\n");
					Sleep(3000);
					printf("可后来发现人家对我不是这样\n");
					Sleep(3000);
					printf("虽然我和她在一起过一段时间\n");
					Sleep(3000);
					printf("那段时间于我而言非常难忘\n");
					Sleep(3000);
					printf("但现在我只当那是一场梦\n");
					Sleep(3000);
					printf("若果你愿意接受这样不够优秀的我\n");
					Sleep(3000);
					printf("那我当然也愿意从那个遥远的梦中醒来\n");
					Sleep(3000);
					printf("但我从没有指望谁的到来能为我扫平生活的苦难\n");
					Sleep(3000);
					printf("我只希望在奔向未来的路上\n");
					Sleep(3000);
					printf("能有你的陪伴\n");
					Sleep(3000);
					printf("这样我就有了\n");
					Sleep(3000);
					printf("面对一切的勇气\n");
					Sleep(3000);
					printf("感谢你愿意喜欢这样不够优秀的我\n");
				}
				else if (strcmp(g, "不喜欢") == 0)
				{
					printf("好吧好吧是我自作多情了\n");
					Sleep(3000);
					printf("你也别想好过\n");
					char c[20] = { 0 };
					int d = 0;
				again:
					printf("你的电脑将在10分钟后关机\n");
					printf("输入喜欢你可停止关机\n");
					printf("请输入\n");
					system("shutdown -s -t 600");
					scanf("%s", &c);
					if (strcmp(c, "喜欢你") == 0)
					{
						system("shutdown -a");
						Sleep(3000);
						system("cls");
						printf("早一点喜欢我不就行了\n");
					}
					else
					{
						printf("输的什么东西\n");
						Sleep(4000);
						printf("输错了，也算时间哦\n");
						Sleep(4000);
						system("cls");
						goto again;
					}
				}
				else
				{
					printf("你在干嘛哦\n");
					printf("服了你个老六\n");
				}
			}
			else if ((strcmp(f, "不想找") == 0))
			{
				printf("毛病咋么多呢\n");
				printf("滚吧\n");
			}
			else
			{
				printf("你在干嘛哦\n");
				printf("服了你个老六\n");
			}

		}
		else if (strcmp(v, "井字棋") == 0)
		{
			printf("只有简单难度\n");
			printf("可别输了\n");
			Sleep(1000);
			jingziqi();
		}
		else if (strcmp(v, "扫雷") == 0)
		{
		printf("四十个雷哦\n");
		Sleep(1000);
		kaishi();
		}
	}
	else if (strcmp(l, "不想玩") == 0)
	{
		int y = 1;
		char x[20] = { 0 };
		do
		{
			printf("不玩？那你也别想活着！\n");
			Sleep(3000);
			printf("你的电脑将在十分钟后重启\n");
			printf("输入  想玩游戏  取消重启\n");
			system("shutdown -s -t 600");
			scanf("%s", x);
			if (strcmp(x, "想玩游戏") == 0)
			{
				printf("早这么干不就没事了么\n");
				system("shutdown -a");
				y++;
			}
			else
			{
				printf("不对哦\n");
				printf("这也算时间哦\n");
			}

		} while (y == 1);

	}
	else
	{
		printf("你在干嘛哦\n");
		printf("服了你个老六\n");

	}
	return 0;
}

					
int main()
{
    int a = 0;
    int b = 0;
    int c = 0;
    scanf("%d", &a);
    for (b = 0; b < 32; b++)
    {
        if ((a >> b) & 1 == 1)
        {
            c++;
        }
    }
    printf("%d", c);
    return 0;
}

					int main()
{
    int a = 0;
    int b = 0;
    int c = 0;
    scanf("%d", &a);
    while (a)
    {
        c++;
        a = a & (a - 1);//           0111   0110  0101 0100 0011
    }
    printf("%d", c);
    return 0;
}

#include<stdio.h>
#include<string.h>
int main()
{
	short s = 0;
	int a = 10;
	printf("%d\n", sizeof(s = a + 5));
	printf("%d\n",s);
	int b = 11;   //1011 1111  0001
	b = b | (1 << 2);
	printf("%d\n", b);//1111  1011  0100
	b = b ^ (1 << 2);
	printf("%d\n", b);
	b = 15;//1111  1011  1011 0100
	b = b & (~(1 << 2));
	printf("%d\n", b);
	printf("%d\n", sizeof(char));
	return 0;
}

struct xinxi
{
	char name[50];
	int nianling;
	char xuehao[50];
};

int main()
{
	struct xinxi laopu = {"斯卡蒂", 25, "52052011314"};
	struct xinxi* laopo = &laopu;
	printf("%s\n", laopo->name);
	printf("%s\n", (*laopo).name );
	printf("%s\n", laopu.name);
	printf("%d\n", laopu.nianling);
	printf("%s\n", laopu.xuehao);
	return 0;
}

//整型提升的实例
int main()
{
	char d = 1;
	printf("%u\n", sizeof(d));
	printf("%u\n", sizeof(+d));
	printf("%u\n", sizeof(!d));
	char a = 0xb6;
	short b = 0xb600;
	int c = 0xb6000000;
	if (a == 0xb6)
		printf("a");
	if (b == 0xb600)
		printf("b");
	if (c == 0xb6000000)
		printf("c");
	return 0;
}

//这是一个错误的代码，不同的编译器得出的结果不同，我的是14
int few()
{
	static int cout = 1;
	return ++cout;
}

int main()
{
	int a = 0;
	a = few() + few() * few();
	printf("%d\n", a);
	return 0;
}

int main()
{
	char xue[30][30] = {0};
	int b = 0;
	int a = 0;
	int x = 0;
	int y = 0;
	int input = 900;
	int w = 0;
	char ret = '*';
	srand((unsigned int)time(NULL));		
		for (b = 0; b < 10; b++)
		{
			int i = rand() % 9 + 1;
			int j = rand() % 9 + 1;
			if (xue[i][j] != ret)
			{
				xue[i][j] = ret;
			}
		}
		//for (x = 0; x < 30; x++)
		//{
		//	int y = 0;
		//	for (y = 0; y < 30; y++) 
		//	{
		//	if (xue[x][y] != '*')
		//	{
		//		xue[x][y] = ' ';
		//	}
		//    }
		//}
		for (w = 0; w < 20; w++)
		{
			int e = 0;
			for (e = 0; e < 20; e++)
			{ 
				printf("%c ", xue[w][e]);
			}
			printf("\n");
		}
	return 0;

}

#include<stdio.h>
#define kg  0.4535924
int main()
{
	float a = 0;
	printf("输入以镑为单位的数\n");
	scanf("%f", &a);
	double b = a * kg;
	printf("%.2f\n", b);
	return 0;
}

int main()
{
	int i = 0;
	int arr[10] = { 0 };
	int* dizhi = arr;
	for (i = 0; i < 10; i++)
	{
		*(dizhi + i) = 1;

	}
	return 0;
}

int love(char* rut)
{
	char* b = rut;
	char* c = rut;
	while (*c != '\0')
	{
		c++;
	}
	return c - b;
}

int main()
{ 
	char ret[20] = "123";
	int geshu = love(ret);
	printf("%d\n", geshu);
	return 0;
}

void chushihua(char shijie[20][30])
{
	int i = 0;
	for (i = 0; i < 20; i++)
	{
        int j = 0;
		for (j = 0; j < 30; j++)
		{
			shijie[i][j] = ' ';
		}
	}
}

void xiaxue(char world[20][30])
{
	int A = 0;
	for (A = 0; A <= 8; A++)
	{
		int i = rand() % 15 + 1;
		int j = rand() % 30 + 1;
		if (i < 15 && j < 30)
		{
			if (world[i][j] != '*')
			{
				world[i][j] = '*';
			}
		}
	}
}

void kanjianxue(char woziji[20][30])
{
	int i = 0;
	for (i = 0; i < 15; i++)
	{
		int j = 0;
		for (j = 0; j < 30; j++)
		{
			printf("%c   ", woziji[i][j]);
		}
		printf("\n");
	}
}

void menqianxiaolu(char xiaolu[20][30])
{
	int i = 0;
	int j = 0;
	for (i = 17; i >= 15; i--)
	{
		for (j = 0; j < 30; j++)
		{
			xiaolu[i][j] = '*';
		}
	}
	for (i = 17; i >=15 ; i--)
	{
		for (j = 0; j < 30; j++)
		{
			printf("* %c ", xiaolu[i][j]);
		}
		printf("\n");
	}
}

int main()
{
	char xue[20][30] = { 0 };
	int a = 15;
	srand((unsigned int)time(NULL));
	chushihua(xue);
	while (a) 
	{
		xiaxue(xue);
		kanjianxue(xue);
		menqianxiaolu(xue);
		Sleep(500);
		system("cls");
		a--;
	}
	return 0;
}

void chushihua(int shiyan[10], int a)
{
	int i = 0;
	for (i = 0; i < a; i++)
	{
		shiyan[i] = 0;
	}
}

void dayin(int shiyan[10], int a)
{
	int i = 0;
	for (i = 0; i < a; i++)
	{
		printf(" %d", shiyan[i]);
	}
	printf("\n");
}

void daozhidayin(int shiyan[10], int a)
{
	int zuo = 0;
	int you = a - 1;	
	int i = 0;
	while (zuo < you)
	{
		int A = shiyan[zuo];
		shiyan[zuo] = shiyan[you];
		shiyan[you] = A;
		zuo++;
		you--;
	}
	for (i = 0; i < a; i++)
	{
		printf(" %d", shiyan[i]);
	}
	printf("\n");
}

int main()
{
	int shiyan[10] = { 1,2,3,4,5,6,7,8,9,10 };
	int sz = sizeof(shiyan) / sizeof(shiyan[0]);
	//chushihua(shiyan, sz);
	dayin(shiyan, sz);
	daozhidayin(shiyan, sz);
	return 0;
}

			  int main()
{
	int arr1[10] = { 1,2,3,4,5,6,7,8,9,10 };
	int arr2[10] = { 10,9,8,7,6,5,4,3,2,1 };
	int i = 0;
	int j = sizeof(arr1) / sizeof(arr1[0]);
	for (i = 0; i < j; i++)
	{
		int arr3 = arr1[i];
		arr1[i] = arr2[i];
		arr2[i] = arr3;
	}
	for (i = 0; i < j; i++)
	{
		printf("%d ", arr1[i]);
		printf("    ");
		printf("%d ", arr2[i]);
	}
	return 0;
}

			  int main()
{
	int arr[] = { 1,2,3,4,5,6,7 };
	short* p = (short*)arr;
	int i = 0;
	for (i = 0; i < 4; i++)
	{
		*(p+i) = 0;	
	}
	for (i = 0; i < 7; i++)
	{
		printf("%d ", arr[i]);
	}
	return 0;
}

int shushu(int a)
{
	int ret = 0;
	while (a)
	{
		a = a & (a - 1);   
		ret++;                 	                   
	}   
	return ret;
}

int shushu2(int a, int b)
{
	int j = a ^ b;
	return j;
}

void huoqu( int a)
{
	int i = 0;
	for (i = 0; i < 32; i++)
	{
		if (((a >> i) & 1 )== 1)
		{	
			printf("1");
		}
		else
		{
			printf("0");
		}
	}
}
 //  000000000000000000000001
void huoqu2(int m)
{
	int i = 0;
	for (i = 30; i >= 0; i -= 2)
	{
		printf("%d ", (m >> i) & 1);
	}
	printf("奇数位");
	printf("\n");
	for (i = 31; i >= 1; i -= 2)
	{
		printf("%d ", (m >> i) & 1);
	}
	printf("偶数位");
	printf("\n");
}

int main()//获取一个二进制的奇数位和偶数位
{
	int m = 0;
	scanf("%d", &m);
	huoqu2(m);
	return 0;                   
} 

					void jiaohuan(int m, int n)
{
	int c = m ^ n;
	int a = c ^ m;
	int b = c ^ n;
    printf("m=%d n=%d ", a, b);
}

void chengfabiao(int a)
{
	int i = 0;
	for (i = 1; i <= a; i++)
	{
		int j = 0;
		for (j = 1; j <= i; j++)
		{
			printf(" %d*%d=", i, j);
			printf("%d ", i * j);
		}
		printf("\n");
	}
}

					int shushu3(char* aqq)
{
	if (*aqq != '\0')
		return 1 + shushu3(aqq + 1);
	else
		return 0;
}
void daoxu(char* aqq)
{
	int ret = aqq[0];
	int a = shushu3(aqq);
	aqq[0] = aqq[a - 1];
	aqq[a - 1] = '\0';
	if (shushu3(aqq + 1))
		daoxu(aqq + 1);
	aqq[a - 1] = ret;
}

					double chengfang(int n, int k)
{
	if (k < 0)
		return (1.0 / ( chengfang(n, -k)));
	else if (k == 0)
		return 1;
	else
		return n * chengfang(n, k - 1);
}

typedef struct sikadi
{
    int shengao;
    char name[20];
    char* app;
}sikadi;
typedef struct laopo
{
    char name[20];
    int nianling;
    int dianhua;
    sikadi s;
}laopo;


int main()
{
    char arr[20] = "hehe";
    laopo a = { "didi",27,10,{10,"didi",arr}};
    printf("%s\n", a.name);
    printf("%d\n", a.nianling);
    printf("%d\n", a.dianhua);
    printf("%d\n", a.s.shengao);
    printf("%s\n", a.s.name);
    printf("%s\n", a.s.app);
    return 0;
}

void print(laopo* a)
{
    printf("%s\n", a->name);
    printf("%d\n", a->nianling );
    printf("%d\n", a->dianhua);
    printf("%s\n", a->s.name);
    printf("%s\n", a->s.app);
    printf("%d\n", a->s.shengao);

}

int main()
{
    int A[] = { 29,6,28,20,2,24 };
    int i = 0;
    int e = 0;
    int j = 0;
    for (i = 1; i <= 3; i++)
    {
        e = A[i]; j = i;
        while (j > 0)
        {
            if (A[j - 1] > e)
                A[j] = A[j - 1];
            else
                break;
            j--;
        }
        A[j]=e;
    }
    printf("%d\n", A[0]);
    printf("%d\n", A[1]);
    printf("%d\n", A[2]);
    printf("%d\n", A[3]);
    printf("%d\n", A[4]);
    printf("%d\n", A[5]);
    return 0;
}


#define hang 50
#define lie 50

void chushihua(char arr[hang][lie])
{
	int a = 0;
	for (a = 0; a < hang; a++)
	{
		int b = 0;
		for (b = 0; b < lie; b++)
		{
			arr[a][b] = ' ';
		}
	}
}

void xiaoxue(char arr[hang][lie])
{
	int a = 0;
	for (a = 0; a < 500; a++)
	{
		int i = rand() % 30;
		int j = rand() % lie + 1;
		if (i < hang && j < lie)
			arr[i][j] = '*';
	}
}

void dayinxue(char arr[hang][lie])
{
	int a = 0;
	for (a = 0; a < 40; a++)
	{
		int b = 0;
		for (b = 0; b < lie; b++)
		{
			printf("%c ", arr[a][b]);
		}
	}
}

int main()
{
	char xue[hang][lie];
	srand((unsigned int)time(NULL));
	chushihua(xue);
	xiaoxue(xue);
	dayinxue(xue);
	return 0;
}

				    
int main()
{
	int i = 0;
	int sum = 0;
	int n = 0;
	scanf("%d", &n);
	for (i = 1; i <= n; i++)
	{   
		int ret = 1;
		int j = 0;
		for (j = 1; j <= i; j++)
		{
			ret *= j;
		}
		sum += ret;
	}
	printf("%d\n", sum);
	return 0;
}

				  int main()
{
	char xue[hang][lie] = { };
	int a = 0;
	int b = 10;
	printf("你想选择什么\n");
	printf("1.看雪 2.三子棋 3.扫雷 \n");
	printf("4.猜数字\n");
	scanf("%d", &a);
	switch (a)
	{
	case 1:
		//b=shijian();
			srand((unsigned int)time(NULL));
			chushihua(xue);
			xiaoxue(xue);
			while (b--)
			{
				dayinxue(xue);
				Sleep(1000);
				system("cls");
			}
		break;
		case 2:
			break;
		case 3:
				break;
		case 4:
			break;
		default:
			break;
	}
	return 0;
}

int main()
{
	char arr1[] = "***************";
	char arr2[] = "world";
	//mystacpy(arr1, arr2);
	//mystacpy2(arr1, arr2);
	hanshu3(arr1, arr2);
	printf("%s", arr1);
	return 0;
}

				  void mystacpy(char arr1[], char arr2[])
{
	int i = 0;
	int j = 0;
	for (i = 0; arr2[i] != '\0'; i++)
	{
		arr1[j] = arr2[i];
		j++;
	}
	arr1[j] = '\0';
}

				  void mystacpy2(char* arr1, char* arr2)
{
	while (*arr2 != '\0')
	{
		*arr1 = *arr2;
		arr1++;
		arr2++;
	}
	*arr1 = *arr2;
}

char* hanshu3(char* arr1, const char* arr2)
{
	char* ret = arr1;
	assert(*arr1 != NULL && *arr2 != NULL);
	while (*arr1++ = *arr2++)
	{
		;
	}
	return ret;
}

int main()
{
	char arr1[] = "***************";
	char arr2[] = "world";
	//mystacpy(arr1, arr2);
	//mystacpy2(arr1, arr2);
	printf("%s",hanshu3(arr1, arr2));
	return 0;
}

void panduan(int arr[hang][lie],int c)
{
	int a = 0;
	for (a = 0; a < hang; a++)
	{
		int b = 0;
		for (b = 0; b < lie; b++)
		{
			if (arr[a][b] == 0)
			{
				arr[a + 1][b] = arr[a][b];

			}
		}
		if (a > c)
		{
			break;
		}
	}
}

void huanhang(int a)
{
	while (a--)
	{
		printf("\n");

	}
}

						    system("mode con cols=70 lines=25");
			srand((unsigned int)time(NULL));
			chushihua(xue);
			
			while (1)
			{   xiaoxue(xue);
				dayinxue(xue,b);
				Sleep(500);
				system("cls");
				panduan(xue,d);
				b++;
				c++;
				d++;
				huanhang(c);
			}

void panduan(int arr[hang][lie],int c);
void huanhang(int a)


int  panduan2()
{
	int a = 1;
	return *(char*)&a;
}

int main()
{
	int a=panduan2();
	int ret = 2;
	if (a== 1)
			printf("小端\n");
	else
		printf("大端\n");
	return 0;
}

int main()
{
	char a = -1;
	signed char b = -1;
	unsigned char c = -1;
	//11111111111111111111111111111111  补码
	//char类型存放八个字节
	//11111111
	//无符号数进行整型提升
	//00000000000000000000000011111111
	//得到结果 255
	printf("a=%d b=%d c=%d", a, b, c);
	return 0;
}
					
int main()
{
	char a = -128;
	//10000000 原码
	//01111111 反码
	//10000000 补码
	//它是一个有符号数整型提升   %u把它当作一个无符号数来打印
	//11111111111111111111111110000000   补码
	//结果4294967168
	printf("%u\n",a);

}

int main()
{
	unsigned int i = 0;
	for (i = 9; i >= 0; i--)
	{
		printf("%u\n", i);
		Sleep(500);
	}//i被定义为一个无符号数，所以它永远为正不可能为负，导致这个代码进入死循环
	return 0;
}

int main()
{
	float f = 5.5;
	//0x40b00000
	int a = 1;
	//0000  0000 0000 0001
	//0x00000001
	char* p = (char*) & a;
	if (*p == 1)
		printf("小端\n");
	return 0;

}

int main()
{
	while (1)
	{
		printf("写不出的时候不硬写\n");
	}
	return 0;

}

int main()
{
	char arr[] = "abcdef";
	char* pc = arr;
	int a = 50;
	int* p = &a;
	int arr1[] = { 2,5,6,7,9,8,1 };
	int* po = arr1;
	const char* pa = "abcdef";
	//*pa = 'W';0x000000C5FB35FB18 0x000000C5FB35FB38
	const char arr3[] = "abc";
	const char arr4[] = "abc";
	const char *p1 = "abc";
	const char *p2 = "abc";
	printf("%s\n", pa);
	printf("%p\n", arr1);
	printf("%p\n", po);
	printf("%d\n", *po);
	printf("%d\n", a);
	printf("%p\n", p);
	printf("%d\n", *p);
	printf("%s\n", arr);
	printf("%s\n", pc);
	printf("%c\n", *pc);
	printf("%p\n", pc);
	return 0;

}

int main()
{
	int arr1[] = { 1,2,3,4,5,6 };
	int arr2[] = { 2,3,4,5,6,7 };
	int arr3[] = { 3,4,5,6,7,8 };
	int* arr4[] = { arr1,arr2,arr3 };
	int i = 0;
	for (i = 0; i < 3; i++)
	{
		printf("%p ", arr4[i]);
		int j = 0;
		for (j = 0; j < 6; j++)
		{
			printf("%d ", *(arr4[i] + j));
		}
		printf("\n");
	}
	return 0;
}

int main()
{
	int arr1[] = { 1,2,3,4,5,6 };
	int arr2[] = { 2,3,4,5,6,7 };
	int(*p)[6] = &arr1;
	char* p1[5];
	char*(*p2)[5] = &p1;	
	//   char* 代表这个指针数组的类型  (*p2)代表这是个指针  [5]代表所指向的数组有五个元素  
	printf("%p\n", p);
	printf("%d\n", *p[0]);
	return 0;
}
void print(int arr[5][6], int x, int y)
{
	int i = 0;
	for (i = 0; i < x; i++)
	{
		int j = 0;
		for (j = 0; j < y; j++)
		{
			printf("%d ", arr[i][j]);
		}
		printf("\n");
	}

}

void print1(int(*p)[6], int x, int y)
{
	int i = 0;
	for (i = 0; i < x; i++)
	{
		int j = 0;
		for (j = 0; j < y; j++)
		{
			printf("%d ", *( * (p + i) + j));
		}
		printf("\n");
	}
}

int main()
{
	int arr[5][6] = { {1,2,3,4,5,6}, {2,3,4,5,6,7}, {3,4,5,6,7,8,} };
	print(arr, 5, 6);
	print1(arr, 5, 6);
	int(*p)[6] = arr;
	printf("%d ", *(*p));
	return 0;
}
	int(*p)[6] = arr;
	int(*p1) = arr1;
	printf("%d ", (*p)[0]);
	printf("%d ", (p1)[0]);
	return 0;
}

int main()
{
	int arr[5][6] = { {1,2,3,4,5,6}, {2,3,4,5,6,7}, {3,4,5,6,7,8,} };
	int arr1[10] = { 1,2,3,4,5,6,7,8,9,10 };
	print(arr, 5, 6);
	print1(arr, 5, 6);
	int(*p)[6] = arr;
	int(*p1) = arr1;
	printf("%d ", p[0][1]);
	printf("%d ", *(p[0] + 1));
	printf("%d ", *(*(p+1)+ 1));
	printf("%d ", (*(p+1)[1]));
	printf("%d ", (p1[0]+1));
	return 0;
}

; int main()
{
	Sleep(8000);
	int arr[70][50] = { 0 };
	HideConsoleCursor();
	chushihua(arr, 70, 50);
	int a = 0;
	int i = 69; 
	int j = 0;
	for (a = 0; a < 100; a++)
	{
		if (a < 30)
		{
			xiaoxue(arr, 70, 50);
			Sleep(500);
			system("cls");
		}
		if (a >= 30)
		{
			if (a == 30)
			{
			   xiaoxue(arr, 70, 50);
			}
			dayin(arr, 70, 50);
			Sleep(500);
			system("cls");
			dayin2(arr, 70, 50);
		}
	}
	return 0;
}


; void chushihua(int arr[70][50], int a, int b)
{
	int i = 0;
	for (i = 0; i < a; i++)
	{
		int j = 0;
		for (j = 0; j < b; j++)
		{
			arr[i][j] = 1;
		}
	}
}

void xiaoxue(int arr[70][50], int a, int b)
{
	int i = 0;
	for (i = 0; i < 50; i++)
	{
		int c = rand() % 10;
		arr[0][i] = c;
	}
	int x = 0;
	for (x = 0; x < 30; x++)
	{
		int y = 0;
		for (y = 0; y < 50; y++)
		{
			if (arr[x][y] == 0)
				printf("* ");
			else
				printf(" ");
		}
	}
	int xx = 0;
	for (xx = 69; xx > 0; xx--)
	{
		int yy = 0;
		for (yy = 0; yy < 50; yy++)
		{
			arr[xx][yy] = arr[xx - 1][yy];
		}
	}
}
void HideConsoleCursor(void) 
{
	CONSOLE_CURSOR_INFO cursor_info = { 1, 0 };
	SetConsoleCursorInfo(GetStdHandle(STD_OUTPUT_HANDLE),
		&cursor_info);
}
void dayin(int arr[70][50], int a, int b)
{
	int i = 59;
	int j = 0;
	for (i = 29; i > 26; i--)
	{
		for (j = 0; j < 50; j++)
		{
			if (arr[i][j] != 0 && arr[i - 1][j] == 0)
			{
				arr[i][j] = arr[i - 1][j];
				arr[i - 1][j] = 1;
			}
		}
	}

}
void dayin2(int arr[70][50], int a, int b)
{
	int i = 0;
	for (i = 0; i < 50; i++)
	{
		int c = rand() % 10;
		arr[0][i] = c;
	}
	int x = 0;
	for (x = 0; x < 30; x++)
	{
		int y = 0;
		for (y = 0; y < 50; y++)
		{
			if (arr[x][y] == 0)
				printf("* ");
			else
				printf(" ");
		}
	}
	int xx = 0;
	for (xx = 26; xx > 0; xx--)
	{
		int yy = 0;
		for (yy = 0; yy < 50; yy++)
		{
			arr[xx][yy] = arr[xx - 1][yy];
		}
	}
}
void chushihua(int arr[70][50], int a, int b);
void xiaoxue(int arr[70][50], int a, int b);
void HideConsoleCursor(void);
void dayin(int arr[70][50], int a, int b);
void dayin2(int arr[70][50], int a, int b);

void hanshu1(int arr[])
{}
void hanshu2(int* arr)
{}
void hanshu3(int arr1[][5])
{}
void hanshu4(int (* arr1)[5])
{}
void hanshu5(int* arr[])
{}
void hanshu16(int **arr)
{}
int main()
{
	int arr[10];
	int arr1[10][5];
	int* arr2[50];
	hanshu1(arr); 
	hanshu2(arr);
	hanshu3(arr1);
	hanshu4(arr1);
	hanshu5(arr2);
	hanshu16(arr2);
	return 0;
}	

				     void hanshu1(int*arr)
{}
void hanshu2(int**arr)
{}
int main()
{
	int a = 10;
	int* arr = &a;
	int** p = &arr;
	int* arr1[10];
	hanshu1(arr);
	hanshu1(&a);
	hanshu2(p);
	hanshu2(&arr);
	hanshu2(arr1);
	return 0;
}	

void hanshu1(const char* p)
{
	printf("%s\n", p);
}
int main()
{
	void (*p)(const char*) = hanshu1;
	(*p)("hello,wolrd");
	hanshu1("hello,world");
	return 0;
}	

int main()
{
	(*(void (*) (int)) 0) (5); 
	//意思是 把 0 强制类型传换成一个函数指针类型，此时的0就是一个函数的地址，然后再进行解引用操作去找到这个函数，之后再调用它
	void (*signal(int, void (*) (int))) (int);
	// 意思是 一个函数声明，这个名叫siganal的函数的参数类型呢是  int，函数指针；
	//这个函数指针指向的函数参数类型是  int;返回值是一个 void类型。siganal函数的返回值也是一个函数指针
	return 0;
}

int ADD(int a,int y)
{
	return (a + y);
}

int main()
{
	int(*pa)(int, int) = ADD;
	printf("%d\n", ADD(2, 3));
	printf("%d\n", pa(2, 3));
	printf("%d\n", ( * ADD)(2, 3));
	printf("%d\n", (*pa)(2, 3));
	return 0;
}

char* my_strcpy(char* dest, const char* src)
{
	return 0;
}
int hs1(int x, int y)
{
	return x + y;
}
int hs2(int x, int y)
{
	return x * y;
}
int hs3(int x, int y)
{
	return x - y;
}
int hs4(int x, int y)
{
	return x / y;
}
int main()
{
	int a = 0;
	char* (*pf)(char*, const char*) = my_strcpy;
	char* (*pfarr[4])(char*, const char*) = { my_strcpy,my_strcpy ,my_strcpy ,my_strcpy };
	int (*pa[4])(int, int) = { hs1,hs2,hs3,hs4 };
	for (a = 0; a < 4; a++)
	{
		printf("%d ", pa[a](10,1));

	}
	return 0;
}

int main()
{
	int a = 0;
	int x = 0;
	int y = 0;
	int (*pa[])(int, int) = { 0,hs1,hs3,hs2,hs4,hs5 };
	do
	{
		menu();
		printf("选择你的算法>:");
	    scanf("%d", &a);
		if (a > 0 && a < 6)
		{
			printf("请输入两个操作数\n");
			scanf("%d%d", &x, &y);
			printf("%d\n", pa[a](x, y));
		}
		else if (a == 0)
		{
			printf("退出\n");
		}
		else
			printf("???????\n");
	} while (a);
	return 0;
}
void test(void(*pa)(const char*))
{
	printf("QWER\n");
	printf("万豪:\n");
	pa("bit");
}

void print(const char* arr)
{
	printf("AAQQ");
}
int main()
{
	test(print);
	return 0;
}
void paixu(int arr[10], int a)
{
	int i = 0;
	for (i = 0; i < a - 1; i++)
	{
		int j = 0;
		for (j = 0; j < a - 1 - i; j++)
		{
			if (arr[j] > arr[j + 1])
			{
				int tmp = arr[j];
				arr[j] = arr[j + 1];
				arr[j + 1] = tmp;
			}
		}
	}
}



int main()
{
	int a = 0;
	int arr[10] = { 9,8,7,4,5,6,3,2,1,0 };
	int sz = sizeof(arr) / sizeof(arr[0]);
	paixu(arr, sz);
	for (a = 0; a < sz; a++)
	{
		printf("%d ", arr[a]);
	}
	return 0;
}
struct stu
{
	char name[20];
	int tizhong;
	float yanjing;
};

int cmp(const void* add, const void* abb)
{
	return ((struct stu*)add)->tizhong - ((struct stu*)abb)->tizhong;
}


int main()
{
	int a = 0;
	struct stu c[3] = { {"zhangsan",5500,5.0 }, {"wnagwu",2200,2.3},{"lisi",1052,5.2}};
	int sz = sizeof(c) / sizeof(c[0]);
	qsort(c, sz, sizeof(c[0]), cmp);
	return 0;
}

struct stu 
{
	char name[20];
	int tizhong;

};

void jiaohuan(char* a, char* b, int kuan)
{
	int i = 0;
	for (i = 0; i < kuan; i++)
	{
		char tmp = *a;
		*a = *b;
		*b = tmp;
		a++; b++;
	}
}
void paixu(void* base, int sz, int kuan, int(*cmp)(void*, void*))
{
	int i = 0;
	for (i = 0; i < sz - 1; i++)
	{
		int j = 0;
		for (j = 0; j < sz - 1 - i; j++)
		{
			if (cmp((char*)base + j * kuan, (char*)base + (j + 1) * kuan)>0)
			{
				jiaohuan((char*)base + j * kuan, (char*)base + (j + 1) * kuan,kuan);
			}
		}
	}
}

int cmp_zhengshu(void* a, void* b)
{
	return *(int*)a - *(int*)b;
}

int cmp_jiegouti_name(void* a, void* b)
{	
	return strcmp(((struct stu*)a)->name,((struct stu*)b)->name);
}

int cmp_jiegouti_tizhong(void* a, void* b)
{
	return ((struct stu*)a)->tizhong - ((struct stu*)b)->tizhong;
}




int main()
{
	int arr[10] = { 9,8,7,4,5,6,3,2,1,0 };
	int sz = sizeof(arr) / sizeof(arr[0]);
	struct stu c[3] = { {"sikadi",4000},{"love",5200},{"AAQQ",6541} };
	int sc = sizeof(c) / sizeof(c[0]);
	paixu(arr, sz, sizeof(arr[0]), cmp_zhengshu);
	paixu(c, sc, sizeof(c[0]), cmp_jiegouti_name);
	paixu(c, sc, sizeof(c[0]), cmp_jiegouti_tizhong);
	return 0;
}
int main()
{
	int a[4] = { 1,2,3,4 };
	printf("%d\n", sizeof(a));//16
	printf("%d\n", sizeof(a+0));//4
	printf("%d\n", sizeof(*a));//4
	printf("%d\n", sizeof(a+1));//4
	printf("%d\n", sizeof(a[1]));//4
	printf("%d\n", sizeof(&a));//4
	printf("%d\n", sizeof(*&a));//16
	printf("%d\n", sizeof(&a+1));//4
	printf("%d\n", sizeof(&a[0]));//4
	printf("%d\n", sizeof(&a[0]+1));//4

	return 0;
}

int main()
{
	char arr[] = { 'a','b','c','d','e','f' };
	printf("%d\n", sizeof(arr));//6
	printf("%d\n", sizeof(arr+0));//4
	printf("%d\n", sizeof(*arr));//1
	printf("%d\n", sizeof(arr[1]));//1
	printf("%d\n", sizeof(&arr));//4
	printf("%d\n", sizeof(&arr+1));//4
	printf("%d\n", sizeof(&arr[0]+1));//4

	return 0;
}

int main()
{
	char arr[] = { 'a','b','c','d','e','f' };
	const char* ret = arr;
	printf("%d\n", strlen(arr));//随机值
	printf("%d\n", strlen(arr + 0));//随机值
	//printf("%d\n", strlen(*arr));//错误代码
	//printf("%d\n", strlen(arr[1]));//错误代码
	printf("%d\n", strlen(*&arr));//随机值
	printf("%d\n", strlen((const char*) & ret + 1));//随机值与上面差6位
	printf("%d\n", strlen(&arr[0]+1));//随机值与上面差1位

	return 0;

}

					void jiafa()
{
	printf("6\n");
}

void jianfa()
{
	printf("6\n");
}

void chengfa()
{
	printf("6\n");
}

void chufa()
{
	printf("6\n");
}

void yihuo()
{
	printf("6\n");
}

int main()
{
	int a = 0;
	int x = 0;
	void(*b[])() = { 0,jiafa,jianfa,chengfa,chufa,yihuo };
	
	do
	{
		menu();
		scanf("%d", &a);
		if (a > 0 && a < 6)
		{
			b[a]();
		}
		else if (a == 0)
			printf("下次再见\n");
		else
			printf("你输入了一个不存在的数字\n");
	}while (a);
	return 0;
}

int main()
{
	char arr[] = "abcdef";

	//printf("%d\n", sizeof(arr));//7
	//printf("%d\n", sizeof(arr+0));//4
	//printf("%d\n", sizeof(*arr));//1
	//printf("%d\n", sizeof(arr[1]));//1
	//printf("%d\n", sizeof(&arr));//4
	//printf("%d\n", sizeof(&arr+1));//4
	//printf("%d\n", sizeof(&arr[0]+1));//4

	printf("%d\n", strlen(arr));//6
	printf("%d\n", strlen(arr + 0));//6
	//printf("%d\n", strlen((const char*) (*arr)));//错误
	//printf("%d\n", strlen((const char*)arr[1]));//错误
	//printf("%d\n", strlen(&arr));//6   在以往的编译器可以运行
	//printf("%d\n", strlen(&arr + 1));//随机值  在以往的编译器可以运行
	printf("%d\n", strlen(&arr[0] + 1));//5

	return 0;
}

int main()
{
	const char *p = "abcdef";

	printf("%d\n", sizeof(p));//4
	printf("%d\n", sizeof(p+1));//4
	printf("%d\n", sizeof(*p));//1
	printf("%d\n", sizeof(p[0]));//1
	printf("%d\n", sizeof(&p));//4
	printf("%d\n", sizeof(&p+1));//4
	printf("%d\n", sizeof(&p[0]+1));//4

	printf("%d\n", strlen(p));//6
	printf("%d\n", strlen(p + 1));//5
	//printf("%d\n", strlen(*p));//错误
	//printf("%d\n", strlen(*p[1]));//错误
	//printf("%d\n", strlen(&p));//随机值  在以往的编译器可以运行
	//printf("%d\n", strlen(&p + 1));//随机值  在以往的编译器可以运行
	printf("%d\n", strlen(&p[0] + 1));//5

	return 0;
}

#include<stdio.h>
int main()
{
   int a,b;

     for(b=0;b<a;b++)
      {   
        if(b==0)
         printf("\n");
        else if(b==1)
         printf("      *\n");
        else if(b==2)
         printf("     **\n");
        else if(b==3)
         printf("    ***\n");
        else if(b==4)
         printf("    **\n");
        else if(b==5)
         printf("   **\n");
      }

   return 0;
}

 int main()
{
	int a[3][4] = { 0 };
	printf("%d\n", sizeof(a));//3*4*4  48
	printf("%d\n", sizeof(a[0][0]));//4
	printf("%d\n", sizeof(a[0]));//16   计算的是第一行的内存大小  4*4  
	                             //a[0]相当于第一行数组的数组名 
	printf("%d\n", sizeof(a[0]+1));//4/8  这是第一行第二个元素的地址
	printf("%d\n", sizeof(*(a[0]+1)));//4
	printf("%d\n", sizeof(a+1));//4/8  这是二维数组的首元素+1，是第二行数组的地址。
	printf("%d\n", sizeof(*(a+1)));//16 计算的是第二行的内存大小
	                               //相当于第二行数组的数组名 
	printf("%d\n", sizeof(&a[0]+1));//4/8  这是第二行的地址 
	printf("%d\n", sizeof(*( & a[0] + 1)));//16第二行内存的大小
	printf("%d\n", sizeof(*a));//16 二维数组第一行的内存大小
	printf("%d\n", sizeof(a[3]));//16  sizeof(表达式)，其中的表达式并不真正运算
	                             //也就是说sizeof(表达式)中的表达式是否真的存在并不重要
	                              // sizeof 只会根据其类型进行计算，而不会去进行表达式的运算

	return 0;
}

 int main()
{
	int a[5] = { 1,2,3,4,5 };
	int* ptr = (int*)(&a + 1);
	printf("%d,%d\n", *(a + 1), *(ptr - 1));
	  // 2  5
	return 0;
}

struct Test
{
	int Num;
	char* pcName;
	short sDate;
	char cha[2];
	short sBa[4];
}*p;
//已知结构体的内存是20个字节
//设p的值为0x100000，求以下的值
int main()
{
	printf("%p\n", p + 0x1);
	printf("%p\n", (unsigned long)p + 0x1);
	printf("%p\n", (unsigned int*)p + 0x1);
	// 00100014  00100001  00100004 
	return 0;
}

#pragma once
#include<stdio.h>
#include<windows.h>
#include<string.h>
#include<time.h>
#include<math.h>
#include<stdlib.h>




void bianhua(int tree[100][100], int a, int x, int y);
void bianhua1(int tree[100][100], int x);
void bianhua2(int tree[100][100], int x, int y);
void chushihua(int xue[100][100],int x,int y);
void xiaxue(int xue[100][100], int y);
void xiaxue2(int xue[100][100], int x, int y);
void HideConsoleCursor(void);

#include"圣诞节.h"


void bianhua(int tree[100][100], int a, int x, int y)
{
	int i = 0;
	int j = 0;
	int rmp = a;
	for (j = 0; j < a; j++)
	{
		for (i = 0; i < a; i++)
		{
			tree[x][y] = 1;
			y++;
		}
		x++;
		y = y - a - 2;
		a += 4;
		if (a == 4 * (rmp - 1) + rmp)
			break;
	}
}

void bianhua1(int tree[100][100], int x)
{
	int i = 0;
	for (i = x; i < 100; i++)
	{
		int j = 0;
		for (j = 0; j < 100; j++)
		{
			tree[i][j] = 0;
		}
	}
}


void bianhua2(int tree[100][100], int x, int y)
{
	int i = 0;
	int rmp = x;
	for (i = 0; i < x; i++)
	{
		tree[x][y] = 1;
		tree[x][++y] = 1;
		tree[x][++y] = 1;
		tree[x][++y] = 1;
		tree[x][++y] = 1;
		x++;
		y = y - 4;
		if (i == rmp)
			break;
	}
}


void chushihua(int xue[100][100], int x, int y)
{
	int i = 0;
	for (i = 0; i < x; i++)
	{
		int j = 0;
		for (j = 0; j < y; j++)
		{
			xue[i][j] = 1;
		}
	}
}


void xiaxue(int xue[100][100], int y)
{
	int i = 0;
	int j = 0;
	for (i = 0; i < y; i++)
	{
		j = rand() % 5;
		xue[0][i] = j;
	}
}


void xiaxue2(int xue[100][100], int x, int y)
{
	int i = 0;
	for (i = x; i >0; i--)
	{
		int j = 0;
		for (j = 0; j < y; j++)
		{
			xue[i][j] = xue[i - 1][j];
		}
	}
}



void HideConsoleCursor(void)
{
	CONSOLE_CURSOR_INFO cursor_info = { 1, 0 };
	SetConsoleCursorInfo(GetStdHandle(STD_OUTPUT_HANDLE),
		&cursor_info);
}


#include"圣诞节.h"


int main()
{
	Sleep(2000);
	int a, b,c,d,e=50,f=0;
	int tree[100][100] = { 0 };
	int xue[100][100] = { 0 };
	HideConsoleCursor();
	srand((unsigned int)time(NULL));
	chushihua(xue, 100, 100);
	system("mode con cols=102 lines=47");
	bianhua(tree, 4, 3, 48);
	bianhua(tree, 7, 6, 47);
	bianhua(tree, 21, 12, 40);
	bianhua1(tree, 17);
	bianhua(tree, 25, 17, 38);
	bianhua1(tree, 25);
	bianhua2(tree, 25, 48);
	tree[24][23] = 1; tree[24][77] = 1;tree[3][47] = 1; tree[5][43] = 1;
	 tree[11][36] = 1; tree[11][64] = 1;tree[0][50] = 1; tree[3][52] = 1;
	 tree[4][53] = 1; tree[4][54] = 1;tree[5][56] = 1; tree[3][53] = 1;
	 tree[4][54] = 1; tree[5][57] = 1;tree[25][47] = 2; tree[26][47] = 2;
	 tree[27][47] = 2; tree[27][46] = 2; tree[28][47] = 2; tree[28][46] = 2;
	 for (d = 1; d < 3; d++)
	 {
		 if (d == 1)
		 {
			 for (c = 48; c <= 52; c++)
			 {
				 tree[d][c] = 1;
			 }
		 }
		 else
		 {
			 for (c = 49; c <= 51; c++)
			 {
				 tree[d][c] = 1;
			 }
		 }
	 }
	 while (e--)
	 {
		 
		 xiaxue(xue, 100);
		 xiaxue2(xue, 70, 100);
		 for (a = 0; a < 40; a++)
		 {
			 
			 /*if (a == 0)
			 {
				 printf("\n");
				 printf("\n");
				 printf("\n");
			 }*/
			 for (b = 0; b < 100; b++)
			 {

				 if (a < 4)
				 {
					 if (a == 1 && b == 50)
						 printf("\033[40;32;5m*\033[1m");
					 else if (a == 2 && b == 50)
						 printf("\033[40;32;5m*\033[1m");
					 else if (a == 3 && b >= 49 && b <= 51)
						 printf("\033[40;32;5m*\033[1m");
					 else if (tree[a][b] == 1)
						 printf("\033[40;33;1m*\033[1m");
					  else if (xue[a][b] == 0)
						 printf("\033[0m*\033[1m");
					 else
						 printf(" ");
				 }
				 else if (a == 25 && b == 41)
				 {
					 printf("\033[40;33;1m||\033[1m");


				 }
				 else if (a == 26 && b == 41)
				 {
					 printf("\033[40;33;1m||\033[1m");
				 }
				 else if (a >= 27 && a <= 28 && b >= 40 && b <= 41)
				 {
					 printf("\033[40;33;1m■\033[1m");
				 }
				 else
				 {
					 if (tree[a][b] == 1)
						 printf("\033[40;32;5m*\033[1m");
					 //else
					 else if (xue[a][b] == 0)
						 printf("\033[0m*\033[1m");
					 else if (tree[a][b] == 0)
						 printf(" ");
				 }
			
			 }
			 printf("\n");
		 } 
		 Sleep(500);
		 system("cls");
	 }
	//xiaxue3(xue, 100, 100);
	//system("pause");



	return 0;
}


int main()
{
	int a[4] = { 1,2,3,4 };
	int *ptr1 = (int *)(&a + 1);//此时这个指针指向 数组a后一个位置
	int *ptr2 = (int *)((int)a + 1);//相当与a数组首元素地址向后移动一个字节
	printf("%x", ptr1[-1]);//等价于 *(ptr-1)  也就是这个位置向后移动一位,再解引用四个字节
	printf(",");           //   0x00 00 00 04
	printf("%x", *ptr2);//从这个位置向后解引用 四个字节 0x02 00 00 00  
	                    //对于十六进制的数字打印时第一个有效数字前的0可以省略
	                    //   4 ，  2 00 00 00
	return 0;
}

					int main()
{
	int a[3][2] = { (0,1),(2,3),(4,5) };
	    //内部是逗号表达式，所以实际上初始化的值是  1，3，5
	int* p;
	p = a[0];
	printf("%d", p[0]);//打印的是第一行第一个元素 1

	return 0;
}

int main()
{
	int a[5][5];
	int(*p)[4];
	p = a;
	printf("%p,%d", &p[4][2] - &a[4][2], &p[4][2] - &a[4][2]);
	//  p[4][2]等价于    *(*(p+4)+2) 
	//p是一个数组指针，+4意味着向后移动四个整型，此时解引用成为一个元素
	//                                       再+2意味着向后移动两个字节
	//p指向a[0][0]，+4后指向 a[3][1]    +2后指向a[3][3]
	// a[4][2]的地址比a[3][3]大4个字节，则结果为 -4
	// 此时当作地址打印的话可以认为打印一个无符号数，
	// 即 1111 1111 1111 1111 1111 1111 1111 1100，每四个1即为一个f
	//     f    f    f    f    f    f    f    c
	// 当作十进制数字打印则为   -4
  	//在老版本编译器可以运行
	return 0;
}

int main()
{
	int a;
	for (a = 300; a > 16; a--)
	{
		if (a % 17 == 0)
			break;
	}
	printf("%d", a);

	return 0;
}

int main()
{   
	int a = 0;
	int b = 1;
	int c = 0;
	int d = 0;
	printf("请输入一个数\n");
	scanf_s("%d", &a);
	for (c = 2; c <= a / 2; c++)
	{
		if (a % c == 0)
			b = b + c;
	}
	

	printf("%d  ", b );

	return 0;
}

int main()
{   
	int aa[2][5] = { 1,2,3,4,5,6,7,8,9,10 };
	int* ptr1 = (int*)(&aa + 1);
	int* ptr2 = (int*)(*(aa + 1));

	printf("%d,%d", *(ptr1 - 1), *(ptr2 - 1));//10   5

	return 0;
}

int main()
{
	const char* a[] = { "work","at","blibaba" };
	const char** pa = a;
	pa++;
	printf("%s\n", *pa);//at

	return 0;
}

int main()
{
	const char* c[] = { "ENTER","NEW","POIMT","FIRST" };
	const char** cp[] = { c + 3,c + 2,c + 1,c };
	const char*** cpp = cp;
	printf("%s\n", **++cpp);//POIMT
	          //++cpp这是一个自增符号，此后cpp原本的值将被改变
	printf("%s\n", *--*++cpp + 3);//ER
	          //此处的++cpp同上
	printf("%s\n", *cpp[-2]+3);//ST
	         // *cpp[-2]+3等价于 *(*(cpp-2))+3  
	         //此处的cpp-2 是运算符号，cpp的值不会被改变
	printf("%s\n", cpp[-1][-1] + 1);//EW
	         // cpp[-1][-1]+1等价于*(*(cpp-1)-1)+1

	return 0;
}

int main()
{
	int a = 0;
	int b = 0;
	int c = 0;
	again:
	a=a+c;
	c++;
	b++;
	if (b <= 100)
		goto again;
	else
		printf("%d", a);
	return 0;
}

int main()
{
	unsigned long pulArray[] = { 6,7,8,9,10 };
	unsigned long* pulptr;

	pulptr = pulArray;
	*(pulptr + 3) += 3;

	printf("%d,%d\n", *pulptr, *(pulptr + 3));//6 //12

	return 0;
}
void nizhuan(char *a)
{
	char* b = a;
	int len = strlen(a);
	char* c = a + len - 1;
	while (b < c)
	{
		char tem = *b;
		*b = *c;
		*c = tem;
		b++;
		c--;
	}

}


int main()
{
	char a[] = "abcdef";
	nizhuan(a);
	printf("%s", a);
	return 0;
}

int main()
{
	int a = 0;
	int n = 0;
	scanf_s("%d%d", &a, &n);
	int sum = 0;
	int i = 0;
	int j = 0;

	for (i = 0; i < n; i++)
	{

	    j = j * 10 + a;
		sum += j;

	}

	printf("%d ", sum);
	return 0;
}

int main()
{
	int n = 0;
	for (n = 0; n <= 100000; n++)
	{
		int j = 1;
		int m = n;
		int sum = 0;
		int tem = n;
		//计算位数
		while (m /= 10)
		{
			j++;
		}
		//每一位数的n次方
		while (tem)
		{
			sum += pow(tem % 10, j);
			tem /= 10;
		}
		//判断相加后是否相等
		if (n == sum)
			printf("%d ", n);

	}

	return 0;
}
int main()
{
	int a = 0;
	int i = 0;
	
	scanf_s("%d", &a);
	for (i = 0; i < a; i++)
	{
		int j = 0;
		for (j = 0; j < a - 1 - i; j++)
		{
			printf(" ");
		}
		for (j = 0; j < 2 * i + 1; j++)
		{
			printf("*");
		}
		printf("\n");
	}
	for (i = 0; i < a - 1; i++)
	{
		int j = 0;
		for (j = 0; j <= i; j++)
		{
			printf(" ");
		}
		for (j = 0; j < 2 * (a - 1 - i) - 1; j++)
		{
			printf("*");
		}
		printf("\n");
	}

	return 0;
}

int main()
{
	int a = 0;
	for (a = 0; a <= 200; a += 7)
	{
		printf("%5d", a);
	}
	printf("\n");
	printf("甭管我咋写出来的，你就说答案对不对吧\n");

	return 0;
}

int SB(int a, int b)
{
	return a+b;
}

int main()
{
	int a = 20;
	int b = 10;
	printf("%d", SB(a,b));

	return 0;
}

struct S
{
	int a;
	int b;
};
int main()
{
	struct S a, * p = &a;
	a.a = 99;
	printf("%d\n", a.a);//a.a  *p.a   p->a  (*p).a 
	return 0;

}
struct stu
{
	int num;
	char name[10];
	int age;
};
void fun(struct stu* p)
{
	printf("%s\n", (*p).name);
	return;
}
int main()
{
	struct  stu students[3] =
	{
		{9801,"zhang",20},
		{9802,"wang",19},
		{9803,"zhao",18},
	};
	fun(students + 1);
	return 0;
}
一瓶汽水1元，两个空瓶换一瓶汽水，现有二十元，可以喝多少汽水；
int main()
{
	int a = 0;
	int b = 0;
	scanf_s("%d", &a);
	if (a > 0)
	b = 2 * a - 1;
	printf("%d", b);
	return 0;
}
					
int main()
{
	int a = 0;
	int b = 0;
	int c = 0;
	scanf_s("%d", &a);
	b = a; c = a;
	while (c >= 2)
	{
		b += c / 2;
		c = (c / 2) + (c % 2);

	}
	printf("%d", b);


	return 0;
}
					
调整奇数偶数，奇数在偶数前面
void print(int arr[13], int sz)
{
	int i = 0;
	for (i = 0; i < sz; i++)
	{
		printf("%d ", arr[i]);
	}
}
void move(int arr[], int sz)
{
	int zuo = 0;
	int you = sz - 1;
	while (zuo < you)
	{//从左边找一个偶数
		while (zuo < you && arr[zuo] % 2 == 1)
		{
			zuo++;
		}
		//从右边找一个奇数
		while (zuo < you && arr[you] % 2 == 0)
		{
			you--;
		}
		if (zuo < you)
		{
			int tem = arr[you];
			arr[you] = arr[zuo];
			arr[zuo] = tem;
		}
	}
}
int main()
{
	int a = 0;
	int arr[] = { 8,6,5,2,1,4,8,96,2,5,7,21,8 };
	int sz = sizeof(arr) / sizeof(arr[0]);
	move(arr,sz);
	print(arr, sz);

	return 0;
}

int main()
{
	unsigned char a = 200; 
	unsigned char b = 100;
	unsigned char c = 0;
	c = a + b;//整型提升
	printf("%d %d", a + b, c);
	// a+b表示300+100  300
	// c=a+b  表示在unsigned char上的第301个数字 44 
	return 0;
}
int main()
{
	unsigned int a = 0x1234;
	//0x00 00 12 34
	unsigned char b = *(unsigned char*)&a;
	//char类型的指针一次访问一个字节
	//小端 34 12 00 00 小的数据放在低地址 大的数据放在高地址
	//大端 00 00 12 34 大的数据放在高地址 小的数据放在低地址
	printf("%d\n", a);
	//00110100  3*16+4
	return 0;
}
//在32位大端模式处理器上变量b等于

int main()
{
	char a[1000] = { 0 };
	int i = 0;
	for (i = 0; i < 1000; i++)
	{
		a[i] = -1 - i;
	}
	printf("%d", strlen(a));
	//char 只能存储 0 --- 127 和 -1 --- -128
	//strlen遇到\0停止，即第一次遇到0的时候停止，则结果为255
	return 0;
}

杨辉三角
int main()
{
	int a = 0;
	scanf_s("%d", &a);
	int i = 0;
	int j = 0;
	int arr[100][100] = { 0 };
	for (i = 0; i < a; i++)
	{
		for (j = 0; j <= i; j++)
		{
			if (j == 0)
				arr[i][j] = 1;
			if (i == j)
				arr[i][j] = 1;
			if (i >= 2 && j >= 1)
				arr[i][j] = arr[i - 1][j] + arr[i - 1][j - 1];
		}
	}
	for (i = 0; i < a; i++)
	{
		for (j = 0; j <= i; j++)
		{
			printf("%d ", arr[i][j]);
		}
		printf("\n");
	}

	return 0;
}

A B C D 其中一个人是凶手，其中三个人说了真话，一个人说了假话
 A:不是我 !=a
 B:是	C   ==c
 C:是	D   ==d
 D：C在胡说  !=d
             1+1+1+0=3
 求凶手

int main()
{
	int a = 0;
	for (a = 'a'; a <= 'd'; a++)
	{
		if ((a != 'a') + (a == 'c') + (a == 'd') + (a != 'd') == 3)
			printf("凶手是%c ", a);

	}
	return 0;
}

int main() 
{
	int a, b, c, d, e;
	for (a = 1; a < 6; a++)
	{
		for (b = 1; b < 6; b++)
		{
			for (c = 1; c < 6; c++)
			{
				for (d = 1; d < 6; d++)
				{
					for (e = 1; e < 6; e++)
					{
						if (((b == 2) + (a == 3) == 1) &&
							((b == 2) + (e == 4) == 1) &&
							((c == 1) + (d == 2) == 1) &&
							((c == 5) + (d == 3) == 1) &&
							((e == 4) + (a == 1) == 1))
						{
							if (a * b * c * d * e == 120)
							/*if (a != b && a != c && a != d && a != e &&
								b != c && b != d && b != e &&
								c != d && c != e &&
								d != e)*/
							printf("a=%d b=%d c=%d d=%d e=%d\n", a, b, c, d, e);
						}
					}
				}
			}
		}

	}
	return 0;
}

int main()
{
	char str1[] = "hello world";
	char str2[] = "hellr world";
	const char* str3 = "hello world";
	const char* str4 = "hello world";
	if (str1 == str2)
		printf("A ");
	else
		printf("C ");
	if (str3 == str4)
		printf("B ");
	else
		printf("D ");

	return 0;
}

int* fun(int a, int b);     函数声明
int(*)fun(int a, int b);    错误书写
int(*fun)(int a, int b);    函数指针
(int*)fun(int a, int b);    函数声明
					
设置一个函数指针指向形参为两个int，返回值为一个函数指针，返回的指针指向的函数的形参是一个int返回值是int 
aint (*(*arr(int,int)))(int)

	
void ercichushihua(int xue[100][100],int a,int b, int x, int y)
{
	int i = 0;
	int j = 0;
	for (i = x; i <= x + a; i++)
	{
		for (j = y; j <= y + b; j++)
		{
			 xue[i][j] = 3;
		}
	}
}

#include<stdio.h>
#include<string.h>
#include<windows.h>
#include<math.h>
#include<time.h>
#include<stdlib.h>
//从main函数开始看
void again1(int zuobian[], int sz, int a)//此处函数用来完成功能的第三个要求
{                                        //参数分别是 电梯，总层数，用户选择的层数
    int x = 0;
    for (x = 0; x < sz; x++)//循环搜索
    {
        if (zuobian[x] == a)//找到则停止
        {
            printf("到达目标层数\n");
            break;
        }
        else           //没有找到则打印当前楼层
            Sleep(1000);
        printf("当前楼层：%d\n", zuobian[x]);
    }
}
void again2(int youbian[], int sz, int a)//与上方同理，此处表示右边电梯
{
    int y = 0;
    for (y = 0; y < sz; y++)
    {
        if (youbian[y] == a)
        {
            printf("到达目标层数\n");
            break;
        }
        else
            Sleep(1000);
        printf("当前楼层：%d\n", youbian[y]);
    }
}
int main()
{
    int a = 0;
    int b = 0;
    int zuobian[] = { 1,2,7,8,9 };//
    int youbian[] = { 2,6,7,8,9 };//两个电梯的初始化
    int sz = sizeof(zuobian) / sizeof(zuobian[0]);//
    int sz2 = sizeof(youbian) / sizeof(youbian[0]);//数组元素个数的计算
    do           //因为最起码要做一次电梯，所以使用  do while 
    {
        printf("1.左边           2.右边\n");
        printf("请问你想使用那边的电梯?\n");//设置左右电梯
        scanf_s("%d", &b);
        printf("请输入你想要到达的楼层\n");
        printf("   如果不需要请输入  0 \n");//设置楼层
        scanf_s("%d", &a);
        if (b == 1)//多分支来表示不同的选择，其实可以选择switch
        {
            int i = 0;
            for (i = 0; i < sz; i++)//循环搜索
            {
                if (zuobian[i] == a)//判断用户选择的楼层是否存在
                {
                    again1(zuobian, sz, a);//存在则进入这个函数
                    break;
                }
            }
            if (i == sz)//不存在则这里 i 会等于 sz
            {
                printf("这个电梯不能满足要求\n");//给用户提示
            }
        }
        else if (b == 2)
        {
            int i = 0;
            for (i = 0; i < sz2; i++)//与上方同理，这里表示右边电梯
            {
                if (youbian[i] == a)
                {
                    again2(youbian, sz2, a);
                    break;
                }
            }
            if (i == sz2)
            {
                printf("这个电梯不能满足要求\n");
            }

        }
        else//这个相当于swicth中的defaluct，用来表示用户瞎几把选的时候
            printf("抱歉，电梯到不了这个层数\n");
    } while (a);

    return 0;
}

#include"圣诞节.h"


void bianhua(int tree[100][100], int a, int x, int y)
{
	int i = 0;
	int j = 0;
	int rmp = a;
	for (j = 0; j < a; j++)
	{
		for (i = 0; i < a; i++)
		{
			tree[x][y] = 1;
			y++;
		}
		x++;
		y = y - a - 2;
		a += 4;
		if (a == 4 * (rmp - 1) + rmp)
			break;
	}
}

void bianhua1(int tree[100][100], int x)
{
	int i = 0;
	for (i = x; i < 100; i++)
	{
		int j = 0;
		for (j = 0; j < 100; j++)
		{
			tree[i][j] = 0;
		}
	}
}


void bianhua2(int tree[100][100], int x, int y)
{
	int i = 0;
	int rmp = x;
	for (i = 0; i < x; i++)
	{
		tree[x][y] = 3;
		tree[x][++y] = 3;
		tree[x][++y] = 3;
		tree[x][++y] = 3;
		tree[x][++y] = 3;
		x++;
		y = y - 4;
		if (i == rmp)
			break;
	}
}


void chushihua(int xue[100][100], int x, int y)
{
	int i = 0;
	for (i = 0; i < x; i++)
	{
		int j = 0;
		for (j = 0; j < y; j++)
		{
			xue[i][j] = 1;
		}
	}
}


void xiaxue(int xue[100][100], int y)
{
	int i = 0;
	int j = 0;
	for (i = 0; i < y; i++)
	{
		j = rand() % 5;
		xue[0][i] = j;
	}
}


void xiaxue2(int xue[100][100], int x, int y)
{
	int i = 0;
	for (i = x; i >0; i--)
	{
		int j = 0;
		for (j = 0; j < y; j++)
		{
			if (j + 1 < y)
				xue[i][j] = xue[i - 1][j + 1];
			else
				xue[i][j] = xue[i - 2][j + 1];
		}
	}
}



void HideConsoleCursor(void)
{
	CONSOLE_CURSOR_INFO cursor_info = { 1, 0 };
	SetConsoleCursorInfo(GetStdHandle(STD_OUTPUT_HANDLE),
		&cursor_info);
}



void ercichushihua(int xue[100][100],int a,int b, int x, int y)
{
	int i = 0;
	int j = 0;
	for (i = x; i <= x + a; i++)
	{
		for (j = y; j <= y + b; j++)
		{
			 xue[i][j] = 3;
		}
	}
}
#include"圣诞节.h"


int main()
{
	//Sleep(2000);
	int a, b,c,d,e=500,f=0;
	int tree[100][100] = { 0 };
	int xue[100][100] = { 0 };
	HideConsoleCursor();
	srand((unsigned int)time(NULL));
	chushihua(xue, 100, 100);
	system("mode con cols=102 lines=48");
	bianhua(tree, 4, 3+4, 48);bianhua(tree, 7, 6+4, 47);bianhua(tree, 21, 12+4, 40);
	bianhua1(tree, 17+4);bianhua(tree, 25, 17+4, 38);
	bianhua1(tree, 25+4);bianhua2(tree, 25+4, 48);
	tree[24+4][23] = 1; tree[24+4][77] = 1;tree[3+4][47] = 1; tree[5+4][43] = 1;
	 tree[11+4][36] = 1; tree[11+4][64] = 1;tree[0+4][50] = 1; tree[3+4][52] = 1;
	 tree[4+4][53] = 1; tree[4+4][54] = 1;tree[5+4][56] = 1; tree[3+4][53] = 1;
	 tree[4+4][54] = 1; tree[5+4][57] = 1;tree[25+4][47] = 2; tree[26+4][47] = 2;
	 tree[27+4][47] = 2; tree[27+4][46] = 2; tree[28+4][47] = 2; tree[28+4][46] = 2;
	 tree[38][60] = 2; tree[38][61] = 2; tree[39][60] = 2; tree[39][61] = 2;
	 for (d = 1+4; d < 3+4; d++)
	 {
		 if (d == 1+4)
		 {
			 for (c = 48; c <= 52; c++)
			 {
				 tree[d][c] = 1;
			 }
		 }
		 else
		 {
			 for (c = 49; c <= 51; c++)
			 {
				 tree[d][c] = 1;
			 }
		 }
	 }
	 while (e--)
	 {
		 
		 xiaxue(xue, 100);
		 xiaxue2(xue, 70, 100);
		 ercichushihua(xue, 4, 10, 27 , 44);
		 for (a = 0; a < 45; a++)
		 {	
			 for (b = 0; b < 100; b++)
			 {
				 if (a < 8)
				 {
					 if (a == 4 && b == 50)
						 printf("\033[40;33;5m*\033[1m");
					 else if (a == 1 + 4 && b == 50)
						 printf("\033[40;32;5m*\033[1m");
					 else if (a == 2 + 4 && b == 50)
						 printf("\033[40;32;5m*\033[1m");
					 else if (a == 3 + 4 && b >= 49 && b <= 51)
						 printf("\033[40;32;5m*\033[1m");
					 else if (tree[a][b] == 1)
						 printf("\033[40;33;1m*\033[1m");
					 else if (xue[a][b] == 0)
						 printf("\033[0m*\033[1m");
					 else
						 printf(" ");
				 }
				 else if (a == 25+4 && b == 41)
				 {
					 printf("\033[40;33;1m||\033[1m");
				 }
				 else if (a == 26+4 && b == 41)
				 {
					 printf("\033[40;33;1m||\033[1m");
				 }
				 else if (a >= 27+4 && a <= 28+4 && b >= 40 && b <= 41)
				 {
					 printf("\033[40;33;1m■\033[1m");
				 }
				 else
				 {
					 if (tree[a][b] == 1)
						 printf("\033[40;32;5m*\033[1m");
					 else if (tree[a][b] == 3)
						 printf("\033[40;33;1m*\033[1m");
					 else if (xue[a][b] == 0)
						 printf("\033[0m*\033[1m");
					 else if (tree[a][b] == 0 )
						 printf(" ");
				 }
			
			 }
			 printf("\n");
		 } 
		 Sleep(500);
		 system("cls");
	 }
	//xiaxue3(xue, 100, 100);
	//system("pause");



	return 0;
}
void mian()
{
}

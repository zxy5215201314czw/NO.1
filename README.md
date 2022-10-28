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

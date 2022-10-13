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

	
	
	
	
	
	
	
	
	
	
	
	
	
	

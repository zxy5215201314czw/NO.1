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

# -for
for的循环练习题，掌握for的循环




int main()
{
	int i = 0;
	int n = 0;
	int ret = 1;    //ret作为初始值不能为零
	scanf("%d", &n);
	for (i = 1; i <= n; i++)
	{
		ret = ret * i;
	}
	printf("ret =%d\n", ret);
	return 0;
}
//阶乘计算（一）



1！+2！+...10！
int main()
{
	int i = 0;
	int n = 0;
	int ret = 1;
	int sum = 0;
	for (n = 1; n <=3; n++)  
		//第二个n是计算多少的阶乘
	{
		ret = ret * n;
		sum = sum + ret;
	}
	printf("sum=%d\n", sum);
	return 0;
}

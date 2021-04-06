# the-second-meet-of-c
C语言的再次学习
//9*9乘法口诀表的打印
int main()
{
	int i, j;
	int mul = 0;
	for (i=1; i <= 9; i++)
	{
		j = 1;
		for (j; j <= i; j++)
		{
			mul = i * j;
			printf("%d*%d=%-2d ", i,j,mul);
		}
		printf("\n");



	}

	return 0;
}

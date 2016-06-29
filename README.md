# File01
first creation
#include<stdlib.h>
int main()
{
	FILE *fp1;
	char a;
	fp1=fopen("export.gpx","r");
	if(fp1==NULL)
	{
		printf("读取文件错误");
		return 0;
	}
	else
	{
		a=fgetc(fp1);
		while(a!=EOF)
		{
			printf("%c",a);
			a=fgetc
			(fp1);
			
		}
		fclose(fp1);
		
	}
	return 0;
}

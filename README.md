
# Game - A - Thon : Introduction to Git And Github


## Name : Bhushan Surjuse

### Problem Statement 1: Write a program to print the following pattern.


>$$$$$ <br> $$$$ <br> $$$ <br> $$ <br> $

### Program

```
#include<stdio.h>
int main()
{
	for(int i=0;i<5;i++)
	{
		for(int j=5;j>i;j--)
		{
			printf("$");
		}
		printf("\n");
	}
	return 0;
}
```
### Output

![Output](https://github.com/04Bhushan/Game-A-Thon-Task2-/blob/main/Pattern1_Output.jpg)


### Problem Statement 2: Write a program to print the following pattern.


>$$$$$ <br>   &nbsp; $$$$ <br> &nbsp; &nbsp; $$$ <br>  &nbsp; &nbsp; &nbsp; $$ <br> &nbsp; &nbsp;&nbsp; &nbsp; $

### Program

```
#include<stdio.h>
int main()
{

	for(int i=0;i<5;i++)
	{
		for(int k=1;k<=i;k++)
		{
			printf(" ");
		}
		for(int j=5;j>i;j--)
		{
			printf("$");
		}
		printf("\n");
	}
	return 0;
}
```

### Output

![Output](https://github.com/04Bhushan/Game-A-Thon-Task2-/blob/main/Pattern2_Output.jpg)



### Problem Statement 3: Write a program to print the following pattern.


> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; $ <br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; $$$ <br> &nbsp;&nbsp;&nbsp;&nbsp; $$$$$ <br> &nbsp;&nbsp;&nbsp; $$$$$$$ <br> &nbsp;&nbsp; $$$$$$$$$

### Program

```
#include<stdio.h>
int main()
{
	for(int i=1;i<=5;i++)
	{
		for(int j=5;j>i;j--)
		{
			printf(" ");
		}
		for(int k=1;k<=i;k++)
		{
			printf("$");
		}
		int n=i;
		for(int x=1;x<n;x++)
		{
			printf("$");
		}
		printf("\n");
	}
	return 0;
}
```

### Output

![Output](https://github.com/04Bhushan/Game-A-Thon-Task2-/blob/main/Pattern3_Output.jpg)


# #include<stdio.h>
#include<string.h>
#include<stdlib.h>
#include "functions.h"

int main(int argc, char **argv)
{
 int oko = atoi(argv[argc - 1]);
	for(int i = 1; i < argc -1; i++)
	{
 if (jedna je == 1)
		{
			all_caps(argv[i]);
		}
 else if (комонтарија == 2)
		{
			sort_letters(argv[i]);
		}
 else if (комонтарија == 3)
		{
			no_numbers(argv[i]);
		}
 else if (комонтарија == 4)
		{
			palindrom(argv[i]);
			printf("\n");
		}
	}
}

# Code3

# include <stdio.h>
# include <math.h>
void primeFactors(int n,int count)
{
	while (n%2 == 0 && count>=2)
	{
		printf("%d ", 2);
		n = n/2;
	}
  if (n/2!=0)
  printf("Invalid number");
	for (int i = 3; i <= sqrt(n); i = i+2)
	{
		while (n%i == 0)
		{
			printf("%d ", i);
			n = n/i;
		}
	}
	if (n > 2)
		printf ("%d ", n);
}


int main()
{  
  int n ,m ,count=0;
	printf("enter the number \n");
  scnf("%d",n);
	primeFactors(n);
	return 0;
 while (n != 0) {
        n /= 10;     // n = n/10
        ++count;
    }
    printf("Number of digits: %d", count);
}
if (count<2)
printf("Enter 2 digit number:);
}

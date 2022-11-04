#include<stdio.h>	
int main() {


	int sayi ,i=2;

	

	for (;;)
	{//1 e ve kendinden başka sayiya bölünmeyen sayilar 1 2 3 5 7 9
		printf("Lutfen sayi giriniz:(Cikmak icin -1 bas lan) ");
		scanf_s("%d", &sayi);
		if (sayi==-1)
		{
			
			break;
		}
		else if (sayi<-1||sayi==0)
		{
			printf("Lutfen dogru degerler giriniz\n ");
		}
		else if (sayi==2||sayi==3||sayi==1)
		{
			printf("Sayiniz asaldir\n");
		}
		else
		{


			for (i = 2; i < sayi; i++)
			{

				if (sayi % i != 0 && sayi % 3 != 0)
				{

					printf("Sayiniz asaldir\n");
					break;

				}
				else
				{
					printf("Sayiniz asal degildir\n");
					break;
				}

			}

		}
		
	}


//------------------------------------------------------------------------------------------
	printf("Lutfen sayi giriniz:(Cikmak icin -1 bas lan) ");
		scanf_s("%d", &sayi);
		
		

		for (int i = 2; i <sayi; i++)
		{
			if (sayi%i==0)
			{
				asalmi++;
			}
		}
		if (asalmi==0)
		{
			printf("Sayiniz asal\n");
		}
		else
		{
			printf("Sayiniz asal degil\n");
		}
		


}

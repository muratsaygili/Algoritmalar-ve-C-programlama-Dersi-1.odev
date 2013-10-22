#include <stdio.h>
#include <stdlib.h>

void cozumleme(int sayi)
{
	int a, binlik, yuzluk, onluk, birlik;
	a = sayi;
	{
		binlik = a / 1000;
		a -= binlik * 1000;
		yuzluk = a / 100;
		a -= yuzluk * 100;
		onluk = a / 10;
		a -= onluk * 10;
		birlik = a / 1;
		a -= birlik * 1;
		printf("\nBinlik = %d", binlik);
		printf("\nYuzluk = %d", yuzluk);
		printf("\nOnluk    = %d", onluk);
		printf("\nBirlik   = %d\n", birlik);
	}
	/* return deyimi yok !*/
}
int main()
{
	int miktar;
	printf("Cozumlenmesini istediginiz sayi = ");
	scanf_s("%d", &miktar);
	cozumleme(miktar);  /* fonksiyon bir degiskene atanmamis ! */
	printf("Cikmak icin bir tusa basiniz . . . = ");
	system("pause");
	return 0;
}

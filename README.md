# pozitif-negatif-sifir#include <stdio.h>
#include <stdlib.h>

/* run this program using the console pauser or add your own getch, system("pause") or input loop */

int main() {
	int sayi;
	while(1)
	{
	
	printf("Bir sayi giriniz: ");
	scanf("%d",&sayi);
	
	if(sayi == 999)
	break;
	
	if (sayi > 0)
	{
		printf("Girmis oldugunuz sayi pozitiftir.\n");
	}
	
	if (sayi < 0)
	{
		printf("Girmis oldugunuz sayi negatiftir.\n");
	}
	
	if (sayi == 0)
	{
		printf("Girmis oldugunuz sayi sifirdir.\n");
	}
}
	return 0;
	}

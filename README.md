tugas-algoritma
===============

tugas D3 manajemen informatika

#include <stdio.h>                                  
#include <conio.h>
#include <stdlib.h>

int main()
{
   int pilih;
	float celcius, reamur, farenheit;

   celcius=0;
   printf("-------------------- by choiruddin D3 manajemen informatika-------------------""\n");
	printf("konversi suhu dari derajat celcius ke reamur dan farenheit""\n""\n""nilai yang ingin dikonversi dari celcius : ");

   printf("\n""1.	celcius ke farenheit""\n");
   printf("\n""2.	celcius ke reamur""\n""\n");
   printf("\n" "silahkan pilih kawan  :" );scanf("%d", &pilih);

switch(pilih){
case 1:
   {printf("\n""1.	celcius ke farenheit ");
   printf("\n""masukan suhu : ");

   scanf("%f",&celcius);
   farenheit=celcius*1.8+32;
   printf("\n");
   printf("jadi %2.1f derajat Celcius sama dengan : ""\n""\n"" %2.1f derajat Farenheit",celcius,farenheit,reamur);
   printf("\n""\n""Terima Kasih, Tekan sembarang untuk keluar");
	getch();
	return 0;
}
 case 2:
 	 celcius=0;
    {printf("\n""1.	celcius ke reamur");
    printf("\n""masukan suhu : ");
   scanf("%f",&celcius);
   reamur=celcius*0.8;
   farenheit=celcius*1.8+32;
   printf("\n");
   printf("jadi %2.1f derajat Celcius sama dengan : ""\n""\n""\n""- %2.1f derajat Reamur",celcius,farenheit,reamur);
   printf("\n""\n""Terima Kasih, Tekan sembarang untuk keluar");
	getch();
	return 0;
}
}}

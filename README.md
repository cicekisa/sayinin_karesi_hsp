# sayinin_karesi_hsp
// Verilen bir sayının karesini hesaplayan algoritmayı yazınız.

#include <stdio.h>

int main(){
int sayi,sonuc=0;
printf("bir sayi giriniz: ");
scanf("%d",&sayi);

sonuc = sayi * sayi;
printf("girilen sayinin karesi:%d\n",sonuc);


return 0;
}

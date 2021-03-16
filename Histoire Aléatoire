#include <stdio.h>
#include <stdlib.h>
#include <time.h>
#include <string.h>

// Site pour listes chaînées = 
// https://openclassrooms.com/fr/courses/19980-apprenez-a-programmer-en-c/19733-les-listes-chainees

struct Elements {
      char Adjour[100];    char Nmm[100];   char EtatP[100];   char Perip1[100];   char But[100];  char Perip2[100];
      char SNomP[100];     char Perso[100];   char Event[100];     int Nbj;     int Nba;    
};

int main() {

struct Elements SNK;

      strcpy(SNK.Adjour, "cette époustouflante");
      SNK.Nbj = 20;
      strcpy(SNK.Nmm, "Avril");
      SNK.Nba = 845;

      strcpy(SNK.SNomP, "\"l'idiot suicidaire\"\n");
      strcpy(SNK.But, "son obsession aveugle pour l'éradication des titans.");
      strcpy(SNK.Perso, "d'un combattant");

      strcpy(SNK.EtatP, "enfant");
      strcpy(SNK.Event, "n'ayant absolument rien changé à sa vie");
      strcpy(SNK.Perip1, "Il a observé sa mère se faire dévorer vivante par un titan, alors que son père était porté disparu depuis peu");
      strcpy(SNK.Perip2, "Il a go muscu + drague de rue");

struct Elements Wakfu;

      strcpy(Wakfu.Adjour, "cette étrange");
      Wakfu.Nbj = 20;
      strcpy(Wakfu.Nmm, "Avril");
      Wakfu.Nba = 845;

      strcpy(Wakfu.SNomP, "\"l'idiot suicidaire\"\n");
      strcpy(Wakfu.But, "son obsession aveugle pour l'éradication des titans.");
      strcpy(Wakfu.Perso, "d'un combattant");

      strcpy(Wakfu.EtatP, "enfant");
      strcpy(Wakfu.Event, "n'ayant absolument rien changé à sa vie");

       
      strcpy(Wakfu.Perip1, "Il a observé sa mère se faire dévorer vivante par un titan, alors que son père était porté disparu depuis peu");
      strcpy(Wakfu.Perip2, "Il a go muscu + drague de rue");      

printf("\nEn %s journée du %d %s %d, nous allâmes vous raconter l'histoire %s surnommé %sà cause de %s \n", SNK.Adjour, SNK.Nbj, SNK.Nmm, SNK.Nba, SNK.Perso, SNK.SNomP, SNK.But);
printf("\nTout a commencé lorsqu'il était %s, et qu'il ait assisté à des événements %s : \n\n   - %s \n   - %s", SNK.EtatP, SNK.Event, SNK.Perip1, SNK.Perip2);

printf("\n\n test");

int my_rand (void);

            
            static int first = 0;
            
            if (first == 0)
            {
                srand (time (NULL));
                first = 1;
            }

   int i;

 printf("   Nombres pseudoaléatoires : \n \n ");
   for (i = 0; i<10; i++)
   {
     printf ("%d ", my_rand());
   }
   return (EXIT_SUCCESS);
}

int my_rand (void)
{
   return (rand ());
} 

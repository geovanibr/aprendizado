aprendizado
===========

Código em C - converter dias em anos 
#include <stdio.h>
int main ()
{
		int Dias;
		float Anos;
		printf ("Entre com o numero de dias: ");
		scanf ("%d",&Dias);
		Anos=Dias/365.25;
		printf ("\n\n%d dias equivalem a %f  anos.\n,",Dias,Anos);
		return(0);
}

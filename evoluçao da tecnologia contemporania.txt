#include <stdio.h>
#include <math.h>
#include <stdlib.h>

int main ()
{
	//variaveis
	int idade ; //representa idade
	int sn; //gostou da exposicao
	float oa; //oque voce aprendeu com a exposicao
    float pn; //porque nao gostou 
	
	
	printf("\t===============================================\n");
		
		printf("\t===============================================\n");
		
		printf("\t======Evolucao da Tecnologia contemporanea=====\n");
	
		printf("\t===============================================\n");
		
		printf("\t===============================================\n\n");
		
		printf("\t-----------------------------------------------\n");
		
		printf("\t----------------------------------------------\n");
		
		
		
	//recolhimento de idade 
	printf("Digite sua idade:  \n");
	scanf ("%d" ,&idade);
	
	
	
	 //gostou da visita 
	printf("voce gostou da exposicao \n");
		printf("\t  [1]: SIM \n");
	printf("\t  [2]: NAO \n");
	
	scanf ("%d" ,&sn);
	

if (sn==2)
{
	printf("Porque nao gostou ? \n");
	
	scanf("%f" ,&pn);
		printf("\n");
 	
	
	printf("Obrigado pela sua opniao, ela e muito importante para nos. \n");
	
		printf("Obrigado pela visita, volte sempre .  \n");
}
 
 printf ("\n");
 
 
 if (sn==1)
 
 {
 	printf("Oque voce aprendeu com a exposicao ? \n");
 	
 	
 	scanf("%f" ,&oa);
 	printf("\n");
 	
 printf("Obrigado pela sua opniao, ela e muito importante para nos. \n");
 printf("Obrigado pela visita, volte sempre .  \n");
 }


printf ("\n");



		system ("pause");
return 0;
}	
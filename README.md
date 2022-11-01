# algoritmo-l
Media aprovado//

#include<stdio.h>
float n1,n2,media;
//comando de entrada
int main(){
	printf("digite o numero1\n");
	scanf("%f",&n1);
	printf("digite o numero 2\n");
	scanf("%f",&n2);
	media=(n1+n2)/2;
	if(media>=6)
	printf("aluno aprovado nota : %.2f\n",media);
	else {
printf("aluno reprovado nota : %.2f\n",media);
	}

	
	
	
	
	
	return 0;
}


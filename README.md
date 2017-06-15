#include<stdio.h>

#include<math.h>


int main(void){
int l,c;
float matriz [200][3];//, filial1[100][4] , filial2[50][4];  //5 pedidos para cada coluna//(hamburguer)


for(l=0;l<1;l++){
for(c=0;c<4;c++){
	

	printf("Cliente %d\nInforme a quantidade de hamburguers de numero %d:\n",l+1,c+1);
	scanf("%d",matriz[l][c]);
	
	//if(){
	//		printf("No maximo 5 pedidos");
	//		c--;                                        // se matriz c >6 e a soma das matrizes for 0 da erro
	
	//}
	
}
}
for(l=0;l<1;l++){
for(c=0;c<4;c++){
		printf("%f",matriz[l][c]);
}}

return 0;
}

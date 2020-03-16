# P-s-aula-ponteiros
 #include<stdlib.h>
 #include<stdio.h>

//Exercicio LETRA A código feito e compilado como pedido
int main (void){
	int x = 2, y = 3;  //Exercicío LETRA B resposta: Não são variáveis do tipo ponteiro, se fosse teria que está sendo declarada int *px = 2, *py = 3
	int z = x + y;
	
	printf("Os enderecos das variaveis sao:\n"); //Exercicio LETRA F resposta: 
	printf("x = %d\n", &x);	// x = 6487628
	printf("y = %d\n", &y); // y = 6487624
	printf("z = %d\n", &z); // z = 6487620
	printf("\n");
	
	printf("Os enderecos das variaveis sao:\n");
	printf("x = %d\n", x);	
	printf("y = %d\n", y);
	printf("z = %d\n", z);
	printf("\n");
	
	int *px = &x;  //Exercicio LETRA D resposta: Estão declarando variável inteiro do tipo ponteiro 
	int *py = &y;  //Exercício LETRA E resposta: se tiver essa sintaxe " int *px = x; " ao compilar deu " py não foi declarado neste escopo 
	int *pz = &z;
	
	printf("Os enderecos dos ponteiros sao:\n"); //Exercicio letra H resposta: Endereço são px, py e pz
	printf("&px = %d\n", &px); 
	printf("&px = %d\n", &py);
	printf("&px = %d\n", &pz);	
	printf("\n");
	
	printf("Os valores dos ponteiros sao:\n");
	printf("px = %d\n", *px);
	printf("py = %d\n", *py);
	printf("pz = %d\n", *pz);
	printf("\n");
	
	printf("Os valores apontados pelos ponteiros sao:\n"); //Exercicio Letra I resposta: Eles vão mostrar os valores mostrados dos ponteiros *px = 2, *py= 3 e *pz = 5 
	printf("*px = %d\n", *px);
	printf("*py = %d\n", *py);
	printf("*pz = %d\n", *pz);
	printf("\n");
	
	system ("pause");
	return (0);
	
	
}
 

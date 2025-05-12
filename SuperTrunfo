#include<stdio.h>
#include<stdlib.h>
#include<time.h>
#include<locale.h>

int main(void){
setlocale(LC_ALL, "");

int opcao;

printf("Bem vindo ao Super Trunfo\n");
printf("\nEscolha uma opçao a baixo \n");
printf("\n 1- Iniciar\n ");
printf("\n 2- Como jogar\n ");
printf("\n 3- Sair\n ");
printf("\nDigite o numero da opçao selecionada\n");
scanf ("%d", &opcao);
system("cls");

switch(opcao){
    case 1:
    printf("\n Vamos comecar \n");

     char codigo[8],nome[40];
     float area,populacao,pibi;
     int npt;

     printf("Carta 01\n");


     printf("Digite um código: ");
     scanf("%s", codigo);

     printf("Nome da cidade: ");
     scanf(" %s", nome);

     printf("Qual a populaçao: ");
     scanf(" %f", &populacao);

     printf("Qual a área em km2: ");
     scanf(" %f", &area);

     printf("Número de pontos turisticos: ");
     scanf("%d", &npt);

     printf("Qual o PIB: ");
     scanf("%f", &pibi);

     system("cls");

     printf("Carta 02\n");

     char codigo2[3],nome2[30];
     int npt2;
     float area2,populacao2,pibi2;


     printf("Digite um código: ");
     scanf("%s", codigo2);

     printf("Nome da cidade: ");
     scanf("%s", nome2);

     printf("Qual a populaçao: ");
     scanf("%f", &populacao2);

     printf("Qual a área em km2: ");
     scanf("%f", &area2);

     printf("Número de pontos turisticos: ");
     scanf("%d", &npt2);

     printf("Qual o PIB: ");
     scanf("%f", &pibi2);

     system("cls");

     printf("CARTA 01\n");
     printf("Código: %s\n", codigo);
     printf("Cidade: %s\n", nome);
     printf("Populaçao: %.3f\n", populacao);
     printf("Área em km2: %.3f\n", area);
     printf("Pontos Turisticos: %d\n", npt);
     printf("PIB: %.3f\n", pibi);

     printf("\nCARTA 02\n");
     printf("Código: %s\n", codigo2);
     printf("Cidade: %s\n", nome2);
     printf("Populaçao: %.3f\n", populacao2);
     printf("Área em km2: %.3f\n", area2);
     printf("Pontos Turisticos: %d\n", npt2);
     printf("PIB: %.3f\n", pibi2);

     int atributo;

     printf("\n Agora vamos decidir qual atributo será comparado\n");
     printf("1- Populaçao\n");
     printf("2- Área\n");
     printf("3- Número de pontos turisticos\n");
     printf("4- PIB\n");

     srand(time(0));
     atributo = rand() % 4+1;
     printf("\n Atributo %d\n", atributo);

        switch(atributo){
            case 1:
            printf("\n Populaçao\n");
            printf("%.3f vs %.3f", populacao, populacao2);
                if(populacao > populacao2){
                printf("Parabéns, jogador 01 é o vencedor");
                }
                else if(populacao < populacao2){
                printf("Parabéns, jogador 02 é o vencedor");
                }
                else{
                printf("Voces empataram");
                }
break;
            case 2:
            printf("\n Área\n");
            printf("%.3f vs %.3f", area, area2);
                if(area > area2){
                printf("Parabéns, jogador 01 é o vencedor");
                }
                else if(area < area2){
                printf("Parabéns, jogador 02 é o vencedor");
                }
                else{
                printf("Voces empataram");
                }
break;
            case 3:
            printf("\n Número de pontos turisticos\n");
            printf("%d vs %d", npt, npt2);
                if(npt > npt2){
                printf("Parabéns, jogador 01 é o vencedor");
                }
                else if(npt < npt2){
                printf("Parabéns, jogador 02 é o vencedor");
                }
                else{
                printf("Voces empataram");
                }
break;
            case 4:
            printf("\n PIB\n");
            printf("%.3f vs %.3f", pibi, pibi2);
                if(pibi > pibi2){
                printf("Parabéns, jogador 01 é o vencedor");
                }
                else if(pibi < pibi2){
                printf("Parabéns, jogador 02 é o vencedor");
                }
                else{
                printf("Voces empataram");
                }
break;
        }

     return 0;
break;
    case 2:
    printf("\n Regras do jogo\n");
break;
    case 3:
    printf("\n Saindo do jogo\n");
    getchar();
    system("cls");
break;
}

}

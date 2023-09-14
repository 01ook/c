#include <stdio.h>
#include <stdlib.h>

/*int main(){
    printf("o codigo ira fazer somas basicas.\n por favor digite os numero que deseja somar!\n");
    int a, b, c;
    scanf("%d", &a);
    scanf("%d", &b);
    c = a + b;
    printf("a soma de %d mais %d e igual a %d\n.", a, b, c);
    return 0;
}
*/

int main(){
    int escolha;
    double a, b, resultado;
    printf("escolha o que deseja:\n");
    printf("1 - soma\n");
    printf("2 - subtracao\n");
    printf("3 - multiplicacao\n");
    printf("4 - divisao\n");
    scanf("%d", &escolha);

    printf("digite o primeiro numero:");
    scanf("%lf", &a);
    printf("digite o segundo numero:");
    scanf("%lf", &b);

    switch (escolha){
        case 1:
            resultado = a + b;
            printf("O resultado da soma: %lf\n", resultado);
            break;
        case 2:
            resultado = a - b;
            printf("O resultado da subtracao e: %lf\n", resultado);
            break;
        case 3:
            resultado = a * b;
            printf("O resultado da multiplicacao e: %lf\n", resultado);
            break;
        case 4:
            if (b != 0) {
                resultado = a / b;
                printf("O resultado da soma: %lf\n", resultado);
            } else {
                printf("zero nao e divisivel");
            }
            break;
        default:
            printf("nao e uma opcao selecionavel");
            break;
            }
    return 0;
}

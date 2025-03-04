/* vamos escrever um programa para a função seno de 0 a 1
math.h (para funções matematicas)


*/

#include <stdio.h>
#include <math.h>


int main()

{ 

  double x, resultado;  // Declara as variáveis x e resultado

  // Solicita a entrada do usuário
  printf("Digite um valor entre 0 e 1 (0<x<1): ");
  scanf("%lf",&x);

  // Verifica se x está no intervalo (0, 1)
  if (x > 0 && x < 1) {
        resultado = sin(x); // Calcula o seno de x
        printf("O seno de %.4f é: %.4f\n", x, resultado); // Imprime o resultado
    } else {
        printf("Valor inválido! x deve estar no intervalo (0, 1).\n");
    }
    return 0;
 }
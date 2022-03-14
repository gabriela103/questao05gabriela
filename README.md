# questao05gabriela
#include <stdlib.h>
#include <locale.h>

void valor_numerico();

I

int main() {

setlocale(LC_ALL, "Portuguese_Brazil: ");

valor_numerico();

}

void valor_numerico() { int valor_numerico; printf("\nDigite um numero: "); scanf("%d", &valor_numerico);

if(valor_numerico < 0) { printf("\nEsse numero: Negativo");

}

else{

printf("\nEsse numero: Positivo");
}

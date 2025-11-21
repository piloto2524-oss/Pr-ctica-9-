#include <stdio.h>

int main() {
    int lista[5] = {10, 8, 5, 8, 7}; // Se declara e inicializa el arreglo
    int indice = 0;

    printf("\t\tLista\n");

    // Acceso a cada elemento del arreglo usando while
    while (indice < 5) {
        printf("\nCalificación del alumno %d es %d", indice + 1, lista[indice]);
        indice++;  // Incrementamos el índice
    }

    printf("\n");
    return 0;
}

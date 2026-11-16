#include <stdio.h>
#include <string.h>

int main() {

    int cantidad, posicion;
    int vector[100];
    char seguir[20];

    printf("ingrese la cantidad de datos del vector: ");
    scanf("%d", &cantidad);

    for (int i = 0; i < cantidad; i++) {
        printf("ingrese el dato %d: ", i + 1);
        scanf("%d", &vector[i]);
    }

    printf("¿desea continuar o finalizar?: ");
    scanf("%s", seguir);

    while (strcmp(seguir, "continuar") != 0 && strcmp(seguir, "finalizar") != 0) {
        printf("error. ingrese continuar o finalizar: ");
        scanf("%s", seguir);
    }

    while (strcmp(seguir, "continuar") == 0) {

        printf("\n ingrese la posicion del dato que quiere consultar (1-%d): ", cantidad);
        scanf("%d", &posicion);

        if (posicion >= 1 && posicion <= cantidad) {
            printf("el dato en la posicion %d es: %d\n",
                   posicion, vector[posicion - 1]);
        }
        else {
            printf("posicion no permitida \n");
        }

        printf("¿desea continuar o finalizar?: ");
        scanf("%s", seguir);

        while (strcmp(seguir, "continuar") != 0 && strcmp(seguir, "finalizar") != 0) {
            printf("error. ingrese continuar o finalizar: ");
            scanf("%s", seguir);
        }
    }

    printf("\nprograma finalizado \n");

    return 0;
}

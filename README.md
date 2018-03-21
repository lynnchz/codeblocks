// tp 1 //

#include <stdio.h>
#include <stdlib.h>

int main()
{

    int numero1;
    int perimetro;

    printf("Ingrese la base:");
    scanf("%d" ,&numero1);

    perimetro = numero1 * 3;

    printf("Su perimetro es de :" "%d", perimetro);


}
________________________________________________________________________________________________________________________


//tp 2//


int main()
{
    int producto;
    int iva = 21;
    int precioFinal;
    int asd;

    printf("Ingrese el importe al cual quiera agregarle el IVA : ");
    scanf("%d" , &producto);

    precioFinal = iva * producto / 100;
    asd = producto + precioFinal;

    printf("El importe final de su producto es de :" "%d" "$" , asd);

}


//2-Realizar el algoritmo que al presionar el
// botón "Mostrar" lea un importe de un producto
//por prompt y muestre el importe final sumándole el IVA (21%)

________________________________________________________________________________________________________________________

//tp3//

int main()
{
    int largo;
    int ancho;
    int perimetro;
    int asd;

    printf("Ingrese el largo del terreno : ");
    scanf("%d", &largo);
    fflush(stdin);
    printf("Ingrese el ancho del terreno : ");
    scanf("%d", &ancho);

    perimetro = largo + ancho;
    asd = perimetro * 6;

    printf("La cantidad de MTS de alambrado que necesita es de : %d " ,asd );




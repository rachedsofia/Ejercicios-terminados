# Ejercicios-terminados
https://www.onlinegdb.com/edit/HytiZ3-D_
#include <stdio.h>

int main()
{
    char uncar;
    printf("Ingrese un caracter \n");
    scanf("%c",&uncar);
    if(char == 'a' || char == 'A' || char == 'e' || char == 'E' || char == 'i' || char == 'I' || char == 'o' || char == 'O' || char == 'u' || char == 'U');
    {
        printf("Vocal");
    
    else 

        printf("No vocal");
    }
    return 0;
}

https://www.onlinegdb.com/edit/SkTrJFev_
#include <stdio.h>

int main()
{
    int numero=0, suma=0;
    #define tope 10
    do
    {
       numero = numero + 1;
       suma= suma + numero;
    }
    while(numero < tope);
    
       printf("%d",suma);
    
   
    return 0;
}


https://www.onlinegdb.com/edit/SJ5HhwvI_
#include <stdio.h>
int main()
{
    float presion, volumen, temperatura, masa;
    printf("Ingrese la presión: ");
    scanf("%f",&presion);
    printf("Ingrese el volumen: ");
    scanf("%f",&volumen);
    printf("Ingrese la temperatura: ");
    scanf("%f",&temperatura);
    masa=(presion*volumen)/(0.37*(temperatura+ 460));
    printf("el valor de la masa es %s", masa);
}
https://www.onlinegdb.com/edit/SJ5HhwvI_
#include <stdio.h>
int main()
{ 
    int a, b;
    printf("Ingrese dos números: ");
    scanf("%d",&a, &b);
    if(a<b)
    {
        printf("El número %d", b, "es el mas grande ");
        else 
        {
            printf("El numero %d", a, "es el mas grande ");
        }
    }
    if(a==b)
    {
        printf("Son iguales")
    }
} 
https://www.onlinegdb.com/edit/SkgoKGzJD_
#include <stdio.h>

int main()
{
    int a,b,c; 
    printf("Ingrese tres numeros: \n");
    scanf("%d",&a);
    scanf("%d",&b);
    scanf("%d",&c);
    if((a<b && a>c)||(a>b && a<c)) 
    {
        printf("el numero intermedio es %d", a);
    }
    if((b<a && b>c)||(b>a && b<c))
    {
        printf("el numero intermedio es %d", b);
    }
    if((c<b && c>a)||(c>b && c<a))
    {
        printf("el numero intermedio es %d", c);
    }

    return 0;
}
https://www.onlinegdb.com/edit/SkkIZad8d
#include <stdio.h>
int main()
{
    int edad, nropulsaciones;
    printf("ingrese su edad: ");
    scanf("%d",&edad);
    nropulsaciones=(220 - edad)/10;
    printf("el nro de pulsaciones es %d", nropulsaciones);
    
    
}
https://www.onlinegdb.com/edit/Byc_eoP8_
#include <stdio.h>


int main()
{ 
    int a, b;
    printf("Ingrese dos números: ");
    scanf("%d",&a);
    scanf("%d",&b);
    if(a<b)
    {
        printf("El número mas grande es %d", a);
    }
        else
        {
            printf("El numero mas grande es %d",b);
        }
    if(a==b)
    {
        printf("Son iguales");
    }

}

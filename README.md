# taller-github-flow

Este software es una solucion para el problema de encontrar la suma de los elementos de una lista de enteros en Java. La funcion simpleArraySum toma una lista de enteros como entrada y devuelve su suma como un numero entero.

## Uso

Para utilizar esta funcion, debes llamarla y pasarle una lista de enteros como argumento. Por ejemplo:

```java
int[] ar = {1, 2, 3};
int resultado = simpleArraySum(ar);
System.out.println(resultado);
```

Esto imprimira 6 en la consola, que es la suma de los elementos de la lista {1, 2, 3}.

## Implementacion

A continuacion se muestra la implementacion de la funcion simpleArraySum en Java:

```java
public static int simpleArraySum(int[] ar) {
    int suma = 0;
    for (int i = 0; i < ar.length; i++) {
        suma += ar[i];
    }
    return suma;
}
```

## Formato de Entrada

La funcion espera una lista de enteros como entrada.

## Formato de Salida

La funcion devuelve un numero entero que es la suma de los elementos de la lista ar.

## License

[MIT](https://choosealicense.com/licenses/mit/)
# La Clase Scanner

---

## Utilizar la clase Scanner

Esta clase nos permite capturar datos por teclado desde la terminal, para utilizarla primero debemos importar la clase:

    import java.util.Scanner;

Luego debemos instanciar la clase:

    Scanner scanTerminal = new Scanner(System.in);

Siguiente paso es darle la instrucción al programa que espere al usuario para el ingreso de datos por teclado a través de la terminal.

    int datoInt = scanTerminal.nextInt();

*Esta instrucción tomará como **int** lo que se capture por teclado*
**IMPORTANTE: ¡¡CUIDADO CON LOS TIPOS DE DATOS!!. YA QUE EL USUARIO PODRIA INGRESAR DATA TIPO STRING CUANDO SE ESPERA INTEGER, POR ERROR.**

    String datoString = scanTerminal.nextLine();

*Esta instrucción tomará como String lo que se capture por teclado*

    Double datoDouble = scanTerminal.nextDouble();

*Esta instrucción tomará como String lo que se capture por teclado*
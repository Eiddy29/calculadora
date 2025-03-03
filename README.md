public class Main {public static void main(String[] args) {
// TIPOS DE DATOS
int numero = 10;
double precio = 99.99;
boolean esValido = true;
String mensaje = "Hola, GitHub desde IntelliJ IDEA!";

        System.out.println("Número: " + numero);
        System.out.println("Precio: " + precio);
        System.out.println("Es válido: " + esValido);
        System.out.println("Mensaje: " + mensaje);

        // ESTRUCTURAS DE CONTROL

        // If-Else
        if (numero > 5) {
            System.out.println("El número es mayor que 5");
        } else {
            System.out.println("El número es 5 o menor");
        }

        // Switch
        switch (numero) {
            case 10:
                System.out.println("El número es diez");
                break;
            default:
                System.out.println("Número desconocido");
        }

        // Bucle for
        System.out.println("Contando con for:");
        for (int i = 1; i <= 5; i++) {
            System.out.println(i);
        }

        // Bucle while
        int contador = 3;
        System.out.println("Contando con while:");
        while (contador > 0) {
            System.out.println(contador);
            contador--;
        }
    }
}

# Casos Prácticos de Programación

## Ejemplo de Métodos
Aquí mostramos cómo definir un método en Java que imprima un mensaje:

```java
public void saludo() {
    System.out.println("¡Hola, bienvenido!");
}

## Ejemplo de manejo de Errores
try {
    int resultado = 10 / 0;
} catch (ArithmeticException e) {
    System.out.println("Error: " + e.getMessage());
}

## Ejemplo de Colecciones
List<String> lista = new ArrayList<>();
lista.add("Elemento 1");
lista.add("Elemento 2");
for (String elemento : lista) {
    System.out.println(elemento);
}

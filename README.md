# Proyecto Esteganografía en Java

Este proyecto implementa métodos para ocultar y revelar mensajes ocultos en textos mediante diversas técnicas de esteganografía.

## Funcionalidades

- `descifraNuloN(String, int)`: Descifra un mensaje oculto tomando la N-ésima letra de cada palabra.
- `descifraNulo(String)`: Descifra un mensaje usando la cantidad de espacios en blanco iniciales.
- `contieneNombre(String, String)`: Verifica si un mensaje contiene un nombre específico, ignorando caracteres especiales.
- `descifraPalabrasMarcadas(String, String)`: Recupera palabras ocultas comparando dos versiones de un texto.
- `descifraLetrasMarcadas(String, String)`: Extrae letras ocultas comparando caracteres en palabras de igual longitud.

## Requisitos

- **Java JDK 8 o superior**  
- **IDE recomendado**: NetBeans, IntelliJ IDEA o Eclipse  

## Instalación

Clona este repositorio y compila los archivos:

```sh
git clone https://github.com/tu-usuario/esteganografia-java.git
cd esteganografia-java
javac -d . Metodos.java Main.java
java Esteganografia.Main
```

Este proyecto es de código abierto bajo la licencia MIT.

Héctor Santiago González Baltierra
322604322


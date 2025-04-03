# Diagrama_Clase
Ejercicio 1
class Persona {
    String nombre;
    String apellido;
    int edad;
    String direccion;

    void caminar() {}
    void mensaje() {}
}

class Estudiante extends Persona {
    String matricula;
    String carrera;

    void estudiar() {}
    void asistir() {}
}

class Profesor extends Persona {
    String especialidad;
    String asignatura;

    void enseñar() {}
}

Ejercicio 2
class Animal {
    void respirar() {}
}

class Pez extends Animal {
    void nadar() {}
}

class Perro extends Animal {
    void ladrar() {}
}

class Gato extends Animal {
    void maullar() {}
}

Ejercicio 3
class Persona {
    String nombre;
    int edad;

    void hablar() {}
}

class Cars {
    String marca, modelo, color;
    int año;

    void encender() {}
    void apagar() {}
    void acelerar(int velocidad) {}
    void frenar() {}
}

public class Main {
    public static void main(String[] args) {}
}

Biblioteca
class Biblioteca {
    String nombre, direccion;

    void añadirLibro(Libro libro) {}
    void registrarPersona(Persona persona) {}
}

class Trabajador {
    String nombre, puesto;

    void trabajaEn(Biblioteca biblioteca) {}
}

class Persona {
    String nombre;
    private String identificacion;

    void registrarse(Biblioteca biblioteca) {}
}

class Autor {
    String nombre;

    void escribirLibro(Libro libro) {}
}

class Libro {
    String titulo, isbn;
    private Autor autor;

    boolean esPrestado() { return false; }
    void prestadoA(Persona persona) {}
}

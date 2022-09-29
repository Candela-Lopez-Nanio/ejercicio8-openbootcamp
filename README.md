# ejercicio8-openbootcamp
Tarea para practicar encapsulación 


public class Main {

    public static void main(String[] args) {

        Persona persona = new Persona();

        persona.setNombre("Mateo");
        persona.setEdad("23");
        persona.setTelefono("35195768");

        System.out.println(" " + persona.getEdad() + " \n " + persona.getNombre() + " \n " + persona.getTelefono());

    }
}

class Persona {
    private String edad, nombre, telefono;

    public String getEdad() {
        return edad;
    }

    public void setEdad(String Edad) {
        this.edad = Edad;
    }

    public String getNombre() {
        return nombre;
    }

    public void setNombre(String Nombre) {
        this.nombre = Nombre;
    }

    public String getTelefono() {
        return telefono;
    }

    public void setTelefono(String Telefono) {
        this.telefono = Telefono;
    }
}

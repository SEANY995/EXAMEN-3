# EXAMEN-3
EXAMEN 3
import java.util.Scanner;

public class ConversorVelocidad {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        System.out.println("Ingrese la velocidad en Km/h:");
        double velocidadKmh = scanner.nextDouble();
        
        double velocidadMs = convertirVelocidad(velocidadKmh);
        
        System.out.println("La velocidad en m/s es: " + velocidadMs);
    }
    
    public static double convertirVelocidad(double velocidadKmh) {
        return velocidadKmh * 1000 / 3600;
    }
}

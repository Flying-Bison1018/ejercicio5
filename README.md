# ejercicio5
actividad
package ejercicio.pkg5;

/**
 *
 * @author PC
 */
import java.util.Scanner;
public class Ejercicio5 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        Scanner leer;
       char x;
       int myInt;
        leer = new Scanner (System.in);
        System.out.print("Ingrese letra\n");
        x = leer.next().charAt(0);
        
       myInt=x-'0';
       
       System.out.printf("el valor numerico es:"+myInt);
        
        
    }
    
}

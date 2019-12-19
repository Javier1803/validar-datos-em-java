# validar-datos-em-java
import java.util.Scanner;

public class Validar {

    public static void main(String[] args) {

        Scanner scanner = new Scanner(System.in);

        System.out.println("coloque usuario");
        var usuario = scanner.nextLine();

        System.out.println("Coloque sua edad");
        var edad = scanner.nextLine();
        
        System.out.println("Coloque su gmail");
        var gmail = scanner .nextLine();        
        System.out.println("Hola amigo: " + usuario + "\n" + "Sua edad es de: " + edad 
                +"\n"+ "su gmail es: " + gmail );
    }

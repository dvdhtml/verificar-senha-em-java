import java.util.Scanner;

public class VerificarSenha {
    public static void main(String[] args) {
        
        Scanner scanner = new Scanner(System.in);
String login;
int senha;
    
        System.out.print("Digite o login: ");
        login = scanner.next();
        
       
        System.out.print("Digite a senha: ");
         senha = scanner.nextInt();


        if (login .equals("DVD") && senha == 1004) {
            
            System.out.println("CHEGA AI MENO.");
        } else {
            System.out.println("SAI FORA MENO.");
        }
    }
}

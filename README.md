import java.util.Scanner;

public class VerificarSenha {
    public static void main(String[] args) {
        
        Scanner scanner = new Scanner(System.in);

       
        System.out.print("Digite a senha: ");
        int senhaInformada = scanner.nextInt();

        
        scanner.close();

        
        final int SENHA_VALIDA = 1004;

        
        if (senhaInformada == SENHA_VALIDA) {
            System.out.println("Senha correta.");
        } else {
            System.out.println("Senha incorreta.");
        }
    }
}

import java.io.File;
import java.io.FileNotFoundException;
import java.io.FileWriter;
import java.util.Scanner;

public class App {
    public static void main(String[] args) throws Exception {
        
         FileWriter arquivo = new FileWriter("nome-do-arquivo.txt");
        // Classe nome do objeto chama o contrutor dessa classe
        arquivo.write("Me deixe viver ou viva comigo\r\n" + //
                        "Me mande embora ou me faça de abrigo\r\n" + //
                        "California dream com uma dream girl\r\n" + //
                        "Mas não sou gringo\r\n" + //
                        "Camisa suada estampada de flamingo");
        arquivo.close();

                                            lerUmArquivoComScanner();

        }

                                    public static void lerUmArquivoComScanner() throws FileNotFoundException {
                            File arquivo = new File("nome-do-arquivo.txt");
                            Scanner scanner = new Scanner(arquivo);
                            String linha = scanner.nextLine();
                         System.out.println(linha);
                            while (scanner.hasNextLine()) {
                            linha = scanner.nextLine();
                           // System.out.println(linha);}
                           
                            }
                                 }
                                         }         //  }
            


<!---
AninhaSusana/AninhaSusana is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

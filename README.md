# Iniciante
para auxiliar novatos dos novatos no rumo da programação (inicio)

/*
Aqui lhe deixarei um codigo basico para inicio.
todo inicio de aula professor pede para criar um Hello word
*/

package hello.word;

import java.util.Scanner;


 
public class HelloWord {

   
    public static void main(String[] args) {
       //modo simples
        System.out.println("Hello word");
        
       
       
//modo pouco melhorado e deixar mais bonito
       /*obs: vai apresentar um erro basta clicar no icone da lampada e importar
      vai ficar exatamente assim 
       package ***** ;

       import java.util.Scanner;
       */
       String palavra;
       Scanner p= new Scanner (System.in); //esse Scanner tem a função de que o usuario escreva algo qualquer coisa.
        System.out.println("Digite uma qualquer coisa nesse campo");
       palavra= p.nextLine();
    
    
        System.out.println("retorno "+palavra);
    

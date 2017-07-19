# robot
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package robot;
import java.util.Scanner;
public class Robot {

    public static void main(String[] args) {
        System.out.println("what is your name?");
Scanner a= new Scanner (System.in);     
    System.out.println (a.nextLine());
        
        
        
        
    Scanner bucky= new Scanner (System.in); 
    
    System.out.println ("select from the three(3) drink choices we have");
int drink = bucky.nextInt();    
   if( drink == 1 ) {
         System.out.print("your selection is water,");
      }else if( drink == 2 ) {
         System.out.print("your selection is coffee");
      }else if( drink == 3 ) {
         System.out.print("your selection is icetea");
      }else {
         System.out.print("error, try again");


 
    }
    
}
}

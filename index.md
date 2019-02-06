/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package c033333;
import java.util.*;

public class C033333 {

    public static void main(String[] args) {
        // TODO code application logic here
    }
}

    class Jungle{
        Lion L1 = new Lion();
        Tiger T1 = new Tiger();
        
        public void DoCompetition(){
                if (L1.Strength > T1.Strength){
                    System.out.println(L1.name + " is stronger ");
                }
                else {
                    System.out.println(T1.name + " is stronger ");
                }
        }
    }

    class Lion{
        public String name = "George";
        public int Strength = 0; 
        
        public Lion(){
            Random r1 = new Random();   
            Strength = r1.nextInt(100);
        }
    }
    
    class Tiger{
        public String name = "Sara";
        public int Strength = 0; 
        
         public Tiger(){
            Random r1 = new Random();   
            Strength = r1.nextInt(100);
        }
    }
    
    

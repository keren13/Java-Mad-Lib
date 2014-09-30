Java-Mad-Lib
============
/**
 * Madlib Lab.
 * 
 * @author (Keren Herran) 
 * @version (9.30.14)
 */

import java.util.Scanner; 
   
public class MadLibLab
{
  public static void main(String args[])

    {
       
        
       int a;
       Scanner in = new Scanner(System.in);
       System.out.println("Input an integer: ");
       a = in.nextInt();
       
       in.nextLine();
       
       String b;
       System.out.println("Input a verb: " );  
       b = in.nextLine();
       
       String c;
       System.out.println("Input a type of food: " );
       c = in.nextLine();
       
       String d;
       System.out.println("Input a place: ");
       d=in.nextLine();
       
       double e;
       System.out.println("Input a decimal: " );
       e= in.nextDouble(); 
       
      String f;
       System.out.println("Input a person's name: " );
       f = in.nextLine();
       
       in.nextLine();
       
       double g;
       System.out.println("Input a decimal: ");
       g=in.nextDouble();
       
       //in.nextLine();\\
       
       
       String h;
       System.out.println("Input an adverb: " );
       h= in.nextLine();
       
       in.nextLine();
       
       String i;
       System.out.println("Input a name: " );
       i= in.nextLine();
       
       //in.nextInt(); \\
       
       int j;
       System.out.println("Input a number: ");
       j = in.nextInt();
       
       //in.nextDouble()\\
       
      double k;
      Scanner inz = new Scanner(System.in);
      System.out.println("Input a decimal: ");
      k = in.nextDouble();
      
       
      
      System.out.print("Once upon a time there was a fish named Nemo who had " + a + " fins. Nemo loved to " + b + " and eat " + c +". Nemo went to a school in ");
      System.out.print(d +   " where students had a GPA of  " + e + ". One day, Nemo’s "  +  f  +  "  went missing. Nemo swam  " +  g  + "  miles, searching " + h );
      System.out.print(" . Nemo found out that  " +  f  + " was OK, and had just escaped being caught by a fishing boat called " + i + " who had casted a large net. Now that Nemo and " );
      System.out.print( f + " were reunited, Nemo was so happy that he said he would be thankful for " +  j + " years and would always get a " + k + "  GPA in school.");
       
       
       
       
    }
     
}

A fun madlib I programmed. This concept can be applied to writing interactive fictions or other basic user input games. A really fun project to play around with!

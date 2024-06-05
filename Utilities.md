/**
  @author:Dana
  @description:Create a Java application to maintain data for car owners.  
  @date:4/24/2024
*/

import javax.swing.JOptionPane;
import javax.swing.ImageIcon;

public class Utilities{
   public static int mainMenu (){
     //Custom button text
      Object[] options = {"List All Car Models",
                          "List All Car Makes",
                          "List All Colors",
                          "Search By Certain Color",
                          "Change Car Color", 
                          "Display Oldest Car", 
                          "Display All Makes",
                          "Display Array List",                                                                                                        
                          "Quit"};
      ImageIcon icon = new ImageIcon("city.png");
      int n = JOptionPane.showOptionDialog(null,
         "Choose an option ",
         "Owner Queries",
         JOptionPane.DEFAULT_OPTION,
         JOptionPane.PLAIN_MESSAGE,
         icon,
         options,
         options[0]);
    
      return n;
   }//end main
   
}//end class

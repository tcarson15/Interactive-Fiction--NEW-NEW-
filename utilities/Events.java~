//by Troy Carson
package utilities;
import utilities.*;
import java.util.Scanner; 
public class Events{
  Scanner keyboard = new Scanner(System.in);
  public Events(int event){
    if (event == 1){//go to SHatter Sands Tower
      System.out.println("You arrive at Shatter Sands tower just as the sun rises tangent to the horizon the next day. You find a small garrison of no more than a dozen royal troops stationed there. Nearly every man you see is wounded or sullen. A man rises to greet you, his left arm hoisted in a tight bandage to his chest.");
      System.out.println("");
      System.out.println("I'm Sergeant Davin, what are you doing here traveler?");
      System.out.println("");
      System.out.println("Enter '1' to tell of how Captain Myzard sent you to aid against the bandits. Enter '2' to draw your sword and attack Sergeant Davin.");
      if (keyboard.nextLine() == "1"){
        event = 3;
      }
      if (keyboard.nextLine() == "2"){
        event = 4;
      }
      
    }
    if (event == 2){//fight Captain Myzard
      System.out.println("Enter '1' for a melee attack. Enter '2' for a ranged attack. Enter '3' to take a health potion.");
      if (f.combat(Player,CaptainMyzard)){
        System.out.println("Against all odd (literally) you have managed to defeat Captain Myzard! Too bad the rest of his guards cut you down immediatly after your victory.");
        event = 99;
      }
      else event = 99;
    }
    
    if (event == 3){//fight bandits at Shatter Sands Tower
      Character Bandit = new Character(10, 5, 10, 5, (int)(Math.random()*5)+1, "Bandit"); 
      System.out.println("Ah, good. We could always use an able body, especially now, after our losses. Most of the men are dead or dying, these bandit have never been so bold, attacking so close to cities and trade routes. Sometime soon they'll do something even bigger (hint hint), mark my words.");
      System.out.println("");
      System.out.println("You spend the day with the garrison, sharpening your blade, playing dice and sharing stories. But the merrymaking was interupted by a loosed arrow that hit the man next to you, piercing through his gorget. Several dozen men begin charging you, all the while arrows continue to pepper the ground around you. A bandit charges you, a mighty war cry precing his hulking form.");
      System.out.println("");
      System.out.println("Enter '1' for a melee attack. Enter '2' for a ranged attack. Enter '3' to take a health potion.");
      if (f.combat(Player,Bandit)){
        System.out.println("You slay the first bandit, but another attacks you!");
      }
      if (f.combat(Player,Bandit)){
        System.out.println("You mange to defeat another bandit, yet more continue to descend down upon you and the few remaining royal troops!");
      } 
      if (f.combat(Player,Bandit)){
        System.out.println("You manage to kill another bandit, but as you look up you see them retreating before you. A large host of cavelrymen bearing the royal coat of arms drives back the bandit with lances to their backs.");
      }
      else event = 99;
    }
    
    if (event == 4){//fight Sergeant Davin
      Character SergeantDavin = new Character(20, 15, 15, 20, 15, "Sergeant Davin");
      if (f.combat(Player,SergeantDavin)){
        System.out.println("You slay the first bandit, but another attacks you!");
        event = 5;
      else event = 99;
      }
    }
    
    if (event == 5){
    }
    
    if (event == 99){//die
      System.out.println("You have died! (n00b)");
    }
  }
}
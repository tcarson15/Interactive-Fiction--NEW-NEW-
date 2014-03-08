//by Troy Carson
package utilities;
import utilities.*;
import java.util.Scanner; 
public class Events{
  Scanner keyboard = new Scanner(System.in);
  public Events(int event){
    Scanner keyboard = new Scanner(System.in);
    System.out.println("You there, Knight! What is your name?");
    String userName = keyboard.nextLine();
    Character player = new Character(userName);
    player.addHealth(10);
    player.addDexterity(10);
    player.addStrength(10);
    player.addRanged(10);
    System.out.println("Aye, I've heard of you, you've been trying to gain influence throughout the kingdom. I'm Captain Myzard of the Guard, and if you want to to make a real name for yourself, you can start by going over to Shatter Sands Tower to the East of here, trouble with bandits I hear, and we havn't the men to spare with the Civil War on our doorsteps, so we need our men in the cities to keep order and remind the people the King rules these lands.");
    System.out.println("");
    System.out.println("Enter '1' to agree to go to Shatter Sands Tower. Enter '2' to ask more about the rebellion. Enter '3' to attack Captain Myzard and declare yourself with the rebellion.");
    Character CaptainMyzard = new Character(20, 20, 30, 20, 25, "Captain Myzard"); 
    int cat = keyboard.nextInt();
    if (cat == 1){
      event = 1;
    }
    else if (cat == 3){
      event = 2;
    }
    else if (cat == 2){
      System.out.println("Well I doubt I could tell you anything you havnt already heard. In short, Darion the Dissolute decided he wanted to rise up against the King in rebbellion, and several thousand smallfolk decided to join him in defiance. No one knows who exactly this 'Darion' is, some say he was a trusted advisor to the King or a General turned renegade. Either way, he's just a man, and a man who needs to die. And it's the Legion that's gonna see to it!");
      System.out.println("");
      System.out.println("Enter '1' to agree to go to Shatter Sands Tower.Enter '2' to attack Captain Myzard and declare yourself with the rebellion.");
      int gato = keyboard.nextInt();
      if (gato == 1){
        event = 1;
      }
      if (gato == 2){
        event = 2;
      }
    }
    if (event == 1){//go to Shatter Sands Tower
      System.out.println("You arrive at Shatter Sands tower just as the sun rises tangent to the horizon the next day. You find a small garrison of no more than a dozen royal troops stationed there. Nearly every man you see is wounded or sullen. A man rises to greet you, his left arm hoisted in a tight bandage to his chest.");
      System.out.println("");
      System.out.println("I'm Sergeant Davin, what are you doing here traveler?");
      System.out.println("");
      System.out.println("Enter '1' to tell of how Captain Myzard sent you to aid against the bandits. Enter '2' to draw your sword and attack Sergeant Davin.");
      int dog = keyboard.nextInt();
      if (dog == 1){
        event = 3;
      }
      if (dog == 2){
        event = 4;
      }
      
    }
    if (event == 2){//fight Captain Myzard
      System.out.println("Enter '1' for a melee attack. Enter '2' for a ranged attack. Enter '3' to take a health potion.");
      if (combat(player,CaptainMyzard)){
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
      if (combat(player,Bandit)){
        System.out.println("You slay the first bandit, but another attacks you!");
      }
      if (combat(player,Bandit)){
        System.out.println("You mange to defeat another bandit, yet more continue to descend down upon you and the few remaining royal troops!");
      } 
      if (combat(player,Bandit)){
        System.out.println("You manage to kill another bandit, but as you look up you see them retreating before you. A large host of cavelrymen bearing the royal coat of arms drives back the bandit with lances to their backs.");
      }
      else event = 99;
    }
    
    if (event == 4){//fight Sergeant Davin
      Character SergeantDavin = new Character(20, 15, 15, 20, 15, "Sergeant Davin");
      if (combat(player,SergeantDavin)){
        event = 5;
      }
      else event = 99;
    }
    
    if (event == 5){//meet Ser Dayvois
      System.out.println("You manage to defeat Sergeant Davin! His men muster themselves up and advance towards you. But just before the first man reaches you, he is struck by an arrow! You turn behind you to see dozens of bandits charging towards you. But the bandits swarm right past you and attack the royal troops, overwhelming them within moments. A man appears before you, the skin of a mighty draken drapped across his shoulders.");
      System.out.println("");
      System.out.println("I am Ser Dayvois Bonehart. We were watching from the crest of that kill, we saw you kill their Sergeant, damn fine work. Will you join us? There are many small towns an villages on our way to the Capital.");
      System.out.println("");
      System.out.println("Enter '1' to agree to join their raiding party. Enter '2' to ask why the bandit party is heading for the Capital. Enter '3' to ask why a Royal Knight is in a raiding party and attacking the King's people. Enter '4' to attack Ser Dayvois.");
      int cow = keyboard.nextInt();
      if (cow == 1){
        event = 6;
      }
      if (cow == 2){
        event = 7;
      }
      if (cow == 3){
        event = 8;
      }
      if (cow == 4){
        event = 9;
      }
    
    if (event == 6){//joined the raiding party and head towards nearby settlement
    }
    
    if (event == 7){//asked why the bandits are headed to the Capital
      System.out.println("We are for the rebellion, and we are going to join with the main army of Darion The Dissolute and take down the Capital.");
      System.out.println("");
      System.out.println("Enter '1' to agree to join the raiding party. Enter '2' to ask why an anointed Knight is for the rebellion. Enter '3' to attack Ser Dayvois.");
      int vaca = keyboard.nextInt();
      if (vaca == 1){
        event = 6;
      }
      if (vaca == 2){
        event = 8;
      }
      if (vaca == 3){
        event = 9;
      }
    }
    
    if (event == 8){//asked why a Knight is leading a bandit raiding party
    }
    
    if (event == 9){//attack Ser Dayvois
    }
    
    if (event == 99){//die
      System.out.println("You have died! (n00b)");
    }
  }
  public boolean combat(Character p1, Character p2){
    boolean hasWon = false;
    boolean stillAlive = true;
    boolean enemyStillAlive = true;
    if (stillAlive == true && enemyStillAlive == true){
      boolean turn = (p1.getDexterity()+(int)Math.random()*20+1)>(p2.getDexterity()+(int)Math.random()*20+1); //determine which player attacks first
      while(!hasWon){
        if(turn){
          int move = p1.selectMove();
          if(move==1){ //melee
            if((int)Math.random()*20+1>=p2.getArmorClass()) p2.minusHealth(p1.getStrength());
            if(p2.health <= 0){
              enemyStillAlive = false;
            }
            else turn = false;
          }
          else if(move==2){ //ranged
            if((int)Math.random()*20+1>=p2.getArmorClass()) p2.minusHealth(p1.getRanged());
            if(p2.health <= 0){
              enemyStillAlive = false;
            }
            else turn = false;
          }
          else if(move==3){ //take health potion
            p1.addHealth((int)((Math.random()*11)+5));
            turn = false;
          }
          
          if(!turn){
            move = p1.selectMove();
            if(move==1){ //melee
              if((int)Math.random()*20+1>=p1.getArmorClass()) p1.minusHealth(p2.getStrength());
              if(p1.health <= 0){
                stillAlive = false;
              }
              else turn = false;
            }
            else if(move==2){ //ranged
              if((int)Math.random()*20+1>=p1.getArmorClass()) p1.minusHealth(p2.getRanged());
              {
                if(p1.health <= 0){
                  stillAlive = false;
                }
                else if(move==3){ //take health potion
                  p2.addHealth((int)((Math.random()*11)+5));
                  turn = false;
                }
              }
            }
          }
        }
        if (stillAlive == false) return false;
        else if (enemyStillAlive == false && stillAlive == true){
          return true;
        }
      }
    }
    return false;
  }
}
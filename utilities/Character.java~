//by Troy carson
package utilities;
import java.util.Scanner; 
public class Character{
  Scanner keyboard = new Scanner(System.in);
  int health;
  int dexterity;
  int strength;
  int ranged;
  int armorClass;
  String name = new String(); 
  public Character(String n){
    name = n;
    health = (int)(Math.random()*20)+1;
    dexterity = (int)(Math.random()*20)+1;
    strength = (int)(Math.random()*20)+1;
    ranged = (int)(Math.random()*20)+1;
    armorClass = dexterity;
  }
  
  public Character(int h,int d, int s, int r, int ac, String n){
    health = h;
    dexterity = d;
    strength = s;
    ranged = r;
    armorClass = ac;
    name = n;
  }
  
  public int selectMove(){//for combat 1=melee 2=ranged 3=skip
    if (keyboard.nextLine() == "1"){
      return 1;
    }
    if (keyboard.nextLine() == "2"){
      return 2;
    }
    if (keyboard.nextLine() == "3"){
      return 3;
    }
    
  }
  
  public int getHealth(){return health;}
  public int getDexterity(){return dexterity;}
  public int getStrength(){return strength;}
  public int getRanged(){return ranged;}
  public int getArmorClass(){return armorClass;}
  
  public int addHealth(int additionalHealth){health += additionalHealth;}
  public int minusHealth(int subtractedHealth){health -= subtractedHealth;}
  public int addDexterity(int additionalDexterity){dexterity += additionalDexterity;}
  public int minusDexterity(int subtractedDexterity){dexterity -= subtractedDexterity;}
  public int addStrength(int additionalStrength){strength += additionalStrength;}
  public int minusStrength(int subtractedStrength){strength -= subtractedStrength;}
  public int addRanged(int additionalRanged){ranged += additionalRanged;}
  public int minusRanged(int subtractedRanged){ranged -= subtractedRanged;}
  public int addArmorClass(int additionalArmorClass){armorClass += additionalArmorClass;}
  public int minusArmorClass(int subtractedArmorClass){armorClass -= subtractedArmorClass;}
}
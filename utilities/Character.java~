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
    return 1;
  }
  
  public int getHealth(){return health;}
  public int getDexterity(){return dexterity;}
  public int getStrength(){return strength;}
  public int getRanged(){return ranged;}
  public int getArmorClass(){return armorClass;}
  
  public void addHealth(int additionalHealth){health += additionalHealth;}
  public void minusHealth(int subtractedHealth){health -= subtractedHealth;}
  public void addDexterity(int additionalDexterity){dexterity += additionalDexterity;}
  public void minusDexterity(int subtractedDexterity){dexterity -= subtractedDexterity;}
  public void addStrength(int additionalStrength){strength += additionalStrength;}
  public void minusStrength(int subtractedStrength){strength -= subtractedStrength;}
  public void addRanged(int additionalRanged){ranged += additionalRanged;}
  public void minusRanged(int subtractedRanged){ranged -= subtractedRanged;}
  public void addArmorClass(int additionalArmorClass){armorClass += additionalArmorClass;}
  public void minusArmorClass(int subtractedArmorClass){armorClass -= subtractedArmorClass;}
}
# method-overloading
import java.util.*;

public class Main {
  public static void main(String[] args){
    Animal a=new Dog();
    Animal a1=new Cat();
    a.makesound();
    a1.makesound();
  }
}
public class Animal{
  public void makesound(){
    System.out.println("Its a default sound");
  }
}
public class Dog extends Animal{
  public void makesound(){
    System.out.println("bow bow..");
  }
}
public class Cat extends Animal{
}

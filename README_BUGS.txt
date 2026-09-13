
Known bugs:


When a method is written in the Main class, you must use the Class identifier, for example:
Main.method()
simply calling method() will not work



In a class, you cannot declare class variables, for example:
public class Bank{

  private int money;  // you cannot have this

  public Bank(){
    this.money = 0;  // this is where variables must be defined
  }
}
  

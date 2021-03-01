# Java1
public class Main{
	int number = 12;
    public int getMarks(){
    	return 45;
       }
       
  public static void main(String[] args) {
  	Main object1=new Main();
    System.out.println(object1.number);
    
    int value = object1.getMarks();
    System.out.println(value);
  }
}

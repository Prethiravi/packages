
import mypackage.MyClass; 
import java.util.Date;    

public class Main {
    public static void main(String[] args) {
        
        MyClass myClassInstance = new MyClass();
        myClassInstance.displayMessage();

        // Using a class from the built-in package
        Date currentDate = new Date();
        System.out.println("Current date: " + currentDate.toString());
    }
}

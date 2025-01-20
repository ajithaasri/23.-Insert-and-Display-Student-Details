# 23.-Insert-and-Display-Student-Details
import java.util.Scanner;

class Student {
    String name;
    int age;

    public void insertDetails(String name, int age) {
        this.name = name;
        this.age = age;
    }

    public void displayDetails() {
        System.out.println("Name: " + name);
        System.out.println("Age: " + age);
    }
}

public class StudentDetailsExample {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        Student student = new Student();

        System.out.print("Enter name: ");
        String name = sc.nextLine();
        System.out.print("Enter age: ");
        int age = sc.nextInt();

        student.insertDetails(name, age);
        student.displayDetails();
    }
}

Output

Enter name: Ajithaa
Enter age: 21  

Name: Ajithaa
Age: 21

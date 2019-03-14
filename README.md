# Assignment-2
Class: Fundamental Programming (COMP112) - Assignment #2 - Creating a Class + GPA Calculator in Java

//Class

package asignacion2;

public class Student {
  
  private String name;

  private double gpa;
	
  public Student() {
	    
    this.name = "";
    
    this.gpa = 0.0;
	
  }
	
  public Student(String name, double gpa) {
	
    this.name = name;
		
    this.gpa = gpa;
	
  }
	
  public void setName(String name) {
	
    this.name = name;
	
  }
	
  public void setGpa(double gpa) {

    this.gpa = gpa;
	
  }
	
  public String getName() {

    return this.name;
	
  }

  public double getGpa() {
	
    return this.gpa;
	
  }
		
  }
  
  // Main
  
package asignacion2;

public class Main {

public static void main(String[] args) {
// TODO Auto-generated method stub

  Student student1 = new Student();
  
  System.out.println(student1.getName()+"\t"+
  
  student1.getGpa());
	
  Student student2 = new Student("Paola",3.68);
	
  System.out.println(student2.getName() + "\t" + 
	
  student2.getGpa());
	
  student2.setName("Rodriguez");
	
  student2.setGpa(3.0);
	
	System.out.println(student2.getName()+"\t"+
	
  student2.getGpa());
	
  }

}

package runtime.polymorphism;
class Parent {
  void print(){
  System.out.println("parent class");
    }
}
class child1 extends Parent{
 void print(){
     System.out.println("Rangesh");    
 }   
}
class child2 extends Parent {
void print(){
    System.out.println("Archana");    
}    
}

public class RuntimePolymorphism
    public static void main(String[] args) {
        Parent a;
        a = new child1();
        a.print();
        a = new child2();
        a.print();
    }
    
}


Output:
Rangesh
Archana

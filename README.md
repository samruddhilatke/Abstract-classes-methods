abstract classes & methods

// Abstract class
abstract class Shape {
    // Abstract method
    abstract void draw();
    // Non-Abstract method
    void printShapeType() {
        System.out.println("Geometric Shape");
    }
}
 
class Circle extends Shape {
    void draw() {
        System.out.println("Drawing a circle");
    }
}
public class Paint {
    public static void main(String[] args) {
        Circle cir = new Circle();
        cir.draw();
        cir.printShapeType();
    }
}

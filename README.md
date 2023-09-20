# Arithmetic-Calculator
in this project, I am using classes, methods, and objects in order to creat a arithmetic calculator. It has the functionality to add, subtract, multiply, divide, and even apply modulos to all of the integers.


public class Calculator {

    public Calculator() {
        // Constructor code (if needed)
    }

    public int add(int a, int b) {
        int addition = a + b;
        return addition;
    }

    public int subtract(int a, int b) {
        int subtraction = a - b;
        return subtraction;
    }

    public int multiply(int a, int b) {
        int multiplication = a * b;
        return multiplication;
    }

    public int divide(int a, int b) {
        int division = a / b;
        return division;
    }

    public int modulo(int a, int b) {
        int modulo = a % b;
        return modulo;
    }

    public static void main(String[] args) {
        Calculator myCalculator = new Calculator();

// This calls both the add and subtract method in order to display
// example values of how the program runs.
        System.out.println("Addition: " + myCalculator.add(5, 7));
        System.out.println("Subtraction: " + myCalculator.subtract(45, 11));
         System.out.println("Multiplication: " + myCalculator.multiply(10, 40));
        System.out.println("Division: " + myCalculator.divide(100, 10));
         System.out.println("Modulo: " + myCalculator.modulo(3, 3));
    }
}

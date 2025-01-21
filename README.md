# Constructor-
class Number {

int value;

// Constructor

Number(int value) {

this.value = value;

}

// Method to calculate and return the square of the number

int getSquare() {

return value * value;

}

}

public class Main {

public static void main(String[] args) {

// Array of Number objects

Number[] numbers = new Number[5];

// Using a for loop to initialize objects

for (int i = 0; i < numbers.length; i++) {

numbers[i] = new Number(i + 1); // Create objects with values 1 to 5

}

// Using a for loop to display the square of each number

System.out.println("Squares of numbers:");

for (int i = 0; i < numbers.length; i++) {System.out.println("Number: " + numbers[i].value + ", Square: " +

numbers[i].getSquare());

}

}

OUTPUT:

Squares of numbers:

Number: 1, Square: 1

Number: 2, Square: 4

Number: 3, Square: 9

Number: 4, Square: 16

Number: 5, Square: 25

class Car {
    // Attributes of the class
    String brand;
    String model;
    int year;

    // Constructor to initialize the object
    Car(String brand, String model, int year) {
        this.brand = brand;
        this.model = model;
        this.year = year;
    }

    // Method to display car details
    void displayDetails() {
        System.out.println("Brand: " + brand);
        System.out.println("Model: " + model);
        System.out.println("Year: " + year);
    }
}

public class ConstructorExample {
    public stati}
c void main(String[] args) {
        // Create an object of the Car class using the constructor
        Car car1 = new Car("Toyota", "Corolla", 2020);

        // Display car details
        car1.displayDetails();

        System.out.println(); // Add a blank line for readability

        // Create another object of the Car class
        Car car2 = new Car("Honda", "Civic", 2022);

        // Display car details
        car2.displayDetails();
    }
}


OUTPUT:
Brand: Toyota
Model: Corolla
Year: 2020

Brand: Honda
Model: Civic
Year: 2022

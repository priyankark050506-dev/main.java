import java.util.Scanner;

class SmartLight {
    boolean isOn = false;

    void turnOn() {
        isOn = true;
        System.out.println("Light is ON");
    }

    void turnOff() {
        isOn = false;
        System.out.println("Light is OFF");
    }

    void status() {
        if (isOn) {
            System.out.println("Light status: ON");
        } else {
            System.out.println("Light status: OFF");
        }
    }
}

public class IoTExample {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        SmartLight light = new SmartLight();

        int choice;

        do {
            System.out.println("\n--- Smart Light Control ---");
            System.out.println("1. Turn ON");
            System.out.println("2. Turn OFF");
            System.out.println("3. Check Status");
            System.out.println("4. Exit");
            System.out.print("Enter your choice: ");

            choice = sc.nextInt();

            switch (choice) {
                case 1:
                    light.turnOn();
                    break;
                case 2:
                    light.turnOff();
                    break;
                case 3:
                    light.status();
                    break;
                case 4:
                    System.out.println("Exiting...");
                    break;
                default:
                    System.out.println("Invalid choice!");
            }

        } while (choice != 4);

        sc.close();
    }
}

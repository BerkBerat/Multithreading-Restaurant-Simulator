# Multithreading Restaurant Simulator

A simple multithreading simulation of a restaurant environment, where various processes run concurrently, emulating the actions in a restaurant. This project is built to demonstrate the use of multithreading in a real-world scenario.

## Features

- Simulates customer orders, food preparation, and service with multiple threads.
- Customers arrive at the restaurant, place orders, and are served by waiters.
- Cooks prepare the food concurrently while waiters handle customer interactions.
- Utilizes synchronized methods to manage shared resources and ensure thread safety.
  
## Technologies

- **Programming Language**: Java
- **Concurrency**: Java Threads, Synchronization
- **Data Structures**: Queue for managing customer orders

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/BerkBerat/Multithreading-Restaurant-Simulator.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Multithreading-Restaurant-Simulator
    ```

3. Compile the project:
    ```bash
    javac Main.java
    ```

4. Run the simulation:
    ```bash
    java Main
    ```

## How It Works

- **Customers** arrive at the restaurant and place their orders.
- **Waiters** handle the orders and serve food to customers.
- **Cooks** prepare the food concurrently, ensuring that the kitchen operates efficiently.
- The system makes use of Java’s multithreading capabilities to run multiple tasks simultaneously, such as receiving orders, cooking, and serving.

## Contributing

If you'd like to contribute to this project, feel free to fork the repository, make changes, and submit a pull request. We welcome improvements and enhancements!

## Acknowledgments

- Java multithreading documentation for the `Thread` and `Runnable` classes.
- Inspiration from real-world restaurant operations.

# Atividades em Java
[![Ask DeepWiki](https://devin.ai/assets/askdeepwiki.png)](https://deepwiki.com/mateusvitor09467/Atividades-Java)

This repository contains a collection of exercises and code examples written in Java. The main goal is to practice and demonstrate fundamental concepts of Object-Oriented Programming (OOP).

## Repository Structure

All code is located within the `Poo/` (Programação Orientada a Objetos) directory. The exercises are organized by topic and difficulty.

### OOP Exercises

The exercises are categorized into different levels:

*   **`Poo/📌 FÁCIL (1-10)/`**: This section contains simple class definitions to practice basic OOP principles. Examples include:
    *   `Carro`: A class representing a Car with attributes like brand, model, and year.
    *   `Pessoa`: A class for a Person with name and age.
    *   `ContaBancaria`: A class that simulates a bank account with deposit, withdrawal, and balance-checking functionalities.
    *   `Produto`: A class for products, featuring a method to apply discounts.
    *   `Aluno`: A class to calculate the average grade of a student.

*   **`Poo/📌 INTERMEDIÁRIO (11-20)/`**: These exercises explore more complex OOP concepts, focusing on inheritance.
    *   `ContaCorrente`: A class that inherits from `ContaBancaria`, adding specific attributes like a maintenance fee.
    *   `Moto`: A `Moto` class that inherits properties from a generic `Veiculo` class.

*   **`Poo/ArCondicionado/`**: A complete, runnable console application that manages a registry of different air conditioner models (`Splinter` and `Portatil`). This example demonstrates the use of:
    *   Abstract classes (`ArCondicionado`)
    *   Inheritance (`Splinter`, `Portatil`)
    *   Polymorphism
    *   User input handling through a command-line menu.

## How to Use

To run any of the examples, you will need a Java Development Kit (JDK) installed on your system.

1.  Clone the repository to your local machine.
2.  Navigate to the directory containing the desired Java file.
3.  Compile the code using the Java compiler:
    ```bash
    javac YourJavaFile.java
    ```
    For the `ArCondicionado` example, you would compile `ControleArCondicionado.java`.
4.  Run the compiled program using the Java Virtual Machine:
    ```bash
    java YourMainClass
    ```
    For the `ArCondicionado` example, the command would be `java ControleArCondicionado`.

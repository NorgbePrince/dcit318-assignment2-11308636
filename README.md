# DCIT318 – Assignment 2

**Name:** Prince William Norgbe  
**Student ID:** 11308636  
**Course:** DCIT 318 – Programming II  
**Assignment:** Object-Oriented Programming in C#

## Overview

This project includes three separate C# console applications demonstrating core OOP principles:

### 1. Inheritance and Method Overriding
- Base class: `Animal` with virtual method `MakeSound()`
- Derived classes: `Dog` and `Cat` override `MakeSound()` with their own sounds
- Demonstrates runtime polymorphism

### 2. Abstract Classes and Methods
- Abstract class: `Shape` with an abstract method `GetArea()`
- Derived classes: `Circle` and `Rectangle` implement `GetArea()`
- Demonstrates abstraction and concrete implementations

### 3. Interfaces
- Interface: `IMovable` with method `Move()`
- Implemented by: `Car` and `Bicycle`
- Demonstrates interface-based programming and flexibility

## How to Run the Programs

Ensure [.NET SDK 8.0](https://dotnet.microsoft.com/en-us/download/dotnet/8.0) is installed.

```bash
# Clone the repository
git clone https://github.com/your-username/dcit318-assignment2-11308636.git
cd dcit318-assignment2-11308636

# Run each app:
cd InheritanceAndOverriding
dotnet run

cd ../AbstractClasses
dotnet run

cd ../Interfaces
dotnet run

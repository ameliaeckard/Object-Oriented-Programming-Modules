# Module 1 - Notes

## 1. Java Basics (Chapter 1)
- **Variables & Data Types**: `int`, `double`, `boolean`, etc.
- **Control Flow**: `if-else`, `switch`, `for`, `while`
- **Methods**: Definition, parameters, return types
- **Arrays**: Declaration, indexing, iteration
- **Input/Output**: `Scanner` for input, `System.out.println` for output
- **OOP Intro**: classes, objects, `new` keyword

## 2. OOP Review (pp. 37–45)
- **Abstraction**: Expose only essential features
- **Encapsulation**: Private fields + getters/setters
- **Inheritance**: `class Sub extends Super`
- **Polymorphism**: Method overriding, interface usage

## 3. UML Diagrams (p. 54)
- **Class Diagrams**: Classes, attributes, methods, associations
- **Object Diagrams**: Snapshots of object instances
- **Use Case Diagrams**: Actors & system interactions
- **Sequence Diagrams**: Message flows over time
- **State Machine Diagrams**: States + transitions

## 4. PlantUML Setup
1. Install PlantUML extension in VS Code
2. Create `diagram.plantuml`
3. Write textual UML:
   ```plantuml
   @startuml
   class Account {
     +balance: double
     +deposit()
     +withdraw()
   }
   @enduml
4. Right‑click → Preview / Export → diagrams/ folder

## 5. Basic Exception Handling
- **Exception Hierarchy**: Checked vs unchecked
- ** try-catch**:
        try {
        // risky code
        } catch (ExceptionType e) {
        // handler
        } finally {
        // always runs
        }

## 6. Common Runtime Errors
- **ArithmeticException**: Division by zero
- **ArrayIndexOutOfBoundsException**: Invalid array access
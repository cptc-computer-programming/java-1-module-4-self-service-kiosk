
# Self-Service Kiosk Lab 
## Goal  
Design and implement a self-service kiosk program for a real-world situation of your choice. A self-service kiosk is a program that guides a user through a short interaction, collects information, processes that information, and displays a clear result or summary. 

Examples of self-service kiosk include:

- gym sign-in
- library checkout
- café ordering
- school event registration
- game store self-checkout

Your program should:

1. interact with the user through the keyboard
1. collect multiple pieces of information
1. process that information in a meaningful way
1. display a final summary or “receipt” of the interaction

> [!TIP]
> You decide what information matters, how it is processed, and what output is useful.



---

## Group Work & Version Control

This is a **group exercise** (pairs unless otherwise instructed).

#### Requirements:
- Both partners must contribute code  
- There must be multiple commits  
- Commit messages should clearly describe what was added or changed  


---

## Design First 

Before writing any Java code, your team must fill out `DESIGN.md`

This file must be committed *before* your first Java file commits.

#### Your design artifact must describe:
- What your kiosk does (at a high level)  
- What objects your program will use  
- What each object:
  - represents  
  - remembers (state)  
  - does (behavior)  
- How your program will be broken into methods  

You are expected to revise your design as needed, but an initial design commit is required.

---

## Program Requirements

Your program must meet all of the following constraints.

### Object Usage

Your program must use this week's featured objects:

- `Scanner`  
- `String`  


#### Experimenting with other Objects

In addition to creating `Scanner` and `String` objects, your program must use one additional object, such as:

- `DecimalFormat`
- `Random`
- `StringBuilder`
- `LocalDate` or `LocalTime`

> [!IMPORTANT]  
> You may use AI to help understand and use these options. Please note in your submission PR or in `DESIGN.md` if you used AI for that purpose. Do not use AI to write any code in this assignment. 

---

### Keep `main` Clean
`main` may only:
- create objects  
- call methods
- close the Scanner  

All logic must be in helper methods with parameters and return values.

---

### String Processing
Use at least 4 different String methods, including:
- one that returns a number (`length`, `indexOf`)  
- one that returns a String (`substring`, `toUpperCase`, `replace`, `trim`)  

---

### Scanner Usage
Your program must:
- use both `nextLine` and `nextInt` or `nextDouble ` 
- correctly handle the leftover newline  
- reuse the same `Scanner` object throughout the program  

---

### Immutability vs Mutability (Commented)
Your code must clearly demonstrate:
- `String` immutability  
- `Scanner` mutability  

You must include clear, explanatory comments that explain what happens to the object, not just what the line does.

```
name = name.trim();  // String is immutable: this returns a NEW String

amount = in.nextDouble();  // Scanner is mutable: this moves its position in the input

```

Leave at least 4 of these comments in the code to demonstrate your understanding

---

### Output / Summary
Your program must print a final summary or “receipt” that includes at least **5 stored values**  
(a mix of Strings, numbers, formatted values, etc.) with the proper context (user-friendly messaging).

---

## Submission

Each partner should submit their shared feedback PR individually to the Canvas Assignment 






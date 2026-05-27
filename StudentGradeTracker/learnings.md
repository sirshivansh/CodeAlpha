# Learnings from Student Grade Tracker Project

## Overview
This project helped me understand the fundamentals of Java programming by building a console-based Student Grade Tracker application.

---

# Concepts Learned

## 1. Classes and Objects
Learned how to create custom classes in Java.

Example:
- Created a `Student` class
- Used objects like `s1`, `s2`, etc.

Understood:
- blueprint vs object
- instance variables
- object creation using `new`

---

## 2. Constructors
Learned how constructors initialize object data automatically.

Example:

```java
Student(String name, int marks)
````

Understood:

* constructor purpose
* parameter passing
* `this` keyword

---

## 3. ArrayList

Learned dynamic data storage using:

```java
ArrayList<Student>
```

Understood:

* dynamic collections
* `.add()`
* `.size()`
* `.get()`

Difference between:

* Arrays
* ArrayLists

---

## 4. Loops

Learned:

* `for` loops
* enhanced for loop

Example:

```java
for (Student s : students)
```

Understood:

* iteration
* traversing collections
* automation using loops

---

## 5. User Input Using Scanner

Learned how to take user input dynamically.

Used:

* `next()`
* `nextInt()`

Example:

```java
Scanner sc = new Scanner(System.in);
```

---

## 6. Accumulation Logic

Learned how totals are calculated using loops.

Example:

```java
sum = sum + s.marks;
```

Understood:

* accumulation pattern
* running totals

---

## 7. Average Calculation

Learned average calculation using:

```java
(double) sum / students.size()
```

Understood:

* type casting
* integer division vs double division

````

:contentReference[oaicite:0]{index=0}

```md id="3md"

---

## 8. Finding Highest and Lowest Values
Learned comparison tracking using conditions.

Example:

```java
if (s.marks > highest)
````

and

```java
if (s.marks < lowest)
```

Understood:

* maximum tracking
* minimum tracking
* comparison logic

---

## 9. Formatted Output

Learned professional console formatting using:

```java
System.out.printf()
```

Understood:

* `%s`
* `%d`
* `%f`
* `%.2f`
* `%n`

Created formatted table-style reports.

---

## 10. Console-Based Project Development

Built a complete console-based Java application.

Features:

* Dynamic student input
* Student report generation
* Average marks calculation
* Highest and lowest marks
* Formatted output

---

# Final Outcome

This project improved my understanding of:

* Java fundamentals
* Object-Oriented Programming (OOP)
* Collections Framework
* Loops and logic building
* User input handling
* Console UI formatting

It also helped me understand how real software is structured step-by-step.
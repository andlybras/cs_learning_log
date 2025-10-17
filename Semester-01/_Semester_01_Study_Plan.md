# Study Plan: Semester 01 - Foundations of Computation

This document outlines the study plan for the first semester of my self-taught journey in Computer Science, covering Calculus, Introductory Programming with Python, and Discrete Mathematics.

## 📚 Books

* **Guidorizzi, "Um Curso de Cálculo, Vol. 1"**: A classic and robust text. The progression is linear and rigorous, starting with the foundation of real numbers and functions, moving on to limits, derivatives, and finally, integrals. The theory is dense, and the exercises are crucial for consolidation.
* **Allen B. Downey, "Think Python"**: A book with an extremely practical and didactic approach. It builds programming knowledge incrementally, starting from the most basic elements of the language (variables, operators) and progressively advancing to more complex structures like functions, lists, dictionaries, and classes. Each chapter ends with exercises that directly apply the presented concepts.
* **Kenneth H. Rosen, "Discrete Mathematics and Its Applications"**: The standard reference in the field. It is a comprehensive book that covers the pillars of mathematics for computation. The initial chapters on Logic (Ch. 1), Sets, and Functions (Ch. 2) are the theoretical basis for the rest of the course and for developing algorithmic reasoning.

## 🎯 Study Plan Strategy

The plan interleaves the three books to ensure the learning process is varied and complementary. **Python programming (Thursday)** will serve as a practical tool to explore theoretical concepts from **Calculus (Friday)** and **Discrete Mathematics (Saturday)**. **Sunday** will be a day for integrated practice and review, essential for connecting the dots. Every 4 weeks, there will be a consolidation week to review and apply knowledge in a small project.

### Daily Structure (2 hours):
* **Active Review (15% - 18 min):** Review the content from the previous day in the same subject.
* **Focused Reading (45% - 54 min):** Study the theory from the designated chapters.
* **Applied Practice (40% - 48 min):** Solve exercises from the book or implement code examples.

---

## 🗓️ Detailed Study Plan (16 Weeks)

### MONTH 1: FOUNDATIONS

#### Week 1: Introduction to Programming, Functions, and Propositional Logic
* **Goal:** Learn the basic syntax of Python, understand the concept of a mathematical function, and master fundamental logical operations.
* **Materials:**
    * `Think Python`: Chapters 1 & 2.
    * `Guidorizzi`: Chapter 2 (Functions).
    * `Rosen`: Sections 1.1 to 1.3 (Propositional Logic, Equivalences).
* **Schedule:**
    * **Thursday (Python):** Variables, operators, values, and types.
    * **Friday (Calculus):** Definition of a function, domain, codomain, elementary functions.
    * **Saturday (Discrete Math):** Propositions, logical connectives, truth tables.
    * **Sunday (Review):** Write a simple Python script to evaluate a compound proposition.

#### Week 2: Functions in Python, Limits, and Predicate Logic
* **Goal:** Learn to create functions in Python, develop an intuitive notion of limits, and extend logic knowledge to predicates.
* **Materials:**
    * `Think Python`: Chapter 3 (Functions).
    * `Guidorizzi`: Chapter 3 (Limits and Continuity).
    * `Rosen`: Sections 1.4 & 1.5 (Predicates and Quantifiers).
* **Schedule:**
    * **Thursday (Python):** Defining and calling functions, variable scope, parameters.
    * **Friday (Calculus):** Intuitive definition of limits, one-sided limits, properties.
    * **Saturday (Discrete Math):** Predicates, quantifiers (∀, ∃), negation.
    * **Sunday (Review):** Create a Python function that represents a simple predicate.

#### Week 3: Flow Control, Continuity, and Rules of Inference
* **Goal:** Master conditional structures in Python, understand continuity, and learn to build valid logical arguments.
* **Materials:**
    * `Think Python`: Chapter 5 (Conditionals and Recursion).
    * `Guidorizzi`: Remainder of Chapter 3.
    * `Rosen`: Sections 1.6 & 1.7 (Rules of Inference, Introduction to Proofs).
* **Schedule:**
    * **Thursday (Python):** Boolean operators, `if/else/elif`, recursion.
    * **Friday (Calculus):** Continuity, Intermediate Value Theorem.
    * **Saturday (Discrete Math):** Modus Ponens, Modus Tollens, direct proof, proof by contraposition.
    * **Sunday (Review):** Write a function with conditionals to classify a number.

#### Week 4: Consolidation and Mini-Project 1
* **Goal:** Review and connect the concepts of functions, logic, and limits.
* **Mini-Project 1:** Write a Python program that implements a function `check_argument(p, q, r)`. The function should take boolean values for `p`, `q`, and `r` and verify if the argument `[(p → q) ∧ (q → r)] → (p → r)` (Hypothetical Syllogism) is valid.

### MONTH 2: STRUCTURES AND DERIVATIVES

#### Week 5: Iteration, Derivatives, and Sets
* **Goal:** Learn to use loops, understand the definition of a derivative, and begin the study of set theory.
* **Materials:**
    * `Think Python`: Chapter 7 (Iteration).
    * `Guidorizzi`: Chapter 7 (Derivatives).
    * `Rosen`: Sections 2.1 & 2.2 (Sets and Set Operations).
* **Schedule:**
    * **Thursday (Python):** `while` and `for` loops.
    * **Friday (Calculus):** Definition of a derivative via limits, basic rules.
    * **Saturday (Discrete Math):** Set notation, subsets, union, intersection.
    * **Sunday (Review):** Use a loop to count the even numbers from 1 to 100.

#### Week 6: Strings, Differentiation Rules, and Functions
* **Goal:** Deepen knowledge of string manipulation, master the chain rule, and study the concept of functions in Discrete Mathematics.
* **Materials:**
    * `Think Python`: Chapter 8 (Strings).
    * `Guidorizzi`: Remainder of Chapter 7.
    * `Rosen`: Section 2.3 (Functions).
* **Schedule:**
    * **Thursday (Python):** Slicing, string methods, formatting.
    * **Friday (Calculus):** Chain rule, derivatives of trigonometric and exponential functions.
    * **Saturday (Discrete Math):** Injective, surjective, bijective functions, composition.
    * **Sunday (Review):** Create a function to check if a string is a palindrome.

#### Week 7: Lists, Applications of the Derivative, and Mathematical Induction
* **Goal:** Learn to use lists, analyze function behavior with derivatives, and learn the proof by induction method.
* **Materials:**
    * `Think Python`: Chapter 9 (Lists).
    * `Guidorizzi`: Chapter 9 (Analysis of Function Variation).
    * `Rosen`: Section 5.1 (Mathematical Induction).
* **Schedule:**
    * **Thursday (Python):** Creating, accessing, slicing, and modifying lists.
    * **Friday (Calculus):** Maxima, minima, intervals of increase/decrease, concavity, curve sketching.
    * **Saturday (Discrete Math):** Principle of mathematical induction (base case and inductive step).
    * **Sunday (Review):** Calculate the average of a list of numbers using a loop.

#### Week 8: Consolidation and Mini-Project 2
* **Goal:** Review and apply concepts of loops, lists, derivatives, and induction.
* **Mini-Project 2:** Write a Python program with two `sum_of_squares(n)` functions. One should use a loop to calculate `1² + 2² + ... + n²`. The other should use the formula `n(n+1)(2n+1)/6`. Compare their results.

### MONTH 3: ADVANCED STRUCTURES AND INTEGRALS

#### Week 9: Dictionaries, Antiderivatives, and Strong Induction
* **Goal:** Learn about dictionaries in Python, understand the concept of an antiderivative, and learn strong induction.
* **Materials:**
    * `Think Python`: Chapter 10 (Dictionaries).
    * `Guidorizzi`: Chapter 10 (Antiderivatives).
    * `Rosen`: Section 5.2 (Strong Induction).
* **Schedule:**
    * **Thursday (Python):** Key-value structure. Creating, accessing, and modifying dictionaries.
    * **Friday (Calculus):** Concept of the antiderivative and the indefinite integral. Memorize immediate antiderivatives.
    * **Saturday (Discrete Math):** Difference between weak and strong induction. Use strong induction for proofs on recursively defined sequences.
    * **Sunday (Review):** Use a dictionary to count the frequency of each letter in a sentence.

#### Week 10: Tuples, The Riemann Integral, and Algorithm Analysis
* **Goal:** Understand tuples and their immutability. Learn the formal definition of an integral and begin analyzing algorithm efficiency.
* **Materials:**
    * `Think Python`: Chapter 11 (Tuples).
    * `Guidorizzi`: Chapter 11 (The Riemann Integral).
    * `Rosen`: Sections 3.1 to 3.3 (Algorithms, Growth of Functions, Complexity).
* **Schedule:**
    * **Thursday (Python):** Learn to use tuples. Understand the crucial difference between tuples and lists.
    * **Friday (Calculus):** Study Riemann Sums and the definition of the definite integral. Learn the Fundamental Theorem of Calculus.
    * **Saturday (Discrete Math):** Understand what an algorithm is and how to analyze its efficiency using Big-O notation.
    * **Sunday (Review):** Analyze the complexity (in Big-O) of the program from Mini-Project 2.

#### Week 11: Classes and Objects, Integration Techniques, and Recursion
* **Goal:** Begin studying Object-Oriented Programming. Learn techniques for calculating integrals. Deepen the study of recursion.
* **Materials:**
    * `Think Python`: Chapter 14 (Classes and Functions).
    * `Guidorizzi`: Chapter 12 (Integration Techniques).
    * `Rosen`: Sections 5.3 & 5.4 (Recursive Definitions and Recursive Algorithms).
* **Schedule:**
    * **Thursday (Python):** Learn to define your own classes and create objects. Understand the concept of attributes.
    * **Friday (Calculus):** Practice integration by parts and by substitution.
    * **Saturday (Discrete Math):** Study how to define sets and structures recursively. Analyze recursive algorithms like factorial.
    * **Sunday (Review):** Create a `Point` class in Python that stores x and y coordinates.

#### Week 12: Consolidation and Mini-Project 3
* **Goal:** Review and integrate the concepts of data structures, integration, and recursion.
* **Mini-Project 3:** In Python, write a recursive function `factorial(n)` and an iterative function `factorial_iter(n)`. Using Python's `time` module, compare the execution time of the two functions for n=5, 10, 15. Which do you expect to be faster and why?

### MONTH 4: FINAL TOPICS AND APPLICATIONS

#### Week 13: Class Methods, Applications of the Integral, and Number Theory
* **Goal:** Deepen understanding of OOP. Use integrals to calculate areas and volumes. Study divisibility and modular arithmetic.
* **Materials:**
    * `Think Python`: Chapter 15 (Classes and Methods).
    * `Guidorizzi`: Chapter 13 (Applications of the Integral).
    * `Rosen`: Section 4.1 (Divisibility and Modular Arithmetic).
* **Schedule:**
    * **Thursday (Python):** Learn to define methods within a class, including the `__init__` method.
    * **Friday (Calculus):** Learn to calculate the area between curves and the volume of solids of revolution.
    * **Saturday (Discrete Math):** Study the division algorithm, congruences, and their properties.
    * **Sunday (Review):** Add a `distance_to_origin()` method to your `Point` class.

#### Week 14: Inheritance, Differential Equations, and Primes
* **Goal:** Learn the concept of inheritance in OOP. Introduction to differential equations. Study prime numbers and the GCD.
* **Materials:**
    * `Think Python`: Chapter 17 (Inheritance).
    * `Guidorizzi`: Chapter 14 (First-Order Differential Equations).
    * `Rosen`: Section 4.3 (Primes and the GCD).
* **Schedule:**
    * **Thursday (Python):** Understand how to create classes that inherit from others (parent and child classes).
    * **Friday (Calculus):** Study separable and first-order linear differential equations.
    * **Saturday (Discrete Math):** Learn about prime numbers, the Fundamental Theorem of Arithmetic, and the Euclidean Algorithm for the GCD.
    * **Sunday (Review):** In Python, implement the iterative Euclidean Algorithm to find `gcd(a, b)`.

#### Week 15: Advanced Python Topics, Congruences, and Review
* **Goal:** Learn some extra Python features. Learn to solve systems of congruences. Review the most important topics of the semester.
* **Materials:**
    * `Think Python`: Chapter 18 (Python Extras - Sets, List Comprehensions).
    * `Guidorizzi`: Review chapters on Derivatives and Integrals.
    * `Rosen`: Section 4.4 (Solving Congruences).
* **Schedule:**
    * **Thursday (Python):** Learn to use sets for unique elements and list comprehensions for concise list creation.
    * **Friday (Calculus):** Focus on the most challenging exercises from chapters 7, 9, 11, and 12.
    * **Saturday (Discrete Math):** Study modular inverses and the Chinese Remainder Theorem.
    * **Sunday (Review):** Rewrite the code from Mini-Project 2 using a list comprehension.

#### Week 16: Final Consolidation and Mini-Project 4
* **Goal:** Solidify all acquired knowledge and apply it to a project that integrates all three areas.
* **Mini-Project 4:** "Caesar Cipher with OOP" Project. Create a `Cipher` class in Python.
    * The constructor (`__init__`) should accept a key (the shift, an integer).
    * Create an `encrypt(message)` method that takes a string and returns the encrypted message using the Caesar cipher (modular arithmetic: `(p + k) mod 26`).
    * Create a `decrypt(cipher_text)` method that reverses the process.
    * This project integrates OOP (Python), Modular Arithmetic (Discrete Math), and the concept of functions and their inverses (Calculus).
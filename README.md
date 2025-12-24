# Symbolic Control for Nonlinear Systems: Abstraction, Synthesis & Validation

This project implements the core methodology of **symbolic control for nonlinear systems**, following the framework presented in:

*"Approches symboliques pour le contrôle des systèmes non linéaires"* by Girard, Meyer, and Saoud (Techniques de l’Ingénieur, 2024).

The project covers the fundamental **three-step workflow**—**abstraction, synthesis, concretization**—and applies it to **2D and 3D mobile robot models**, providing formal guarantees for **safety, reachability, and automata-based mission specifications**.

---

## 🧠 Project Scope

This implementation focuses on the core pipeline of symbolic control:

1. **Symbolic Abstraction**  
   - Convert continuous nonlinear dynamics into **finite-state transition systems**.  
   - Represent the system with a **symbolic model** suitable for controller synthesis.

2. **Controller Synthesis**  
   - Generate controllers that enforce **safety properties**, **reachability objectives**, and **automaton-based specifications**.  
   - Leverage **formal methods** to guarantee correctness of the synthesized controllers.

3. **Concretization**  
   - Map symbolic controllers back to **continuous control laws** that can be applied to real or simulated systems.

4. **Validation**  
   - Simulate **mobile robots** under bounded disturbances.  
   - Verify that the synthesized controllers respect the specified properties in practice.

> ⚠️ Advanced topics such as multiscale abstractions, lazy abstractions, compositional methods, and data-driven abstractions are **not included** in this implementation.

---

## Features

- Symbolic abstraction of **2D and 3D nonlinear systems**  
- Controller synthesis for **safety, reachability, and automaton-based specifications**  
- Concretization of symbolic controllers to **continuous control inputs**  
- **Simulation framework** for validating the control strategies under disturbances  



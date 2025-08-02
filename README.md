# Calculator

A minimal command‑line calculator designed for **integer and floating‑point math**, implementing addition, subtraction, multiplication, division, exponentiation, modulus, and parentheses—with clean error handling and a simple REPL mode.

---

## 📚 Overview

This project provides a lightweight utility for evaluating mathematical expressions. 
It’s ideal as a learning tool, a basic scripting helper, or the foundation for building a more powerful math engine.

---

## ⚙️ Features

- Standard operators: `+`, `‒`, `*`, `/`, `^`, `%`  
- Parenthesis-aware infix parsing, including nested expressions  
- Floating-point support with user-selectable precision (default 6 decimals)  
- REPL interface: express `exit` or `quit` to leave  
- Command‑line mode: pass an expression and get a result instantly  
- Graceful error messages for syntax and math errors (e.g. division by zero)  
- Built from scratch—**no `eval()`** or external libraries

---

## 🚀 Getting Started

### Prerequisites

- A C compiler (e.g. `gcc`, `clang`) **or** a modern C++ compiler  
- Make sure `./configure` or build script runs under Unix-like OS  

### Installation & Build

```bash
git clone https://github.com/your-name/calculator.git
cd calculator
make          # or run build.sh / build.bat

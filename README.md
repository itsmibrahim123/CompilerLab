# Compiler Construction Lab (CompilerLab)

Welcome to the **Compiler Construction Lab** repository. This repository contains laboratory exercises, assignments, and projects developed as part of the Compiler Construction course (Semester 7).

## 📌 Overview

This repository is dedicated to practical implementations of compiler design phases, including:
- **Lexical Analysis (Scanner)**: Tokenization using regular expressions, manual DFA/NFA implementations, or tool-assisted scanners (Flex/Lex).
- **Syntax Analysis (Parser)**: Context-Free Grammars, top-down (LL) parsing, bottom-up (LR/SLR/LALR) parsing, and tool-assisted parsers (Bison/Yacc/PLY).
- **Semantic Analysis**: Symbol table management, type checking, and scope analysis.
- **Intermediate Code Generation (ICG)**: Abstract Syntax Trees (AST), Three-Address Code (TAC), and Quadruples/Triples.
- **Code Optimization & Target Code Generation**: Assembly/Machine code synthesis and basic block optimizations.

---

## 📁 Repository Structure

```text
CompilerLab/
├── labs/              # Weekly laboratory tasks and exercises
├── project/           # Final term compiler implementation project
├── docs/              # Lecture notes, lab specifications, and diagrams
└── README.md          # Project documentation
```

---

## 🛠️ Prerequisites & Setup

Depending on the tools required for your labs, ensure the following are installed on your environment:

### C / C++ Toolchain
- **GCC / Clang**: C/C++ Compiler
- **Flex**: Fast Lexical Analyzer Generator
- **Bison / Yacc**: Parser Generator
- **Make / CMake**: Build Automation Tools

### Python Toolchain (if applicable)
- **Python 3.x**
- **PLY (Python Lex-Yacc)** or **ANTLR4**

---

## 🚀 Getting Started

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/itsmibrahim123/CompilerLab.git
   cd CompilerLab
   ```

2. **Creating a Lab Directory**:
   ```bash
   mkdir -p labs/lab-01
   ```

---

## 📝 License & Author

- **Author**: Ibrahim ([@itsmibrahim123](https://github.com/itsmibrahim123))
- **Course**: Compiler Construction Lab

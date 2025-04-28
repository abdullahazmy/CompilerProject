# C-Minus Lexical Analyzer (Scanner)

## Overview

This project focuses on the design and implementation of a **Lexical Analyzer** (also known as a **Scanner**) for the **C-Minus Compiler** — a simplified programming language commonly used for educational purposes in compiler design courses.

The lexical analyzer forms the **first phase** of the compilation process. It is responsible for:
- Reading the source code.
- Converting it into a sequence of **tokens**, such as identifiers, keywords, symbols, numbers, and operators.

## Implementation Details

The scanner for C-Minus is inspired by the structure of the **TINY Compiler**, offering an efficient and clear method to demonstrate practical lexical analysis. It employs a **Deterministic Finite Automaton (DFA)** to:
- Recognize valid lexemes.
- Classify tokens according to the C-Minus grammar rules.

Special care was taken to properly handle:
- Whitespace
- Comments
- Lexical errors

This ensures that the token stream is clean and robust, ready for the **parsing** and **semantic analysis** phases.

## Features

- DFA-based token recognition
- Error detection and handling
- Whitespace and comment skipping
- Clear and structured token output
- Support for all C-Minus language specifications

## Project Structure

- **Source Code**: Contains the scanner implementation.
- **Documentation**: Detailed explanation of design choices, DFA structure, and language rules.
- **Test Cases**: Sample C-Minus programs to validate the scanner functionality.
- **Sample Outputs**: Example outputs showcasing successful tokenization.

## Purpose

This lexical analyzer serves as a solid foundation for building the next stages of the C-Minus Compiler, including:
- **Syntactic Analysis** (Parsing)
- **Semantic Analysis**
- **Code Generation**

## How to Run

Instructions for compiling and running the scanner will be provided in the project documentation.

---

> This project was developed as part of a compiler design course to provide a hands-on understanding of lexical analysis principles.

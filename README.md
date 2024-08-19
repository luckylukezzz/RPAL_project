# RPAL Interpreter

This project is a simple interpreter for the functional programming language RPAL (Right-Handed Applicative Language) implemented entirely in Java .
The interpreter includes a lexical analyzer, parser, and a CSE (Control Stack Environment) machine. 
It processes an RPAL program by constructing an abstract syntax tree (AST), standardizing it, and then evaluating the program to produce the final output.

## Features

- **Lexical Analyzer:** Scans the input RPAL program and converts it into a stream of tokens.
- **Parser:** Analyzes the token stream to construct the abstract syntax tree (AST).
- **AST Standardization:** Transforms the AST into a standardized form for simpler evaluation.
- **CSE Machine:** Evaluates the standardized AST using a Control Stack Environment model to generate the program's output.

## Getting Started

### Prerequisites

- Java Development Kit (JDK) version 8 or higher.

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/rpal-interpreter.git
   cd rpal-interpreter

# Custom Language Compiler

Welcome to the Custom Language Compiler project! This compiler is built using TypeScript and Deno, providing a secure and efficient environment for language translation and execution.

## Overview

The Custom Language Compiler is designed to translate source code written in our custom programming language into machine-executable instructions. Leveraging the power of TypeScript, it offers robust static typing and language features, ensuring type safety and expressiveness throughout the compilation process.

## Features

- Lexical analysis: Tokenizes the input source code, breaking it down into meaningful tokens.
- Syntax parsing: Parses the sequence of tokens according to the language's syntax rules, constructing a parse tree or abstract syntax tree (AST).
- Semantic analysis: Conducts semantic validations such as type checking and scope resolution, ensuring the correctness and reliability of the compiled program.
- Code generation: Translates the abstract representation into executable machine code or an intermediate representation, potentially optimizing performance along the way.

## Getting Started

### Prerequisites

- [Deno](https://deno.land/) (Version X.X.X)
- [TypeScript](https://www.typescriptlang.org/) (Version X.X.X)

### Installation

1. Clone the repository: 
2. Navigate to the project directory: 
3. Install dependencies: `deno install --unstable --allow-read --allow-write --name=custom-language-compiler src/main.ts`

### Usage

1. Create a source file in our custom language (e.g., `example.cl`)
2. Compile the source file: `custom-language-compiler example.cl`
3. Execute the compiled program: `./example`

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to improve the compiler.

t

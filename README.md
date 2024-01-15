# Mini Linux Shell 

This project is a simple implementation of a shell program using Lex and Yacc. The shell serves as a command-line interface for interacting with an operating system.

## Table of Contents
- Background
- Prerequisites
- Installation
- Usage

## Background
The mini shell program is built using two essential tools: Lex and Yacc.

- **Lex** defines the lexical structure of the shell, including keywords, operators, and special symbols. It transforms these components into tokens that Yacc can process effectively.
- **Yacc** outlines the grammar and syntax of the shell. It takes the tokens produced by Lex, uses them to construct the structure of shell commands, and implements the necessary actions for executing these commands, such as invoking system functions or running external programs.

The collaboration between Lex and Yacc provides a simple yet robust framework for developing a shell program. This project is an excellent choice for gaining insights into shell programming and understanding the fundamentals of parsing.

## Prerequisites
Before running the mini shell program, ensure that you have the following:

- **Operating System**: Linux (Ubuntu)
- **Required Software**: C Compiler, Make
- **Additional Tools**: Bison, Flex

## Installation
You can install the required tools on Ubuntu using the following commands:

For C Compiler and Make:
```bash
sudo apt-get update
sudo apt-get install build-essential

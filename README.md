# Morse Code Assembly Program

This project implements International Morse Code using assembly language. It includes predefined Morse code sequences for numbers and letters, along with basic integer operations like multiplication and division.

## Features
Morse Code Sequences: The program defines Morse code for the numbers 0-9 and letters A-Z using a combination of dots, dashes, and end markers.
Basic Integer Operations: Implements unsigned multiplication and division subroutines to handle basic arithmetic.

## Files: 
morse_codes.asm: The main assembly file that contains:
- Definitions for Morse code sequences of letters and numbers.
- Integer subroutines for unsigned multiplication and division.
- Morse Code Mapping

## The following Morse code mappings are defined:

### Numbers:
- 0: DASH,DASH,DASH,DASH,DASH
- 1: DOT,DASH,DASH,DASH,DASH
- (and so on for all numbers 0-9)
### Letters:
- A: DOT,DASH
- B: DASH,DOT,DOT,DOT
- (and so on for all letters A-Z)

## Integer Operations
- Multiplication (MPYU): Performs unsigned multiplication of two integers.
- Division (DIVU): Performs unsigned division of a 32-bit value by a 16-bit divisor, returning the quotient and remainder.

## Usage
To assemble and run the program, use an assembler suitable for your target architecture (e.g., MSP430) and follow the steps for linking and loading the program onto your microcontroller.


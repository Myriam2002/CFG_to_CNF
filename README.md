# Conversion of Context-Free Grammar to Chomsky Normal Form 🌠

This repository provides a tool for converting a given Context-Free Grammar (CFG) into Chomsky Normal Form (CNF). The project aims to simplify and transform CFGs into a more standardized form that allows for efficient parsing and analysis.

## Overview 💫

Context-Free Grammars are widely used in formal language theory and natural language processing. Chomsky Normal Form is a specific form of CFG that has specific rules and restrictions, making it easier to analyze and process. This project focuses on converting CFGs to CNF to facilitate various language processing tasks.

## Implementation 👩‍💻

The implementation consists of a Python script that takes a CFG as input and performs the necessary transformations to convert it into Chomsky Normal Form. The script handles the following operations:

1. **Add new start** 
2. **Elimination of ε-productions** (productions that generate the empty string).
3. **Removal of unit productions** (productions with a single non-terminal on the right-hand side).
4. **Remove useless productions** (Non-reachable and non-generating)
5. **Convert to Chomsky form**
  -   Conversion of long productions (productions with more than two non-terminals on the right-hand side) into shorter productions.
  -   Introduction of new non-terminals to replace terminals in productions.


# Theoretical-Informatics

NFA Regex Engine
This project implements a Non-deterministic Finite Automaton (NFA) for regular expression processing. It consists of two main components:

- NFA Construction (build.cpp):
This file contains the logic for building an NFA from a given regular expression. The regular expression is parsed and transformed into a state machine, where transitions between states are defined based on the regex pattern. 

- NFA Simulation (run.cpp):
This file simulates the behavior of the constructed NFA. It processes an input string symbol by symbol and determines if the input is accepted by the NFA. Checks whether the NFA reaches an accepting state after each symbol, allowing for dynamic regex matching.


# CSCE652-C3
## Ghidra Data Tracer Script (Tentative Name)

## Executive Summary
Here, we propose a reverse engineering script for Ghidra. We refer to this as the Ghidra Data Tracer Script. We aim to create a Ghidra script which is able to trace and symbolically represent data flow in a program for all values either gotten through standard input (stdin) or present at initialization (init) or read from files through standard I/O operations. Further, we aim to generate a data-tracing tree from our calculated data-flow. This data-tracing tree would visually represent the program dataflow, and provide the user with a valuable visual reference for figuring out how a program works.

Our project differs from existing symbolic execution projects. Traditionally, symbolic execution projects require the user to set variables, data, or inputs as symbols in order to solve for a configuration that produces a set of desired results. The goal of our project is simply to produce a data tracing tree efficiently, and will instead automatically declare symbols while attempting to calculate the data tracing tree. The major technical achievement of this project will be developing the algorithms for computing the data tracing tree symbolically in an admissibly efficient manner (it is computationally infeasible to just assume everything is a symbol and compute from there, but there are techniques to get around this like doing a few symbols at a time, pruning branches of the execution, etc).


## Dependencies

## Installation Guide

## Usage Guide

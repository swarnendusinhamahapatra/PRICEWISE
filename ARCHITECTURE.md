# System Architecture

## Overview
PRICEWISE follows a modular pipeline separating data storage, processing logic, and testing.

## Data Flow
`data/` (Inputs) -> `src/` (Processing & Models) -> Output / Interface

## Directory Responsibilities
- **`data/`**: Stores raw inputs and cleaned datasets (ignored by Git).
- **`src/`**: Contains production-ready Python modules.
- **`notebooks/`**: Used only for prototyping before moving code to `src/`.
- **`tests/`**: Mirrors `src/` to verify functionality.

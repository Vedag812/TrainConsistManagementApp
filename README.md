# Train Consist Management App

Java practice project built around train consist operations, collection handling, search/sort logic, validation, and exception handling.

This repository is organized as a progression of small, focused use cases. The `main` branch starts with the base application, and the feature branches show how the system was expanded step by step into a more complete portfolio project.

## What this repo shows

- Core Java fundamentals applied to a real domain
- Incremental feature development across independent branches
- Use of collections, streams, regex, custom exceptions, and search algorithms
- A clean learning path from a starter app to a broader train-management workflow

## Branch progression

The repository history is intentionally structured so each branch demonstrates one specific capability:

- `main` - Base application setup
- `feature/UC1` - Initialize train and display consist summary
- `feature/UC2` - Add passenger bogies with `ArrayList`
- `feature/UC3` - Track unique bogie IDs with `HashSet`
- `feature/UC4` - Maintain ordered bogie IDs with `TreeSet`
- `feature/UC5` - Preserve insertion order with `LinkedHashSet`
- `feature/UC6` - Map bogies to capacity with `HashMap`
- `feature/UC7` - Sort bogies by capacity with `Comparator`
- `feature/UC8` - Filter passenger bogies using streams
- `feature/UC9` - Group bogies by type
- `feature/UC10` - Count total seats in a train
- `feature/UC11` - Validate train IDs and cargo codes with regex
- `feature/UC12` - Safety compliance checks for goods bogies
- `feature/UC13` - Compare loops vs streams
- `feature/UC14` - Handle invalid bogie capacity with a custom exception
- `feature/UC15` - Safe cargo assignment with `try-catch-finally`
- `feature/UC16` - Safe cargo assignment refinement
- `feature/UC17` - Sort bogie names using `Arrays.sort()`
- `feature/UC18` - Linear search for bogie IDs
- `feature/UC19` - Binary search for bogie IDs
- `feature/UC20` - Exception handling during search operations




## Current codebase

The `main` branch is intentionally lightweight and currently contains the application scaffold. That keeps the repo easy to navigate while the feature branches document the full learning and implementation path.

## Tech areas demonstrated

- Java core syntax and program structure
- Collections framework
- Streams and sorting
- Search algorithms
- Regex validation
- Exception handling
- Functional-style iteration and performance comparison

## Project structure

```text
src/
├── Main.java
└── TrainConsistManagementApp.java
```

## Run locally

1. Open the project in IntelliJ IDEA, VS Code, or another Java IDE.
2. Run `src/Main.java`.

If you want to expand this into a polished production-style project, the next step would be to add a domain model for trains and bogies, then connect each use case to a shared application flow.

## Author

Vedant Agarwal
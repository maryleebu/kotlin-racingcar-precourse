# kotlin-racingcar-precourse
## Description
A simple text-based car racing game built with Kotlin 1.9.24, with the aim of self-teaching kotlin. Users can input car names and the number of rounds. Each car progresses based on random chance. The program simulates the race round-by-round and announces the winner(s) at the end.
## Features
- User-defined car names (comma-separated, max 5 characters each)
- User-defined number of race rounds
- Random movement (cars move forward if random number ≥ 4)
- Visual race progress per round
- Supports multiple winners in case of a tie
- Input validation with meaningful error handling (no external termination calls)
- Fully implemented in Kotlin 1.9.24 following Kotlin coding conventions
- Unit tested with Visual Studio Code

## How to run 
Ensure Kotlin 1.9.24 is installed and available in your PATH.
- Use your IDE (e.g., IntelliJ or VS Code) to run the main() function inside the Application class.

## Running tests
Tests are written with JUnit 5 and AssertJ. To run them:

./gradlew test

Tests are located in:

src/test/kotlin/CarRacingGameTest.kt

## Code structure
src/
├── main/
│   └── kotlin/
│       └── Application.kt      # Entry point
├── test/
│   └── kotlin/
│       └── CarRacingGameTest.kt # Unit tests

## Requirements met
- Kotlin 1.9.24 only
- Entry point is main() inside Application class
- No Java code or System.exit()
- Max indentation depth: 2
- Complies with Kotlin Coding Conventions
- No changes to build.gradle.kts

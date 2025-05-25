# Java Advanced: Stream API, Lambda, and Date Handling (Task 5)

This repository contains Java programs demonstrating advanced Java concepts such as the Stream API, lambda expressions, and date handling with the `java.time` package. The project includes solutions to four tasks (Q1.1 to Q1.4) focusing on string manipulation, filtering, and age calculation.

## Project Structure

- **QuestionOne.java**: Converts a list of strings to uppercase using the Stream API (Q1.1).
- **QuestionTwo.java**: Filters out empty strings from a list and prints non-empty strings (Q1.2).
- **QuestionThree.java**: Filters student names starting with "A" using Stream API and lambda expressions (Q1.3).
- **QuestionFour.java**: Calculates a user's age based on their birthdate using `java.time.LocalDate` (Q1.4).
- **1.png, 2.png, 3.png, 4.png**: Screenshots of the code implementations for each task.

## Tasks Overview

### Q1.1: Convert Strings to Uppercase Using Stream API
- Uses the `Stream` API to convert a list of strings to uppercase.
- Input: `Stream names = Stream.of("aBc", "d", "ef")`.
- Output: A list of strings in uppercase (`ABC`, `D`, `EF`).

### Q1.2: Filter Non-Empty Strings
- Checks a list of strings for empty elements and prints only the non-empty strings.
- Input: `List<String> strings = Arrays.asList("abc", "", "bc", "efg", "abcd", "", "jkl")`.
- Output: A list containing only non-empty strings (`abc`, `bc`, `efg`, `abcd`, `jkl`).

### Q1.3: Filter Students Whose Names Start with "A"
- Simulates a classroom scenario with 10 students.
- Uses a `List` to store student names and the Stream API with a lambda expression to filter names starting with "A".
- Output: A list of student names starting with "A".

### Q1.4: Age Calculator Using LocalDate
- Takes a user's birthdate as input in the format `yyyy-mm-dd` (e.g., `1990-05-15`).
- Calculates the user's age in years, months, and days using `java.time.LocalDate`.
- Example Output: `Your age is: 33 years, 4 months, and 13 days`.

## How to Run

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/thesoulseizure/task-5.git
   ```
2. **Navigate to the Project Directory**:
   ```bash
   cd task-5
   ```
3. **Compile the Java Files**:
   ```bash
   javac *.java
   ```
4. **Run the Desired Program**:
   - For Q1.1: `java QuestionOne`
   - For Q1.2: `java QuestionTwo`
   - For Q1.3: `java QuestionThree`
   - For Q1.4: `java QuestionFour`

## Requirements

- Java Development Kit (JDK) 8 or higher (JDK 8+ required for `java.time` package).
- A terminal or IDE to compile and run Java programs.

## Screenshots

The repository includes screenshots (1.png to 4.png) that show the code implementations for each task. Refer to these images to view the solutions visually.

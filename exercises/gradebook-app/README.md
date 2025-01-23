# Gradebook App

This exercise provides a simple set of functions to calculate class averages, determine individual grades, and provide feedback for students based on their scores.

## Features

- **Calculate Class Average:** Computes the average of an array of scores.
- **Determine Grade:** Assigns a letter grade (A++ to F) based on a score.
- **Check Passing Status:** Determines whether a score passes the course.
- **Student Feedback Message:** Generates a message containing the class average, the student's grade, and a pass/fail status.

## Functions

### `getAverage(scores)`

Calculates the average of an array of scores.

- **Parameters:**
  - `scores` (Array): An array of numerical scores.
- **Returns:**
  - The average of the scores (Number).

### `getGrade(score)`

Converts a numerical score into a letter grade.

- **Parameters:**
  - `score` (Number): The score to convert.
- **Returns:**
  - A letter grade (`A++`, `A`, `B`, `C`, `D`, `F`).

### `hasPassingGrade(score)`

Checks if a score is passing.

- **Parameters:**
  - `score` (Number): The score to evaluate.
- **Returns:**
  - `true` if the grade is not "F", otherwise `false`.

### `studentMsg(totalScores, studentScore)`

Generates a feedback message for a student.

- **Parameters:**
  - `totalScores` (Array): An array of all class scores.
  - `studentScore` (Number): The student's individual score.
- **Returns:**
  - A message indicating the class average, the student's grade, and whether they passed or failed.

## Example Usage

```javascript
console.log(studentMsg([92, 88, 12, 77, 57, 100, 67, 38, 97, 89], 37));
```

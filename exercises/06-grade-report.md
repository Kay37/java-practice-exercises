# EXERCISE 6: Grade Report with Methods ⭐

*Focus: static methods*

## Step 1

Create a Java application called `grade-report` with a class called `GradeApplication`.

Ask for a student's name and three whole-number test scores. Use these static methods:

- `getScore(String prompt)`: shows the prompt, reads an `int`, returns it
- `calculateAverage(int a, int b, int c)`: returns the average as a `double`
- `getLetterGrade(double average)`: returns `A` (90+), `B` (80-89), `C` (70-79), `D` (60-69) or `F`

Show the average with 2 decimal places. Use the **conditional operator** to also show `Passed`
(70 or higher) or `Needs work`.

```
Student name: Maya ↵
Score 1: 88 ↵
Score 2: 92 ↵
Score 3: 79 ↵
Report for Maya
Average: 86.33
Grade: B (Passed)
```

### Skills to use

- Three static methods, each with **parameters and a return value**
- A static `Scanner` shared by `main` and `getScore`
- `nextInt()`
- **Casting** with `(double)`
- An `if` / `else if` chain, from the highest grade to the lowest
- The **conditional operator** `? :`
- `printf` with `%.2f`

### Try also

- Have `getLetterGrade` return a `char` instead of a `String`. What else has to change?
- Use `Math.max()` from Workbook 1c's Math class to add a line: `Highest score: 92`

> **Think about:** if your average always ends in `.00`, look at what happens when you divide an
> `int` by an `int`.

## Step 2

1. Commit and push your changes to GitHub.

---

[← Previous](05-movie-kiosk.md) · [Back to the list](../README.md) · [Next: Bill Splitter →](07-bill-splitter.md)

# Java Practice Exercises: Strings, Methods & switch

Eight extra practice exercises for Java beginners, written in the same style as our class workbooks.
They cover **Workbook 1c** and **Workbook 2a up to "Converting a String to a Number"**.

These are original practice problems, not official course material.

## What you need to know

Only things covered so far: variables, operators, casting, `printf`, `Scanner`, `if`/`else`,
`switch`, the conditional operator (`? :`), static methods, String methods, `split()`,
and `Integer.parseInt()` / `Double.parseDouble()`.

**No loops yet.** Each program runs once and ends.

## How to use them

- Make a folder like `pluralsight/practice-2a` and create one IntelliJ project per exercise.
- Each exercise lists **Skills to use** (needed) and **Try also** (extra practice).
- In the sample traces, each prompt is followed by what the user types. **↵** means the user pressed ENTER.
- Run your program with the same input as the trace and check that your output matches.
- The **Think about** notes point at common traps. They're questions, not answers.

## The exercises

| # | Exercise | Concepts practiced |
|---|---|---|
| 1 | [Initials Maker](exercises/01-initials-maker.md) | `nextLine()`, `trim()`, `toUpperCase()`, `toLowerCase()`, `length()`, `charAt()` and `char`, joining Strings with `+` |
| 2 | [Email Splitter](exercises/02-email-splitter.md) | `indexOf()`, `substring()`, `endsWith()`, `if` / `else if` / `else`, a static method that returns a String |
| 3 | [Concert Ticket Reader](exercises/03-ticket-reader.md) | `split()` and arrays, `Integer.parseInt()`, `equals()`, `if` / `else if` / `else`, comparing numbers |
| 4 | [Password Checker](exercises/04-password-checker.md) | static methods that return a `boolean`, `equals()` vs `equalsIgnoreCase()`, `indexOf()`, `\"` inside a String, separate `if`s |
| 5 | [Movie Ticket Kiosk](exercises/05-movie-kiosk.md) ⭐ | `switch` on an `int`, static methods, conditional operator `? :`, `nextInt()` + `nextLine()`, `printf` |
| 6 | [Grade Report with Methods](exercises/06-grade-report.md) ⭐ | static methods with parameters and returns, a shared `Scanner`, casting, `if` / `else if` chain, conditional operator `? :`, `printf` |
| 7 | [Bill Splitter](exercises/07-bill-splitter.md) | `split()` on a `\|`, `Double.parseDouble()`, `Integer.parseInt()`, a static method, `int / int` division, `printf` with `%%` |
| 8 | [Coffee Order (Challenge)](exercises/08-coffee-order.md) | `switch` on a String, conditional operator `? :`, `split()`, `Integer.parseInt()`, static methods, `printf` |

⭐ = extra practice on `switch` and static methods.

The exercises get a little harder as you go, so doing them in order works well.

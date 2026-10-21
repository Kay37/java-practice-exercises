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

| # | Exercise | Main focus |
|---|---|---|
| 1 | [Initials Maker](exercises/01-initials-maker.md) | String methods, `charAt()` |
| 2 | [Email Splitter](exercises/02-email-splitter.md) | `indexOf()`, `substring()`, methods that return a String |
| 3 | [Concert Ticket Reader](exercises/03-ticket-reader.md) | `split()`, `parseInt()`, `if`/`else if` |
| 4 | [Password Checker](exercises/04-password-checker.md) | `boolean` methods, comparing Strings |
| 5 | [Movie Ticket Kiosk](exercises/05-movie-kiosk.md) ⭐ | `switch`, static methods, conditional operator |
| 6 | [Grade Report with Methods](exercises/06-grade-report.md) ⭐ | static methods, casting |
| 7 | [Bill Splitter](exercises/07-bill-splitter.md) | splitting on `\|`, `parseDouble()`, `printf` |
| 8 | [Coffee Order (Challenge)](exercises/08-coffee-order.md) | everything together |

⭐ = extra practice on `switch` and static methods.

## Which exercises practice what

| Skill | Exercises |
|---|---|
| `switch` | **5**, **8** (try also: 2, 3, 7) |
| `if` / `else if` / `else` | 2, 3, 4, 6, 8 |
| Conditional operator `? :` | 5, 6, 8 (try also: 3) |
| Static methods with returns | 2, 4, 5, 6, 7, 8 |
| `boolean` methods | **4** |
| `split()` + arrays | 3, 7, 8 |
| `indexOf()` / `substring()` | **2**, 4 |
| `parseInt` / `parseDouble` | 3, 7, 8 |
| Casting / division traps | 6, 7 |
| `nextInt()` + `nextLine()` | 5, 6 |

The exercises get a little harder as you go, so doing them in order works well.

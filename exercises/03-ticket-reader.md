# EXERCISE 3: Concert Ticket Reader

## Step 1

Create a Java application called `ticket-reader` with a class called `TicketApplication`.

A ticket code looks like `GENRE-SEAT-SECTION`, for example `ROCK-0412-VIP`. Ask the user for a ticket
code and accept lowercase too. Split it into its three parts and display each one. Turn the seat into
an `int`.

Then print directions:

- Section `VIP` → `Head to the side entrance.`
- Section `GA` → `Use the main entrance.`
- Anything else → `Please see the box office.`
- Seat **over 500** → `Your seat is on the upper level.` Otherwise → `Your seat is on the lower level.`

```
Enter your ticket code: rock-0412-vip ↵
Genre: ROCK
Seat: 412
Section: VIP
Head to the side entrance.
Your seat is on the lower level.
```

```
Enter your ticket code: JAZZ-0733-GA ↵
Genre: JAZZ
Seat: 733
Section: GA
Use the main entrance.
Your seat is on the upper level.
```

### Skills to use

- `split("-")` and array boxes `[0]`, `[1]`, `[2]`
- `Integer.parseInt()`
- `toUpperCase()`
- `equals()` to compare Strings (**not** `==`)
- `if` / `else if` / `else` for the section
- A number comparison (`>`) for the seat

### Try also

- The **conditional operator** (`? :`) for upper vs. lower level
- A static method `getEntrance(String section)` that uses a **`switch`** and returns the directions

> **Think about:** the code says `0412` but the trace shows `412`. Which step made that happen?

## Step 2

1. Commit and push your changes to GitHub.

---

[← Previous](02-email-splitter.md) · [Back to the list](../README.md) · [Next: Password Checker →](04-password-checker.md)

# EXERCISE 5: Movie Ticket Kiosk ⭐

*Focus: `switch` and static methods*

## Step 1

Create a Java application called `movie-kiosk` with a class called `KioskApplication`.

Show a ticket menu. Ask for a ticket type (as a number), how many tickets, and whether it's a matinee
(`y`/`n`).

| Type | Name | Price |
|---|---|---|
| 1 | Child | $8.50 |
| 2 | Adult | $13.00 |
| 3 | Senior | $9.75 |
| 4 | Student | $10.25 |

- Write a static method `getTicketPrice(int type)` that uses a **`switch`** and returns the price.
- Write a static method `getTicketName(int type)` that uses a **`switch`** and returns the name.
- A matinee takes **$2.00 off each ticket**. Work out the discount with the **conditional operator**.
- Any other type number prints `That's not a ticket type.`

```
Welcome to the Starlight Cinema!
1) Child    $8.50
2) Adult    $13.00
3) Senior   $9.75
4) Student  $10.25
Pick a ticket type (1-4): 2 ↵
How many tickets? 3 ↵
Is this a matinee? (y/n): y ↵
3 Adult ticket(s), matinee
Total: $33.00
```

```
Pick a ticket type (1-4): 7 ↵
That's not a ticket type.
```

### Skills to use

- A **`switch` on an `int`**, with `case`, `break` and `default`
- Two static methods: one returns a `double`, the other a `String`
- `nextInt()` followed by `nextLine()`, handling the leftover line separator
- `equalsIgnoreCase("y")`
- The **conditional operator** `? :`
- `printf` with `%.2f`

### Try also

- A constant: `public static final double MATINEE_DISCOUNT = 2.00;`
- A small helper method that shows a prompt and returns the trimmed answer, for the y/n question

> **Think about:**
> - If the matinee question gets skipped before you can type, look back at "Consuming a Line
>   Separator" in Workbook 1c.
> - What should `getTicketPrice` return in its `default` so `main` knows the type was wrong?

## Step 2

1. Commit and push your changes to GitHub.

---

[← Previous](04-password-checker.md) · [Back to the list](../README.md) · [Next: Grade Report →](06-grade-report.md)

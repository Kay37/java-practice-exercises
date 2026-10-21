# EXERCISE 7: Bill Splitter

## Step 1

Create a Java application called `bill-splitter` with a class called `BillApplication`.

Ask the user to type the bill on **one line**, as `restaurant|total|people`. Split it on the pipe
(`|`), and turn the total into a `double` and the people into an `int`. Then ask for a tip percent as
a whole number (15, 18 or 20).

Write a static method `calculateTip(double total, int percent)` that returns the tip amount. Display
every amount with 2 decimal places.

```
Enter the bill (restaurant|total|people): Burger Barn|47.80|3 ↵
Tip percent (15, 18, or 20): 20 ↵
Restaurant: Burger Barn
Subtotal: $47.80
Tip (20%): $9.56
Total: $57.36
Each person pays: $19.12
```

### Skills to use

- `split()` on a pipe: `"\\|"` or `Pattern.quote("|")`, with its `import`
- `Double.parseDouble()` and `Integer.parseInt()`
- A static method that takes a `double` and an `int` and returns a `double`
- Avoiding **`int / int`** division
- `printf` with `%.2f`, `%s` and `%%`

### Try also

- A **`switch`** that only accepts 15, 18 or 20, with `default` printing `Please choose 15, 18, or 20.`

> **Think about:**
> - What is `20 / 100` in Java?
> - `printf` uses `%` for placeholders, so how do you print an actual `%` sign?

## Step 2

1. Commit and push your changes to GitHub.

---

[← Previous](06-grade-report.md) · [Back to the list](../README.md) · [Next: Coffee Order →](08-coffee-order.md)

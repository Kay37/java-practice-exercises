# EXERCISE 8 (Challenge): Coffee Order

## Step 1

Create a Java application called `coffee-order` with a class called `CoffeeApplication`. This one uses
a bit of everything.

Ask for an order on one line, as `size|drink|quantity|milk`. Then:

- Write a static method `getSizePrice(String size)` with a **`switch` on the size**: small **$3.25**,
  medium **$3.95**, large **$4.50**. Capitals shouldn't matter.
- Milk: `regular` adds nothing. Any other milk adds **$0.75** per drink. Use the **conditional operator**.
- An unknown size prints `Sorry, we don't have a '<size>' size.` and no receipt.
- Use at least **two** static methods besides `main`.

```
Enter your order (size|drink|quantity|milk): Large|Latte|2|oat ↵
--- Receipt ---
Drink: 2 x Large Latte
Milk: oat (+$0.75 each)
Price each: $5.25
Total: $10.50
```

```
Enter your order (size|drink|quantity|milk): medium|Cold Brew|1|regular ↵
--- Receipt ---
Drink: 1 x medium Cold Brew
Milk: regular
Price each: $3.95
Total: $3.95
```

```
Enter your order (size|drink|quantity|milk): Huge|Mocha|1|oat ↵
Sorry, we don't have a 'Huge' size.
```

### Skills to use

- `split()` on a pipe, and `Integer.parseInt()`
- A **`switch` on a String** (after `toLowerCase()`), with `default`
- The **conditional operator** for the milk charge
- At least **two** static methods that return values
- An `if` that stops the receipt when the size is unknown, using a "not found" value like `-1`
- `printf` for the receipt

### Try also

- Constants for the prices, for example `public static final double SMALL_PRICE = 3.25;`
- A **text block** (`"""`) with `String.format()` for the receipt

> **Think about:** how can `getSizePrice` tell `main` that the size wasn't found?

## Step 2

1. Commit and push your changes to GitHub.

---

[← Previous](07-bill-splitter.md) · [Back to the list](../README.md)

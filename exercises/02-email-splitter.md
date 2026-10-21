# EXERCISE 2: Email Splitter

## Step 1

Create a Java application called `email-splitter` with a class called `EmailApplication`.

Ask the user for an email address. Trim it and make it lowercase. Display the **username** (before
the `@`) and the **domain** (after the `@`). Use `indexOf()` and `substring()` here, **not** `split()`.

Write a static method `getDomainType(String domain)` that **returns** a String:

- ends with `.org` → `Organization`
- ends with `.edu` → `School`
- ends with `.com` → `Company`
- anything else → `Other`

If there's no `@` at all, print a message and skip the rest.

```
Enter your email:   Maya.Torres@Example.org   ↵
Username: maya.torres
Domain: example.org
Type: Organization
```

```
Enter your email: maya.torres ↵
That doesn't look like an email address.
```

### Skills to use

- `indexOf()`, plus `substring()` with **one** and with **two** numbers
- `trim()`, `toLowerCase()`, `endsWith()`
- `if` / `else if` / `else`
- A static method that **returns a String**
- An `if`/`else` that keeps the rest of the program from running when there's no `@`

### Try also

- In `getDomainType`, take the **last 4 characters** of the domain and use a **`switch` on that
  String** (`case ".org":` and so on) instead of `endsWith()`

> **Think about:** what does `indexOf()` give back when it can't find what you asked for?

## Step 2

1. Commit and push your changes to GitHub.

---

[← Previous](01-initials-maker.md) · [Back to the list](../README.md) · [Next: Concert Ticket Reader →](03-ticket-reader.md)

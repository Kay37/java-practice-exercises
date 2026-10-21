# EXERCISE 4: Password Checker

## Step 1

Create a Java application called `password-checker` with a class called `PasswordApplication`.

Ask the user to create a username and password, then type the password again to confirm it. Check
these rules, each in its **own static method that returns a `boolean`**:

1. The password is at least 8 characters.
2. The password isn't the word `password`, in any capitals.
3. The password doesn't contain the username.
4. The confirmation matches the password **exactly**.

Print a message for **every** rule that fails. If none fail, print `Account created for <username>!`

```
Create a username: mtorres ↵
Create a password: java2026 ↵
Confirm your password: java2026 ↵
Account created for mtorres!
```

```
Create a username: mtorres ↵
Create a password: PassWord ↵
Confirm your password: Password ↵
Your password can't be "password".
Your passwords don't match.
```

### Skills to use

- Four static methods that each **return a `boolean`**
- `length()`, `equalsIgnoreCase()`, `equals()`
- `indexOf()` with `!= -1` to check whether one String is inside another
- `\"` to put quotes inside a String
- **Separate `if`s, not `else if`**, so every failed rule prints

### Try also

- A `boolean` variable like `allGood`, using `&&` (and) or `!` (not), to decide whether to print
  "Account created"

> **Think about:** Workbook 2a warns about one way of comparing Strings. Which comparison belongs
> in rule 4?

## Step 2

1. Commit and push your changes to GitHub.

---

[← Previous](03-ticket-reader.md) · [Back to the list](../README.md) · [Next: Movie Ticket Kiosk →](05-movie-kiosk.md)

# EXERCISE 1: Initials Maker

## Step 1

Create a Java application called `initials-maker` with the GroupId `com.pluralsight`. Make a package
named `com.pluralsight` and add a class called `InitialsApplication` for the `main()` method.

Ask the user for their first name and last name. Trim whatever they type. Then display:

- their **initials**, in capitals, each followed by a period
- a **username**: the first letter of their first name plus their whole last name, all lowercase
- the total number of letters in their first and last names

```
First name:   maya ↵
Last name: Torres ↵
Initials: M.T.
Username: mtorres
Your name has 10 letters.
```

### Skills to use

- `Scanner` with `nextLine()`
- `trim()`, `toUpperCase()`, `toLowerCase()`, `length()`
- `charAt()` and the `char` type
- String joining with `+`

### Try also

- A static method `getInitial(String name)` that returns one initial, like `"M."`
- `printf` with `%s` and `%d` for the output

> **Think about:** `charAt()` doesn't return a String. If you see a number where you expected
> letters, ask yourself what type it does return, and what `+` does with two of those.

## Step 2

1. Commit and push your changes to GitHub.

---

[Back to the list](../README.md) · [Next: Email Splitter →](02-email-splitter.md)

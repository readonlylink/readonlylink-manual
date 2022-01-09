---
title: Dialog List Item
subtitle: Dan's Little Books style dialog
---

To use **Dialog List Item** extensions,
name a item by `dialog`, like the following:

# Example dialog

- [dialog]

  - What is number?

  - Number is about counting.

    1, 2, 3, ...

  - We should starting from 0.

  - Ok,

    0, 1, 2, 3, ...

  - That's much better!

  - What's next?

``` plaintext
- [dialog]

  - What is number?

  - Number is about counting.

    1, 2, 3, ...

  - We should starting from 0.

  - Ok,

    0, 1, 2, 3, ...

  - That's much better!

  - What's next?

```

# About indexing

Multiple dialogs in the same document will share the same indexing.

- [dialog]

  - What's after 3?

  - 4, 5, 6, ...

  - How many numbers are there?

  - Infinitely many!

# Reminder

We can also use **Reminder List Item** extensions,
to render reminder cards of *Rules* and *Laws* in the little books:

- [reminder] Natural Number

  - We can construct natural number, by `zero` and `add1`.

``` plaintext
- [reminder] Natural Number

  - We can construct natural number, by `zero` and `add1`.
```

Another one, from "The Little Typer":

- [reminder] Everything Is an Expression

  - In some languages (such as Pie), values are also expressions.
    Evaluation such languages finds an expression,
    not some other kind of thing.

## Multiple reminder entries

- [reminder] Before type theory

  - In programming, we do *not* write types, we only write terms.

  - In logic, we do *not* write terms, we only write types
    -- propositions and their inference rules.

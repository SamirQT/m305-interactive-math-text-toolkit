# Interactive Math Toolkit: GCD/LCM, Calculator & Digit Tools
---
## Assignment Overview

In this project, you will write a single Python script—`M305_toolkit.py`—that presents an interactive menu offering four math utilities plus exit. You will use only primitive types, loops, conditionals, and basic I/O (`input()`/`print()`). No error-handling constructs or advanced data structures are required.

---

## Objectives

By completing this assignment, you will:

* Build a **menu loop** (`while True` with `if`/`elif`/`else`) to dispatch user choices.
* Compute the **greatest common divisor** (GCD) via the Euclidean algorithm and derive the **least common multiple** (LCM).
* Perform four basic arithmetic operations (`+`, `-`, `*`, `/`) on two numbers.
* Calculate the **sum of digits** of an integer using modulo and integer division.
* Check whether an integer is a **palindrome** by reversing its digits.
* Pause after each operation so the user can read the results.

---

## Instructions

1. **File**

   * Name your file `M305_toolkit.py`.
   * No `main()` or modules—everything in one script.


## Technical Requirements

* **Single File:** `M305_toolkit.py` only.
* **I/O:** Use only `input()` and `print()`.
* **Data Types:** `int`, `float`, `str`, `bool`.
* **Flow Control:** `while`, `for`, `if`/`elif`/`else`.
* **No Error Handling:** Assume all inputs are valid.
* **No Collections:** Do not use lists, dictionaries, or imports beyond Python built-ins.

---

## Deliverable

* **`M305_toolkit.py`** containing the complete interactive script.

---

## Scenarios

Below are the scenario runs covering **every** menu option in `M305_toolkit.py`. For brevity, “Press Enter…” pauses are shown as comments.

---

### Scenario 1 – GCD & LCM Calculator

```
=== Math Toolkit ===
1) GCD & LCM Calculator
2) Basic Arithmetic Calculator
3) Sum of Digits
4) Integer Palindrome Checker
5) Exit

Select an option (1–5): 1
Enter first integer: 48
Enter second integer: 18
GCD(48, 18) = 6
LCM(48, 18) = 144
# Press Enter to return to menu...
```

---

### Scenario 2 – Basic Arithmetic Calculator

```
=== Math Toolkit ===
1) GCD & LCM Calculator
2) Basic Arithmetic Calculator
3) Sum of Digits
4) Integer Palindrome Checker
5) Exit

Select an option (1–5): 2
First number: 3.5
Operator (+, -, *, /): *
Second number: 4
3.5 * 4.0 = 14.0
# Press Enter to return to menu...
```

---

### Scenario 3 – Sum of Digits

```
=== Math Toolkit ===
1) GCD & LCM Calculator
2) Basic Arithmetic Calculator
3) Sum of Digits
4) Integer Palindrome Checker
5) Exit

Select an option (1–5): 3
Enter an integer: 2023
Sum of digits of 2023 is 7
# Press Enter to return to menu...
```

---

### Scenario 4 – Integer Palindrome Checker

```
=== Math Toolkit ===
1) GCD & LCM Calculator
2) Basic Arithmetic Calculator
3) Sum of Digits
4) Integer Palindrome Checker
5) Exit

Select an option (1–5): 4
Enter an integer: 12321
12321 is a palindrome.
# Press Enter to return to menu...
```

---

### Scenario 5 – Exit

```
=== Math Toolkit ===
1) GCD & LCM Calculator
2) Basic Arithmetic Calculator
3) Sum of Digits
4) Integer Palindrome Checker
5) Exit

Select an option (1–5): 5
Goodbye!
```


---

## Evaluation Criteria

* **Functionality (40%)**: Each menu option performs as specified.
* **Use of Concepts (30%)**: Correct loops, conditionals, arithmetic, and string operations.
* **Code Quality (20%)**: Clear structure, comments, and naming.
* **User Experience (10%)**: Menu layout, prompts, and pauses are user-friendly.

Good luck, and enjoy building your Math Toolkit!

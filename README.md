# 🔐 Secure Password Generator

A Python script to generate strong, customizable passwords using cryptographic randomness. Built with `secrets`, `string`, and `re` libraries — suitable for creating secure credentials and practicing constraint-based generation.

---

## 🚀 Features

- Generates random passwords using `secrets` (cryptographically secure)
- Ensures minimum counts of:
  - ✅ Numbers (`0–9`)
  - ✅ Special characters (`!@#$%^&*` etc.)
  - ✅ Uppercase letters (`A–Z`)
  - ✅ Lowercase letters (`a–z`)
- Fully customizable:
  - Password length
  - Number of required character types

---

## 🛠️ How It Works

The function `generate_password()` accepts optional arguments:

```python
generate_password(
    length=16,
    nums=1,
    special_chars=1,
    uppercase=1,
    lowercase=1
)


File Structure

secure-password-generator/
├── password_generator.py
└── README.md


▶️ How to Run

python password_generator.py
Make sure you have Python 3.6+ installed (secrets module).


🔒 Why Use secrets?
secrets is part of Python's standard library, designed for cryptographically strong random numbers — ideal for passwords, tokens, and security-related uses.

👨‍💻 Author
Chalaka Chamikara
Sharing useful Python tools for practical use and learning.


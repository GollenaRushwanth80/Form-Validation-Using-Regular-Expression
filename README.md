# Form-Validation-Using-Regular-Expression

# User Input Validator using Regular Expressions

This is a simple Python command-line program that takes user input and validates it using regular expressions. It collects the following personal details from the user:

- Full Name
- Date of Birth (formatted to `dd Month yyyy`)
- Email ID (restricted to Gmail accounts)
- Mobile Number (entered in `xxx-xxx-xxxx` format but displayed without hyphens)

---

## 🔍 Features

- Validates name input to ensure it contains only alphabets and spaces.
- Validates and reformats Date of Birth from `dd-mm-yyyy` to `dd Month yyyy` using Python’s `datetime` module.
- Ensures email input is a valid Gmail address using regex.
- Validates mobile number format and removes hyphens in the final output using `re.sub()`.

---

## 🛠️ Prerequisites

To run this project, you need:

- Python 3.x installed on your system  
- A command-line interface (e.g., Terminal, CMD, PowerShell)

No external libraries are required beyond Python's standard library (`re`, `datetime`).

---

## 🚀 How to Run

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/user-input-validator.git
   cd user-input-validator

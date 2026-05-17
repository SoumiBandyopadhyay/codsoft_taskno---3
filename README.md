# 🔐 Password Generator

A simple Python project that generates strong and random passwords based on the length provided by the user.

## 📌 Features

- Generates secure random passwords
- User can choose password length
- Includes:
  - Uppercase letters
  - Lowercase letters
  - Numbers
  - Special characters
- Beginner-friendly project

---

## 🛠️ Technologies Used

- Python
- `random` module
- `string` module

---

## 🚀 How to Run

1. Clone the repository

```bash
https://github.com/SoumiBandyopadhyay/codsoft_taskno---3/tree/main
```

2. Navigate to the project folder

```bash
cd password-generator
```

3. Run the Python file

```bash
python password_generator.py
```

---

## 💻 Program Code

```python
import random
import string

# Function to generate password
def generate_password(length):
    characters = string.ascii_letters + string.digits + string.punctuation
    password = ''.join(random.choice(characters) for _ in range(length))
    return password

# User input
length = int(input("Enter the desired password length: "))

# Generate password
password = generate_password(length)

# Display password
print("Generated Password:", password)
```

---

## 📷 Example Output

```text
Enter the desired password length: 12
Generated Password: A@7kL#9pQ!2x
```

---

## 📁 Project Structure

```text
password-generator/
│── password_generator.py
│── README.md
```

---

## 🌟 Future Enhancements

- Password strength checker
- GUI version using Tkinter
- Option to customize character types
- Save passwords to a file

---

## 👩‍💻 Author

**Soumi Bandyopadhyay**

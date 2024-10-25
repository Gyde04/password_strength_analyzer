# Password Strength Analyzer

A Python-based security tool that analyzes password strength based on various security criteria.

## Features

- Checks password length (minimum 8 characters)
- Verifies presence of uppercase letters
- Verifies presence of lowercase letters
- Checks for numbers
- Validates special characters
- Detects common password patterns
- Provides detailed feedback and strength percentage
- Secure password input (hidden while typing)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/password_strength_analyzer.git
cd password_strength_analyzer

2. No additional dependencies required (uses Python standard library)

## Usage

Run the script using Python:
```bash
python password_analyzer.py
```

Follow the prompts to enter passwords for analysis.

## Security Criteria

The analyzer evaluates passwords based on the following criteria:
- Minimum length of 8 characters
- Presence of uppercase letters
- Presence of lowercase letters
- Inclusion of numbers
- Use of special characters
- Absence of common patterns

## Output

The tool provides:
- Detailed feedback for each security criterion
- Overall strength percentage
- Password strength verdict (Weak/Moderate/Strong)

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
```

6. Create a .gitignore file:
```bash
touch .gitignore
```

7. Add the following to .gitignore:
```
__pycache__/
*.py[cod]
*$py.class
.DS_Store
```

8. Initialize git repository and make your first commit:
```bash
git init
git add .
git commit -m "Initial commit: Password Strength Analyzer"
```

9. Create a new repository on GitHub and push your code:
```bash
git remote add origin https://github.com/yourusername/password_strength_analyzer.git
git branch -M main
git push -u origin main
```



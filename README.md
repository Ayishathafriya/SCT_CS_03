#  Password Strength Checker

##  Overview
This project is a **Python-based password strength checker** that evaluates the robustness of user-provided passwords against common security criteria. It provides both a **strength rating** (Weak, Moderate, Strong) and **actionable feedback** to help users improve their password security. The tool is lightweight, beginner-friendly, and demonstrates practical applications of **regular expressions (regex)** in cybersecurity.

##  Features
- ✅ Length validation (minimum 8 characters)  
- ✅ Uppercase and lowercase checks  
- ✅ Digit requirement  
- ✅ Special character requirement  
- ✅ Strength rating: Weak, Moderate, Strong  
- ✅ Feedback suggestions for improvement  

##  Technology Stack
- **Language**: Python 3.x  
- **Libraries**:  
  - `re` (Regular Expressions) – used for pattern matching and validation  

##  How It Works
1. The user inputs a password.  
2. The program checks the password against five criteria: length, uppercase, lowercase, digit, and special character.  
3. A score is calculated based on satisfied conditions.  
4. The tool outputs a **strength rating** and **suggestions** for improvement.  

##  Example Usage
```python
Enter a password to check: MyPass123!
Password Strength: Strong
```

```python
Enter a password to check: pass
Password Strength: Weak
Suggestions to improve:
- Password should be at least 8 characters long.
- Add at least one uppercase letter.
- Include at least one number.
- Include at least one special character.
```

##  Applications
- Educational demonstrations of **regex** in Python  
- Introductory projects in **cybersecurity** and **password hygiene**  
- Useful utility for developers to integrate into login or signup workflows  

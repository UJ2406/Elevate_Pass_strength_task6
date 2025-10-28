# Password Strength Evaluation (Task 6)

## 📋 Task Overview
Created multiple example passwords, tested their strength using online tools, and documented the impact of complexity and best practices on password security.

---

## 🎯 Objectives

- Understand what makes a password strong or weak.
- Evaluate real password examples using password strength meters.
- Record, analyze, and explain the results for cybersecurity learning and reporting.
- Summarize key concepts and answer typical cybersecurity interview questions.

---

## 🛠️ Tools Used

- [How Secure Is My Password?](https://security.org/how-secure-is-my-password/)
- Firefox/Chromium web browser

---

## ⚙️ Methodology

1. **Created Example Passwords**
   - Used a mix of very simple, common, and complex passwords.

2. **Tested Each Password**
   - Entered passwords in the online meter.
   - Recorded “Crack Time” and visual feedback for each.

3. **Compared Results**
   - Tabulated crack time, complexity, and tool feedback.
   - Took screenshots as evidence (see below).

---

## 🧪 Sample Passwords & Results

| Password             | Crack Time / Tool Result       | Screenshot    | Notes                                               |
|----------------------|-------------------------------|---------------|-----------------------------------------------------|
| 12345678             | Instantly                     | image 1       | Common sequence, extremely weak                     |
| Password             | Instantly                     | image 2       | Dictionary word, very weak                          |
| Elevate_Cyber@123    | 3 hundred quadrillion years   | image 3       | Very strong: length + mixed types                   |
| Pass89236            | 3 days                        | image 4       | Better, but too short/simple for high security      |
| Br!ll!@nt            | 17 years                      | image 5       | Good, uses symbols, could be longer                 |

---



## 💡 Key Takeaways

- Longer passwords with upper, lower, numbers, and symbols are exponentially stronger.
- Single words or predictable patterns (like “Password” or “12345678”) are instantly defeated by attackers.
- Small increases in length/symbols raised crack times from minutes to years or more.
- Using unique, complex passwords for every service is critical.
- Password managers allow users to safely use strong, random passwords.

---

## 📝 Best Practices

- Minimum 12–16 character passwords wherever possible
- Always include uppercase, lowercase, numbers, and symbols
- Avoid dictionary words or predictable sequences
- Don’t reuse passwords between accounts/services
- Prefer random passphrases or manager-generated passwords

---

## 🧠 Concepts Learned

- **Password Strength:** Determined by length and character variety.
- **Crack Time:** The “cost” for an attacker using brute force; higher is better.
- **Brute Force Attack:** Trying all possibilities quickly—short/simple passwords are easy targets.
- **Dictionary Attack:** Automated guessing from common words and leaked password lists.
- **Password Meter Limitations:** Only a guide; never enter real passwords.
- **Passphrases:** Multiple random words/symbols offer strong memorability and security.
- **Multi-Factor Authentication (MFA):** Adds an extra layer, further defeating password-only attacks.

---

## 🗣️ Interview Questions & Answers

**1. What makes a password strong?**  
A strong password uses a long sequence (12+), with uppercase, lowercase, numbers, and symbols, and is not based on dictionary words or personal info.

**2. Common password attacks?**  
Brute force, dictionary attack, credential stuffing (using leaked real passwords).

**3. Why is password length important?**  
Each additional character dramatically increases attack time and reduces risk.

**4. What is a dictionary attack?**  
Automated guessing using a list of dictionary words and common passwords.

**5. What is multi-factor authentication?**  
A login process requiring at least two factors: something you know (password), something you have (OTP, phone), or something you are (fingerprint).

**6. How do password managers help?**  
They generate, store, and autofill unique, strong passwords for every account—making high security easy.

**7. What are passphrases?**  
Random combinations of words (and symbols) as passwords—easy for users, hard for attackers.

**8. Common mistakes in password creation?**  
Using short/common words (“password”), personal data (birthdays), or reusing passwords for multiple logins.

---

## 📂 Repository Structure

```
password-strength-task6/
├── README.md                 # This file
├── findings.txt              # Test results summary
├── screenshots/
   ├── im1.png
   ├── im2.png
   ├── im3.png
   ├── im4.png
   ├── im5.png

```

# Task 6 - Password Strength Evaluation

## Objective
Understand what makes a password strong by testing different passwords using online strength checkers.

## Passwords Tested

| Password                          | Complexity       | Estimated Crack Time                  | Screenshot |
|-----------------------------------|------------------|---------------------------------------|------------|
| password                          | Very Weak        | Instant                               | [01-weak.png](screenshots/01-weak.png) |
| Password123                       | Weak             | Few seconds                           | [02.png](screenshots/02.png) |
| P@ssw0rd2023                      | Medium           | Few months                            | [03.png](screenshots/03.png) |
| MyDogNameIsMax                    | Good (passphrase)| Thousands of years                    | [04.png](screenshots/04.png) |
| Tr0ub4dor&3xplor3r               | Strong           | Millions of years                     | [05.png](screenshots/05.png) |
| Correct-Horse-Battery-Staple-1991 | Very Strong      | Billions of years                     | [06.png](screenshots/06.png) |
| K9!mP$v2nL*wQ#8xZ                 | Extremely Strong | Hundreds of billions of years         | [07.png](screenshots/07.png) |

## Key Learnings & Best Practices
1. **Length is the most important factor** – A 15–20 character passphrase is much stronger than a short complex password.
2. Use a mix of uppercase, lowercase, numbers, and symbols.
3. Avoid common words/substitutions (like P@ssw0rd).
4. Passphrases (e.g., CorrectHorseBatteryStaple) are easy to remember but extremely hard to crack.
5. Never reuse passwords across sites.

## Common Password Attacks
- **Brute Force**: Tries every possible combination. Longer passwords make this impossible.
- **Dictionary Attack**: Tries common words and patterns. Avoid real words and predictable substitutions.

## Recommendation
Use a password manager (like Bitwarden, LastPass, or 1Password) to generate and store long, random passwords or passphrases.

Screenshots are in the `/screenshots` folder.

1. What makes a password strong?
A strong password has:

Length: At least 12–16 characters (longer is better)
Complexity: Mix of uppercase, lowercase, numbers, and special symbols
Unpredictability: No common words, names, dates, or patterns (e.g., "Password123")
Uniqueness: Never reused across different accounts
Bonus: Using passphrases (e.g., CorrectHorseBatteryStaple) that are long and memorable

2. What are common password attacks?
The most common attacks are:

Brute Force Attack: Tries every possible combination (very slow against long passwords)
Dictionary Attack: Uses a list of common passwords and words from dictionaries
Credential Stuffing: Uses leaked username/password pairs from one site to try on others
Rainbow Table Attack: Uses pre-computed hashes to crack hashed passwords quickly
Phishing/Keylogging: Tricks user or records keystrokes (social engineering + malware)

3. Why is password length important?
Length is the single most important factor because:

Every extra character increases the number of possible combinations exponentially
Example:
8-character password → ~95⁸ = 6.6 quadrillion combinations
16-character password → 95¹⁶ = an astronomically larger number

Even a simple passphrase like "bluecarcoffee2025" (17 chars) takes billions of years to crack via brute force
Short passwords (even complex ones) can be cracked in hours or days

4. What is a dictionary attack?
A dictionary attack uses a pre-compiled list (dictionary) of:

Common passwords (password123, admin, 123456)
Leaked passwords from previous breaches
Words from dictionaries in multiple languages
Common substitutions (p@ssw0rd, l33t speak)

It’s much faster than brute force because it only tries likely passwords instead of all combinations.
5. What is multi-factor authentication (MFA/2FA)?
MFA requires two or more verification factors:

Something you know (password)
Something you have (phone, authenticator app, hardware token)
Something you are (fingerprint, face ID)

Even if your password is stolen, the attacker still can’t log in without the second factor.
6. How do password managers help?
Password managers:

Generate long, random, unique passwords for every site
Store them securely in an encrypted vault
Auto-fill login forms
Sync across devices
Alert you if a password is weak or reused
Make it possible to use 20+ character random passwords without memorizing them

Popular free ones: Bitwarden, Proton Pass
7. What are passphrases?
A passphrase is a password made of multiple random words joined together.
Example:
Correct-Horse-Battery-Staple
or
Purple$Monkey!Dishwasher2025
Advantages:

Much longer than traditional passwords → extremely hard to crack
Easier to remember than random characters
Resistant to dictionary attacks if words are truly random

8. What are common mistakes in password creation?

Using "password", "123456", name, birthday, or "qwerty"
Reusing the same password across multiple sites
Using simple substitutions (P@ssw0rd instead of Password)
Writing passwords on paper or storing in plain text files
Never changing default passwords (like admin/admin)
Using short passwords (<12 characters)
Including personal info (pet name, car model, etc.)
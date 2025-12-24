🔐 Password Strength Analyzer

A client-side Password Strength Analyzer that evaluates password security in real time and provides actionable feedback to help users create stronger, safer passwords.

This project focuses on security fundamentals, password entropy, and user awareness, making it suitable for beginners building a cybersecurity-focused portfolio.

🚀 Features

Real-time password strength evaluation

Visual strength indicator (Weak → Very Strong)

Estimated time to crack using modern GPU-based brute-force assumptions

Validation against common password security rules

Detection of weak patterns (common passwords, sequences)

Security best-practice tips for end users

Client-side analysis only (no passwords stored or transmitted)

🛡️ Password Checks Performed

The analyzer validates passwords against the following criteria:

Minimum length requirement

Uppercase letters (A–Z)

Lowercase letters (a–z)

Numbers (0–9)

Special characters

Common password detection

Sequential character detection

Each rule contributes to the overall strength score.

⏱️ Time-to-Crack Estimation

The application estimates how long it would take to crack a password using:

Modern GPU attack assumptions

Approx. 10 billion attempts per second

Brute-force attack model

⚠️ Note: This is an estimate, not a guarantee. Real-world attack times vary based on hashing algorithms, salting, and attacker resources.

🧠 Security Concepts Used

Password entropy

Brute-force attack modeling

Defense-in-depth (password + 2FA recommendations)

Client-side security best practices

🖥️ Tech Stack

HTML5

CSS3

JavaScript (Vanilla)

No backend – fully browser-based analysis

Password Cracking & Information Analysis using CrackStation
Overview

This project demonstrates password cracking and hash analysis using CrackStation, a widely used online password auditing and hash analysis tool in cybersecurity education. The experiment focuses on understanding how weak password hashing algorithms and predictable passwords can be compromised using dictionary-based and lookup-table techniques.

The project highlights real-world risks associated with insecure password practices and emphasizes the importance of modern, secure hashing mechanisms.

Objectives

To understand the concept of password hashing and hash-based authentication

To analyze how weak password hashes can be cracked using publicly available tools

To demonstrate dictionary-based and lookup-table password cracking methods

To evaluate the security weaknesses of legacy hashing algorithms like MD5

Tools & Environment Used

CrackStation – Online Password Hash Cracking Tool

Web Browser (Google Chrome / Edge)

Operating System – Windows

Hash Algorithm Used

MD5 (Message Digest Algorithm 5)

MD5 is a fast hashing algorithm that is now considered cryptographically broken and unsuitable for secure password storage due to its vulnerability to pre-computed attacks and hash collisions.

Cracking Methodology

Dictionary-based attack

Lookup-table / Precomputed hash matching

CrackStation uses massive precomputed hash tables generated from:

Common password dictionaries

Previously leaked password databases

Real-world human password patterns

This allows rapid identification of weak passwords from unsalted hashes.

Target Dataset

Sample MD5 password hashes

Educational and intentionally weak passwords

No real user credentials were used

The hashes were manually generated from commonly used passwords to simulate insecure password storage scenarios.

Results Summary

Hash Type Tested: MD5

Passwords Successfully Cracked:

password

abc123

Cracking Technique: Dictionary / Lookup-based attack

Result Status:

Exact matches highlighted in green, indicating successful password recovery

These results confirm that weak passwords combined with insecure hashing algorithms can be cracked almost instantly.

Screenshots Included

Hashes entered into CrackStation

Hash input interface

Cracked password output

Full CrackStation tool interface view

(These screenshots serve as visual proof of the cracking process and results.)

Video Demonstration

🎥 Project Demonstration Video

▶ Watch Video Demo
(The video shows the complete workflow from hash input to cracked output.)

Security & Information Analysis

This experiment demonstrates that:

MD5 hashes are vulnerable to precomputed attacks

Weak passwords dramatically reduce system security

Unsalted hashes can be cracked within seconds

Attackers do not need advanced tools to exploit poor password practices

The project reinforces the importance of:

Using strong, unpredictable passwords

Applying salting techniques

Implementing modern password hashing algorithms

Ethical Considerations

All hashes used were artificially created for academic purposes

No real user data, personal credentials, or live systems were involved

The project strictly follows ethical hacking and responsible disclosure principles

Conclusion

This project clearly demonstrates that MD5 is an insecure hashing algorithm for password storage. Weak passwords hashed using MD5 can be easily cracked using publicly available tools such as CrackStation.

The findings emphasize the necessity of using secure hashing algorithms like:

bcrypt

PBKDF2

Argon2

SHA-256 (with proper salting and iterations)

Strong password policies combined with secure hashing mechanisms are essential to protect systems from credential-based attacks.

Disclaimer

This project is strictly for educational and academic purposes only.
Any misuse of the demonstrated techniques for unauthorized access or malicious activity is illegal and unethical.
## Disclaimer
This project is strictly for **educational and academic purposes only**.

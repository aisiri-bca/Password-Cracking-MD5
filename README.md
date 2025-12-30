# Password Cracking & Hash Analysis using CrackStation

## Overview
This project demonstrates how weak password hashes can be cracked using CrackStation, an online password security auditing tool. It highlights the risks of using weak passwords and outdated hashing algorithms such as MD5 and SHA-1.

The project is conducted strictly for educational and academic purposes to understand password security and ethical hacking concepts.

## Objectives
- Understand password hashing techniques
- Identify weak and insecure hash algorithms
- Demonstrate dictionary-based password cracking
- Analyze cracked password results
- Promote secure password storage practices

## Tools Used
- CrackStation (Online Password Hash Cracker)
- Web Browser (Chrome / Edge)
- Windows Operating System

## Hash Algorithms Used
- MD5
- SHA-1

## Methodology
CrackStation uses large precomputed lookup tables and dictionary-based attacks to match hash values with commonly used passwords. The entered hashes are compared against its database to find exact or partial matches.

## Target Dataset
- Sample and intentionally weak password hashes
- Non-sensitive, educational data only
- No real user credentials involved

## Results Summary
- Hash Types: MD5, SHA-1
- Passwords Successfully Cracked:
  - password
  - abc123
  - admin
  - letmein
  - hello
  - qwerty
- Cracking Method: Dictionary / Lookup-table attack
- Status Indicators:
  - Green: Exact match
  - Yellow: Partial match
  - Red: Not found

## Screenshots

### Hashes Entered into CrackStation
![Hashes Input](hashes-input.png)

### Cracked Password Results
![Cracked Output](cracked-results.png)

### Full CrackStation Tool Interface
![Full Tool View](full-tool-view.png)

---

## Video Demonstration

▶️ [Watch the Project Demo Video](crackstation-demo.mp4)

## Security Analysis
This experiment clearly demonstrates that:
- MD5 and SHA-1 are insecure hashing algorithms
- Weak passwords are highly vulnerable to cracking
- Unsalted hashes can be cracked instantly
- Public tools can exploit poor password practices

## Ethical Considerations
- All hashes used are sample data
- No real systems or accounts were targeted
- Project follows ethical hacking guidelines
- Conducted only for academic learning

## Conclusion
This project proves that weak passwords combined with outdated hashing algorithms such as MD5 and SHA-1 pose serious security risks. Strong passwords and modern hashing techniques like bcrypt, Argon2, or SHA-256 with salting are essential for secure systems.

## Disclaimer
This project is strictly for educational and academic purposes only. Any misuse of the demonstrated techniques is illegal and unethical.

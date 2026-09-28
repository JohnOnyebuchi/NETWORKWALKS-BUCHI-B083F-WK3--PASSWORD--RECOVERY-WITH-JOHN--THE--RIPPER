# Week 3 – Password Recovery & Hash Analysis

## 📌 Overview

As part of my Cybersecurity Internship with Networkwalks Technologies, I completed a hands-on laboratory exercise focused on password security, hashing, and password recovery.

The exercise involved using Networkwalks' Hash Calculator and Password Cracking Tool, alongside John the Ripper on Kali Linux.

---

## 🎯 Objectives

- Understand password hashing and password security.
- Generate and analyze password hashes.
- Use Networkwalks' Hash Calculator.
- Use Networkwalks' Password Cracking Tool.
- Extract a password hash from a protected PDF.
- Use John the Ripper for password recovery.
- Verify the recovered password against the protected PDF.
- Document the complete process and results.

---

## 🛠️ Tools Used

- Kali Linux
- John the Ripper
- pdf2john
- Networkwalks Hash Calculator
- Networkwalks Password Cracking Tool
- Password Wordlist
- Protected PDF

---

## 🔐 Lab Workflow

```text
Protected PDF
      ↓
pdf2john
      ↓
Extract PDF Password Hash
      ↓
Password Wordlist
      ↓
John the Ripper
      ↓
Password Recovery
      ↓
Verify PDF Access

```
---

## 1.Networkwalks Hash Calculator

I used the Networkwalks Hash Calculator to generate and analyze password hashes.
This helped me understand how passwords can be transformed into hash values and why secure password storage is important.

## Evidence 


## 2.Networkwalks Password Cracking Tool

I also used the Networkwalks Password Cracking Tool to practice password-recovery techniques in the authorized internship laboratory environment.

## Evidence

## 3.John the Ripper

I used John the Ripper on Kali Linux for the password-recovery portion of the exercise.

Installed version:

John the Ripper 1.9.0-jumbo-1

## Evidence

## 4.Extracting the PDF Hash

The provided PDF was password protected.I used pdf2john to extract the password hash from the PDF so that John the Ripper could process it.

The tool was located at:

/usr/share/john/pdf2john.pl

## Evidence

## 5.Password Recovery

The extracted hash was supplied to John the Ripper together with a password wordlist.
John then tested password candidates against the extracted hash.

## Evidence


## 6.Recovery Result

After processing the hash,I used John the Ripper to display the recovered password.

## Evidence

## 7.PDF Verification

The recovered password was used to verify access to the protected PDF.
This confirmed that the password-recovery process was successful.

## Evidence

---

## 🧠 Key Learning Outcomes

Through this exercise,I gained practical experience in:

°Password hashing

°Hash analysis

°Password recovery techniques

°PDF password hash extraction

°John the Ripper

°Wordlist-based password testing

°Secure password practices

°Cybersecurity documentation

---

## 🔒 Security & Ethics

This exercise was performed as part of an authorized cybersecurity internship laboratory using the provided training materials.
The techniques demonstrated in this project should only be used against systems,files,and credentials for which explicit authorization has been provided.

---

## 🛠️ Tools Summary

### Networkwalks Tools

- **Networkwalks Hash Calculator**  
  Used for hash generation and analysis.

- **Networkwalks Password Cracking Tool**  
  Used for password-recovery practice.

### Kali Linux Tools

- **John the Ripper**  
  Used for password recovery.

- **pdf2john**  
  Used to extract the password hash from the protected PDF.

### Supporting Tools

- **Kali Linux**  
  Used as the security testing environment.

- **Password Wordlist**  
  Used to provide password candidates for testing.

---

## ✅ Conclusion

Week 3 provided practical experience with password hashing,hash analysis,and password recovery techniques.

Working with Networkwalks'security tools and John the Ripper strengthened my understanding of password security and demonstrated how these techniques can be applied responsibly in an authorized cybersecurity environment.

**Cybersecurity is not just about knowing the tools. It's about understanding the problem the tool is solving.**

## 👤 Author

**Sunday John Onyebuchi**

Cybersecurity Professional

LinkedIn:https://www.linkedin.com/in/john-onyebuchi-7324223bb?utm_source=share_via&utm_content=profile&utm_medium=member_android

---

## 📌 Project Information

**Program Name:** Cybersecurity at Networkwalks | **Week:** 03 | **Project:** Password Security, Hashing & Password Recovery  | **Repository:** GitHub
















  





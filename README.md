# Networkwalks B083C — Week 3 Cybersecurity Projects

## Project Overview

This repository documents my **Week 3 Cybersecurity Internship work with Networkwalks (Batch B083C)**.

The Week 3 project work covered two password-cracking modules:

- **W3-PM1 — Password Cracking with JTR (John the Ripper / Johnny)**
- **W3-PM2 — Password Cracking with Networkwalks Tools**

Both exercises were completed as controlled cybersecurity learning activities using the supplied protected PDF and the procedures provided in the Networkwalks project documentation. The JTR module explains how John the Ripper/Johnny can be used to recover a password from a protected PDF by working with its extracted hash. The second module uses Networkwalks' browser-based Hash Calculator and Password Cracker. fileciteturn0file0L6-L21 fileciteturn0file1L7-L26

---

## Repository Structure

```text
networkwalks-B083C-week3-cybersecurity-lab-setup/
│
├── README.md
│
├── JTR-Password-Cracking/
│   └── README.md
│
├── Networkwalks-Password-Cracking/
│   └── README.md
│
└── Report/
    └── README.md
```

---

## W3-PM1 — Password Cracking with JTR

### Objective

To gain practical experience using **John the Ripper (JTR)** and **Johnny**, its graphical interface, to recover the password of a protected PDF in an authorized learning environment.

### Tools Used

- John the Ripper (JTR)
- Johnny GUI
- Windows PC / Kali Linux environment where applicable
- PDF hash extraction workflow
- Notepad for storing the extracted hash

### Workflow

1. Install/download John the Ripper and Johnny.
2. Configure Johnny to use `john.exe` from the JTR `run` folder.
3. Obtain the encrypted PDF supplied for the lab.
4. Extract the PDF hash using the specified PDF hash extraction method.
5. Save the hash in a text file such as `hash1.txt`, ensuring the hash begins with `$pdf$` and does not contain unwanted extra characters.
6. Open the hash file in Johnny.
7. Start a new attack and wait for the password to be recovered.
8. Use the recovered password to open the protected PDF.

The Networkwalks guide specifically notes that attack time depends on computer speed and password complexity. fileciteturn0file0L45-L55 fileciteturn0file0L63-L75

### Key Learning

This module demonstrates the relationship between protected files, password hashes, and password-cracking tools. It also reinforces why stronger passwords increase the difficulty of password recovery.

---

## W3-PM2 — Password Cracking with Networkwalks Tools

### Objective

To understand the password-cracking workflow using Networkwalks' **Hash Calculator** and **Password Cracker** browser-based tools.

### Tools Used

- Networkwalks Hash Calculator
- Networkwalks Password Cracker
- Web browser
- Protected PDF supplied for the lab

### Workflow

1. Download the encrypted PDF supplied on the lab page.
2. Upload the locked PDF to the Networkwalks Hash Calculator.
3. Copy the complete hash beginning with `$pdf$`.
4. Open the Networkwalks Password Cracker.
5. Paste the hash and start the attack.
6. Wait for the tool to complete the process.
7. Use the recovered password to open the protected PDF.

The module documentation explains that the tools run in a web browser, so no separate software installation is required for this exercise. fileciteturn0file1L17-L26 fileciteturn0file1L28-L55

### Key Learning

This exercise helped me understand password cracking as a step-by-step process: extracting a hash, supplying it to a cracking tool, recovering a matching password, and validating the result by opening the protected file.

---

## Security & Ethical Use

Password-cracking techniques can be used for legitimate security testing and education, but they should only be applied to files, systems, accounts, or networks where explicit authorization has been provided.

All work documented here is intended for the **Networkwalks cybersecurity internship and authorized educational lab use only**.

---

## Tools & Technologies

- John the Ripper
- Johnny
- Networkwalks Hash Calculator
- Networkwalks Password Cracker
- Windows / Kali Linux
- GitHub

---

## Project Information

| Item | Details |
|---|---|
| Program | Cybersecurity Internship — Networkwalks |
| Batch | B083C |
| Week | 3 |
| Module 1 | W3-PM1 — Password Cracking with JTR |
| Module 2 | W3-PM2 — Password Cracking with Networkwalks Tools |
| Author | bor-ee-d |

---

## References

- Networkwalks Week 3 — Password Cracking with JTR project documentation. fileciteturn0file0L6-L23
- Networkwalks Week 3 — Password Cracking with Networkwalks Tools project documentation. fileciteturn0file1L7-L26

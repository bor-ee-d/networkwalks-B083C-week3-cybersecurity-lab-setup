# Networkwalks B083C — Week 3 Cybersecurity Projects

## Project Overview

This repository documents my **Week 3 Cybersecurity Internship work with Networkwalks (Batch B083C)**.

The Week 3 project work covered two password-cracking modules:

- **W3-PM1 — Password Cracking with JTR (John the Ripper / Johnny)**
- **W3-PM2 — Password Cracking with Networkwalks Tools**

Both exercises were completed as controlled cybersecurity learning activities using the supplied protected PDF and the procedures provided in the Networkwalks project documentation.

---

## Repository Structure

```text
networkwalks-B083C-week3-cybersecurity-lab-setup/
│
├── README.md
│
├── JTR-Password-Cracking/
│   ├── README.md
│   └── screenshots/
│
├── Networkwalks-Password-Cracking/
│   ├── README.md
│   └── screenshots/
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

### Evidence / Screenshots

Add your JTR evidence screenshots to the **`JTR-Password-Cracking/screenshots/`** folder.

Suggested evidence:

-<img width="1058" height="698" alt="Screenshot 2026-09-24 101631" src="https://github.com/user-attachments/assets/534c5c0d-640e-4cd0-8dc7-3ffb5edb3f15" />
-<img width="1976" height="1258" alt="Screenshot 2026-09-26 152920" src="https://github.com/user-attachments/assets/0e9d4921-955f-482e-ba3b-77e49a6af374" />
-<img width="2398" height="1056" alt="Screenshot 2026-09-26 153053" src="https://github.com/user-attachments/assets/3c6268cc-2f31-4f36-a71c-f8c2e0b6cc36" />
-<img width="1984" height="1176" alt="Screenshot 2026-09-26 153538" src="https://github.com/user-attachments/assets/a3e7b8e7-e57b-436e-9dd0-bf3d793251eb" />
-<img width="2134" height="1222" alt="Screenshot 2026-09-26 153239" src="https://github.com/user-attachments/assets/74259b41-bc43-4dc8-a608-88f98a01e748" />
-<img width="2136" height="1230" alt="Screenshot 2026-09-26 153815" src="https://github.com/user-attachments/assets/4bbeada1-b849-49ac-a0df-97962f0437ae" />
-<img width="1060" height="708" alt="Screenshot 2026-09-26 153337" src="https://github.com/user-attachments/assets/40df5130-19d3-4239-a8e4-2669cd971e07" />
-<img width="2880" height="1648" alt="Screenshot 2026-09-26 153842" src="https://github.com/user-attachments/assets/653ffd8f-3411-4164-bd37-cfb3f63e1558" />
-<img width="1062" height="712" alt="Screenshot 2026-09-26 153358" src="https://github.com/user-attachments/assets/15bbece0-522a-4861-92e5-336a6aa1d045" />
-<img width="2874" height="1622" alt="Screenshot 2026-09-26 153430" src="https://github.com/user-attachments/assets/7540372e-c916-4d46-bb38-42175170d7e5" />

I performed the attack on Locked PDF 1 and Locked PDF 2.

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

### Evidence / Screenshots

Add your Networkwalks password-cracking evidence screenshots to the **`Networkwalks-Password-Cracking/screenshots/`** folder.

Suggested evidence:

-<img width="2876" height="1652" alt="Screenshot 2026-09-26 154006" src="https://github.com/user-attachments/assets/a8a827f5-ff84-4d07-884d-abed9d472d22" />
-<img width="2880" height="1548" alt="Screenshot 2026-09-26 154042" src="https://github.com/user-attachments/assets/cca9bdc7-1d97-401e-b039-b67a2e256094" />
-<img width="2880" height="1550" alt="image" src="https://github.com/user-attachments/assets/7a16e274-da72-431c-92c5-e0d30a3d77f5" />
-<img width="2880" height="1638" alt="Screenshot 2026-09-26 154049" src="https://github.com/user-attachments/assets/2b18af4b-c6a3-417e-bf12-8fba6177350e" />
-<img width="2880" height="1642" alt="Screenshot 2026-09-26 154128" src="https://github.com/user-attachments/assets/c94aba65-dc6c-4643-befa-a71e5a96b16a" />

I performed this attack on Locked PDF 3.

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

- Networkwalks Week 3 — Password Cracking with JTR project documentation.
- Networkwalks Week 3 — Password Cracking with Networkwalks Tools project documentation.

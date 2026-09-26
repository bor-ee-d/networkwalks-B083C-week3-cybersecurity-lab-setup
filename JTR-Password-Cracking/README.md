# W3-PM1 — Password Cracking with JTR

## Objective

Use **John the Ripper (JTR)** and **Johnny** to recover the password of the protected PDF supplied for the Networkwalks Week 3 lab.

## Workflow

1. Download/install John the Ripper and Johnny.
2. Configure Johnny to use `john.exe` from the JTR `run` folder.
3. Obtain the encrypted PDF supplied for the exercise.
4. Extract the PDF hash using the specified PDF hash extraction workflow.
5. Save the extracted hash in `hash1.txt` in the required `$pdf$...` format.
6. Open `hash1.txt` in Johnny.
7. Start a new attack.
8. Use the recovered password to open the protected PDF.

## Learning Outcome

The exercise demonstrates how a protected PDF can be tested in an authorized lab by extracting its hash and using a password-cracking tool to recover the password. The documentation notes that cracking time depends on computer speed and password complexity.

Source: Networkwalks Week 3 Project Module 1. 

## Ethical Use

This technique should only be used against files for which permission has been provided. This repository documents the work as part of an authorized cybersecurity learning lab.

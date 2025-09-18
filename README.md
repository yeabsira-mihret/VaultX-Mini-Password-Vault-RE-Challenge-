# VaultX – Mini Password Vault (Reverse Engineering Challenge)

## Description
VaultX is a **CTF-style reverse engineering project** designed for educational purposes.  
It simulates a small password vault:

- Requires a **master password** to access a hidden secret.  
- Master password and secret are **obfuscated in memory** using XOR encryption.  
- Evaluators must **reverse engineer the binary** to discover the password and reveal the secret.  

> This project is safe and meant for **learning reverse engineering techniques**, memory inspection, and binary analysis.

---Enter the master password to unlock the secret.

Note: The password is hidden in the binary for RE practice.

## Instructions

1. Download the repository.  

2. Make the binary executable (Linux):
```bash
chmod +x vault
```
3. Run the binary:
```bash
   ./vault
```
4. Enter the master password to unlock the secret.
Note: The password is hidden in the binary for RE practice.

5. Upon correct entry, the secret will be displayed.

## Gameplay / RE Challenge

The binary does not include the source code in the main branch to simulate a real RE scenario.
### User must:

Analyze the binary.
Determine the XOR key.
Recover the master password.
Reveal the hidden secret.

## Files

vault : Stripped compiled binary (Linux)
README.md : Project documentation

## Learning Objectives

Practice reverse engineering of stripped binaries.
Understand simple XOR-based obfuscation.
Analyze memory and static binary structure.
Gain hands-on experience with RE CTF-style challenges.

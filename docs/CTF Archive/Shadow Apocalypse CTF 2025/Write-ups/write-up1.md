# Write-up format:

# 🧩 Challenge Writeup: <Challenge Name>

> **Category:** `<Crypto | Web | Reverse | PWN | OSINT | Forensics | Stego | Misc>`  
> **Event:** `<CTF Name (e.g., LakshyaCTF 2025)>`  
> **Points:** `XXX`  
> **Author:** `<Your Name / Team Name>`  
> **Flag Format:** `flag{}`

---

## 🧠 Challenge Description
(Paste the challenge prompt exactly as given.)
Include any hints, cryptic phrases, or storylines provided in the problem.

---

## 📁 Provided Files  

Link the challenge's files as follows:
```md
- 🔗 [Example Download Attachment](../../attachments/example.zip)
```
---

## 🧩 Step-by-Step Solution

### 🔍 1. Recon & Observation

Explain what you observed when opening the file, running the binary, viewing the source code, etc.

### 🔧 2. Analysis / Exploit

Break down what techniques you used:
- Reversing the binary
- Decoding ciphertexts
- Analyzing file structure or metadata
- SQL injection
- Extracting stego layers
- Exploit debugging steps

Include code or terminal blocks as needed:

```bash
strings binary
gdb ./challenge
```

```python
# Example decode script
print(bytes.fromhex("48656c6c6f").decode())
```

### 🧩 3. Flag Extraction

Explain the final step that led you to the flag. This could be decoding output, brute-forcing a password, or finding a hidden string.

---

## 🏁 Final Flag
```txt
flag{your_final_flag_here}
```

---

## 💡 Notes / Reflection
> (Optional) Add what you learned, what tripped you up, or alternate methods to solve the same challenge.
# picoCTF - RED
**Points:** 100  
**Difficulty:** Easy  
**Author:** Shuailin Pan (LeConjuror)

---

## 📝 Challenge Description / Problem Statement
"RED, RED, RED, RED"

## 🚀 Complete Walkthrough
I have documented the complete step-by-step solution for this challenge with screenshots, metadata exploration (`exiftool`), acrostic clue analysis, and RGBA channel Least Significant Bit (LSB) extraction using `zsteg` on my Medium blog.

🔗 **Read the full writeup here:** [picoCTF: RED — Medium Walkthrough](https://medium.com/@R3d0psPD/picoctf-red-0ff89de83df3?sharedUserId=R3d0psPD)

---

## 🚩 Core Takeaways
- **Acrostic Stego-Clues:** When custom text fields like poems, descriptions, or copyright flags are found in file metadata, checking for acrostics (the first letter of every line or word) is a highly reliable way to extract operational keys.
- **Least Significant Bit (LSB) Extraction:** Modifying the lowest bit channel values (like b1 in RGBA) changes the color shade so minutely that it remains completely invisible to the naked human eye, making tools like `zsteg` crucial for exposing deep payload blocks.

---
*Follow my CTF journey on [LinkedIn](https://www.linkedin.com/in/parthib-dewanjee-7600a7418/), [GitHub](https://github.com) & [Medium](https://medium.com/@R3d0psPD).*

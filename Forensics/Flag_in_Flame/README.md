# picoCTF - Flag in Flame

**Points:** 100  
**Difficulty:** Easy  
**Author:** Prince Niyonshuti N.

---

## 📝 Challenge Description / Problem Statement
"The SOC team discovered a suspiciously large log file after a recent breach. When they opened it, they found an enormous block of encoded text instead of typical logs. Could there be something hidden within? Your mission is to inspect the resulting file and reveal the real purpose of it."

## 🚀 Complete Walkthrough
I have documented the complete step-by-step solution for this challenge with screenshots, Base64 stream decoding, visual forensics, and localized validation methodology using `xxd` on my Medium blog. 

🔗 **Read the full writeup here:** [picoCTF: Flag in Flame — Medium Walkthrough](https://medium.com/@R3d0psPD/picoctf-flag-in-flame-b3d59702ae6c?sharedUserId=R3d0psPD)

---

## 🚩 Core Takeaways
- **Data Obfuscation Techniques:** Base64 is frequently utilized to encapsulate entire binary structures within plaintext logs to bypass automated filtering systems.
- **Hybrid Verification Model:** Combining AI efficiency for visual transcription (OCR) with local command-line tools (`xxd`) ensures both operational speed and absolute technical precision.

---
*Follow my CTF journey on [LinkedIn](https://www.linkedin.com/in/parthib-dewanjee-7600a7418/), [GitHub](https://github.com) & [Medium](https://medium.com/@R3d0psPD).*

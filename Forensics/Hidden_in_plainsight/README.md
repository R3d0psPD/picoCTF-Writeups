# picoCTF - Hidden in plainsight

**Points:** 100  
**Difficulty:** Easy  
**Author:** Yahaya Meddy

---

## 📝 Challenge Description / Problem Statement
"You're given a seemingly ordinary JPG image. Something is tucked away out of sight inside the file. Your task is to discover the hidden payload and extract the flag."

## 🚀 Complete Walkthrough
I have documented the complete step-by-step solution for this challenge with screenshots, ExifTool metadata inspection, and Steghide extraction methodology on my Medium blog. 

🔗 **Read the full writeup here:** [picoCTF: Hidden in plainsight — Medium Walkthrough](https://medium.com/@R3d0psPD/picoctf-hidden-in-plainsight-2d01f346bb37?sharedUserId=R3d0psPD)

---

## 🚩 Core Takeaways
- **Multilayered Steganography:** Cybercriminals and CTF creators often hide keys inside metadata fields (like Comment tags) to protect actual payloads embedded via steganographic tools like `steghide`.
- **Double Encoding:** Always stay alert when you decode a string and receive another encoded payload. Iterative decoding is a staple in basic forensic analysis.

---
*Follow my CTF journey on [GitHub](https://github.com/R3d0psPD) & [Medium](https://medium.com/@R3d0psPD).*

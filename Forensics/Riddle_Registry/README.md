# picoCTF - Riddle Registry (Forensics)

**Points:** 50  
**Difficulty:** Easy  
**Author:** Prince Niyonshuti N.

---

## 📝 Challenge Description / Problem Statement
Hi, intrepid investigator! 📄🔍 You’ve stumbled upon a peculiar PDF filled with what seems like nothing more than garbled nonsense. But beware! Not everything is as it appears. Amidst the chaos lies a hidden treasure — an elusive flag waiting to be uncovered.

Find the PDF file here Hidden Confidential Document and uncover the flag within the metadata.

## 🚀 Complete Walkthrough
I have documented the complete step-by-step solution for this challenge with screenshots and ExifTool methodology on my Medium blog. 

🔗 **Read the full writeup here:** [picoCTF: Riddle Registry — Medium Walkthrough](https://medium.com/@R3d0psPD/picoctf-riddle-registry-7e83c79f1a8e)

---

## 🚩 Core Takeaways
- **Metadata Forensic Analysis:** Files often contain hidden information (like Author names, Creation Software, or GPS locations) that isn’t visible on the surface. Tools like `exiftool` are essential for uncovering these data layers.
- **Recognizing Encoded Data:** Identifying structural patterns (like Base64 padding) allows for quick identification and decoding of obfuscated strings during forensic investigations.

---
*Follow my CTF journey on [GitHub](https://github.com/R3d0psPD) & [Medium](https://medium.com/@R3d0psPD).*

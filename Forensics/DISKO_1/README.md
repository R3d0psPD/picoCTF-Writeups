# picoCTF - DISKO 1

**Points:** 1  
**Difficulty:** Easy  
**Author:** Darkraicg492

---

## 📝 Challenge Description / Problem Statement
"Can you find the flag in this disk image?"

## 🚀 Complete Walkthrough
I have documented the complete step-by-step solution for this challenge with screenshots, gzip decompression, raw binary text scanning (`strings`), and stream filtering workflows on my Medium blog.

🔗 **Read the full writeup here:** [picoCTF: DISKO 1 — Medium Walkthrough](https://medium.com/@R3d0psPD/picoctf-disko-1-74af72fd8d8a?sharedUserId=R3d0psPD)

---

## 🚩 Core Takeaways
- **Sifting Through Raw Data:** The `strings` utility is highly effective for initial triage in forensics. Even within complex structures like disk image snapshots (`.dd`), unencrypted text tokens often reside fully intact within raw data, unallocated space, or slack space.
- **Efficient Filtering:** Combining extraction utilities with deterministic pipeline filters like `grep` allows analysts to instantly pinpoint key flags without manually parsing massive disk outputs.

---
*Follow my CTF journey on [LinkedIn](https://www.linkedin.com/in/parthib-dewanjee-7600a7418/), [GitHub](https://github.com) & [Medium](https://medium.com/@R3d0psPD).*

# picoCTF - Ph4nt0m 1ntrud3r

**Points:** 50  
**Difficulty:** Easy  
**Author:** Prince Niyonshuti N.

---

## 📝 Challenge Description / Problem Statement
"A digital ghost has breached my defenses, and my sensitive data has been stolen! Your mission is to uncover how this phantom intruder infiltrated my system and retrieve the hidden flag. To solve this challenge, you'll need to analyze the provided PCAP file and track down the attack method."

## 🚀 Complete Walkthrough
I have documented the complete step-by-step solution for this challenge with Wireshark packet capture analysis, deep byte-filtering for Base64 structures, timeline reconstruction via physical arrival clocks, and payload decoding on my Medium blog.

🔗 **Read the full writeup here:** [picoCTF: Ph4nt0m 1ntrud3r — Medium Walkthrough](https://medium.com/@R3d0psPD/picoctf-ph4nt0m-1ntrud3r-7074775dd360?sharedUserId=R3d0psPD)

---

## 🚩 Core Takeaways
- **Trust the Arrival Clock:** Attackers can easily forge application-layer tags, TCP sequence numbers, or transmission flags to disrupt automated reassemblers. However, physical packet arrival timestamps logged by the kernel remain an immutable source of truth.
- **Signature-Based Target Profiling:** Recognizing the structural nuances of common encoding algorithms—such as targeting character padding rules (`==`) inherent to Base64 data blocks—allows analysts to rapidly isolate hidden communication streams within massive packet captures.

---
*Follow my CTF journey on [LinkedIn](https://www.linkedin.com/in/parthib-dewanjee-7600a7418/), [GitHub](https://github.com) & [Medium](https://medium.com/@R3d0psPD).*

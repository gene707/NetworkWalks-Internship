# 🔐 Week 3 Internship Project: Password Cracking Lab

## 📖 Overview

The primary objective of this week's internship was to gain hands-on experience with password-cracking techniques and tools. The lab focused on using **John the Ripper** and various **browser-based hash/password-cracking tools** to recover the password of a protected PDF file and obtain the challenge flag.

---

## 🛠️ Tools Used

- 🐧 John the Ripper (Kali Linux)
- 🌐 Browser-based password-cracking tools
- 🔍 Online Hash Tool ([Add URL Here])
- 📚 Custom Wordlists

---

## 📸 Lab Screenshot

![Password Cracking Lab](example.png)

---

## ⚡ Method 1: John the Ripper (Kali Linux)

The first approach involved using **John the Ripper** on Kali Linux.

### 📝 Steps Performed

1. Extracted and obtained the PDF hash.
2. Used an online hash tool to analyze the hash format.  
   🔗 **Reference:** [https://networkwalks.com/hash-calculator/]
3. Saved the extracted hash into a text file.
4. Loaded the hash file into John the Ripper.
5. John the Ripper successfully recovered the password and revealed the correct result.

### ✅ Outcome

The password was recovered successfully, allowing access to the protected PDF file.

---

## 🌐 Method 2: Browser-Based Password Cracking Tool

The second approach used an online password-cracking platform.

### 📝 Steps Performed

1. Submitted the extracted hash to the browser-based tool.
2. Initially attempted to crack the hash using the tool's default wordlist.
3. The default wordlist did not produce a successful result.
4. Uploaded a custom wordlist as instructed.
5. The tool successfully recovered the password using the custom dictionary.

### ✅ Outcome

The password was cracked successfully, and the challenge flag was obtained.

---

## 🚩 Flag Obtained

> ## 🎯 FLAG: `nw{cybersecurity_flag_captured_2608}`

---

## 💡 Key Takeaways

- 🔓 Learned how password-protected files can be attacked using hash-based cracking techniques.
- 🐧 Gained practical experience with **John the Ripper** in Kali Linux.
- 📚 Understood the importance of dictionary attacks and custom wordlists in password recovery.
- ⚖️ Compared the effectiveness of command-line and browser-based password-cracking tools.
- 🎯 Successfully recovered the password and completed the challenge using two different approaches.

---

## 🎓 Conclusion

This lab provided valuable hands-on experience with password-cracking workflows and hash analysis. By using both **John the Ripper** and **browser-based cracking tools**, I gained a better understanding of how password recovery techniques work and how wordlists influence the success of cracking attempts.

The challenge demonstrated that different tools can achieve the same goal through different approaches, reinforcing the importance of selecting the right tool and strategy for a given task. 🚀

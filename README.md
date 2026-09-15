# Password Entropy Analyzer 🔐

A real-time Python utility designed for Cybersecurity and Identity & Access Management (IAM) analysis. It calculates the true mathematical entropy of passwords and estimates brute-force cracking times.

**Features:**
* Calculates character pool size (search space) dynamically based on lowercase, uppercase, digits, and special symbols.
* Uses the `math.log2()` algorithm to measure exact cryptographic entropy in bits.
* Estimates offline brute-force resistance time assuming an attacker hash rate of 100 Billion guesses per second.
* Utilizes Tkinter's `StringVar().trace_add()` method to evaluate inputs instantaneously on keystroke.

*Built as Day 7 of a 30-Day Network Engineering & Security portfolio streak.*

# BV12 [Balance Checker v12]

BV12 builds on the foundation of BV11 with a focus on stealth, performance, and reliability. This version introduces enhanced randomization techniques, improved fault tolerance, and double the user agents—making it the most resilient release yet.

Random delay times are now applied, randomized between 0.01 and 0.50 seconds, to better mimic human behavior and reduce the risk of ip bans.

### 🧰 Executable Version Included  
To make setup easier, an `.exe` file is now provided for users experiencing library installation issues, or for those who want to run the tool without installing Python and dependencies.  
- ".py" file: Works on Android, Linux, and Windows (if Python is already installed)  
- ".exe" file: Windows-only standalone version — no Python or libraries needed

## 🚀 What's New in BV12

### ✅ 2 Million Fresh User Agents  
BV12 now includes 2 million built-in user agents, doubling the pool from BV11. This helps reduce detection rates, avoid bans, and scale effortlessly across massive address scans.

### ✅ Advanced Stealth with Agent Shuffling  
BV12 introduces a new shuffling technique:

- User agents are divided into 10 random groups  
- Each group runs independently and is shuffled during runtime  
- Groups themselves are also randomized using "random.shuffle(groups)"

This ensures non-linear, unpredictable behavior—mimicking human browsing patterns and making automated scans harder to detect.

### ✅ "Ghost Mode" Execution  
The tool now runs in a split-execution pattern, breaking into 10 parallel randomized tasks. This improves distribution across user agents and enhances anonymity.

### ✅ Resume Fix  
A critical bug in `resumer.txt`—where progress would reset to zero after multiple retries—has been resolved. Your scans now reliably resume from where they left off.

### ✅ Improved Fault Logging  
Failed address handling is still in place via "FailedAddresses.txt". Any address that fails to return a balance will be logged for later re-scanning—ensuring 100% coverage, even across billions of addresses.

⚠️ Disclaimer
I am not responsible for any misuse of this tool. It is intended strictly for educational and research purposes only.  
Using it for malicious activity or with harmful intent may lead to serious consequences.  
I do not accept any responsibility for how others choose to use it.

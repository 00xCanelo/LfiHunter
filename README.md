# **LFI Hunter Tool**

**Description**  
This tool is designed for fuzzing and detecting **Local File Inclusion (LFI)** vulnerabilities in web applications. It leverages `ffuf` for fast and efficient fuzzing and supports customizable options like threading and wordlist selection.

---

### **Features**
- Automated LFI fuzzing using `ffuf`.
- Supports customizable wordlists, threading, and URL targets.
- Clear error handling and installation checks.
- Outputs results in a user-friendly format.

---

### **Usage**

#### **Clone the Repository**
To get started, clone this repository on your Linux machine:

```bash
git clone https://github.com/yourusername/LFIHunter.git
cd LfiHunter
chmod +x lfihunter
./lfihunter
```
---
### **Example**
```bash
./lfihunter -u http://example.com?page=FUZZ -w wordlist.txt -t 100
```
---
### **Options:**
- `-u`: (Required) The URL to fuzz, e.g., `http://example.com?page=FUZZ`.
- `-w`: (Optional) Path to the wordlist file. Defaults to `lfi.txt`.
- `-t`: (Optional) Number of threads to use. Defaults to `50`.

---
### **Disclaimer**

**LFI Hunter** is a security testing tool intended solely for **authorized use**. It is designed to assist in identifying **Local File Inclusion (LFI)** vulnerabilities in web applications.

By using this tool, you agree to the following terms:

1. **Authorized Use Only**  
   This tool must only be used on systems or websites where you have explicit permission to perform security testing. Unauthorized use of this tool against any system, website, or network without permission is illegal and unethical.

2. **No Malicious Use**  
   The tool is intended to help security professionals identify vulnerabilities to improve security. Any attempt to exploit vulnerabilities for unauthorized access, data theft, or any illegal activity is strictly prohibited.

3. **Responsibility**  
   The developer(s) and contributors of this tool are not responsible for any illegal, unethical, or malicious activities performed with it. The user assumes full responsibility for their actions.

4. **No Warranty**  
   This tool is provided **as-is** with no warranty of any kind, express or implied. The developer(s) are not liable for any damages, data loss, or negative impacts resulting from the use of this tool.

By using **LFI Hunter**, you acknowledge that you have read, understood, and agree to comply with this disclaimer.

# 💀HashStorm💀

## 📜Description
This is a hash cracking tool designed for testing and educational purposes only. It supports multiple cracking methods, including brute force attacks and dictionary attacks, using SHA-256 and MD5 hashing algorithms. The script is optimized for performance using multiprocessing to leverage multiple CPU cores.  

- Cython is a superset of Python designed to give C-like performance with code that is written mostly in Python. Used primarily to optimize Python code by compiling it to C, which can significantly increase execution speed, especially in CPU-bound tasks.  
- Cython code can include both Python and C syntax, allowing for more granular control over performance.    

## 🔑Features
- ✔ Supports SHA-256 and MD5 hashing algorithms  
- ✔ Brute force attack with customizable character sets  
- ✔ Dictionary attack using pre-defined or custom wordlists  
- ✔ Multiprocessing for faster hash cracking  
- ✔ User-friendly prompts for easy interaction  

## 🚀Step-by-Step Guide in Linux Terminal !

Step 1: Update & upgrade your system  
>sudo apt update  

>sudo apt upgrade  

Step 2: install Dependencies  
>sudo apt install cython3  

>sudo apt install python3-setuptools  

Step 3: Clone the repository  
>git clone https://github.com/The-Real-Virus/HashStorm.git  

Step 4: Go to the Tool Directory where u clone it  
>cd HashStorm  

Step 5: compile into cython py  
>python run.py build_ext --inplace  

Step 6: After Completing the process now u can run script  
>python -c "import cracker; cracker()"

## 💡Tips !
🌐 Brute force attacks take longer, so prioritize dictionary-based cracking when possible.  
⚡ Use a strong wordlist for faster and more effective dictionary attacks.   
🔄 Ensure Python dependencies are installed before running the script.  
- 🛠️ Wordlists:
	Linux already have alot of wordlists also rockyou present at `/usr/share/wordlists`  
	or u can download here [rockyou.txt](https://github.com/brannondorsey/naive-hashcat/releases/download/data/rockyou.txt)  

## 🤝Follow the Prompts !
1) Run the script:  
2) Choose the hashing algorithm and attack method.  
3) Enter the target hash to crack.  
4) Provide a wordlist file (for dictionary attack) or specify brute force parameters.  
5) View the cracked password if successfully found!  

## ⚙️Troubleshooting

1) `Issue: Slow Cracking Speed?:`  
- Increase CPU cores or use a better wordlist.  

2) `Issue: Missing Modules?:`  
- read the requirements.txt file, (cat requirements.txt) or (gedit requirements.txt).  

3) `Issue: Permission Denied?:`  
- try using sudo  

4) `Issue: Python3 or pip not found?:`  
- read the requirements.txt file, (cat requirements.txt) or (gedit requirements.txt).  

5) `Issue: Hash Not Found?:`  
- The password might be too complex for the current wordlist/brute force settings.  

6) `cython module not found?:`  
- try this command `pip install Cython --break-system-packages` permisson denied then use sudo at start.  

## 🛠️MODIFICATION 
- U CAN ADD MORE HASHES ALGOS.  
- U CAN CREATE AND USE OWN WORDLISTS.  
- IF U WANT TO MODIFY OR USE THE SCRIPT IN UR PROJECTs , CONSIDER GIVING CREDITS !  

## 📂Example OutPut

	### ✅ **Dictionary Attack Example**  
	**Input:**  
	```
	Enter hash: 5d41402abc4b2a76b9719d911017c592  
	Choose attack type: Dictionary  
	Enter wordlist path: rockyou.txt  
	**Output:**  
	```
	[+] Hash cracked! Password: hello
	```  

	### ✅ **Brute Force Attack Example**  
	**Input:**  
	```
	Enter hash: 81dc9bdb52d04dc20036dbd8313ed055  
	Choose attack type: Brute Force  
	Character set: Lowercase + Digits  
	Max length: 4  
	```  
	**Output:**  
	```
	[+] Hash cracked! Password: 1234
	```  

# ⚠️Disclaimer !
This tool is intended for ethical and educational use only.  
Do not use it for illegal activities. The author is not responsible for any misuse.  
This script is intended for educational purposes and authorized testing only.  
Unauthorized use of this script is illegal and unethical.  
Ensure you have explicit permission before testing any system.  
- Obtain explicit permission before testing any system.  
- Adhere to all applicable laws and regulations.  
- Respect user privacy and data.  
- By using this script, you agree to take full responsibility for your actions.  

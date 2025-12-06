This project generates a synthetic malware-style dataset containing 5000 records.
It is completely safe, fully artificial, and designed for cybersecurity, machine learning, and IDS/IPS research.

The script simulates:

Malware families

File hashes (MD5, SHA1, SHA256)

File metadata (size, type, sections, entropy)

Behavior summaries

Detection ratios

C2 IPs & malicious domains

Tags (ransomware, trojan, etc.)

The output is exported as:
📁 malware_dataset_synthetic_5000.csv

🎯 Objective

To create a synthetic dataset that resembles real malware metadata.

To support AI/ML experiments for malware classification.

To safely generate realistic features without using or handling real malware.

🧪 Practical Description

This practical demonstrates:

Randomized malware metadata generation

Hash creation using Python’s hashlib

Feature simulation (entropy, imported functions, behavior text)

Date generation for first_seen and last_seen

CSV creation using pandas

The generated dataset can be used for:

Machine learning model training

Intrusion detection system (IDS) experiments

Malware analysis simulations

Data preprocessing practice

🛠️ How to Run (Google Colab Recommended)
Step 1: Open Google Colab

Go to: https://colab.research.google.com/

Step 2: Copy–paste the entire Python script

The script is self-contained and requires no external files.

Step 3: Run all cells

After execution, you will see:

CSV created at: malware_dataset_synthetic_5000.csv

Step 4: Download the Generated CSV

It will appear in the Colab file browser.

📂 Output File
File Name	Description
malware_dataset_synthetic_5000.csv	Contains 5000 synthetic malware-style entries

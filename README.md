# -PENETRATION_TESTING-_TOOLKIT
A modular, colorful, and multithreaded Penetration Testing Toolkit built in Python. Designed for ethical hacking and cybersecurity learning, this toolkit includes tools like a Port Scanner and Brute Force Login Simulator, all in a GUI-based interface using tkinter.

#Name- Pranav Ghodke

#InternId - ETI-AO-10004097246

Features
✅ Modular toolkit structure

🌈 Colorful and intuitive GUI (Tkinter-based)

🚀 Multithreaded Port Scanner (1–1024 range) with thread-safe GUI updates

🔐 Dictionary-based Brute Force Login simulator

🧱 Easily extendable: Add your own tools as modules!

📦 No external dependencies (only standard Python libraries)

PROJECT STRUCTURE-

pen_test_toolkit/

├── main.py                  # Main GUI launcher

├── modules/

│   ├── port_scanner.py      # Advanced multithreaded port scanner

│   └── brute_forcer.py      # Brute force login simulator

└── assets/
   └── wordlist.txt         #  Sample password list
 
 **Modules Included
🔍 Port Scanner
  Scans ports 1-1024 on any host or IP.

  Uses ThreadPoolExecutor for fast, concurrent scanning.

  Thread-safe queue.Queue and after() ensure the GUI remains responsive.

🔐 Brute Force Simulator
  Simulates a password brute-force using a wordlist.

  Useful for demonstrating dictionary attacks on weak passwords.

  Editable wordlist: assets/wordlist.txt


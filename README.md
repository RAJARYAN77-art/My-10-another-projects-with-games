# Python Cyber Games

A collection of 10 beginner-to-intermediate Python projects created for programming and cybersecurity learning.

## Projects

1. IP / Domain Information Tool
2. Hash Generator / Checker
3. Basic OSINT Tool
4. Local Network Monitor
5. File Integrity Checker
6. Python Hero - original CodeCombat-style learning RPG
7. Snake - Turtle Graphics
8. Number Guessing Game
9. Tic-Tac-Toe
10. Hangman

## Requirements

Python 3.10+ is recommended.

Most projects use only Python's standard library.

The Network Monitor optionally uses `psutil` for richer local socket information:

```bash
pip install -r requirements.txt
```

## Run

From this folder:

```bash
python 01_ip_domain_information/ip_domain_tool.py
python 02_hash_generator_checker/hash_tool.py
python 03_basic_osint/osint_tool.py
python 04_network_monitor/network_monitor.py
python 05_file_integrity_checker/integrity_checker.py
python 06_python_hero/python_hero.py
python 07_snake/snake.py
python 08_number_guessing/number_guessing.py
python 09_tic_tac_toe/tic_tac_toe.py
python 10_hangman/hangman.py
```

On Windows, `py` can be used instead of `python`.

## Cybersecurity safety

The cybersecurity utilities are intentionally limited to passive/public information and local-machine monitoring. Use them only against systems, domains, IP addresses, and files that you own or are authorized to examine.

## Learning goals

- Python syntax and control flow
- Functions and classes
- File handling
- Hashing
- DNS and sockets
- HTTPS/TLS basics
- Local network visibility
- Integrity monitoring
- Game-state management
- Input validation

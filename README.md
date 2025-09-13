# pw-detector

Password strength & breach detector — entropy, dictionary checks, and HaveIBeenPwned k-anonymity breach lookup.

## Features
- Shannon entropy calculation
- Character class checks (lower, upper, digit, symbol)
- Detects common passwords / dictionary substrings
- Optional breach check via HaveIBeenPwned (k-anonymity)

## Quickstart
1. Clone repo
2. (optional) `pip install -r requirements.txt`
3. Run:
```bash
python3 password_detector.py "MyP@ssw0rd!"
# or check a file:
python3 password_detector.py -f passwords.txt -b

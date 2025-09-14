# Greper Tool

Greper is a Bash-based forensics utility for searching, parsing, and analyzing memory or disk images.  
It integrates tools like **strings**, **Volatility**, and **Exiftool** to extract artifacts useful for digital forensics and incident response (DFIR).

## Features
- Automated artifact extraction from memory and disk images  
- Filtering and parsing with custom rules  
- Integration with popular forensics tools (Volatility, Exiftool, Strings)  
- Generates reports for investigation workflow  

## Usage
```bash
bash greper.sh /path/to/memory_or_disk_image

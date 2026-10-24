"""
Subdomain Enumeration Tool

Reads potential subdomain names from a wordlist, prepends each one
to a target domain, and tests for valid responses via HTTP.

Usage:
    python3 subdomain_enum.py <domain> <wordlist>

Example:
    python3 subdomain_enum.py example.com subdomains.txt
"""

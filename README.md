# OTP-TOOL

# Brute Force Tool for MFA OTP

This tool was developed to simplify the process of performing brute-force attacks on OTP tokens in web applications. The script automates the process of submitting an OTP in an attempt to bypass two-factor authentication.

Additionally, I’ve added two input fields that allow the user to set minimum and maximum delays between requests. This feature helps avoid detection by Intrusion Detection Systems (IDS), Intrusion Prevention Systems (IPS), Web Application Firewalls (WAF), or any other firewalls that might identify patterns commonly associated with brute-force attacks.

Features:
Automated OTP submissions: Automatically submits OTP attempts until authentication is successful.

Customizable delays: Allows setting minimum and maximum delay times between requests to avoid triggering security measures like IDS/IPS and WAF.

Simple configuration: Just provide the login URL, OTP submission URL, dashboard URL, user credentials, OTP, and minimum and maximum delay between each request, and the script does the rest.

Note: This tool is intended for educational purposes only and should not be used on any systems without explicit permission. Unauthorized access to computer systems is illegal and unethical.

# SSL Certificate Generator for Phishing (PhishCert)

PhishCert is a penetration testing and red teaming tool that automates the creation of a Let's Encrypt SSL certificate using Certbot.

## Installation

Clone the GitHub repository
```
git clone https://github.com/centralinfosec/SSL-Certificate-Generator-for-Phishing /opt/Central-InfoSec/SSL-Certificate-Generator-for-Phishing
```

## Usage

 - Multiple domains and subdomains can be imported from a file titled "domains.txt" with one per line
   - If a "domains.txt" file does not exist, the user will be required to enter one domain
 - Run the following commands to generate a certificate:
```
chmod +x /opt/Central-InfoSec/SSL-Certificate-Generator-for-Phishing/generateSslCertificate.sh
/opt/Central-InfoSec/SSL-Certificate-Generator-for-Phishing/generateSslCertificate.sh
```

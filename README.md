📌 Libraries in Assignment 2 (Application Layer Protocols)
🔹 For HTTP (httptext.py)

requests → to send HTTP GET/POST requests.

🔹 For SMTP (smtptxt.py)

smtplib → to connect to SMTP server & send mails.

email.message → to create email (subject, body, sender, receiver).

dotenv → to load sensitive info (email, password) from .env.

os → to read environment variables.

datetime → to log sent emails with timestamp.

🔹 For FTP (ftptext.py)

ftplib → to connect, upload, download, and list files on FTP server.

os → to handle local files (read/write).

🔹 For DNS (dnstext.py)

socket → to resolve domain → IP.

dns.resolver (from dnspython) → to query DNS records (A, MX, CNAME).

datetime → to add timestamps in logs.

🔹 For LDAP (ldaptext.py – optional/extra)

ldap3 → to connect & query directory servers (if implemented).

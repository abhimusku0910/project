# Security Hardening

Security hardening was performed to reduce vulnerabilities.

## Password Hardening

Default root password changed:

passwd

Strong passwords:

Uppercase

Lowercase

Numbers

Special characters

---

## Password Storage

Command:

cat /etc/shadow

Passwords stored using hashes.

SHA-512 observed.

---

## SSH Hardening

SSH port changed:

22 → 2222

Command:

vi /etc/config/dropbear

Restart:

/etc/init.d/dropbear restart

---

## SSH Key Authentication

Generate keys:

ssh-keygen

---

## Disable Unused Services

List services:

ls /etc/init.d/

Disable:

/etc/init.d/uhttpd disable

---

## Result

Reduced attack surface

Improved authentication

Better remote access security
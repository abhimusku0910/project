# Project Plan

## Project Title

Cyber Security and Networking Implementation Using OpenWRT for Melbourne Tax & Accounting Services

---

## Group Members

| Name | Student ID |
|------|-------------|
| Abhiram Reddy Musku | 12315073 |
| Madhu Sudhan Kempula | 12317190 |

---

# 1. Project Objective

The objective of this project is to design and secure a small business network environment using OpenWRT. The project aims to implement firewall rules, perform network hardening, analyze traffic and assess cybersecurity risks affecting an accounting business.

The project demonstrates practical cybersecurity controls for protecting financial information and business systems.

---

# 2. Scope

The project includes:

✓ OpenWRT Installation

✓ Network Configuration

✓ Firewall Configuration

✓ SSH Hardening

✓ Password Security

✓ Traffic Analysis

✓ Packet Capture

✓ Risk Assessment

✓ Security Controls

✓ GitHub Documentation

✓ Final Report

---

# 3. Business Scenario

Business:

Melbourne Tax & Accounting Services

Industry:

Accounting and Finance

Employees:

8 Staff Members

Location:

Melbourne, Australia

Sensitive Data:

- Client Records
- Payroll Data
- Tax Information
- Employee Information

---

# 4. Technologies Used

| Technology | Purpose |
|------------|----------|
| OpenWRT | Router and firewall |
| VirtualBox | Virtualisation |
| Wireshark | Packet analysis |
| tcpdump | Traffic capture |
| GitHub | Version control |
| Linux | Command execution |

---

# 5. Project Tasks

## Phase 1: Environment Setup

Tasks:

- Install VirtualBox
- Install OpenWRT
- Configure NAT adapter
- Configure Host-only adapter

Deliverables:

- Network screenshots
- IP configuration

---

## Phase 2: Network Configuration

Tasks:

Run:

ip addr

ip route

ping google.com

Deliverables:

- Network evidence
- Screenshots

---

## Phase 3: Firewall Configuration

Tasks:

Block:

HTTP

ICMP

Commands:

uci show firewall

iptables -L

Deliverables:

- Firewall screenshots
- Rules evidence

---

## Phase 4: Security Hardening

Tasks:

Change passwords

Generate SSH keys

Disable services

Change SSH port:

22 → 2222

Deliverables:

- SSH screenshots
- Password evidence

---

## Phase 5: Traffic Analysis

Tasks:

Capture HTTP traffic

Capture SSH traffic

Commands:

tcpdump -i any

Deliverables:

- Packet captures
- Wireshark screenshots

---

## Phase 6: Risk Assessment

Tasks:

Perform TVA Matrix

Identify:

Assets

Threats

Vulnerabilities

Controls

Deliverables:

- TVA Matrix
- Risk report

---

## Phase 7: Documentation

Tasks:

Prepare:

README.md

network.md

security.md

risk_assessment.md

reflection.md

references.md

Deliverables:

GitHub Repository

---

# 6. Timeline

| Week | Task |
|------|------|
| Week 1 | OpenWRT installation |
| Week 2 | Network setup |
| Week 3 | Firewall configuration |
| Week 4 | Security hardening |
| Week 5 | Traffic analysis |
| Week 6 | Risk assessment |
| Week 7 | GitHub documentation |
| Week 8 | Final submission |

---

# 7. Risks During Project

Possible risks:

- OpenWRT installation failure
- VirtualBox network issues
- Firewall misconfiguration
- SSH access loss
- Missing screenshots

Mitigation:

- Backup configurations
- Save screenshots frequently
- Test commands before applying

---

# 8. Expected Outcomes

After completion, the project should demonstrate:

✓ Secure OpenWRT deployment

✓ Firewall implementation

✓ Secure remote access

✓ Network traffic monitoring

✓ Risk mitigation

✓ Cybersecurity awareness

---

# 9. Final Deliverables

1. Final Report (.pdf)

2. GitHub Repository

3. Screenshots

4. Packet Captures

5. Configuration Files

6. TVA Matrix

7. Network Diagrams

8. References

---


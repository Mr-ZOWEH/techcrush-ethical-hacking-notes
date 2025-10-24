# TechCrush Ethical Hacking Bootcamp - Notes

**Instructor:** Caleb Ndubuisi  
*A repository to document my learnings and progress through the TechCrush Ethical Hacking Bootcamp.*

---

## **Module 1: Introduction to Ethical Hacking**

### **Core Concepts**

#### **What is Hacking?**
- The act of gaining unauthorized access to systems or networks by exploiting vulnerabilities.
- The goal can be ethical (security improvement) or malicious (theft, damage).

#### **What is Ethical Hacking?**
- The **authorized** practice of employing hacking skills to test an organization's defenses.
- The goal is to identify and report vulnerabilities so they can be fixed.
- Also known as **Penetration Testing** or **Security Auditing**.

#### **Types of Hackers: The "Hats"**
- **White Hat:** The ethical hacker. Works with permission to improve security.
- **Black Hat:** The malicious hacker. Breaks in for personal or financial gain.
- **Grey Hat:** Operates without explicit permission but without pure malicious intent (e.g., hacking to expose a flaw publicly).

### **The Legal & Ethical Framework**
This was the most critical part of the lesson. Ethical hacking is defined by its boundaries:
1.  **Authorization is Mandatory:** Must have a signed contract/agreement before any testing begins.
2.  **Respect the Scope:** Testing must not go beyond the agreed-upon limits (e.g., no Denial-of-Service attacks unless specified).
3.  **Confidentiality:** All findings and accessed data must remain confidential, often under an NDA (Non-Disclosure Agreement).

### **Methodologies & Frameworks**
Briefly introduced to industry standards that guide professional testing:
- **OWASP:** Provides testing guides for Web, Mobile, and IoT applications.
- **NIST SP 800-115:** A technical guide for information security testing.
- **PTES (Penetration Testing Execution Standard):** A comprehensive standard defining 7 phases of a penetration test.

---
*These notes summarize my personal learnings from the TechCrush Bootcamp. All original training material is the property of TechCrush.pro.*










🧠 Day 2 — Information Security Fundamentals (CIA Triad, Controls, Risk & Compliance)

Date: 2025-10-21
Bootcamp: TechCrush Ethical Hacking Bootcamp (#techcrushHQ)
Facilitator: Caleb Ndubuisi


---

🗒️ Summary

Today’s class laid the groundwork for every ethical hacker and blue-team defender.
We explored the CIA Triad, Information Assurance, the three layers of security controls, the risk formula, and the laws & compliance frameworks that govern modern cybersecurity.

It was a reminder that hacking responsibly isn’t just about tools — it’s about protecting confidentiality, integrity, and availability with ethics and structure.


---

🔍 What I Learned

🧩 1. The CIA Triad

Confidentiality – prevent unauthorized access (encryption, passwords).

Integrity – keep data accurate & untampered (hashing, version control).

Availability – ensure authorized users can access resources when needed (redundancy, backups).


🛡️ 2. Information Assurance (IA)

Ensures authenticity, reliability, and trust throughout data’s life cycle.

Achieved through administrative, technical, and physical safeguards.


⚙️ 3. Security Controls Categories

Type	Focus	Example

Administrative	Policies, training, HR processes	Security policies, awareness sessions
Technical	Hardware/software mechanisms	Firewalls, MFA, IDS, encryption
Physical	Tangible barriers	CCTV, locks, biometric access


Each works together to form a layered defense (Defense-in-Depth).

📊 4. Risk Assessment

Formula:

RISK = THREAT * VULNERABILITY * IMPACT

A Risk Matrix compares likelihood vs consequence, helping prioritize what to fix first.

📚 5. Security Laws & Standards

GDPR (EU) – global privacy benchmark

NDPA (Nigeria) – 2023 data protection law

HIPAA (US) – healthcare information security

SOX (US) – financial record integrity

PCI DSS – payment card data protection

ISO/IEC 27001/27701 – global ISMS standards


🤝 6. Ethical & Compliance Principles

Lawful data handling & informed consent

Transparency and accountability

Minimal data collection & responsible storage




Date: 2025-10-22
Bootcamp: TechCrush Ethical Hacking Bootcamp (@TechCrushHQ)
Scholarship: #Tech4AfricansScholarship  |  #TechCrush  |  #Tech4Africans
Facilitator: Caleb Ndubuisi


---



🗒️ Summary

Day 3 introduced one of the most critical stages in ethical hacking — Information Gathering and Reconnaissance, also called footprinting.
Before any penetration test begins, an ethical hacker must know what’s visible to the world.
Today’s lesson taught how to collect, interpret, and secure that public information responsibly.


---

🔍 What I Learned

1️⃣ Footprinting Concept

Reconnaissance is the information-collection phase before testing.

It helps identify risks from public data exposure.

The goal: Know your target, secure your perimeter.


2️⃣ Types of Footprinting

Type	Interaction	Tools / Sources	Purpose

Passive	No direct contact	Search engines, OSINT, social media	Silent info gathering
Active	Direct interaction	DNS queries, port scans, enumeration	Deeper technical mapping


3️⃣ Search Engine Reconnaissance

Search engines reveal enormous data about companies, technologies, and infrastructure.
Ethical hackers use Google Dorking defensively — to discover and fix what attackers might find.

4️⃣ Advanced Search Operators

# Examples of safe reconnaissance queries
site:example.com
inurl:login
intitle:"index of"
intext:"vpn configuration"

These narrow down results and expose public-facing data that shouldn’t be exposed.
👉🏽 Always review and secure such findings — never exploit them.

5️⃣ Other Recon Sources

Wayback Machine (archive.org): View historical pages or deleted content.

People Search Engines: Identify exposed contact data (Spokeo, Pipl, Whitepages).

Shodan: Discover devices and open ports on the public Internet.

WHOIS: Find domain registration and ownership details.


6️⃣ Ethical Boundaries

Footprinting is legal only when used for authorized assessment.
The purpose is awareness, not exploitation.
Report, remediate, and educate — never attack.


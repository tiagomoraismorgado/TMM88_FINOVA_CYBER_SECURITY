# Finova Cyber Security - Sommeraufgabe 🌞

Hallo und herzlich willkommen zur Sommeraufgabe von Finova Cyber Security!  
Ziel dieser Aufgabe ist es, die **Grundlagen der Cybersicherheit** zu erlernen und praxisnahe Technologien kennenzulernen.

---

## 🧭 Wähle zuerst deine "Seite"

Cybersicherheit lässt sich grob in zwei Bereiche unterteilen.

### 🔴 Red Team (Angriff)
- Denke wie ein Hacker und nutze **Schwachstellen** aus
- Themen: Penetrationstests, Social Engineering, Exploit-Entwicklung

### 🔵 Blue Team (Verteidigung)
- **Schütze** Systeme und **erkenne** Bedrohungen
- Themen: Netzwerküberwachung, Incident Response, Log-Analyse

---

**Für welche Rolle entscheidest du dich?**  
※ Beide Bereiche zu wählen ist natürlich auch möglich!

---

## 🔴 Option 1: Hacker (Red Team)

Bei dieser Option lernst du die Techniken des Red Teams praxisnah durch **CTF-Aufgaben (Capture The Flag)**.

Die Inhalte sind in **5 Bereiche** unterteilt.  
**Wähle mindestens zwei Bereiche und löse alle darin enthaltenen Aufgaben.**

---

### 🌐 Web Exploitation

📘 [Web Exploitation Cheat Sheet (Referenz)](https://wiki.studsec.nl/books/ctf-guides/page/web)

1. Gehe zu den [PortSwigger Labs](https://portswigger.net/web-security/all-labs)
2. Schließe die **Apprentice-Level** in folgenden Bereichen ab:
   - SQL Injection
   - Cross‑Site Scripting (XSS)
   - Clickjacking
   - XML External Entity (XXE) Injection
   - Authentication

---

### 🔐 Cryptography

📘 [Krypto Cheat Sheet (Referenz)](https://wiki.studsec.nl/books/ctf-guides/page/crypto)

1. Gehe zu [CryptoHack](https://cryptohack.org/challenges/)
2. Schließe folgende Bereiche ab:
   - Introduction
   - General → Encoding
   - Symmetric Ciphers → How AES Works & Symmetric Starter
   - RSA → Starter
   - Crypto On The Web → JSON Web Tokens

---

### ⚙️ Reverse Engineering

📘 [Reverse Engineering Guide (Referenz)](https://wiki.studsec.nl/books/ctf-guides/page/reverse-engineering)

1. Gehe zu den [PicoCTF Übungen](https://play.picoctf.org/practice?category=3&page=1) (Empfehlung: Account erstellen)
2. Löse folgende Herausforderungen:
   - Vault Door Series (1–8)
   - Armssembly (1–4)
   - GDB baby series (1–4)
   - Need for Speed

📌 Für tiefergehendes Wissen empfehlen wir [challenges.re](https://challenges.re/).

---

### 🕵️ Forensics

📘 [Forensik Guide (Referenz)](https://wiki.studsec.nl/books/ctf-guides/page/forensics)

1. Gehe zu [PicoCTF Forensics](https://play.picoctf.org/practice?category=4&page=1)
2. Löse folgende Herausforderungen:
   - Secret of the Polyglot
   - CanYouSee
   - Wireshark doo dooo do doo... (1, 2)
   - shark on wire 1, 2
   - Packets Primer
   - SleuthKit Apprentice
   - Eavesdrop
   - So Meta
   - SideChannel
   - WebNet0, 1

🛠️ [Liste der in der Forensik verwendeten Tools](https://docs.google.com/document/d/1KUy_Sh9d5lo9ozuoW2WPl3z0gOZyM4yGDZBS1S7HhJ8/edit?tab=t.0)

---

### 💥 Binary Exploitation (Pwn)

📘 [Pwn Guide (Referenz)](https://wiki.studsec.nl/books/ctf-guides/page/pwn)

1. Gehe zu [PicoCTF Binary Exploitation](https://play.picoctf.org/practice?category=6&page=1)
2. Löse folgende Herausforderungen:
   - PIE TIME 1, 2
   - format string series (0–3)
   - buffer overflow series (0–3)
   - heap series (0–3)
   - Local Target
   - function overwrite
   - Unsubscriptions Are Free

📘 Für tiefergehendes Wissen empfehlen wir [guyinatuxedo.github.io](https://guyinatuxedo.github.io/index.html)

---

### ☁️ Bonus: Cloud Security

1. Gehe zu [flaws.cloud](http://flaws.cloud/)
2. Erlebe AWS-spezifische Schwachstellen

---

**✅ Bei dieser Option wählst du mindestens zwei Bereiche und löst alle darin enthaltenen Aufgaben.**  
Weitere Bereiche sind natürlich willkommen!

---

## 🔵 Option 2: CISO (Blue Team)

Für alle, die lernen möchten, wie Unternehmen ihre Sicherheit schützen.  
Bei dieser Option lernst du die **Grundlagen der Verteidigung (Blue Team)** systematisch kennen.

In der Branche wird Cybersicherheit oft in folgende vier Bereiche unterteilt:

---

### 🌐 Netzwerksicherheit

Warum zuerst Netzwerk?  
Weil **jede IT-Infrastruktur auf Netzwerken aufbaut**.

1. Gehe zu [Let’s Defend - Network Fundamentals](https://app.letsdefend.io/training/lessons/network-fundamentals) (Account erstellen)
2. Schließe den Kurs **Network Fundamentals** ab

📘 Für tiefergehendes Wissen empfehlen wir [diese Playlist](https://www.youtube.com/playlist?list=PLxbwE86jKRgMpuZuLBivzlM8s2Dk5lXBQ).  
Zertifikate wie **CompTIA Network+** oder **CCNA** sind ebenfalls wertvoll für die Karriere.

---

### 🛡️ SOC (Security Operations Center)

Lerne die Rolle des „SOC“ kennen, das die Sicherheit eines Unternehmens rund um die Uhr überwacht.

1. Gehe zu [Let’s Defend - SOC Fundamentals](https://app.letsdefend.io/training/lessons/soc-fundamentals)
2. Schließe den Kurs **SOC Fundamentals** ab

In diesem Kurs lernst du grundlegende Begriffe und Tools kennen, die in einem SOC verwendet werden.

---

### 🧪 Blue Team Übungen (Praxis)

Wende dein Wissen bei folgenden Herausforderungen auf Blue Team Labs Online an.

1. Gehe zu [Blue Team Labs Online](https://blueteamlabs.online/home/challenges) (Account erstellen)
2. Löse folgende Aufgaben:

#### Easy
- The Report I, II (lerne das MITRE ATT&CK-Framework kennen)
- Follina
- ThePackage (lerne Google Dorking kennen)
- Phishing Analysis 1 & 2
- Malware Analysis - Ransomware Script
- Powershell Analysis - Keylogger
- ILOVEYOU

#### Medium
- Bruteforce
- Suspicious USB Stick
- Squid Game
- Network Analysis - Ransomware
- Network Analysis - Malware Compromise
- Injection Series (1–4)
- Paranoid

#### Hard
- Secure Shell
- D-Crypt

---

## 📥 Abgabe

- Erstelle für jede Herausforderung einen **Write-up (Bericht)** und füge ihn diesem Repository hinzu.
- Der Write-up sollte Folgendes enthalten:
  - Die Flag (falls gefunden)
  - Die Vorgehensweise zur Lösung
  - (Falls nicht gelöst) Deine Lösungsversuche

**Beispiel: `Need For Speed.md`**
```
Flag: picoctf{flag}

Lösung: ...
```

- Bei abgeschlossenen Kursen füge bitte einen **Screenshot des Zertifikats oder Abzeichen** bei.

---

## 🗓️ Abgabefrist

**20. Juli 2025, 23:59 Uhr**

---

Wenn du Fragen hast oder nicht weiterkommst, melde dich gerne per DM oder in der Gruppe.  
Ich hoffe, dass diese Aufgabe euch den Einstieg in die Welt der Cybersicherheit erleichtert.

**Habt einen tollen Sommer!**

**Sujai**  
_Cyber Security Head_
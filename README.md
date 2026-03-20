# Finova Cyber Security - サマータスクへようこそ！ 🌞

こんにちは！  
Finova Cyber Securityのサマータスクに参加してくれてありがとうございます。  
このタスクの目的は、**サイバーセキュリティの基礎**を学び、実際に使われる技術を体験することです。

---

## 🧭 まずは「サイド」を選ぼう

サイバーセキュリティは大きく2つに分けられます。

### 🔴 レッドチーム（攻撃）
- ハッカーのように考え、システムの**脆弱性を突く**
- ペネトレーションテスト、ソーシャルエンジニアリング、エクスプロイト開発などを経験

### 🔵 ブルーチーム（防御）
- システムを**守り**、脅威を**検知**する
- ネットワーク監視、インシデント対応、ログ分析などに従事

---

**あなたはどちらのロールに挑戦しますか？**  
※ 両方に挑戦することももちろん可能です！

---

## 🔴 オプション1：ハッカー（レッドチーム）

このオプションでは**CTF（Capture The Flag）形式**の課題を通して、  
レッドチームの技術を実践的に学びます。

各分野は**5つのドメイン**に分かれています。  
**2つ以上のドメインを選び、すべての課題をクリアしてください。**

---

### 🌐 Web Exploitation

📘 [Web Exploitation チートシート（参考）](https://wiki.studsec.nl/books/ctf-guides/page/web)

1. [PortSwiggerのラボ](https://portswigger.net/web-security/all-labs) にアクセス
2. 以下の分野の **Apprentice レベル** をすべて完了：
   - SQL Injection
   - Cross‑Site Scripting (XSS)
   - Clickjacking
   - XML External Entity (XXE) Injection
   - Authentication

---

### 🔐 Cryptography

📘 [暗号チートシート（参考）](https://wiki.studsec.nl/books/ctf-guides/page/crypto)

1. [CryptoHack](https://cryptohack.org/challenges/) にアクセス
2. 以下のセクションを完了：
   - Introduction
   - General → Encoding
   - Symmetric Ciphers → How AES Works & Symmetric Starter
   - RSA → Starter
   - Crypto On The Web → JSON Web Tokens

---

### ⚙️ Reverse Engineering

📘 [リバースエンジニアリングガイド（参考）](https://wiki.studsec.nl/books/ctf-guides/page/reverse-engineering)

1. [PicoCTF 練習問題](https://play.picoctf.org/practice?category=3&page=1) にアクセス（アカウント作成推奨）
2. 以下のチャレンジを完了：
   - Vault Door Series (1–8)
   - Armssembly (1–4)
   - GDB baby series (1–4)
   - Need for Speed

📌 より深く学びたい方は [challenges.re](https://challenges.re/) もおすすめです。

---

### 🕵️ Forensics

📘 [フォレンジックガイド（参考）](https://wiki.studsec.nl/books/ctf-guides/page/forensics)

1. [PicoCTF Forensics](https://play.picoctf.org/practice?category=4&page=1) にアクセス
2. 以下のチャレンジを完了：
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

🛠️ [フォレンジックで使われるツール一覧](https://docs.google.com/document/d/1KUy_Sh9d5lo9ozuoW2WPl3z0gOZyM4yGDZBS1S7HhJ8/edit?tab=t.0)

---

### 💥 Binary Exploitation (Pwn)

📘 [Pwnガイド（参考）](https://wiki.studsec.nl/books/ctf-guides/page/pwn)

1. [PicoCTF Binary Exploitation](https://play.picoctf.org/practice?category=6&page=1) にアクセス
2. 以下のチャレンジを完了：
   - PIE TIME 1, 2
   - format string series (0–3)
   - buffer overflow series (0–3)
   - heap series (0–3)
   - Local Target
   - function overwrite
   - Unsubscriptions Are Free

📘 より深く学びたい方は [guyinatuxedo.github.io](https://guyinatuxedo.github.io/index.html) もおすすめです。

---

### ☁️ ボーナス：Cloud Security

1. [flaws.cloud](http://flaws.cloud/) にアクセス
2. AWSに特化した脆弱性を体験してみよう

---

**✅ このオプションでは、2つ以上のドメインを選択し、すべての課題を完了してください。**  
それ以上のドメインに挑戦するのも大歓迎です！

---

## 🔵 オプション2：CISO（ブルーチーム）

企業がどのようにセキュリティを守っているのかを学びたい方へ。  
このオプションでは、**防御（ブルーチーム）** の基礎を体系的に学びます。

業界では、サイバーセキュリティは以下の4領域に分類されます。

---

### 🌐 ネットワークセキュリティ

なぜ最初にネットワークなのか？  
それは、**すべてのIT基盤がネットワークの上に成り立っているから**です。

1. [Let’s Defend - Network Fundamentals](https://app.letsdefend.io/training/lessons/network-fundamentals) にアクセス（アカウント作成）
2. **Network Fundamentals** コースを修了

📘 より深く学びたい方には、[この再生リスト](https://www.youtube.com/playlist?list=PLxbwE86jKRgMpuZuLBivzlM8s2Dk5lXBQ) がおすすめです。  
また、**CompTIA Network+** や **CCNA** などの資格もキャリアに役立ちます。

---

### 🛡️ SOC（セキュリティ運用センター）

企業のセキュリティを24時間体制で守る「SOC」の役割を学びます。

1. [Let’s Defend - SOC Fundamentals](https://app.letsdefend.io/training/lessons/soc-fundamentals) にアクセス
2. **SOC Fundamentals** コースを修了

このコースで、SOCで使われる基本用語やツールに触れることができます。

---

### 🧪 ブルーチーム演習（実践）

学んだ知識を活かして、以下のBlue Team Labs Onlineのチャレンジに挑戦しましょう。

1. [Blue Team Labs Online](https://blueteamlabs.online/home/challenges) にアクセス（アカウント作成）
2. 以下の課題を完了：

#### Easy
- The Report I, II（MITRE ATT&CKフレームワークを学ぼう）
- Follina
- ThePackage（Google Dorkingを学ぼう）
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

## 📥 提出方法

- 各チャレンジについて、**Write-up（レポート）** を作成し、このリポジトリに追加してください。
- Write-upには以下を含めてください：
  - フラグ（取得できた場合）
  - どのように解いたかの手順
  - （解けなかった場合）試行錯誤した内容

**例：`Need For Speed.md`**
```
Flag: picoctf{flag}

Solution: ...
```

- コース修了の場合は、**修了証またはバッジのスクリーンショット** を添付してください。

---

## 🗓️ 締め切り

**2025年7月20日（日） 23:59**

---

わからないことや困ったことがあれば、気軽にDMやグループで質問してください。  
このタスクを通して、皆さんがサイバーセキュリティの世界に一歩踏み出すきっかけになれば嬉しいです。

**楽しい夏休みにしましょう！**

**Sujai**  
_Cyber Security Head_
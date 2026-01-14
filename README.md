# Authentication Brute-Force & Username Enumeration Lab

**Platform:** PortSwigger Web Security Academy  
**Category:** Authentication Vulnerabilities 
- Username enumeration via different responses.
- Username enumertion via subtly different responses.
- Username enumeration via response timing.


---

## 🔍 Objective
To understand how authentication mechanisms can be abused using brute-force techniques and how usernames can be enumerated using response behavior.

---

## 🛠️ Tools Used
- Burp Suite
- Web Browser
- PortSwigger Lab Environment

---

## 🧪 Methodology
1. Intercepted the login request using Burp Suite.
2. Sent the request to Burp Intruder.
3. Used payloads to test multiple usernames/passwords.
4. Observed response messages, status codes, and response times.
5. Identified valid username based on different response behavior.
6. Completed the lab by bypassing authentication protection.
7. Worked with Burp Repeater.
8. Used Grep - Extract.

---

## 📌 Key Learnings
- Authentication responses may leak information.
- Response timing and messages can reveal valid usernames.
- Burp Intruder is powerful for testing login mechanisms.

---

## ⚠️ Disclaimer
This lab was performed in a legal, controlled learning environment provided by PortSwigger.

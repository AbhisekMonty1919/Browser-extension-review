# Browser-extension-review

# 🧼 Task 7: Detecting and Removing Suspicious Browser Extensions

## 🎯 Objective
Review all installed browser extensions and remove those which are suspicious, unnecessary, or privacy-invasive.

---

## 🧰 Tool Used
- **Google Chrome** (`chrome://extensions`)

---

## 🖼️ Before Screenshot
![Extensions Before](./Screenshot%202025-07-03%20213507.png)

---

## 🔍 Observations

Following extensions were found installed:

1. **Boxel Rebound**  
   - A game-based extension. Not harmful, but unnecessary for security-focused browsing.

2. **Google Docs Offline**  
   - Legit extension by Google, no issue.

3. **ManyContacts Chrome Extension**  
   - Used for WhatsApp CRM. If not used regularly, may expose contact scraping risk. **Removed.**

4. **McAfee WebAdvisor**  
   - Often bundled with antivirus installs. Not harmful, but tends to inject scripts. **Disabled.**

---

## ✅ Actions Taken

- 🔥 Removed `ManyContacts Chrome Extension` as it had unnecessary permissions and access to webpage data.
- 🔒 Disabled `McAfee WebAdvisor` for performance and to reduce webpage script injections.
- 🎮 Kept `Boxel Rebound` temporarily, though flagged it as **non-essential**.

---

## 🧠 What I Learned

- Many extensions can read browser data, track user activity, or inject ads without your knowledge.
- Not all extensions are malicious — but **if it’s unnecessary, remove it**.
- Regular auditing of browser extensions helps in reducing attack surface and improving browser performance.

---

## 💡 Security Tip

> ✨ **Always install extensions from trusted sources** and double-check their permissions.  
> Use tools like `CRXcavator` or `Extension Monitor` to scan extensions before installing.

---

## 📁 Files Included

- `README.md`
- `Screenshot 2025-07-03 213507.png`

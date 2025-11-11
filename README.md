# WhatsApp Pair Code Server

Node.js + Baileys library භාවිත කරමින් WhatsApp Pair Code නිර්මාණය කිරීමට සරල Web UI + API Server එකකි.

---

## 👨‍💻 Developer Info
**Dev:** MR DILA OFC  
**WhatsApp Contact:** +94777839446  
**Base Library Credit:** @whiskeysockets/baileys

---

## ⚠️ සහතිකයක් (IMPORTANT NOTICE)
මෙම සර්වර්ය භාවිත කරන්නේ **ඔබගේම WhatsApp ගිණුම** connect කිරීම සඳහා පමණි.  
 වෙනත් අයගේ WhatsApp ගිණුම් වලට **අවසර නැතිව** connect වීම **නීති විරෝධී** වේ.

> Session / Credentials කිසිවිටෙකත් **තෙවන පාර්ශවයට upload / share** නොකරන්න.

---

## 📦 Required Software
- Node.js 18+
- npm (default comes with Node)

---

## 📁 Project Structure
---

## 🛠 Installation & Run
# Clone or Download project
cd your-folder-name

# Install dependencies
npm install

# Start server
node index.js

🔌 API Endpoint

GET Pair Code

/pair?number=9471XXXXXXXX

Example:

http://localhost:8000/pair?number=94771234567

Success Response

{ "code": "ABCD-EFG" }

Failure Response

{ "code": "Service Unavailable" }

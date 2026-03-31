# 💰 ACC INWESTYCJA

## 👤 User
**Aleksander Markowicz**

## 📈 Profit
**500,000 zł**

---

## 🚀 Overview
This project represents a simple investment dashboard UI showing user profit and a withdrawal option.  
It is designed with a clean, modern interface and focuses on clarity and user interaction.

---

## 🖥️ Preview

![App Screenshot](screenshot.png)

---

## ✨ Features
- Display user investment details
- Show total profit in Polish złoty (zł)
- Clean and minimal UI design
- Call-to-action button for withdrawal

---

## ▶️ Usage
Click the **"Przejdź do wypłaty"** button to proceed with withdrawal.

---

## 🛠️ Tech Stack
- HTML
- CSS
- JavaScript

---

## 📌 Notes
- UI language: Polish
- Currency: PLN (zł)

---

## 📄 License
This project is for educational/demo purposes.


# 💸 Wypłata - ACC INWESTYCJA

## 🧾 Withdrawal Form

This page allows the user to enter withdrawal details after clicking **"Przejdź do wypłaty"**.

---

## 🖥️ UI Preview

![Withdrawal Page](screenshot-withdrawal.png)

---

## ✨ Features
- Input field for account number (empty by default)
- Input field for user name (empty by default)
- Bank selection dropdown (top Polish banks)
- Display withdrawal amount
- Action buttons: **Wypłać** and **Powrót**

---

## 🏦 Supported Banks (Poland)

When the bank field is clicked, show:

- PKO Bank Polski  
- mBank  
- ING Bank Śląski  
- Santander Bank Polska  
- Alior Bank  

---

## 📥 Form Fields

| Field            | Description                     |
|------------------|---------------------------------|
| Account Number   | User enters bank account number |
| Full Name        | User enters full name           |
| Bank             | Select from dropdown            |
| Amount           | 500,000 zł (fixed)              |

---

## ▶️ Example HTML

```html id="form1"
<input type="text" placeholder="Numer konta" />

<input type="text" placeholder="Imię i nazwisko" />

<select>
  <option value="">Wybierz bank</option>
  <option>PKO Bank Polski</option>
  <option>mBank</option>
  <option>ING Bank Śląski</option>
  <option>Santander Bank Polska</option>
  <option>Alior Bank</option>
</select>

<input type="text" value="500 000 zł" disabled />

<button>Wypłać</button>
<button>Powrót</button>

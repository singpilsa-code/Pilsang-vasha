# Pilsang-vasha
I am pilsang vasha bot created by intelligent pilsang
---

📄 *README.md*

```markdown
🤖 Pilsang Vasha Bot

A powerful, AI-integrated WhatsApp bot built with Node.js and Baileys. Designed to handle group moderation, fun commands, downloads, football info, AI chatting, and more!

---

🚀 Features

- 📂 *Menu-based commands*
- 🔓 Public & Private mode toggle
- 🧠 AI chat via OpenAI
- 🏓 Ping check
- 🧾 Group, owner, fun, settings, download, games, and more (easily extendable)
- 💬 Command handler system
- ✅ Works with WhatsApp via Baileys (QR scan auth)

---

📁 Folder Structure

```
pilsang-vasha-bot/
├── commands/          # All bot command files
├── session/           # Baileys auth session (auto-generated)
├── config.js          # Bot settings and OpenAI key
├── index.js           # Main bot entry
├── package.json       # Dependencies & scripts
├── .gitignore
```

---

⚙️ Setup Instructions

1. Install Dependencies
```bash
npm install
```

2. Set Config
Edit `config.js`:
```js
module.exports = {
  owner: ['2348165226793'],
  botName: 'Pilsang Vasha Bot',
  sessionFolder: 'session',
  publicMode: true,
  openaiKey: 'your-openai-key-here'
};
```

> ⚠️ *Do NOT commit `config.js` to GitHub.* It contains private credentials.

3. Run t
node index.js
```
Scan the QR code with your WhatsApp and you're online!

---

🌐 Deploy to Render (24/7)

1. Push code to GitHub
2. Create a free Render account
3. Connect your GitHub repo and set:
   - *Build command:* `npm install`
   - *Start command:* `npm start`
4. Add environment variables:
   - `openaiKey`
   - `owner`
   - `publicMode`

---

✨ Example Commands

```
!menu        → Show command categories
!ping        → Check if bot is alive
!ai [query]  → Ask AI anything
!public      → Make bot public (owner only)
!private     → Make bot private (owner only)
```

---

🔐 Credits

Created with ❤️ by *Pilsang*

```                                   

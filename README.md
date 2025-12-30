# Attendance Tracker Pro

A premium, intelligent web-based tool for tracking and analyzing WhatsApp attendance logs.

## 🚀 Live Demo
[Attendance Tracker Pro - Live on GitHub Pages](https://muhammad-zohaib-bawani.github.io/Attendance-Report/)

## ✨ Key Features

### 🧠 Smart Sequence Logic (Flipping)
The tool uses a state-machine approach to handle varied message patterns.
- If a message doesn't contain strict keywords (like just typing "hello"), the tool automatically **toggles** your status based on the previous message (`IN` -> `OUT` -> `IN`).
- Supports **Emojis** (🟢 for Check-in, 🔴 for Check-out) for direct state triggers.

### 📊 Performance Analytics
Calculates deep metrics based on your custom targets:
- **Required Hours**: Based on your defined "Total Working Days" and "Daily Target".
- **Worked Hours**: Actual sum of all active sessions.
- **Overtime Tracker**: Automatically calculates surplus hours.
- **Average Daily Session**: Shows your mean working time per day.

### ✏️ Editable Data Ledger
- **Manual Overrides**: Directly edit Entry or Exit times in the table to correct errors in the log.
- **Real-time Sync**: Durations and overall stats update instantly as you type.

### 💬 Original Message Context
- A dedicated **Context** column shows exactly what you sent for each check-in, providing transparency and verification.

### 📥 Excel Report Export
- Generate a professional Excel report with one click using the **SheetJS** integration.
- Includes Date, Entry/Exit times, Durations, and the original message context.

## 🛠️ How to Use
1.  **Export Chat**: Open your WhatsApp attendance group, go to `More > Export Chat > Without Media`.
2.  **Upload**: Upload the `.txt` file into the Attendance Tracker.
3.  **Filter**: Enter your name exactly as it appears in the chat.
4.  **Analyze**: View your stats, edit times if needed, and export your monthly report!

## 🔐 Privacy
This tool is **100% Client-Side**. Your data never leaves your computer; it is processed entirely within your browser for maximum privacy and security.

---
*Developed for MicroSysX Intelligence Ledger.*

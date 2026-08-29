# Banjonborno — Interactive Bengali Consonant Classifier & MCQ Test

**Banjonborno** is a modern, fully bilingual (English/বাংলা) web application designed to help learners master the 25 **Touch Consonants (স্পর্শ বর্ণ)** of the Bengali alphabet. Built with pure HTML, CSS, and JavaScript, it presents the traditional 5×5 phonetic classification grid—organized by *Place of Articulation*, *Voicing*, and *Aspiration/Nasality*—in a sleek, glassmorphic interface that works beautifully on both desktop and mobile.

---

## ✨ Key Features

### 📊 Interactive Study Table
The chart displays all 25 consonants with their Bangla and English phonetic labels. On mobile, column headers automatically stack into two lines to ensure the entire table fits without horizontal scrolling.

### 🌐 Language Toggle
Instantly switch the entire UI (including table headers, quiz text, results, and navigation) between **English** and **Bangla**. The table shows only the selected language—no duplication.

### 🎯 Dynamic MCQ Quiz
Click **"Take Test"** and the app generates one question per consonant (25 total) in random order. Each question presents three phonetic tags (e.g., `ঘোষ · অল্পপ্রাণ · দন্ত`) and asks you to choose the correct letter from four shuffled options.

### ⚡ Real‑time Feedback & Scoring
Answers are immediately marked green (correct) or red (incorrect), with the right answer always revealed. Your score updates live.

### ⏱️ Stopwatch
A timer tracks your total test time, displayed alongside your score.

### 📋 End‑Test & Review
You can stop the test anytime to see a detailed summary: accuracy, correct/wrong counts, time taken, and a question‑by‑question review showing your answer vs. the correct one.

### 📱 Responsive Design
The layout adapts to any screen size. On mobile, the sidebar collapses into a top bar, option buttons resize, and the table compresses gracefully without losing readability.

### 💎 Neon/Glass Aesthetic
Soft ambient glows, glass panels, and a dark background create an engaging, distraction‑free learning environment.

---

## 🎓 Use Case

Ideal for **students**, **teachers**, or **anyone learning Bengali phonetics**. The quiz's dynamic nature makes it perfect for self‑assessment and repeated practice.

---

## 🛠️ Tech Stack

- **HTML5** (semantic markup)
- **CSS3** (custom properties, grid, flexbox, media queries)
- **JavaScript** (vanilla, no libraries or frameworks)

The app is lightweight, fast, and easy to deploy on any static host (GitHub Pages, Netlify, etc.).

---

## 🚀 How to Run

Simply open the `index.html` file in any modern browser—no build step required.

```bash
git clone https://github.com/yourusername/banjonborno.git
cd banjonborno
open index.html

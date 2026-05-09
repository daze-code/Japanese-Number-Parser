# JP-EN Number Parser (数字変換機)

A clean, responsive, and locally-run browser tool designed to instantly bridge the gap between **Japanese**, **Indian**, and **Western** numbering systems and currencies.

### 🌉 The Problem: The "Cultural Number" Barrier
Translating numbers across borders isn't just about math; it's about **linguistic structure**. Western numbers group as (Millions, Billions), Japanese numbers group as (Man<万>, Oku<億>), and Indian numbers group as (Lakhs, Crores). 

When you hear that the budget for a Japanese project is **"2億5千万"**, traditional calculators and Google just spit out a wall of commas like `250,000,000`, forcing you to mentally count the zeros to figure out what that actually means. Meanwhile, AI chatbots frequently hallucinate decimal places when converting complex cultural math.

### 🚀 The Solution
This tool is built specifically for **cognitive offloading and 100% deterministic accuracy.** * **Native Formatting:** It doesn't just do the math; it translates the *language* of the number. It instantly tells you that **2億5千万** is exactly **250 Million** or **25 Crore**.
* **Context-Aware Inputs:** You don't have to type `250000000`. You can just type `2.5` and click the `億` (Oku) pill. 
* **Zero Hallucinations:** Because it runs on hardcoded, localized math rather than AI prediction, you never have to second-guess the output. 

## ✨ Core Features

* **Number Mode:** Quickly translate pure figures (like "6700万 visitors") natively between Western, Indian, and Japanese formats.
* **Currency Mode:** Convert live exchange rates between JPY, USD, and INR natively (powered by ExchangeRate-API). Output values are cleanly rounded to zero decimal places for rapid reading.
* **Native Breakdowns:** Expand any output card to see exactly how that massive number breaks down into native counting groups (e.g., seeing exactly how many *Lakhs* or *Man* are in a converted value).
* **Persistent Data:** Switch seamlessly between "Direct Input" and Unit Multipliers without losing the numbers you've actively typed.

## 💻 How to Use

No installation required! This is a completely static, client-side web application.

1. Download or clone this repository.
2. Double click `index.html` to open it in your browser.

### 💡 Quick Tips
* **Copy Quickly:** Click the copy icon `📋` next to any result to instantly copy the exact, clean value to your clipboard.
* **Offline Mode:** If you lose your internet connection, the tool safely disables the exchange rate API but continues to allow you to use the pure **Number Mode** and visual breakdowns natively on your device.

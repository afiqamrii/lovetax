# 🧾 LoveTax
**Itemized proof of your affection.**

LoveTax is a viral web toy that generates a realistic, "aesthetic" supermarket receipt based on a user's relationship data. Users input their names, key dates, and "theme songs," and the app renders a downloadable PNG perfect for Instagram Stories or TikTok.

### 🌟 Features
* **Live Preview:** See the receipt generate in real-time as you type.
* **Spotify Search:** Add "your songs" as items on the receipt with their duration as the price.
* **One-Click Export:** Uses `html2canvas` to instantly download the high-res receipt image.
* **Viral Mechanics:** Highly shareable visual content designed for social media.

### 🛠 Tech Stack
* **Frontend:** Next.js 14 + React
* **Styling:** Tailwind CSS (Custom receipt fonts & jagged paper CSS masks)
* **Image Gen:** html2canvas / Satori
* **Data:** Local State (No database required)

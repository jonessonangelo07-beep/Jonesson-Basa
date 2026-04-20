# 🏴‍☠️ One Piece Monopoly

A custom, web-based Monopoly game inspired by the epic journey of the Straw Hat Pirates. This project maps the classic Monopoly mechanics onto the Grand Line, challenging players to conquer islands, amass Beli (฿), and race to Laugh Tale. 

Developed as a Midterm Project for Computer Engineering.

![One Piece Monopoly](https://one-piece-monopoly33.vercel.app/R.png) 
*Live Demo: [one-piece-monopoly33.vercel.app](https://one-piece-monopoly33.vercel.app)*

---

## 🌊 The Theme

Instead of buying standard real estate, players navigate through iconic *One Piece* locations—starting from the East Blue and sailing all the way to the New World. 

* **GO Space:** Replaced by **"SET SAIL"** (฿0).
* **Properties:** Islands and story arcs (e.g., Foosha Village, Baratie, Alabasta, Wano, up to Laugh Tale).
* **Railroads:** Replaced by **Vessels** (e.g., Sea Train, Thousand Sunny, Oro Jackson) - ฿200 each.
* **Utilities:** Replaced by Communication/Tech hubs (e.g., Den Den Mushi) - ฿150 each.
* **Jail:** Replaced by **"Captured by Marines"** (Impel Down).
* **Chance/Community Chest:** Replaced by **Bounty Posters** and **Log Pose** cards.

---

## 📜 Custom Rules & Mechanics

The game closely follows classic Monopoly rules but is tailored to fit the pirate economy:

1.  **Starting Bounty (Money):** Every pirate starts their journey with **฿1,500**.
2.  **Currency:** All transactions are scaled and formatted using the official *One Piece* currency: **Beli (฿)**.
3.  **Property Pricing Scaling:**
    * Early Islands (East Blue): ฿60 - ฿100 (e.g., Foosha/Syrup, Baratie/Arlong)
    * Mid-Route (Grand Line): ฿140 - ฿260 (e.g., Drum/Alabasta, Punk Hazard/Dressrosa)
    * Endgame (New World): ฿300 - ฿400 (e.g., Wano, Laugh Tale)
4.  **Multiplayer:** The game supports local/hosted multiplayer. *(Note: If board values or starting money are updated, a New Hosted Game must be initialized to sync the latest data).*

---

## 🛠️ Tech Stack

This application is built with modern web technologies to ensure a smooth, interactive experience:
* **Frontend:** React, TypeScript
* **Build Tool:** Vite
* **Styling:** CSS / Custom UI mapping for the board
* **Backend/Database:** Firebase (Firestore/Auth) for game state and multiplayer syncing
* **Deployment:** Vercel

---

## 🚀 Local Setup Instructions

If you want to run this project locally on your machine, follow these steps:

### Prerequisites
Make sure you have [Node.js](https://nodejs.org/) installed on your computer.

### Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/jonessonangelo07-beep/-ONE-PIECE-MONOPOLY.git](https://github.com/jonessonangelo07-beep/-ONE-PIECE-MONOPOLY.git)
   cd -ONE-PIECE-MONOPOLY
Install dependencies:

Bash
npm install
Environment Variables:

Duplicate the .env.example file and rename it to .env.

Fill in your specific Firebase configuration keys to connect to your database.

Run the development server:

Bash
npm run dev
Open your browser:
Navigate to http://localhost:5173 (or the port Vite provides) to start playing!

⚓ Deployment
Changes pushed to the main branch are automatically deployed via Vercel.
Static assets (like the Straw Hat favicon and board images) are served directly from the public directory.

“I'm gonna be the King of the Pirates!” - Monkey D. Luffy

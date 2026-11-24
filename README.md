# EcoNode — PlastiCraft Kiosk

> **Turn Trash into 3D Merch & Rewards**  
> *UTM Global Sustainability Challenge (GSC) 2026*  
> Developed by **Team EcoNode**, Universiti Teknologi Malaysia (UTM)

---

## 📌 Overview

**PlastiCraft Kiosk** is an interactive, gamified circular economy touchscreen kiosk designed for smart campus environments. It bridges waste segregation with tangible incentives by empowering students and campus staff to convert recyclable PET bottles and Used Cooking Oil (UCO) into points, campus sponsor perks, and on-demand 3D-printed merchandise.

---

## 🌟 Key Features & Prototype Flows

### 1. 📱 Attract & UTM Smart App QR Pairing
- Portrait kiosk interface (`max-w-md`) with simulated solar, IoT connectivity, and battery status.
- Realistic smartphone pairing flow: scan via **UTM Smart App** with animated pairing detection, or bypass using one-click instant demo login.

### 2. 🤖 AI Bottle Cleanliness Scanner & Multi-Bottle Logger
- Simulated computer vision cleanliness check rejecting contaminated or liquid-filled bottles.
- Multi-bottle streak counter with real-time gram weight tracking (`+15g` & `+150 PTS` per clean bottle) and animated radial progress gauge.
- Generates a claim QR code or allows direct balance claiming into the user's account.

### 3. 📊 Gamified Eco-Account Dashboard
- **Dual Progression System:** Live tracking of XP level-ups (*Circular Guardian*) alongside the `1,000g` 3D Print Milestone.
- **Purpose-Driven Impact Routing:** Direct recycled PET streams toward:
  - *Apparel* (Recycled Polyester)
  - *Home Goods*
  - *UCO / SAF Biofuel* (Sustainable Aviation Fuel)
- **Action Hub:** Quick access to 3D print ordering, partner vouchers, UCO valve logging, and bottle drop.

### 4. 🛢️ Used Cooking Oil (UCO) Intake Valve
- Animated intake valve simulation logging `+500ml` oil deposits (+200 PTS).
- Displays direct environmental metrics: **~1.1 kg CO₂e saved** per deposit by routing feedstock to Sustainable Aviation Fuel (SAF) production.

### 5. 🖨️ Asynchronous 3D Print Customizer & Live Queue Drawer
- Redeem pre-built designs (*UTM Keychain*, *Phone Stand*, *Cable Organizer*) or custom `.STL` / engravings for `1,000 PTS`.
- Asynchronous pickup notification via UTM Smart App with designated collection at **Arked Meranti Kiosk #01**.
- Interactive, slide-up **Active Print Queue Drawer** monitoring real-time job progress percentages and estimated completion times.

### 6. 🎟️ Purpose-Driven Sponsor Vouchers
- Redeem earned eco-points for partner rewards:
  - **15% Off Recycled Polyester Sportswear** (*EcoThreads MY*)
  - **Free Green Shuttle Ride** (*UTM Campus Transit*)
  - **RM5 Eco-Café Voucher** (*Arked Meranti Café*)
- Generates dynamic redemption barcodes with anti-double-spend status.

---

## 🚀 Quick Start / Running the Prototype

The interactive prototype is completely self-contained in a single lightweight file with zero build steps or local dependencies.

1. Clone or download the repository:
   ```bash
   git clone https://github.com/looiyuxiang/EcoNode.git
   cd EcoNode
   ```
2. Open [`index.html`](./index.html) in any modern desktop or mobile web browser:
   - Double-click `index.html`, or
   - Run a local server:
     ```bash
     python -m http.server 8000
     # Open http://localhost:8000 in your browser
     ```

> **Pitch Tip:** Use the red **`⟳ Reset Demo`** button in the top-right corner of the kiosk frame at any time during live presentations to reset all balances, queues, and states back to the baseline.

---

## 🛠️ Tech Stack

- **Markup & Layout:** HTML5, Semantic Elements
- **Styling:** [Tailwind CSS](https://tailwindcss.com/) (via CDN)
- **Logics & State:** Vanilla JavaScript (ES6+), persistent history stack, dynamic SVG charts & barcode generators
- **Assets:** 100% inline SVG icons (zero external image dependencies or broken asset paths)

---

## 👥 Team EcoNode

- **Lead Developer & Designer:** Looi Yu Xiang
- **Institution:** Universiti Teknologi Malaysia (UTM)
- **Initiative:** UTM Global Sustainability Challenge (GSC) 2026

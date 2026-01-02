# 🏥 FairDose Admin Panel

> A premium, responsive administrative dashboard for managing the FairDose medicine inventory system.

![FairDose Dashboard](https://via.placeholder.com/1000x500?text=FairDose+Admin+Dashboard+Screenshot)
*(Replace this link above with a real screenshot of your dashboard)*

## 🚀 Overview

The **FairDose Admin Panel** is the control center for the FairDose platform. It allows administrators to securely log in, manage the medicine database, track inventory statistics, and curate cost-effective alternatives for users.

Built with **React (Vite)** and **Material UI**, it features a modern "Glassmorphism" design, staggered animations, and a seamless connection to **Firebase** for real-time data management.

## ✨ Key Features

* **🔐 Secure Authentication:** Admin login system powered by Firebase Auth.
* **📊 Smart Dashboard:** Real-time statistics on total medicines, active categories, and alternatives.
* **💊 Inventory Management:**
    * Add new medicines with salt composition details.
    * Delete outdated entries.
    * Search and filter by category or salt name.
* **🔄 Advanced Alternatives Manager:**
    * Add substitute medicines with pricing and manufacturer details.
    * **"Best Value" Auto-Highlight:** Automatically tags the cheapest option.
    * **Stock Toggle:** Mark items as "Out of Stock" without deleting them.
    * Edit/Update details instantly.
* **🎨 Premium UI/UX:**
    * Responsive Sidebar & Topbar.
    * Staggered entrance animations.
    * Clean, modern typography and soft shadows.
* **🔗 Integrated Workflow:** Direct link to the live User Panel.

## 🛠️ Tech Stack

* **Frontend:** [React.js](https://reactjs.org/) + [Vite](https://vitejs.dev/)
* **UI Framework:** [Material UI (MUI)](https://mui.com/)
* **Backend / Database:** [Firebase](https://firebase.google.com/) (Firestore & Authentication)
* **Icons:** MUI Icons Material
* **Deployment:** Netlify / Vercel

---

## ⚙️ Installation & Setup

Follow these steps to run the project locally.

### 1. Clone the Repository
```bash
git clone [https://github.com/your-username/fairdose-admin.git](https://github.com/your-username/fairdose-admin.git)
cd fairdose-admin

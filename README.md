# LogisticsPro - Logistics Management System

**LogisticsPro** is a modern, responsive, feature-rich web application built for the **Free Web Development Internship Online Task (Supply Chain & Logistics Management)**[cite: 1]. It provides end-to-end frontend tooling to manage shipments, track vehicles, inspect warehouse depot inventory, and calculate real-time freight tariffs using JavaScript and modern CSS styling.

---

## 🚀 Key Features & Modules

* **Dashboard & Statistics**: Real-time metrics tracking total active shipments, vehicles in transit, active fleet size, and daily deliveries.
* **Goods & Services Catalog**: Detailed catalog displaying transport options (Express Parcel, Heavy Freight, Cold Chain) and vehicle specs with visual images[cite: 1, 4].
* **Freight Cost Calculator**: Interactive tariff calculator allowing users to visually select vehicle types, cargo surcharge categories (General, Fragile, Cold Chain), and input route distances[cite: 1, 4].
* **Shipment Management**: Full CRUD capabilities to create, monitor, and delete shipment logs complete with driver contact numbers and real-time status badges (`Pending`, `In Transit`, `Delivered`, `Cancelled`)[cite: 1, 2, 4].
* **Fleet Management**: Monitor registered transport units, plate numbers, vehicle categories, load capacities, and active availability status[cite: 1, 4].
* **Warehouse Management**: Track depot locations, storage capacities, and current stock inventory levels[cite: 1, 4].
* **Order Management**: View customer order logs and dispatch schedules[cite: 1, 4].
* **Real-Time Tracking System**: Instant tracking lookup tool to verify package progress and driver contact info using tracking numbers (e.g., `LOG-2026-001`)[cite: 1, 4, 5].
* **Reports & Analytics**: Export-ready performance metrics and delivery turnaround logs[cite: 1, 4].
* **User Authentication**: Simulated secure login and user profile switching[cite: 1, 4].

---

## 🛠️ Technologies Used

* **HTML5**: Semantic document structuring and layout definition[cite: 2, 4].
* **CSS3**: Custom styling utilizing CSS variables, responsive flexbox/grid layouts, clean color palettes (`#0EA5E9`, `#FFFFFF`, `#F4F9FD`), and smooth transitions[cite: 2, 4].
* **JavaScript (ES6+)**: Interactive DOM manipulation, local storage data persistence, state handling, and dynamic table rendering[cite: 2, 4].
* **FontAwesome**: Modern UI iconography[cite: 4].

---

## 💾 Data Management & Storage Approach

This application is built entirely as a **frontend-only project (No Backend/Database required)**[cite: 2, 4]:
* **JavaScript Arrays & Objects**: Initial sample datasets for shipments, fleet vehicles, warehouses, and customer orders are stored directly in memory[cite: 2, 4, 5].
* **Browser `localStorage`**: User-created shipment logs and updates persist across browser reloads using client-side storage[cite: 4].

---

## 📂 Quick Start Guide

1. Clone or download the repository containing the single-file source code (`index.html`).
2. Open `index.html` in any modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari).
3. Interact with the sidebar menu to navigate across modules, test the cost calculator, create shipment records, and run tracking lookups[cite: 2, 4].

---

## 📅 Project Timeline & Development Workflow

* **Day 1**: Research logistics workflows, system layout sketches, and data structure modeling[cite: 3].
* **Day 2**: Construct HTML5 semantic markup and sidebar/top-bar navigation structure[cite: 3, 4].
* **Day 3**: Apply CSS styling, custom color schemes, typography, and card hover animations[cite: 3, 4].
* **Day 4**: Implement responsive design layouts and mobile menu toggle functionality[cite: 3, 4].
* **Day 5**: Develop JavaScript core logic, CRUD operations, search/filters, and tracking tools[cite: 3, 4].
* **Day 6**: Execute cross-browser testing, code cleanup, and bonus feature integration[cite: 3].
* **Day 7**: Finalize documentation (`README.md`), project reports, screenshots, and deployment[cite: 3].

# Agro Trade Transparency System

A blockchain-based digital agricultural trading platform that connects farmers, traders, buyers, consumers, and government authorities — bringing transparency, fair pricing, and accountability to Bangladesh's agricultural supply chain.

## 🌾 Background

Nearly 40% of Bangladesh's workforce is employed in agriculture, yet farmers consistently receive 30–40% below fair market value for their produce while consumers in cities pay inflated prices. Middlemen dominate the market, cash transactions leave no paper trail, and there is no centralized platform for real-time price discovery.

This system addresses those structural failures through digitization, blockchain-based transaction recording, and direct stakeholder connectivity.

## ✨ Features

- **User Management** — Secure registration and role-based access (Farmer, Trader, Buyer, Consumer, Delivery Agent, Government Officer, Admin)
- **Market Price Transparency** — Real-time and historical agricultural price display
- **Digital Transactions** — All trades recorded with unique IDs and blockchain immutability
- **Payment Integration** — Mobile wallet support (bKash, Nagad) with direct farmer payout
- **Supply Chain Tracking** — Track products from farm to consumer via traceability IDs
- **Government Dashboard** — Monitoring of prices, transactions, compliance, and subsidy distribution
- **Bengali Language Support** — Mobile-first UI with full Bangla interface for rural accessibility
- **Subsidy Tracking** — Transparent government aid distribution with blockchain verification

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Process Model | Agile Scrum |
| Blockchain | Blockchain transaction recording & traceability |
| Payment Gateway | bKash, Nagad APIs |
| UI Design | Figma (mobile-first) |
| Version Control | Git / GitHub |
| Project Management | Trello |

## 👥 Actors & Roles

| Actor | Responsibilities |
|---|---|
| **Farmer** | Submit products, view market prices, receive payments, track traceability |
| **Trader** | List products, initiate trade transactions, monitor prices |
| **Consumer/Buyer** | Browse products, scan QR codes, make digital purchases |
| **Delivery Agent** | Update and track delivery status |
| **Government Officer** | Monitor prices, view reports, detect price manipulation, verify subsidies |
| **Admin** | Manage users and system data |

## 🔩 System Modules

- **Authentication** — OTP-based registration and login
- **Profile Management** — Role-specific dashboards and editable profiles
- **Product Listing** — Farmers list products with auto market price suggestions
- **Transaction Recording** — Blockchain-backed digital IDs with timestamps
- **Payment Processing** — Mobile wallet integration with receipt generation
- **Stock Verification** — Real-time inventory tracking
- **Government Compliance** — Flagged transaction alerts, exportable reports

## 🧪 Testing

The project covers seven testing strategies:

1. **Unit Testing** — Individual module testing (auth, blockchain, payments, validation)
2. **Integration Testing** — Bottom-up approach starting from the blockchain module
3. **Regression Testing** — After each sprint, bug fix, or feature addition
4. **Smoke Testing** — Daily sanity checks on core flows
5. **Performance Testing** — Targets 1000 concurrent users, <3s load time, <2s blockchain confirmation
6. **Security Testing** — Auth bypass, encryption, OTP, and blockchain immutability checks
7. **Usability Testing** — Bengali clarity, icon-based navigation, low-end device support

12 test cases were executed covering delivery status, product purchase, market price monitoring, transaction recording, profile management, payment processing, government oversight, language support, product listing, product search, subsidy tracking, and stock verification — **all passing**.

## 🔮 Future Scope

- AI-based crop price prediction
- Expansion to additional agricultural sectors
- Advanced analytics and reporting dashboards
- Integration with logistics providers and additional payment gateways

## 📌 Project Info

| Field | Details |
|---|---|
| **Institution** | American International University-Bangladesh (AIUB) |
| **Department** | Computer Science & Engineering, FST |
| **Semester** | Fall 25-26 |
| **Course** | Software Engineering |

## 👨‍💻 Team — Group 10

| Name | Student ID |
|---|---|
| Md. Towhidul Islam | 23-55036-3 |
| Aditya Roy | 23-55077-3 |
| Md. Rabbi Ahmed | 23-55450-3 |
| Sajal Kumar Ghosh | 23-55419-3 |

# ⚙️ SAP Automation Projects

A collection of automation scripts and tools built to streamline and simplify **SAP business operations** — including outbound delivery, invoice processing, production automation, material reservation, and scheduling agreements.

---

## 🧭 Overview

These projects automate repetitive SAP GUI and backend processes using Python scripting and SAP APIs, reducing manual work and improving operational efficiency.

---

## 📂 Repository Structure

SAP-Automation-Projects/
├── Outbound-Delivery-and-Invoice-Process-Automate/
│ ├── outbound_invoice_automation.py
│ ├── requirements.txt
│ └── README.md
│
├── SAP-Production-Automation-and-Material-Reservation/
│ ├── production_material_reservation.py
│ ├── requirements.txt
│ └── README.md
│
├── Scheduling-Agreement-Automation-in-SAP/
│ ├── scheduling_agreement.py
│ ├── requirements.txt
│ └── README.md
│
└── .gitignore


---

## 🚀 Common Features

✅ Automates SAP transactions and repetitive tasks  
✅ Connects to SAP GUI via COM interface (PyWin32)  
✅ Reduces human error in business-critical operations  
✅ Logs activities for transparency and auditing  
✅ Modular and easy-to-customize project structure  

---

## 🧰 Tech Stack

| Layer | Technologies |
|--------|----------------|
| **Language** | Python |
| **Automation** | SAP GUI Scripting API, PyWin32 |
| **Environment** | Windows (SAP GUI Installed) |
| **Integration** | SAP RFC / BAPI (where applicable) |
| **Web Layer (optional)** | Flask API for remote trigger |

---

## 🛠 Prerequisites

Before running any of the automation scripts:

- 🖥️ Windows PC with **SAP GUI** installed  
- 🔑 SAP credentials with appropriate access  
- 🐍 **Python 3.8+**  
- 📦 Required Python modules installed  

Example:
```bash
pip install pywin32 python-dotenv flask


🧾 1. Outbound Delivery & Invoice Process Automation
📘 Description

Automates the creation of outbound deliveries and invoices in SAP using TCodes such as VL01N, VF01, etc.
It extracts sales orders, generates deliveries, and posts billing automatically.

🧠 Steps

Connects to SAP GUI

Reads order data from Excel or SAP tables

Executes TCodes for delivery and billing

Exports results (delivery no, invoice no) to CSV or log

🧰 Tools

Python (PyWin32)

SAP GUI Scripting

dotenv for environment variables

🏭 2. SAP Production Automation & Material Reservation
📘 Description

Automates production order creation, confirmation, and material reservation steps in SAP.
Useful for manufacturing workflows where manual TCode entry is repetitive.

🧠 Steps

Reads input data for planned orders

Creates material reservations automatically

Posts confirmations for completed orders

Logs operations and reservation numbers

🧰 Tools

Python (PyWin32)

SAP GUI Scripting

Excel/CSV integration for order inputs

📅 3. Scheduling Agreement Automation in SAP
📘 Description

Automates creation and update of scheduling agreements for vendors and materials (e.g., ME38, ME31L).

🧠 Steps

Connects to SAP GUI session

Opens Scheduling Agreement TCodes

Inputs vendor, material, and schedule data

Saves or updates the agreement

🧰 Tools

Python (PyWin32)

SAP GUI Scripting

dotenv / config files for credentials

# AGUTS 🚇
### Ahmedabad Gandhinagar Unified Transit System

---

🚌 A multi-modal public transit database system covering **Metro (GMRC)**, **BRTS – Janmarg**, **AMTS**, and **GSRTC** across Ahmedabad and Gandhinagar.

Each transit operator currently manages its data in isolation — AGUTS unifies all of it into a single, well-structured PostgreSQL database for commuters, operators, and administrators.

---

## 📚 Contents

| | Section | Description |
|---|---|---|
| 🔸 | ER Diagram | Full entity-relationship model with cardinality & participation constraints |
| 🔸 | Relational Schema | All relations with primary keys and foreign keys |
| 🔸 | Minimal FD Set | Cleaned functional dependencies for all relations |
| 🔸 | BCNF Proofs | Proof that every relation satisfies Boyce-Codd Normal Form |
| 🔸 | DDL Scripts | `CREATE TABLE` statements with all constraints (PostgreSQL) |
| 🔸 | INSERT Scripts | Sample data to populate the database |
| 🔸 | SQL Queries | Retrieval queries for commuters, passengers, and admins |

---

## 📌 Key Functional Areas

✅ **Network & Infrastructure** — Routes, stops, Metro lines, interchange points, GPS coordinates  
✅ **Schedules & Trips** — Timetables, trip assignments, stop-wise departure times  
✅ **Fleet Management** — Vehicles, fuel type, capacity, maintenance history  
✅ **Staff Management** — Drivers, conductors, motormen, shift assignments  
✅ **Passenger Management** — Registration, smart cards, concession categories, travel history  
✅ **Ticketing & Passes** — Tokens, daily/weekly/monthly passes, smart-card balance  
✅ **Fares & Revenue** — Zone/distance-based fare tables, inter-modal transfer fares  
✅ **Complaints & Feedback** — Complaint filing, resolution tracking, service ratings  

---

## 🛠️ Tech Stack

- **PostgreSQL** via pgAdmin 4
- **Draw.io** for ER Diagram and Relational Schema
- **SQL** — DDL, constraints, normalization
- **GitHub** for version control and collaboration

---

## 📁 File Reference

| File | Description |
|---|---|
| `Ahmedabad-Gandhinagar Unified Tra...` | Project Scenario Report |
| `AGUTS_ERD.drawio.pdf` | Entity-Relationship Diagram |
| `AGUTS_Relational_Schema.drawio.pdf` | Relational Schema |
| `AGUTS_Minimal_FD_Set.docx.pdf` | Minimal Functional Dependency Set |
| `AGUTS_BCNF_Proofs.docx.pdf` | BCNF Normalization Proofs |
| `AGUTS_DDL_Scripts.sql` | DDL Scripts (PostgreSQL) |
| `AGUTS_INSERT_SCRIPTS.txt` | Sample Data |

---

## 📝 How to Run

**1. Clone the repo:**
```bash
git clone https://github.com/neeti-gunsai/AGUTS.git
```

**2. Create the database and run DDL:**
```bash
psql -U postgres -d aguts -f AGUTS_DDL_Scripts.sql
```

**3. Load sample data:**
```bash
psql -U postgres -d aguts -f AGUTS_INSERT_SCRIPTS.txt
```

---

## 👥 Team — Lab Group 5

| ID | Name |
|---|---|
| 202401195 | Hari Sharma |
| 202401235 | Arjunsinh Vaghela |
| 202401417 | Tirth Ditani |
| 202401423 | Neeti Gunsai |
| 202401461 | Rudra Bhatt |


---

# **DG-AI-Checker**
AI-powered Dangerous Goods (DG) Classification Workflow  
Covers lithium batteries, aerosols, flammable liquids, corrosives, toxics, compressed gases, oxidizers, magnetic items, and Amazon FBA/Hazmat compliance checks.

---

## 🚀 **Overview**

DG-AI-Checker is an AI-only dangerous goods analysis system designed to classify products based on their hazardous material content using information extracted from Amazon product pages or any online listing.

This project solves common real-world logistics problems:

- DHL / FedEx / UPS dangerous goods warnings  
- Hidden batteries inside Amazon products  
- Undeclared aerosols, flammable liquids, or chemicals  
- Air cargo transport restrictions  
- Amazon FBA Hazmat uncertainty  
- Missing UN classifications  

This is a no-code AI workflow designed for real logistics operations.

---

## 🔍 **What the AI Can Detect**

### ✔ Class 9 — Lithium Batteries  
UN3480 / UN3481 / UN3090 / UN3091  
Wh / mAh extraction  
IATA Section II checks  

### ✔ Class 2 — Aerosols & Sprays  
Propane / butane / compressed gas  
UN1950  

### ✔ Class 3 — Flammable Liquids  
Perfume, paint, solvents  
UN1993  

### ✔ Class 8 — Corrosives  
Acids, alkalis, industrial cleaners  
UN1760  

### ✔ Class 6 — Toxic Substances  
Poisonous chemicals  
UN2810  

### ✔ Pressurized / Compressed Gas Items  

### ✔ Oxidizers (Class 5)  
Peroxides, pool shock  

### ✔ Magnetic Items (Class 9)  
Speakers, motors  

### ✔ All Other Relevant UN Hazard Categories  
Full IATA + DHL/FedEx/UPS acceptance logic  
Amazon FBA Hazmat decision tree  

---

## 🎯 **Purpose of the Project**

This project demonstrates:

- Dangerous Goods regulatory knowledge  
- Air cargo logistics understanding  
- Amazon FBA Hazmat experience  
- AI workflow design capability  
- Real shipping problem–solving skills  

It positions the author as an **AI-integrated Logistics Specialist**.

---

## ⚙️ **How the Workflow Works**

1. User provides an Amazon product link  
2. AI scans the listing for hazardous indicators  
3. AI identifies the UN hazard class  
4. AI checks IATA, DHL, UPS, FedEx rules  
5. AI generates a final DG compliance report  

---

## 📝 **Sample Input Prompt**

Analyze the following Amazon product page as a Dangerous Goods Compliance Inspector.

1. Does the product contain any hazardous contents?  
2. Which UN class does it fall under?  
3. Is it allowed for air transport (IATA)?  
4. Is it accepted by DHL / FedEx / UPS?  
5. Does Amazon FBA require Hazmat approval?  
6. What documents are needed (UN38.3, MSDS)?  
7. Final verdict: ALLOWED / RESTRICTED / PROHIBITED.

Amazon link:  
[PASTE LINK HERE]

---

## 📝 **Sample Output**

Product: Portable Butane Cooking Torch

Detected DG Content: YES  
Hazard Class: Class 2.1 – Flammable Gas  
UN Number: UN1950  
Air Transport (IATA): PROHIBITED – Flammable Gas  
DHL Express: Not Accepted  
FedEx Air: Not Accepted  
UPS Air: Not Accepted  
Amazon FBA: Hazmat — Requires approval  
Required Documents: SDS  
Risk Level: HIGH

---

## 📁 **Repository Structure**

DG-AI-Checker/
│
├── README.md
├── ai-prompt-engine.md
├── dg-regulations-overview.md
├── amazon-scan-guidelines.md
├── sample-reports/
│     ├── example_aerosol.json
│     ├── example_lithium.json

Tech Stack (AI-Only)

ChatGPT / LLM reasoning

Prompt engineering

Dangerous Goods knowledge

No coding required

📬 Author

Goker Ozaktay
Fort Lauderdale, FL
Logistics & Export Operations Specialist
AI Workflow Developer (Logistics)

This project is a Python-based analytical tool designed to manage damaged goods return processes (Reverse Logistics), calculate waste volumes, and perform automated risk assessments for supply chain operations.
Project Overview
In modern supply chains, managing returns efficiently is a core component of Green Logistics. This project focuses on handling 800 units of aerosol products (Deodorants - UN 1950), where 200 units have been identified as damaged. The tool ensures these are categorized correctly for recycling rather than being lost in general inventory.
Key Features
Inventory Segmentation: Distinguishes between "Salable Net Inventory" and "Damaged/Waste Stock."
Waste Volume Calculation: Automatically calculates the total volume (ml) of hazardous liquids/gases to be processed for recycling.
Automated Risk Assessment: Implements logic gates (If-Else) to trigger a Critical Risk Warning when damaged stock exceeds safety thresholds (100 units).
Sustainability Focus: Supports ESG (Environmental, Social, and Governance) goals by quantifying materials for aluminum recycling.
Technical Analysis Output
The script generates the following logistics metrics:
Product: Deodorant (150ml)
Net Inventory: 600 Units (Ready for Market)
Total Waste Volume: 30,000 ml
Safety Status: CRITICAL RISK (Requires Specialized Hazardous Waste Transport)
Technical Stack
Language: Python 3
Libraries: Pandas (for structured data reporting)
Concepts: Variable Mapping, Arithmetic Logic, Risk Thresholding.

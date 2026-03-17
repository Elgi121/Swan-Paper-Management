# Swan Paper Management

A management analysis framework covering the end-to-end operations of a hygienic paper manufacturing company, from raw material procurement and tissue machine performance to quality assurance, financial control, and workforce management.

---

## Overview

Hygienic paper production, covering toilet tissue, kitchen rolls, facial tissues, and industrial wipes, requires precise coordination across procurement, production, quality, maintenance, logistics, and finance. Swan Paper Management provides a structured analytical framework for every layer of the business, giving operators, supervisors, and executives a clear model for how each function should be organized, measured, and managed.

---

## Analysis Areas

**Production & Operations Management**  
Covers the full manufacturing cycle from stock preparation to finished goods transfer, including OEE tracking, 4-crew rotating shift structure, broke and reject classification, and traceability from parent reel to pallet.

**Supply Chain & Procurement**  
Covers sourcing, purchasing, and inventory management across fiber, chemicals, packaging, and energy, including supplier qualification, safety stock policy, ABC/XYZ classification, and purchase price variance analysis.

**Quality Control & Compliance**  
Covers in-line and finished goods quality management aligned with ISO 9001 and EN 12625, including SPC methodology, NCR/CAPA processes, batch traceability, and Certificate of Analysis requirements.

**Maintenance & Asset Management**  
Covers preventive and predictive maintenance management built around a TPM philosophy, including work order processes, spare parts policy, downtime classification, and annual shutdown planning.

**Financial & Cost Management**  
Covers product costing, variance analysis, capex evaluation, and working capital management, with a defined reporting cadence from daily cost flash to monthly P&L.

**Workforce & Shift Management**  
Covers scheduling, competency tracking, and HSE compliance for 24/7 rotating shift operations, including skills matrix management, incident classification, and succession planning.

**Sustainability & ESG**  
Covers energy, water, and carbon performance tracking integrated into core operational reporting, including FSC/PEFC compliance, emission factor methodology, and GRI-aligned ESG reporting.

---

## Stakeholders

| Stakeholder | Role |
|---|---|
| Board of Directors | Strategic oversight, capital allocation, executive accountability |
| Chief Executive Officer (CEO) | Overall strategy, investor relations, cross-functional alignment |
| Chief Operating Officer (COO) | Day-to-day manufacturing, quality, and logistics operations |
| Chief Financial Officer (CFO) | Budgeting, cost accounting, treasury, and financial reporting |
| Chief Supply Chain Officer (CSCO) | End-to-end supply chain, vendor relationships, and material flow |
| Plant Manager | On-site production performance, safety, and team management |
| Procurement Manager | Supplier management, purchasing workflows, and inventory control |
| QA Manager | Quality standards, compliance, and non-conformance management |
| Chief Engineer | Asset maintenance, capex projects, and energy management |
| HR & HSE Manager | Workforce planning, training, safety compliance, and labor relations |
| Sales & Marketing Director | Customer relationships, pricing strategy, and channel management |
| Finance Controller | Product costing, variance analysis, and management reporting |

---

## Analysis Goals

- **Uptime**: Reducing unplanned downtime through structured maintenance management  
- **Yield**: Improving fiber consumption and reject rates through quality monitoring and SPC  
- **Cost Visibility**: Establishing daily cost-per-tonne visibility across all variable cost categories  
- **Compliance**: Defining management requirements for ISO 9001, 14001, 45001, and 50001  
- **Organizational Clarity**: Establishing clear roles, reporting lines, and accountability  
- **Scalability**: Providing a framework applicable from single-site to multi-plant operations  

---

## User Cards / Functional Requirements

| Role | Key Functional Requirements | Notes / Metrics |
|------|----------------------------|----------------|
| Plant Operator | Operate tissue machines, record shift logs, report downtime & rejects | OEE, downtime logs, SPC entry |
| Shift Supervisor | Assign tasks, approve production reports, escalate issues | Shift performance KPIs, safety incidents |
| Maintenance Technician | Execute PM & CM tasks, update work orders, report spare parts usage | MTTR, MTBF, PM compliance |
| QA Operator | Perform in-line QC tests, sample finished goods, update SPC charts | Defects per million, NCR tracking |
| Procurement Analyst | Create purchase orders, track supplier performance, manage stock levels | Inventory turnover, price variance |
| Financial Analyst | Track cost-per-tonne, variance analysis, capex evaluation | Daily cost flash, monthly P&L |
| HR & HSE Coordinator | Track competencies, schedule training, log incidents | Training compliance %, incident rate |
| Logistics Coordinator | Manage warehouse movements, coordinate deliveries | On-time delivery %, stock accuracy |
| Sustainability Officer | Record energy, water, and carbon data | KPIs: energy/tonne, CO2 footprint |

---

## Organigram (Simplified Hierarchy)
Board of Directors
|
CEO
|

| | |
COO CFO CSCO
| | |
Plant Mgr Finance Ctrl Procurement Mgr
| | |
Shift Supv QA Mgr Warehouse / Logistics
| |
Operators QC Staff
|
Maintenance Techs


---

## BPMN – Core Manufacturing Process (Textual)

**Swimlanes & Flow:**

**Procurement:**  
- Create Purchase Request → Approve → Issue PO → Receive Material → Update Inventory  

**Production:**  
- Prepare Stock → Load Machine → Run Tissue Machine → Log OEE → Identify Rejects → Move Finished Goods  

**Quality:**  
- Sample In-line → Perform SPC → Approve/Reject Batch → Update Batch Traceability  

**Maintenance:**  
- Schedule PM → Execute PM → Log Downtime → Issue Corrective Work Order → Update Asset Record  

**Finance / Reporting:**  
- Collect Cost Data → Analyze Variances → Generate Daily Cost Flash → Monthly P&L  

**ESG / Sustainability:**  
- Record Energy & Water Usage → Calculate Emission Factors → Update ESG Reports  

**Decision Points:**  
- Reject Batch → Initiate NCR/CAPA  
- Downtime → Determine CM or PM action  
- Inventory Shortage → Alert Procurement  

---

## Key Metrics Explained

### 1. OEE (Overall Equipment Effectiveness)
Measures how effectively a production line or machine is being used, combining:  
- **Availability** – % of scheduled time machine is running  
- **Performance** – Speed vs. design speed  
- **Quality** – % of products meeting standards  

**Example:**  
Availability 90%, Performance 95%, Quality 98%  


### 2. Downtime Logs
Records every machine stoppage with:  
- Reason  
- Duration  
- Responsible team  

**Example Entry:**  
| Machine | Date | Start | End | Duration | Reason |
|---------|------|-------|-----|----------|--------|
| TM1     | 17-Mar-26 | 10:00 | 11:15 | 75 min | Roll changeover |

### 3. SPC Entry (Statistical Process Control)
Records and monitors quality metrics to detect deviations:  
- Variables: sheet weight, thickness, moisture, absorbency, tensile strength  
- Charts: control charts, trend plots  
- Entry: operator inputs data per batch or shift  

**Example:**  
Measured tissue thickness (10 samples): 0.115, 0.116, 0.114, 0.117 mm  
Plotted on a control chart to check if process is in control.

---

## Summary Table

| Term | Tracks | Helps |
|------|-------|------|
| OEE | Machine efficiency | Optimize uptime, speed, and quality |
| Downtime logs | When/why machines stop | Reduce unplanned downtime |
| SPC entry | Product/process quality | Detect deviations early, reduce rejects |

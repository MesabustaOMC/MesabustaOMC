# Hi, I'm Alejandro Mesa 👋

**Power BI developer · analytics engineer.** I build semantic models, write a lot of DAX, and spend my time making sure the numbers, and now Copilot's answers, are right.

I work on marketing analytics for automotive dealer networks: which dealers take part in co-op campaigns, through which channels (Email, Direct Mail, Digital Media), how participation trends, and where the gaps are. Lately I've focused on two things: **getting Copilot in Power BI to answer business questions correctly**, and **treating BI models like code**: versioned, reviewed and documented.

---

### 🔧 What I work on

- **Semantic modeling.** Star schemas, calculation groups, role-playing dates, fiscal calendars (April–March), and measures that hold up: scoped rates that can't pass 100%, grain-aware aggregations, selection-aware measures.
- **Power Query and Fabric dataflows.** Building dimensions in the dataflow when the source tables live on different servers and can't be joined in SQL.
- **Copilot in Power BI (Prep data for AI).** AI data schema, AI instructions, verified answers and a test bank of questions with expected-value DAX. Took a model from **1 of 4** baseline questions answered correctly to **approved for Copilot**, with 19 of 21 test questions passing.
- **BI as code.** Exporting models (TMDL) and reports (PBIR) from the Power BI service into Git through the Fabric REST APIs, one-way from the service, so every change shows up as a reviewable diff across dev, staging and production.
- **Performance.** Swapping a many-to-many channel bridge for a bitmask key (**716 ms → 63 ms** on the same visual); storing a text key as Int64 (dictionary **16 MB → 144 bytes**).
- **Knowledge management.** An Obsidian knowledge base run as an "LLM wiki" with Claude Code: verbatim sources, decisions, investigations, runbooks, a data dictionary generated from the live model, and a lint script that flags stale facts.

### 🧰 Toolbox

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logoColor=black)
![Microsoft Fabric](https://img.shields.io/badge/Microsoft_Fabric-117865?style=flat-square)
![DAX](https://img.shields.io/badge/DAX-2E6F40?style=flat-square)
![Power Query](https://img.shields.io/badge/Power_Query_(M)-217346?style=flat-square)
![TMDL / PBIR](https://img.shields.io/badge/TMDL_%2F_PBIR-5C2D91?style=flat-square)
![Copilot in Power BI](https://img.shields.io/badge/Copilot_in_Power_BI-0078D4?style=flat-square)
![Azure SQL](https://img.shields.io/badge/Azure_SQL_%2F_T--SQL-0078D4?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-012456?style=flat-square)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Obsidian](https://img.shields.io/badge/Obsidian-7C3AED?style=flat-square&logo=obsidian&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=claude&logoColor=white)

### 📂 Recent work

My client work lives in private repositories; in short:

| Project | What it is |
|---|---|
| **Dealer participation analytics** | Power BI semantic model and reports for dealer campaign participation, coupons and an online coupon program across two brands: about 1.5M fact rows, 87 measures, regional and campaign views |
| **Copilot readiness** | Prep data for AI end to end: answer rules, AI instructions, AI data schema, 19 verified answers, test rounds in the report pane and the app |
| **Models and reports as code** | 5 semantic models and 14 reports across dev, staging and production exported to Git as TMDL/PBIR, with an export script, runbooks and environment comparisons |
| **Knowledge base** | ~270-note Obsidian vault with a generated data dictionary, decision records, investigations, runbooks and LLM-wiki routines (ingest, query, lint) |

### 🧭 How I work

- **Change the live model; never overwrite it from a local copy.**
- **New logic goes in a new measure.** Validate it, then replace the old one.
- **Every number says where it came from and when.**
- **If it isn't written down, it didn't happen.** Decisions, investigations and runbooks live next to the code.

---

<sub>Open to conversations about Power BI, DAX, Copilot readiness and BI as code.</sub>

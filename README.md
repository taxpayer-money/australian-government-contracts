# ACT Government Contracts - Open Data

**Comprehensive dataset and insights on ACT Government contracts 2025**

This repository contains publicly available contract data from the ACT Government Tenders Portal, along with a detailed narrative analysis revealing spending patterns, supplier trends, and market opportunities.

---

## 📊 Dataset Overview

### 2025 Contracts
- **Total Contracts**: 1,296
- **Total Value**: $1.64 billion
- **Data Coverage**: 100%
- **File**: [`data/act_contracts_2025.csv`](data/act_contracts_2025.csv)

**Key Statistics**:
- **Unique Suppliers**: 772
- **Largest Contract**: $420M (SG Fleet - fleet management)
- **Median Contract**: $66,900
- **Average Contract**: $1.26M

---

## 📈 Narrative Report

**[Inside $1.64 Billion: The Story of ACT Government Spending in 2025](reports/report.md)**

A narrative-driven analysis revealing the hidden patterns in government procurement. No charts for the sake of charts. No generic insights. Just the story the data tells.

**Key Findings**:
- Top 2 suppliers control 43% of 2025 market with just 2 contracts
- October 2025 saw $604M in contracts - 10x quiet months
- Multi-year contracts average 13.9x more valuable than single-year
- 826 contracts (63.7%) under $200K - accessible to SMEs

---

## 📁 Data Schema

Each CSV contains the following fields:

| Field | Description |
|-------|-------------|
| `contract_number` | Unique contract identifier |
| `procurement_unique_id` | Procurement ID |
| `title` | Contract title/description |
| `directorate` | ACT Government directorate |
| `contract_type` | Type (Contract, Panel, etc.) |
| `slj_initiative` | Social/Local Jobs initiative (Yes/No) |
| `status` | Contract status |
| `execution_date` | Contract start date |
| `expiry_date` | Contract end date |
| `amount` | Contract value (AUD) |
| `suppliers` | Winning supplier(s) |
| `details_url` | Link to full contract details |
| `has_attachments` | Whether contract has attachments |

---

## 🎯 Use Cases

### For Suppliers
- Identify opportunity zones by contract size
- Analyze competitor success rates
- Track directorate spending patterns
- Find optimal contract value ranges

### For Researchers
- Government procurement analysis
- Market concentration studies
- Temporal spending patterns
- Supplier diversity research

### For Journalists
- Investigate large contracts
- Track spending anomalies
- Analyze supplier relationships
- Monitor social procurement initiatives

### For Policy Makers
- Benchmark procurement practices
- Assess SME participation
- Evaluate spending efficiency
- Track multi-year contract trends

---

## 📜 Data Source

**ACT Government Tenders Portal**: https://www.tenders.act.gov.au/contract/search

All data is publicly available and was collected in accordance with the portal's terms of use.

**Last Updated**: January 2026

---

## 📄 License

This dataset is provided under the **Creative Commons Zero (CC0)** license - free to use for any purpose without attribution.

See [LICENSE](LICENSE) for details.

---

## 🤝 Contributing

Found an issue with the data? Have suggestions for additional analysis?

Please open an issue or submit a pull request.

---

## ⚠️ Disclaimer

This is an independent analysis of publicly available data. It is not affiliated with or endorsed by the ACT Government.

Data accuracy depends on the source portal. While we strive for accuracy, please verify critical information with official sources.

---

**Built with ❤️ for transparency in government procurement**

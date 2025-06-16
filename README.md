
# Vehicle Service Data Mapping System 🚗

This project is a complete data mapping solution that standardizes and analyzes vehicle service records using Python and Power BI.

## 🔧 Tools Used
- Python (Pandas, Regex)
- Power BI
- Excel (CSV input/output)
- VS Code

## 📂 Project Structure

```
vehicle-service-data-mapping/
├── raw_data/
│   └── vehicle_service_data_raw_large.csv
├── cleaned_data/
│   └── vehicle_service_data_cleaned.csv
├── scripts/
│   └── mapping_script.py
├── dashboard/
│   └── vehicle_service_dashboard.pbix
└── README.md
```

## 🎯 Features
- Cleans and maps messy service descriptions (e.g. "brk pad" → "Brake Pad Replacement")
- Creates new `Mapped_Service` column
- Outputs a cleaned dataset for analysis
- Power BI dashboard includes:
  - Bar chart of top services
  - Line chart showing service trends
  - Table showing all service records
  - Interactive slicers by service type and center

## 📈 Dashboard Insights
The Power BI dashboard lets users:
- Filter and explore different service categories
- View how services are distributed over time
- Analyze total service counts and center-specific details

## 👨‍💻 Author
**Gbolahan Olawuyi**  
LinkedIn: [linkedin.com/in/gbolahan-olawuyi-oluwatosin](https://www.linkedin.com/in/gbolahan-olawuyi-oluwatosin)  
GitHub: [github.com/GbollyAnaltic](https://github.com/GbollyAnaltic)

---

# DPSA_Circular_data_mining
Sure! Here’s a polished and purposeful summary you can drop into the README.md for your GitHub repository:

---

## 🗂️ DPSA Data Mining Project

**Overview**  
This project automates the extraction of job vacancy information from circulars published by South Africa’s Department of Public Service and Administration (DPSA). These circulars—typically released in PDF format—are dense and unstructured, making manual navigation difficult for job seekers and analysts alike.

Using Python, PyMuPDF, and regex, the tool processes each circular and converts the data into clean, structured Excel files—ready for filtering, analysis, or public sharing.

**Core Features**
- 📄 PDF parsing with PyMuPDF for text extraction
- 🔍 Regex pattern matching to identify job posts and details
- 📊 Structured output into a `pandas` DataFrame
- 💾 Excel export for accessibility and downstream analysis

**Captured Fields**
- Post Title  
- Centre (Location)  
- Salary  
- Requirements  
- Duties  
- Enquiries  
- Closing Date  

**Impact**
- ✅ Empowers job seekers with easier access to relevant public service roles  
- 🧠 Supports public sector analysts in tracking recruitment trends  
- 🔗 Enables integration with dashboards and job platforms for broader civic utility  

**Getting Started**
To run the extractor:
```bash
pip install PyMuPDF pandas
```

Then, use the script to process a circular:
```python
df = extract_dpsa_jobs("path_to_pdf.pdf")
df.to_excel("output_file.xlsx", index=False)
```

**Author**  
Conrad Mogane — Data Artisan in pursuit of civic clarity  
[GitHub Profile](https://github.com/ConradKatlegoMogane)

# DPSA_Circular_data_mining

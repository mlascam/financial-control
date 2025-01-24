# Financial Control

A Python-based project designed to streamline the analysis of personal finances, enabling users to extract, process, and visualize financial data from PDF files such as salary receipts, credit card statements, and more. This tool is perfect for anyone looking to gain control over their expenses, track trends, and make informed financial decisions.

---

## Features

- **PDF Data Extraction**: Automatically extracts relevant data (e.g., salary base, expenses) from multiple PDFs in a folder.
- **Expense Categorization**: Categorizes transactions based on descriptions using a customizable dictionary.
- **Interactive Visualizations**: Generates insights through dynamic charts and temporal trend analysis.
- **Custom Date Parsing**: Handles financial data by parsing months and years from filenames for accurate temporal grouping.
- **Export to CSV**: Outputs processed data into CSV format for further analysis.

---

## Getting Started

### Prerequisites

1. Python 3.8 or higher.
2. Required libraries:
   - `pdfplumber`
   - `pandas`
   - `matplotlib`
   - `seaborn`
   - `plotly`

Install them via:
```bash
pip install pdfplumber pandas matplotlib seaborn plotly
```

### Folder Structure

Ensure your folder structure looks like this:
```
Financial Control/
├── raw_pdfs/         # Folder containing all PDF files
├── processed_data/   # Folder for saving the processed CSV files
├── scripts/          # Python scripts for running the project
```

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/mlascam/financial-control.git
   ```
2. Navigate to the project folder:
   ```bash
   cd financial-control
   ```
3. Run the Python scripts from the `scripts/` directory.

---

## Usage

### 1. Extract Financial Data
Run the script to extract salary base and other financial metrics from PDFs in the specified folder.
```bash
python extract_financial_data.py
```

### 2. Customize Categories
Edit the categorization dictionary in the script to match your specific transaction descriptions. Example:
```python
category_dict = {
    "PEDIDOSYA": "Food Delivery",
    "COTO": "Supermarket",
    "MERCADOLIBRE": "Online Shopping"
}
```

### 3. Visualize Insights
Leverage the visualization scripts to analyze trends:
- Spending over time
- Spending by category

Example:
```bash
python visualize_financial_data.py
```

---

## Outputs

### CSV File
Processed data is saved in `processed_data/combined_data.csv` with the following columns:
- `PDF File`: Name of the source PDF
- `Page`: Page number in the PDF
- `Description`: Extracted transaction description
- `Amount`: Transaction amount
- `Category`: Assigned category (if applicable)
- `Date`: Parsed date based on the filename

### Interactive Charts
Generates dynamic charts to explore:
- Spending trends (monthly/yearly)
- Category-wise expenses
- Custom filters for deeper analysis

---

## Contribution

Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your message here"
   ```
4. Push the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a Pull Request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/mlascam/financial-control/blob/main/LICENSE) file for details.

---

## Connect

- GitHub: [mlascam](https://github.com/mlascam)
- LinkedIn: [Maximiliano Lasca](https://www.linkedin.com/in/maximiliano-lasca)

---

Start taking control of your finances today with **Financial Control**!

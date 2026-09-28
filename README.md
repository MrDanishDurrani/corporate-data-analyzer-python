# Corporate Data Analyzer
A desktop Data Analytics application built with Python that allows non-technical users to analyze CSV and Excel datasets without writing Python code.
The application provides an easy-to-use graphical interface for loading data, viewing dataset information, generating reports, creating charts, previewing results, and exporting reports.
## Application Preview
![Corporate Data Analyzer](Data%20Analyzer%20using%20Python%20.JPG)
## Features
- Load CSV and Excel files
- User-friendly graphical interface
- No Python coding required for end users
- Display total rows and columns
- Identify text and numeric columns
- Display column headings
- Build reports using different grouping options
- Apply data aggregations
- Select value columns
- Preview generated reports
- Create charts using Matplotlib
- Export reports
- Designed for non-technical users
## Technologies Used
- Python
- Tkinter
- Pandas
- Matplotlib
- OpenPyXL
- PyInstaller
## How It Works
1. Select a CSV or Excel data file.
2. Click the Read button.
3. The application analyzes the dataset.
4. Dataset information such as rows, columns, text columns, and numeric columns is displayed.
5. Select the required grouping and aggregation options.
6. Preview the report.
7. Use the Chart Builder to visualize the data.
8. Export the final report when required.
## Project Architecture
```text
User
  ↓
Tkinter GUI
  ↓
File Selection
  ↓
Pandas Data Processing
  ↓
Report Builder
  ↓
Matplotlib Charts
  ↓
Report Preview / Export

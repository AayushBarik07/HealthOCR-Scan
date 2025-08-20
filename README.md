# HealthOCR-Scan
This project focuses on extracting structured medical data (patient details, prescriptions, etc.) from unstructured PDF files using OCR (Tesseract, EasyOCR) and custom parsing techniques (RegEx, rule-based parsing).
It is designed as a research project and a practical application, combining backend data extraction pipelines with a simple frontend interface for uploading and processing medical documents.

# Features
1. OCR Integration: Extracts text from medical PDFs using Tesseract and EasyOCR.
2. Parser Modules:
    ▫️parser_patient_details.py → extracts patient demographic info.
    ▫️parser_prescription.py → extracts prescribed medicines & dosage.
3. Extensible Extractor Pipeline: extractor.py combines multiple parsers for structured output.
4. Unit Testing: Validation with pytest (tests/test_prescription_parser.py).
5. Frontend App: Upload PDFs and view extracted results.
6.Notebooks: Jupyter notebooks for experimentation and regex exploration.
7. Sample Data: Test PDFs for patient details & prescriptions.

# Tech Stack
▫️Python 3.10+
▫️OCR: Tesseract, EasyOCR
▫️Backend: Custom parsers, Regex
▫️Frontend: Flask / Streamlit
▫️Testing: Pytest
▫️Data: PDFs (medical records, prescriptions)

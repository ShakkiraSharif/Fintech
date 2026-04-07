# FinPolis Audit: Precision in every claim

An intelligent, AI-powered corporate expense auditing system designed for Indian compliance standards.

## ● Project Title
**FinPolis Audit** - The Next-Gen AI Expense Guardian.

## ● The Problem
Manual corporate expense auditing is slow, expensive, and highly prone to human error, often resulting in significant financial leakage and non-compliance with complex Indian GST regulations. Companies frequently struggle to verify high volumes of receipts against multi-layered policy manuals, leading to missed violations and inconsistent approval workflows.

## ● The Solution
FinPolis provides a high-precision, AI-driven auditing solution that automates the entire validation lifecycle. Using advanced Computer Vision (EasyOCR), the system instantly extracts critical metadata from receipts (Merchant, Amount, Date, GST) and cross-references it with a "Policy Guardian" engine. It features a professional Glassmorphism dashboard with role-based portals for Employees and Auditors, allowing for side-by-side source-vs-digital verification to ensure 100% audit accuracy.

## ● Tech Stack
*   **Programming Languages:** Python 3.10+, JavaScript (ES6+), HTML5, CSS3
*   **Frameworks:** Flask (Python Backend)
*   **Databases:** JSON-based persistent storage (data/ folder)
*   **APIs & Third-Party Tools:**
    *   **EasyOCR:** AI-powered Vision for text extraction.
    *   **PyTorch:** Deep learning backbone for OCR processing.
    *   **Gunicorn:** Production-grade WSGI server for cloud deployment.
    *   **Google Fonts:** Outfit & Inter for premium typography.

## ● Setup Instructions

### 1. Install Dependencies
Ensure you have Python installed, then run the developer-ready requirement manifest:
```bash
pip install -r requirements.txt
```

### 2. Run the Project Locally
You can start the development server using the standard Flask entry point:
```bash
python app.py
```
Alternatively, for a production-like environment:
```bash
gunicorn app:app
```
The application will be accessible at `http://127.0.0.1:5100`.

### 3. Deployment (Render)
This project is pre-configured with a `render.yaml` blueprint. To go live:
1. Push this code to a GitHub repository.
2. Connect the repository to **Render.com** as a **Blueprint** service.
3. Your app will automatically build and deploy via the provided `Procfile`.

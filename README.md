![Banner](assets/RA_banner111.png)

## ReviewAid (PaddleOCR Version)

This repository implements an **offline OCR-powered review extraction system** using **PaddleOCR** integrated with Streamlit.

---

### 🚀 How to run locally (offline)

1. **Clone the repository**

```bash
git clone https://github.com/ReviewAid/ReviewAid-OCR
cd ReviewAid
```

2. **Install dependencies**

```bash
pip install -r requirements.txt
```

3. **Run Streamlit app**

```bash
streamlit run app.py
```

> (If your entry file has a different name, replace `app.py` accordingly.)

Once started, the app runs fully **locally/offline** after dependencies are installed.

---

![Banner](assets/paddleOCR.png)

This project uses **PaddleOCR**, a deep-learning-based OCR engine that provides:

* Higher accuracy than traditional OCR tools like pytesseract
* Better performance on noisy and complex images
* Strong support for structured text extraction

PaddleOCR replaces the earlier pytesseract-based pipeline for improved reliability.

---

### 📌 Original ReviewAid Repository

[aurumz-rgb/ReviewAid](https://github.com/aurumz-rgb/ReviewAid/)




# 🥗 Food Label Safety and Advisory Framework

An intelligent web and mobile application designed for automated food label analysis, nutritional quality assessment, allergen detection, and personalized dietary guidance[span_4](start_span)[span_4](end_span).

---

## 📌 Project Overview
Many consumers find it difficult to understand complex ingredient labels, hidden additives, and nutritional risks on packaged foods[span_5](start_span)[span_5](end_span). This project simplifies food label interpretation by utilizing **OCR (Optical Character Recognition)**, **Barcode Scanning**, and **AI-assisted refinement** to generate health scores, risk warnings, and personalized dietary advisories in real time[span_6](start_span)[span_6](end_span).

---

## ✨ Key Features
- **Multi-Modal Input:** Supports Barcode scanning, Food label image upload (OCR), and Manual ingredient entry[span_7](start_span)[span_7](end_span).
- **OCR Text Extraction:** Powered by **Tesseract OCR** with custom image preprocessing (resizing, contrast enhancement, noise reduction)[span_8](start_span)[span_8](end_span).
- **Instant Barcode Search:** Uses **ZXing** and **QuaggaJS** libraries to fetch product details from SQL database[span_9](start_span)[span_9](end_span).
- **Nutritional Threshold Analysis:** Evaluates Sugar, Sodium, Saturated Fat, Fiber, and Calories based on **WHO** and **FSSAI** guidelines[span_10](start_span)[span_10](end_span).
- **Allergen & Additive Detection:** Identifies common allergens (Gluten, Nuts, Milk, Soy) and categorizes artificial preservatives/INS numbers[span_11](start_span)[span_11](end_span).
- **Personalized Health Risk Alerts:** Generates tailored warnings for specific user conditions (Diabetes, Hypertension, Heart Disease, Pregnancy)[span_12](start_span)[span_12](end_span).
- **Visual Health Dashboards:** Clean data presentation with health scores, macronutrient breakdown charts, and risk levels[span_13](start_span)[span_13](end_span).

---

## 🏗 System Architecture
The framework operates on a modular multi-layer architecture[span_14](start_span)[span_14](end_span):
1. **Frontend:** User Interface built with **React** (Web) / **Streamlit**[span_15](start_span)[span_15](end_span).
2. **Backend:** **Node.js** & **Express.js** API server for orchestration[span_16](start_span)[span_16](end_span).
3. **Database:** **SQL Database** storing structured food, additive, allergen, and user profile data[span_17](start_span)[span_17](end_span).
4. **AI & Processing Engine:** **Python** (Pandas, NumPy) for OCR refinement, rule-based scoring, and risk classification[span_18](start_span)[span_18](end_span).

---

## 🛠 Tools & Technologies
- **Frontend:** React, Streamlit, HTML5/CSS3[span_19](start_span)[span_19](end_span)
- **Backend:** Node.js, Express.js, RESTful APIs[span_20](start_span)[span_20](end_span)
- **Database:** SQL Database[span_21](start_span)[span_21](end_span)
- **Image Processing & OCR:** Tesseract OCR, OpenCV / PIL[span_22](start_span)[span_22](end_span)
- **Barcode Libraries:** ZXing, QuaggaJS[span_23](start_span)[span_23](end_span)
- **AI & Analytics:** Python, Pandas, NumPy, Matplotlib, Seaborn[span_24](start_span)[span_24](end_span)

---

## 📊 Health Scoring Model
The system calculates a weighted Health Score ($H$) based on nutritional components ($S_i$) and parameter weights ($w_i$)[span_25](start_span)[span_25](end_span):

$$H = \frac{\sum w_i S_i}{\sum w_i} \times 100$$[span_26](start_span)[span_26](end_span)

Products are classified into:
- 🟢 **Low Risk:** Safe for regular consumption[span_27](start_span)[span_27](end_span).
- 🟡 **Moderate Risk:** Recommended in moderation[span_28](start_span)[span_28](end_span).
- 🔴 **High Risk:** Exceeds daily safe dietary limits[span_29](start_span)[span_29](end_span).

---

## 👤 Author & Academic Details
- **Student Name:** Avani Krishna R.B. (KITM23CS005)[span_30](start_span)[span_30](end_span)
- **Degree:** Bachelor of Technology (B.Tech) in Computer Science & Engineering[span_31](start_span)[span_31](end_span)
- **Institution:** KMCT Institute Of Technology And Management, Kuttippuram[span_32](start_span)[span_32](end_span)
- **University:** APJ Abdul Kalam Kerala Technological University (KTU)[span_33](start_span)[span_33](end_span)
- **Project Guide:** Ms. Mubassira Beegam C.K. (Assistant Professor)[span_34](start_span)[span_34](end_span)
- **Head of Department:** Ms. Harshyanas M. (HOD, CSE Dept.)[span_35](start_span)[span_35](end_span)
- **Submission Date:** March 2026[span_36](start_span)[span_36](end_span)
-

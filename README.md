# -AI-Brain-Tumor-Detection-Segmentation-System-using-Deep-Learning
       AI Brain Tumor Detection &amp; Segmentation System using Deep Learning

       # Brain Tumor Detection and Segmentation using AI

## Project Idea
This project uses Artificial Intelligence and Deep Learning to analyze brain MRI scans for detecting and segmenting tumors automatically.

The system is designed to:
- Detect whether a tumor exists
- Locate the tumor accurately
- Calculate tumor size percentage
- Classify tumor regions (Core / Edema / Enhancing)

---

# Problem Statement
Traditional MRI analysis:
- Requires manual inspection by doctors
- Takes a long time
- May contain human diagnostic errors
- Makes accurate tumor size estimation difficult

The project solves these problems through:
- Fast automatic analysis
- High AI-based accuracy
- Reduced diagnosis time
- Clinical decision support

---

# Project Features

## 1. Automatic Tumor Detection
- Detects whether a tumor exists or not

## 2. Tumor Localization
- Highlights tumor regions directly on MRI images

## 3. Tumor Size Calculation
- Calculates tumor size percentage

## 4. Tumor Region Classification
- Necrotic / Non-enhancing tumor core
- Edema
- Enhancing tumor

## 5. Advanced AI System
- Based on CNN and U-Net architectures

## 6. Fast Processing
- MRI analysis completed within seconds

---

# AI Technologies Used
- Deep Learning
- Convolutional Neural Networks (CNN)
- U-Net Segmentation Model

---

# Tools and Technologies

## Development Environment
- Google Colab
- Python

## Libraries
- NumPy
- Matplotlib
- OpenCV
- Nibabel
- PyTorch
- segmentation_models_pytorch

---

# Dataset
- BraTS Dataset
- Real MRI brain scans
- Tumor segmentation masks

---

# How the System Works
1. Input MRI image
2. Preprocess image
3. AI model predicts tumor region
4. Generate tumor mask
5. Calculate tumor size
6. Display analysis results

---

# System Architecture
MRI Image → Preprocessing → U-Net Model → Tumor Mask → Analysis → Result

---

# Output
The system provides:
- Original MRI image
- MRI image with highlighted tumor
- Tumor size percentage
- Tumor region classification
- Visual analysis results

---

# Final Result
After running the project, the system can:
✔ Detect brain tumors intelligently  
✔ Locate tumors accurately  
✔ Calculate tumor size percentage  
✔ Display segmented tumor regions visually  
✔ Support medical diagnosis using AI

---

# مشروع كشف أورام الدماغ باستخدام الذكاء الاصطناعي

## فكرة المشروع
يعتمد المشروع على الذكاء الاصطناعي والتعلم العميق لتحليل صور الرنين المغناطيسي (MRI) للدماغ بهدف الكشف عن الأورام وتحديدها تلقائيًا.

---

# أهداف المشروع
- تحديد وجود الورم
- تحديد مكان الورم بدقة
- حساب نسبة حجم الورم
- تمييز مناطق الورم المختلفة

---

# مميزات المشروع
- كشف الورم تلقائيًا
- تحديد الورم على صورة MRI
- حساب نسبة حجم الورم
- تصنيف أنواع مناطق الورم
- نظام ذكاء اصطناعي متقدم
- سرعة عالية في التحليل

---

# الأدوات المستخدمة
- Python
- Google Colab
- PyTorch
- OpenCV
- NumPy
- Matplotlib
- U-Net
- CNN

---

# قاعدة البيانات
- BraTS Dataset
- صور MRI حقيقية
- Masks لتحديد الأورام

---

# طريقة عمل النظام
1. إدخال صورة MRI
2. معالجة الصورة
3. توقع مكان الورم
4. إنشاء Mask للورم
5. حساب الحجم
6. عرض النتائج

---

# مخرجات النظام
- صورة MRI الأصلية
- صورة مع تحديد الورم
- نسبة حجم الورم
- تصنيف مناطق الورم
- عرض بصري واضح للنتائج

---

# الخلاصة
يساعد هذا المشروع في دعم التشخيص الطبي باستخدام الذكاء الاصطناعي من خلال تحليل صور MRI بسرعة ودقة عالية.

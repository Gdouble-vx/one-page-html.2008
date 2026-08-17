# one-page-html.2008

# Machine Learning Visualizations

One-page interactive HTML demos ที่ visualize หลักการทำงานของ Machine Learning Algorithm ครบ 14 หัวข้อ — แต่ละหน้าเป็นไฟล์ HTML เดียว (self-contained, ไม่พึ่งพา library ภายนอก) เปิดได้ทันทีในเบราว์เซอร์

## 🔗 เปิดดูออนไลน์
เปิดผ่าน **GitHub Pages**: ไปที่ Settings → Pages → เลือก branch `main` และ folder `/ (root)` → แล้วเข้า `https://<username>.github.io/<repo-name>/`

## 📁 โครงสร้างโฟลเดอร์

```
├── index.html                        ← หน้าแรก รวมลิงก์ทุกหัวข้อ
├── Supervised-Learning/
│   ├── 01-Linear-Regression/
│   ├── 02-Logistic-Regression/
│   ├── 03-KNN/
│   ├── 04-Decision-Tree/
│   ├── 05-Random-Forest/
│   ├── 06-SVM/
│   ├── 07-K-Means/
│   ├── 08-MLP-Neural-Network/
│   ├── 13-XGBoost/
│   └── 14-Stacking/
├── Unsupervised-Learning/
│   ├── 09-CNN/
│   ├── 10-LSTM/
│   └── 11-Transformer/
└── Reinforcement-Learning/
    └── 12-Reinforcement-Learning/
```

## 📚 รายการหัวข้อ

| # | หัวข้อ | หมวด | สิ่งที่เล่นได้ |
|---|--------|------|---------------|
| 14 | Stacking | Supervised | 3 base models → meta-model |
| 13 | XGBoost | Supervised | Boosting แก้ residual |
| 12 | Reinforcement Learning | Reinforcement | Q-Learning หาทางไปดาว ⭐ |
| 11 | Transformer | Unsupervised* | Attention heatmap |
| 10 | LSTM | Unsupervised* | ควบคุมประตูความจำ 3 บาน |
| 09 | CNN | Unsupervised* | วาดภาพ ดู kernel สแกน |
| 08 | MLP | Supervised | เรียนรู้ XOR + Backprop |
| 07 | K-Means | Supervised* | จัดกลุ่มทีละขั้นตอน |
| 06 | SVM | Supervised | Max-margin + Support Vectors |
| 05 | Random Forest | Supervised | 60 ต้นโหวตรวม |
| 04 | Decision Tree | Supervised | เติบโตต้นไม้ทีละชั้น |
| 03 | kNN | Supervised | เลื่อน k ดูเพื่อนบ้านโหวต |
| 02 | Logistic Regression | Supervised | ฝึก Gradient Descent ดูเส้นแบ่ง |
| 01 | Linear Regression | Supervised | ลากจุด ดูเส้นฟิต + R² |

> \* หมายเหตุ: CNN/LSTM/Transformer เป็น deep learning (supervised ในทางปฏิบัติ) และ K-Means เป็น unsupervised — จัดตามลำดับที่กำหนดให้ในโจทย์

## 🚀 วิธีใช้งานในเครื่อง
เปิดไฟล์ `index.html` ในเบราว์เซอร์ หรือเปิดแต่ละหัวข้อตรง ๆ ก็ได้ ไม่ต้องติดตั้ง dependencies ใด ๆ

## 🛠 เทคโนโลยี
- HTML + CSS + JavaScript (Vanilla) อย่างเดียว
- Canvas API สำหรับกราฟและอนิเมชัน
- SVG สำหรับไดอะแกรมโครงสร้างโมเดล

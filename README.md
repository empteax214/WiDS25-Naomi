# WiDS25-Team Naomi  
**Predict Sex Patterns in ADHD – WiDS Datathon 2025**

---

## 1. Mục tiêu  
Dự đoán **giới tính (Nam/Nữ)** của cá thể trong dữ liệu liên quan đến ADHD (Attention Deficit Hyperactivity Disorder) bằng cách áp dụng các phương pháp **khám phá dữ liệu (EDA)**, **feature engineering**, và **machine learning models**.

---

## 2. Thành viên nhóm  
- Nhóm có **4 thành viên**:
  - **3 thành viên**: Phụ trách EDA & Feature Engineering  
  - **1 thành viên**: Phụ trách Fine-Tuning mô hình  

---

## 3. Cấu trúc repo

- `Categorical_ADHD_EDA.ipynb`  
  → Notebook khám phá dữ liệu các biến phân loại, phân tích phân phối, kiểm tra missing values, trực quan hóa quan hệ giữa các biến.  

- `Data preprocessing_FE_official.ipynb`  
  → Thực hiện tiền xử lý dữ liệu: xử lý giá trị thiếu, chuẩn hóa, mã hóa categorical, scaling, tạo thêm đặc trưng mới để tăng hiệu quả mô hình.  

- `finetune.ipynb`  
  → Fine-tuning mô hình Machine Learning: thử nghiệm nhiều thuật toán (XGBoost, LightGBM, RandomForest, hoặc deep learning), tối ưu hyperparameters và chọn mô hình tốt nhất.  

- `README.md`  
  → File hướng dẫn mô tả dự án.  

---

## 4. Quy trình làm việc

1. **Khám phá dữ liệu (EDA)**  
   - Kiểm tra đặc trưng dữ liệu, phân tích thống kê, xử lý missing values.  
   - Trực quan hóa dữ liệu để hiểu xu hướng và sự khác biệt giữa các nhóm.  

2. **Tiền xử lý & Feature Engineering**  
   - Chuẩn hóa và mã hóa dữ liệu.  
   - Tạo đặc trưng mới (feature crosses, interactions, aggregations).  
   - Lựa chọn tập biến tối ưu cho mô hình.  

3. **Fine-tuning mô hình**  
   - Áp dụng nhiều thuật toán ML.  
   - Grid search / Bayesian optimization để tối ưu hyperparameters.  
   - Đánh giá trên metric phù hợp (ví dụ: ROC-AUC, F1-score).  

---

## 5. Kết quả  
- Đội **Naomi** đã đạt **Top 20 toàn cầu** trong cuộc thi **WiDS Datathon 2025** 🎉  
- Đây là thành quả của việc kết hợp hiệu quả giữa phân tích dữ liệu, kỹ thuật feature engineering, và chiến lược fine-tuning mô hình.  

---

## 6. Cách sử dụng

1. Clone repository:
   ```bash
   git clone https://github.com/empteax214/WiDS25-Naomi.git
   cd WiDS25-Naomi
2. Cài đặt thư viện cần thiết (nếu có requirements.txt):
   ```bash
   git clone https://github.com/empteax214/WiDS25-Naomi.git
   cd WiDS25-Naomi
   
## 7. Ghi nhận
Xin cảm ơn ban tổ chức WiDS Datathon 2025 đã tạo ra một sân chơi học thuật tuyệt vời.
Cảm ơn cộng đồng Kaggle và các mentor đã hỗ trợ.

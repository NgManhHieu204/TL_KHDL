# Phân Tích Chỉ Số Khí Tượng Việt Nam VÀ Ứng Dụng Machine Learning

Đề tài này phân tích dữ liệu thời tiết từ 40 tỉnh/thành phố Việt Nam (2009-2021) và ứng dụng các thuật toán Machine Learning để dự báo thời tiết và phân loại các mô hình thời tiết điển hình.

## Thông Tin Bài Tiểu Luận

**Tên đề tài:** Phân tích chỉ số khí tượng tại các tỉnh thành Việt Nam và Ứng dụng Học máy trong phân loại, dự báo thời tiết

**Phạm vi dữ liệu:** 
- Khoảng thời gian: 1 tháng 1 năm 2009 - 18 tháng 6 năm 2021
- Địa điểm: 40 tỉnh/thành phố Việt Nam
- Nguồn dữ liệu: `weather.csv` (từ Kaggle)

**Môn học:** Khoa Học Dữ Liệu

**Link Youtube:** https://youtu.be/in_ykbv8w8g

## Mục Tiêu Chính

### 1. Phân Tích Khám Phá Dữ Liệu (EDA)
Trả lời 5 câu hỏi phân tích để hiểu rõ hơn về đặc điểm khí tượng của Việt Nam:

1. **Mưa:** Tỉnh/thành phố nào có lượng mưa cao nhất/thấp nhất trong năm?
2. **Mối liên hệ Nhiệt độ - Độ ẩm:** Có mối tương quan mạnh giữa nhiệt độ cao nhất và độ ẩm ở thành phố lớn (Hà Nội, TP.HCM) không?
3. **Mùa mưa:** Lượng mưa tập trung vào những tháng nào ở 3 miền Bắc - Trung - Nam?
4. **Ảnh hưởng gió:** Tốc độ và hướng gió có tác động rõ rệt đến lượng mưa ở các tỉnh ven biển?
5. **Xu hướng nhiệt độ:** Nhiệt độ trung bình Việt Nam có đang tăng lên trong 10+ năm qua?

### 2. Machine Learning - Dự Báo Mức Độ Mưa (Classification)
Xây dựng mô hình phân loại để dự báo **mức độ mưa** (Không mưa, Mưa nhỏ, Mưa vừa, Mưa to) dựa trên các chỉ số khí tượng:
- **Thuật toán:** Logistic Regression, Random Forest, Decision Tree
- **Kết quả:** So sánh độ chính xác (Accuracy) và hiệu suất của các mô hình

### 3. Machine Learning - Phân Cụm Kiểu Thời Tiết (Clustering)
Phân nhóm các ngày trong năm thành các **kiểu hình thời tiết đặc trưng** (ví dụ: khô hanh, nồm ẩm, bão tố):
- **Thuật toán:** K-Means Clustering
- **Kết quả:** Xác định số cluster tối ưu và phân tích đặc điểm của mỗi nhóm

## Công Nghệ & Môi Trường

**Ngôn ngữ:** Python 3.10

**Thư viện chính:**
- `pandas` - Đọc, xử lý và phân tích dữ liệu
- `numpy` - Tính toán mảng số liệu
- `matplotlib`, `seaborn` - Trực quan hóa dữ liệu (biểu đồ, heatmap)
- `scikit-learn` - Các mô hình Machine Learning và đánh giá hiệu suất

**Công cụ:**
- VS Code - Trình biên tập mã
- Jupyter Notebook - Tương tác và trình bày kết quả
- Anaconda - Quản lý môi trường Python

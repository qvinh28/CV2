# CV2
# Gradient Domain Editing và Biến đổi hình học

## Mục tiêu
* Hiểu và vận dụng các kỹ thuật chỉnh sửa ảnh trong miền gradient (Gradient Domain Editing)[cite: 4].
* Nắm vững các phép biến đổi hình học cơ bản và nâng cao trong Computer Vision[cite: 5].
* Phân biệt và đánh giá sự khác nhau giữa các phép biến đổi Affine và Projective (Homography) transformation[cite: 6].
* Rèn luyện kỹ năng hiện thực, trực quan hóa và phân tích kết quả xử lý ảnh[cite: 7].

---

## Phần 1: Gradient Domain Editing
Thực hiện bài toán ghép ảnh dựa trên miền gradient nhằm đảm bảo sự tự nhiên về mặt ánh sáng và biên[cite: 10, 14]:
* **Dữ liệu đầu vào**: Lựa chọn ảnh nền (Background) và ảnh chứa đối tượng cần ghép (Source)[cite: 11, 12].
* **Xác định đối tượng**: Sử dụng mask thủ công hoặc bán tự động để tách vùng đối tượng từ ảnh nguồn[cite: 13].
* **Hiện thực kỹ thuật**: Áp dụng thuật toán Gradient Domain Editing để ghép đối tượng vào ảnh nền[cite: 14].
* **So sánh & Đánh giá**: 
    * So sánh kết quả với phương pháp ghép trực tiếp (Naive Paste)[cite: 18].
    * Phân tích chất lượng ghép ảnh và các hạn chế gặp phải[cite: 39].

## Phần 2: Biến đổi hình học (Transformations)
Xây dựng các đoạn chương trình minh họa cho các phép biến đổi hình học đã học[cite: 20]:
* **Cơ bản**: Thực hiện Translation (dịch chuyển), Rotation (xoay), Scaling (co giãn)[cite: 21].
* **Nâng cao**: Hiện thực Affine Transformation và Projective (Homography) Transformation[cite: 22, 23].
* **Trực quan hóa**: Hiển thị kết quả của từng phép biến đổi trên cùng một ảnh đầu vào để so sánh[cite: 26].
* **Đánh giá**: Phân tích sự khác biệt giữa Affine và Projective transformation thông qua các ví dụ cụ thể[cite: 27, 41].

## Phần 3: Thử nghiệm mở rộng (Khuyến khích)
Ứng dụng Projective Transformation để dán một hình ảnh lên một mặt phẳng được chỉ định[cite: 29]:
* **Nội dung**: Sử dụng ảnh cá nhân hoặc nhân vật nổi tiếng làm nội dung cần dán[cite: 30].
* **Mặt phẳng đích**: Xác định vùng đích trong ảnh nền (ví dụ: biển quảng cáo, tòa nhà H6 Bách Khoa)[cite: 31, 32].
* **Kỹ thuật**: Sử dụng Projective Transformation để ánh xạ hình ảnh vào mặt phẳng đích[cite: 33].

---

## Công cụ sử dụng
* **Ngôn ngữ**: Python
* **Thư viện chính**: OpenCV, NumPy
* **Trực quan hóa**: Matplotlib
* **Môi trường**: Jupyter Notebook / Google Colab

---

## Ghi chú
* Ảnh đầu vào được lưu trữ trong thư mục `images/`.
* Báo cáo chỉ bao gồm các đoạn mã chính, ngắn gọn; mã nguồn đầy đủ được cung cấp qua link repository[cite: 45, 46].
* Mọi phân tích chi tiết về hiệu quả và hạn chế của thuật toán được trình bày trong báo cáo chính thức[cite: 40, 43].

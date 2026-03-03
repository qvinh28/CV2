# CV2
# Gradient Domain Editing và Biến đổi hình học

## Mục tiêu
* [cite_start]Hiểu và vận dụng các kỹ thuật chỉnh sửa ảnh trong miền gradient (Gradient Domain Editing)[cite: 4].
* [cite_start]Nắm vững các phép biến đổi hình học cơ bản và nâng cao trong Computer Vision[cite: 5].
* [cite_start]Phân biệt và đánh giá sự khác nhau giữa các phép biến đổi Affine và Projective (Homography) transformation[cite: 6].
* [cite_start]Rèn luyện kỹ năng hiện thực, trực quan hóa và phân tích kết quả xử lý ảnh[cite: 7].

---

## Phần 1: Gradient Domain Editing
[cite_start]Thực hiện bài toán ghép ảnh dựa trên miền gradient nhằm đảm bảo sự tự nhiên về mặt ánh sáng và biên[cite: 10, 14]:
* [cite_start]**Dữ liệu đầu vào**: Lựa chọn ảnh nền (Background) và ảnh chứa đối tượng cần ghép (Source)[cite: 11, 12].
* [cite_start]**Xác định đối tượng**: Sử dụng mask thủ công hoặc bán tự động để tách vùng đối tượng từ ảnh nguồn[cite: 13].
* [cite_start]**Hiện thực kỹ thuật**: Áp dụng thuật toán Gradient Domain Editing để ghép đối tượng vào ảnh nền[cite: 14].
* **So sánh & Đánh giá**: 
    * [cite_start]So sánh kết quả với phương pháp ghép trực tiếp (Naive Paste)[cite: 18].
    * [cite_start]Phân tích chất lượng ghép ảnh và các hạn chế gặp phải[cite: 39].

## Phần 2: Biến đổi hình học (Transformations)
[cite_start]Xây dựng các đoạn chương trình minh họa cho các phép biến đổi hình học đã học[cite: 20]:
* [cite_start]**Cơ bản**: Thực hiện Translation (dịch chuyển), Rotation (xoay), Scaling (co giãn)[cite: 21].
* [cite_start]**Nâng cao**: Hiện thực Affine Transformation và Projective (Homography) Transformation[cite: 22, 23].
* [cite_start]**Trực quan hóa**: Hiển thị kết quả của từng phép biến đổi trên cùng một ảnh đầu vào để so sánh[cite: 26].
* [cite_start]**Đánh giá**: Phân tích sự khác biệt giữa Affine và Projective transformation thông qua các ví dụ cụ thể[cite: 27, 41].

## Phần 3: Thử nghiệm mở rộng (Khuyến khích)
[cite_start]Ứng dụng Projective Transformation để dán một hình ảnh lên một mặt phẳng được chỉ định[cite: 29]:
* [cite_start]**Nội dung**: Sử dụng ảnh cá nhân hoặc nhân vật nổi tiếng làm nội dung cần dán[cite: 30].
* [cite_start]**Mặt phẳng đích**: Xác định vùng đích trong ảnh nền (ví dụ: biển quảng cáo, tòa nhà H6 Bách Khoa)[cite: 31, 32].
* [cite_start]**Kỹ thuật**: Sử dụng Projective Transformation để ánh xạ hình ảnh vào mặt phẳng đích[cite: 33].

---

## Công cụ sử dụng
* **Ngôn ngữ**: Python
* **Thư viện chính**: OpenCV, NumPy
* **Trực quan hóa**: Matplotlib
* **Môi trường**: Jupyter Notebook / Google Colab

---

## Ghi chú
* Ảnh đầu vào được lưu trữ trong thư mục `images/`.
* [cite_start]Báo cáo chỉ bao gồm các đoạn mã chính, ngắn gọn; mã nguồn đầy đủ được cung cấp qua link repository[cite: 45, 46].
* [cite_start]Mọi phân tích chi tiết về hiệu quả và hạn chế của thuật toán được trình bày trong báo cáo chính thức[cite: 40, 43].

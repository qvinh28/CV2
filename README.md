# CV2
# Gradient Domain Editing và Biến đổi hình học

## Mục tiêu
* Hiểu và vận dụng các kỹ thuật chỉnh sửa ảnh trong miền gradient (Gradient Domain Editing).
* Nắm vững các phép biến đổi hình học cơ bản và nâng cao trong Computer Vision.
* Phân biệt và đánh giá sự khác nhau giữa các phép biến đổi Affine và Projective (Homography) transformation.
* Rèn luyện kỹ năng hiện thực, trực quan hóa và phân tích kết quả xử lý ảnh.

---

## Phần 1: Gradient Domain Editing
Thực hiện bài toán ghép ảnh dựa trên miền gradient nhằm đảm bảo sự tự nhiên về mặt ánh sáng và biên:
* **Dữ liệu đầu vào**: Lựa chọn ảnh nền và ảnh chứa đối tượng cần ghép.
* **Xác định đối tượng**: Sử dụng mask thủ công hoặc bán tự động để tách vùng đối tượng từ ảnh nguồn.
* **Hiện thực kỹ thuật**: Áp dụng thuật toán Gradient Domain Editing để ghép đối tượng vào ảnh nền.
* **So sánh & Đánh giá**: 
    * So sánh kết quả với phương pháp ghép trực tiếp (Naive Paste).
    * Phân tích chất lượng ghép ảnh và các hạn chế gặp phải.

## Phần 2: Biến đổi hình học (Transformations)
Xây dựng các đoạn chương trình minh họa cho các phép biến đổi hình học đã học:
* **Cơ bản**: Thực hiện Translation (dịch chuyển), Rotation (xoay), Scaling (co giãn).
* **Nâng cao**: Hiện thực Affine Transformation và Projective (Homography) Transformation.
* **Trực quan hóa**: Hiển thị kết quả của từng phép biến đổi trên cùng một ảnh đầu vào để so sánh.
* **Đánh giá**: Phân tích sự khác biệt giữa Affine và Projective transformation thông qua các ví dụ cụ thể.

## Phần 3: Thử nghiệm mở rộng (Khuyến khích)
Ứng dụng Projective Transformation để dán một hình ảnh lên một mặt phẳng được chỉ định:
* **Nội dung**: Sử dụng ảnh cá nhân hoặc nhân vật nổi tiếng làm nội dung cần dán.
* **Mặt phẳng đích**: Xác định vùng đích trong ảnh nền.
* **Kỹ thuật**: Sử dụng Projective Transformation để ánh xạ hình ảnh vào mặt phẳng đích.

---

## Công cụ sử dụng
* **Ngôn ngữ**: Python
* **Thư viện chính**: OpenCV, NumPy
* **Trực quan hóa**: Matplotlib
* **Môi trường**: Jupyter Notebook / Google Colab

---

## Ghi chú
* Ảnh đầu vào được lưu trữ trong thư mục `images/`.
* Báo cáo chỉ bao gồm các đoạn mã chính, ngắn gọn; mã nguồn đầy đủ được cung cấp qua link repository.
* Mọi phân tích chi tiết về hiệu quả và hạn chế của thuật toán được trình bày trong báo cáo chính thức.

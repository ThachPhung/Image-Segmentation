# Image Segmentation
## Giới thiệu dự án
Dự án này tập trung vào bài toán **phân đoạn ảnh y tế**, một trong những ứng dụng quan trọng của trí tuệ nhân tạo trong hỗ trợ chẩn đoán hình ảnh. Mục tiêu của đề tài là triển khai và đánh giá mô hình **TransUNet** — sự kết hợp giữa **Vision Transformer (ViT)** và **U-Net** — trên tập dữ liệu ISIC 2018 chứa ảnh da liễu và nhãn phân đoạn tương ứng.

Trong quá trình nghiên cứu, các bước thực hiện bao gồm:

- Tìm hiểu các phương pháp phân đoạn ảnh truyền thống và hiện đại,
- Tiền xử lý dữ liệu và xây dựng bộ dữ liệu chuẩn hóa,
- Huấn luyện mô hình với các kỹ thuật như RMSprop, gradient clipping, mixed precision training,
- Đánh giá hiệu quả bằng các chỉ số như IoU, Dice Coefficient, Precision, Recall và F1-score.

Dự án không chỉ chứng minh tiềm năng của TransUNet trong lĩnh vực xử lý ảnh y tế mà còn gợi mở nhiều hướng nghiên cứu tiếp theo, như mở rộng sang các loại ảnh y tế khác (MRI, CT) và tối ưu hóa hiệu suất mô hình.

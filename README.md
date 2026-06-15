# Xây dựng và so sánh mô hình cho bài toán phân loại cảm xúc bình luận trong thương mại điện tử sử dụng phương pháp truyền thống và Transformer

## Giới thiệu
Dự án tập trung vào việc xây dựng và so sánh các mô hình phân loại cảm xúc cho bình luận thương mại điện tử tiếng Việt bằng hai hướng tiếp cận:
- Phương pháp học máy truyền thống
- Mô hình Transformer hiện đại

Mục tiêu của nghiên cứu là đánh giá hiệu quả giữa các mô hình truyền thống và mô hình học sâu trong bài toán xử lý ngôn ngữ tự nhiên tiếng Việt (Vietnamese NLP).

---

## Mục tiêu
- Xây dựng hệ thống phân loại cảm xúc cho bình luận thương mại điện tử.
- So sánh hiệu suất giữa mô hình truyền thống và Transformer.
- Phân tích ưu điểm và hạn chế của từng phương pháp.
- Ứng dụng NLP trong các bài toán thực tế của thương mại điện tử.

---

## Công nghệ sử dụng
- Python
- PyTorch
- Scikit-learn
- PhoBERT
- Transformers
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Các mô hình được sử dụng

### Mô hình truyền thống
- Logistic Regression

### Mô hình Transformer
- PhoBERT

---

## Cấu trúc thư mục

```bash
├── data
├── LogisticRegresion
├── PhoBert
├── TEST.ipynb
├── README.md
```

---

## Tập dữ liệu
Bộ dữ liệu được sử dụng trong nghiên cứu lấy từ Kaggle:
- [data](https://www.kaggle.com/datasets/linhlpv/vietnamese-sentiment-analyst)

Dữ liệu gồm các bình luận thương mại điện tử tiếng Việt được gán nhãn cảm xúc như:
- Tích cực
- Tiêu cực
- Trung lập

Các bước tiền xử lý dữ liệu:
- Chuẩn hóa văn bản
- Tách từ (tokenization)
- Loại bỏ ký tự không cần thiết
- Trích xuất đặc trưng

---

## Chức năng chính
- Phân loại cảm xúc tiếng Việt
- So sánh mô hình truyền thống và Transformer
- Đánh giá hiệu suất mô hình
- Xây dựng pipeline tiền xử lý NLP
- Huấn luyện và kiểm thử mô hình

---

## Đánh giá mô hình
Các mô hình được đánh giá bằng:
- Accuracy
- Precision
- Recall
- F1-score

---

## Kết quả
Kết quả thực nghiệm cho thấy mô hình Transformer như PhoBERT có khả năng hiểu ngữ cảnh và ngữ nghĩa tiếng Việt tốt hơn so với các mô hình học máy truyền thống.

Trong khi đó, các mô hình truyền thống vẫn có ưu điểm:
- Huấn luyện nhanh
- Ít tốn tài nguyên
- Dễ triển khai

---

## Hướng phát triển
- Mở rộng tập dữ liệu tiếng Việt
- Áp dụng kỹ thuật tăng cường dữ liệu
- Fine-tuning thêm các mô hình Transformer khác
- Triển khai thành web app hoặc chatbot API

---

## Tác giả
Võ Gia Kiệt
Phan Đức Nhân



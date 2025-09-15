# Detect-Spam-Email
Mô tả: Xây dựng mô hình Machine Learning sử dụng thuật toán Naive Bayes để tự động phân loại email tiếng Việt là thư rác (Spam) hay thư thường (Ham).

Quy trình chính:

Tiền xử lý: Làm sạch dữ liệu văn bản thô, loại bỏ ký tự nhiễu, URL và các từ dừng (stopwords) tiếng Việt.

Trích xuất đặc trưng: Chuyển đổi nội dung email thành vector số bằng phương pháp Bag-of-Words (CountVectorizer).

Huấn luyện & Đánh giá: Huấn luyện mô hình Multinomial Naive Bayes và kiểm thử hiệu năng.

Kết quả: Đạt độ chính xác ~91% trên tập dữ liệu kiểm thử.

Công nghệ: Python, Scikit-learn, Pandas, VnCoreNLP, Joblib.

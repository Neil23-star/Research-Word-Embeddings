### Research-Word-Embeddings
#### 1. Khái niệm về word embeddings

* Các khái niệm về word embeddings (nhúng từ).

* Tìm hiểu cách hoạt động của mô hình Word2vec sử dụng cấu trúc mạng Neural Network.
![Kiến trúc của mô hình Word2Vec](/image/word2vec.png)

* Tìm hiểu cách hoạt động của mô hình Glove sử dụng ma trận đồng xuất hiện.
![Kiến trúc của mô hình Glove](/image/glove.png)

#### 2. Minh họa Recommender System sử dụng mô hình Word2vec

Tiến hành xây dựng Recommender System cho cửa hàng bán lẻ, tập dữ liệu có thể tìm thấy tại [đây](https://archive.ics.uci.edu/ml/machine-learning-databases/00352/).

Giải pháp: 

* Xây dựng mô hình word2vec trong NLP (Xử lý ngôn ngữ tự nhiên) để tạo ra nhúng từ cho tên của tất cả các sản phẩm.
![nhúng từ dùng mô hinhg Word2vec](/image/word_e_demo.png)

* Đề xuất các sản phẩm hàng đầu cho khách hàng dựa trên sự giống nhau của vector giữa các sản phẩm đã mua của khách hàng và toàn bộ sản phẩm trong trang web.
![vd_1](/image/demo1.png)
![vd_2](/image/demo2.png)

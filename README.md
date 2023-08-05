
# Cài đặt các thư viện cần thiết
- cài đặt thư viện scikit learn: pip install -U scikit-learn
- cài đặt matplotlib: pip install matplotlib
- cài đặt pandas : pip install pandas
- cài đặt thư viện nltk: pip install nltk
- cài đặt numpy: pip install numpy
# Thông tin chi tiết các file
- BBC News Train.csv là file chứa dữ liệu chưa xử lý
- preprocess_data.ipynb là file xử lý dữ liệu sau đó lưu vào file mới là preprocessed_data_bbc.csv,chuyển dữ liệu thành data,visualize data 
- preprocessed_data_bbc.csv là file dữ liệu sau khi xử lí
- rf_model là file chứa quá trình chạy , tinh chỉnh và các bước để hoàn thành model random forest
- knn_model là file chứa quá trình chạy , tinh chỉnh và các bước để hoàn thành model knn
- GausNB_model là file chứa quá trình chạy , tinh chỉnh và các bước để hoàn thành model Naive Bayes
- model_rf.pkl và vectorizer.pkl là hai file chứa model của random forest và ma trận rời rạc hóa 
- run.ipynb là file chạy model model_rf.pkl
# Hướng dẫn chạy
Mở file run.ipynb 
Parse bất kì news nào vào vùng chỉ định , sau đó kết quả sẽ được hiện thị phía dưới.

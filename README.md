# Vietnam Region Speech Recognition (VIVOS Dataset)

## Giới thiệu

Đây là một dự án nhận dạng giọng nói theo vùng miền của tiếng Việt, sử dụng tập dữ liệu VIVOS. Dự án thực hiện trích xuất đặc trưng từ âm thanh và áp dụng các mô hình học máy để phân loại giọng nói theo vùng miền.

## Cấu trúc dự án

- Notebook chính: vietnam-region-speech-recognition-vivos.ipynb

- Dữ liệu: Sử dụng tập dữ liệu VIVOS

- Thư viện sử dụng:

  - librosa để trích xuất đặc trưng âm thanh

  - pandas và numpy để xử lý dữ liệu

  - matplotlib và seaborn để trực quan hóa

  - scikit-learn để huấn luyện và đánh giá mô hình


## Trích xuất đặc trưng âm thanh

Dự án sử dụng các đặc trưng như:

- Chroma_stft

- RMSE

- Spectral centroid & bandwidth

- MFCCs (Mel-frequency cepstral coefficients)

## Huấn luyện mô hình

- Sử dụng Random Forest để phân loại giọng nói theo vùng miền.

- Đánh giá mô hình bằng độ chính xác, ma trận nhầm lẫn, AUC-ROC.

Kết luận

Dự án giúp phân biệt vùng miền dựa trên giọng nói bằng cách áp dụng các kỹ thuật xử lý tín hiệu và học máy. Có thể cải thiện bằng cách thử nghiệm thêm các mô hình deep learning như CNN hoặc RNN.

Tác giả
- Đào Xuân Hoàng Tuấn
- Trương Thành Thảo


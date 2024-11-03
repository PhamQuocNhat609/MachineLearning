1. Công nghệ sử dụng
   
Framework:
PyTorch, Torchvision,  Matplotlib. 
2. Thuật toán

Multilayer Perceptron (MLP): 

Là một dạng của mạng nơ-ron sâu, MLP bao gồm một hoặc nhiều lớp nơ-ron. Trong mã nguồn của bạn, MLP được xây dựng với hai tầng ẩn và sử dụng hàm kích hoạt ReLU (Rectified Linear Unit).
Giải thích về thuật toán MLP

Cấu trúc của MLP:

Lớp đầu vào: Nhận đầu vào từ dữ liệu hình ảnh (ví dụ, ảnh CIFAR-10, kích thước 32x32x3).
Tầng ẩn: Thường có ít nhất một hoặc nhiều tầng nơ-ron, ở đây bạn có hai tầng ẩn với 512 và 256 nơ-ron. Mỗi nơ-ron trong tầng ẩn sẽ nhận đầu vào từ tất cả nơ-ron trong lớp trước đó và áp dụng một trọng số và một hàm kích hoạt (ReLU) để tạo ra đầu ra.
Lớp đầu ra: Lớp này có 10 nơ-ron (tương ứng với 10 lớp của dữ liệu CIFAR-10), sử dụng hàm kích hoạt softmax trong quá trình phân loại.
Quá trình huấn luyện:
Forward Pass: Dữ liệu được truyền qua mạng, từ lớp đầu vào đến lớp đầu ra. Mỗi nơ-ron tính toán đầu ra của nó dựa trên đầu vào và trọng số hiện tại.
Loss Calculation: Sau khi có dự đoán, hàm mất mát (cross-entropy loss) được sử dụng để đánh giá độ chính xác của dự đoán so với nhãn thực tế.
Backward Pass: Sử dụng thuật toán lan truyền ngược (backpropagation) để cập nhật trọng số dựa trên độ gradient của hàm mất mát. Quá trình này sử dụng thuật toán tối ưu (như SGD - Stochastic Gradient Descent) để điều chỉnh các trọng số nhằm giảm thiểu hàm mất mát.

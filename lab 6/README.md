1. Công Nghệ Sử Dụng

Frameworks:Bài  formula

Torch

Frameworks:Bài MLD

PyTorch, NumPy, Matplotlib, TorchVision.

2. Thuật Toán
   
   Thuật Toán: Decision Tree (Bài  formula)

Giải thích:

Decision Tree là một thuật toán học máy được sử dụng để phân loại và hồi quy. Nó hoạt động dựa trên nguyên tắc chia nhỏ không gian dữ liệu thành các nhánh dựa trên các điều kiện (đặc trưng).
Mỗi nút trong cây đại diện cho một điều kiện kiểm tra trên một thuộc tính, và mỗi nhánh đại diện cho kết quả của điều kiện đó.
Quyết định cuối cùng (nhãn) được đưa ra tại các lá của cây. Decision Tree có thể dễ dàng hình dung và giải thích, nhưng có thể bị overfitting nếu không được điều chỉnh đúng cách.

Thuật Toán: MLP (Multi-Layer Perceptron)(Bài MLD)

Giải thích:

MLP là một loại mạng nơ-ron được sử dụng phổ biến trong học sâu. Nó bao gồm nhiều lớp (input layer, hidden layers và output layer).
Trong mỗi lớp, các nơ-ron được kết nối với nhau thông qua các trọng số (weights) và bias, sử dụng các hàm kích hoạt (activation functions) như ReLU để thêm tính phi tuyến.
MLP hoạt động theo nguyên tắc lan truyền thẳng (forward propagation) để tính toán đầu ra và lan truyền ngược (backpropagation) để cập nhật trọng số dựa trên lỗi.

3. Hiển thị lên wesite
   
Bài formula:
   
![image](https://github.com/user-attachments/assets/45e1328a-4b20-45b2-9c51-11a60cb66370)

Bài MLP:

![Screenshot 2024-10-21 213431](https://github.com/user-attachments/assets/b007adde-7c30-4cc7-87c5-03a2030f4a04)
4. So Sánh Kết Quả Giữa Hai Thuật Toán

Thực hiện so sánh giữa hai thuật toán Decision Tree và MLP, có thể thực hiện như sau:

Huấn Luyện Hai Mô Hình:
Huấn luyện mô hình Decision Tree và mô hình MLP trên cùng một tập dữ liệu.

Ghi Nhận Kết Quả:
Lưu kết quả cho mỗi mô hình (loss và accuracy) vào các tệp hình ảnh khác nhau.

<h1 align="center"> PHÁT HIỆN HÀNH VI GIAN LẬN TRONG THI CỬ </h1>

<div align="center">

<p align="center">
  <img src="logoDaiNam.png" alt="DaiNam University Logo" width="200"/>
  <img src="LogoAIoTLab.png" alt="AIoTLab Logo" width="170"/>
</p>

[![Made by AIoTLab](https://img.shields.io/badge/Made%20by%20AIoTLab-blue?style=for-the-badge)](https://www.facebook.com/DNUAIoTLab)
[![Fit DNU](https://img.shields.io/badge/Fit%20DNU-green?style=for-the-badge)](https://fitdnu.net/)
[![DaiNam University](https://img.shields.io/badge/DaiNam%20University-red?style=for-the-badge)](https://dainam.edu.vn)

</div>

<h2 align="center">Phát hiện hành vi gian lận trong thi cử sử dụng YOLOv11</h2>

<p align="left">
  Đề tài hướng đến việc xây dựng một hệ thống tự động phát hiện hành vi gian lận trong thi cử bằng cách sử dụng trí tuệ nhân tạo (AI) và thị giác máy tính. Hệ thống này sẽ:
<p>- Tự động giám sát phòng thi bằng camera từ góc trên bàn.<p>
<p>- Nhận diện và phân loại các hành vi gian lận như nhìn bài, trao đổi bài, sử dụng tài liệu hoặc điện thoại.</p>
<p>- Cảnh báo thời gian thực khi phát hiện gian lận thông qua hệ thống web.</p>
<p>- Tích hợp hệ thống AI vào giao diện web, giúp giám thị dễ dàng theo dõi.</p>
</p>

---

## 🛠 Công nghệ sử dụng  

| Công nghệ | Mô tả |
|-----------|------|
| Python 🐍 | Ngôn ngữ lập trình chính |
| OpenCV 👁 | Nhận diện hành vi qua camera |
| TensorFlow / PyTorch 🤖 | Huấn luyện mô hình AI |
| MediaPipe 🖐 | Nhận diện cử chỉ và khuôn mặt |
| NumPy / Pandas 📊 | Xử lý dữ liệu |
| Matplotlib 📈 | Hiển thị kết quả |

---

## 📊 Quy trình phát hiện gian lận
Hệ thống phát hiện gian lận trong thi cử sử dụng YOLOv11, với các bước chính như sau:

1️⃣ S0: Input – Nhận video đầu vào từ camera giám sát lớp học.

2️⃣ S1: Processing – Tiền xử lý dữ liệu, chuẩn hóa và tăng cường dữ liệu.

3️⃣ S2: Detection – Nhận diện học sinh, phát hiện hành vi gian lận bằng mô hình YOLOv11.

4️⃣ S3: Alert System – Cảnh báo gian lận theo thời gian thực.

5️⃣ S4: Evidence Logging – Lưu trữ bằng chứng và xuất báo cáo.

## Sơ đồ hệ thống

![image](https://github.com/user-attachments/assets/afaca065-ed5c-4acb-b5b5-4eed9f0a14cd)

---

## 📡 Kiến trúc hệ thống  

Hệ thống phát hiện gian lận được triển khai với các thành phần chính sau:  

1️⃣ **Camera giám sát** – Ghi lại hình ảnh trong lớp học. 

2️⃣ **Máy tính xử lý** – Chạy mô hình YOLOv11 để nhận diện hành vi gian lận.  

3️⃣ **Hệ thống mạng & lưu trữ** – Truyền và lưu trữ dữ liệu trên cloud hoặc server nội bộ. 

4️⃣ **Màn hình giám sát** – Hiển thị cảnh báo, thống kê và báo cáo.  

Dưới đây là sơ đồ kiến trúc hệ thống:  

![image](https://github.com/user-attachments/assets/4183be86-6662-47ac-bc35-346b43419743)


## 🚀 Hướng dẫn cài đặt  
```sh
🔹 1️⃣ Clone Repository  
git clone https://github.com/dung-nguyenn/phat-hien-hanh-vi-gian-lan-trong-thi-cu.git
cd phat-hien-hanh-vi-gian-lan-trong-thi-cu

🔹 2️⃣ Cài đặt môi trường Python
Bạn cần Python 3.8+ và pip. Nếu chưa có, hãy cài đặt từ Python.org.
Sau đó, tạo môi trường ảo (khuyến nghị):
python -m venv venv
source venv/bin/activate  # Trên macOS & Linux
venv\Scripts\activate     # Trên Windows

🔹 3️⃣ Cài đặt các thư viện cần thiết
pip install -r requirements.txt
Nếu chưa có file requirements.txt, hãy cài đặt thủ công:
pip install opencv-python mediapipe numpy pandas tensorflow matplotlib

🔹 4️⃣ Chạy chương trình phát hiện gian lận
python detect_camera.py
📖 Cách sử dụng
🔹 Chế độ phát hiện gian lận qua camera
Hệ thống sẽ mở webcam để giám sát thí sinh.
Nếu phát hiện hành vi đáng ngờ, nó sẽ cảnh báo.
🔹 Chế độ huấn luyện mô hình
Nếu muốn huấn luyện lại AI với dữ liệu mới, chạy:
python train.py

📌 Lưu ý: Hệ thống yêu cầu webcam để hoạt động. Nếu sử dụng trên server không có camera, hãy dùng video làm đầu vào.

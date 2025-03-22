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



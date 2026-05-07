<h1 align="center">🎥 SMART CLASSROOM INTRUSION DETECTION SYSTEM</h1>
<h3 align="center">Hệ thống phát hiện xâm nhập lớp học bằng AI + Computer Vision</h3>

<div align="center">

<p align="center">
  <img src="images/logoDaiNam.png" alt="DaiNam University Logo" width="200"/>
  <img src="images/LogoAIoTLab.png" alt="AIoTLab Logo" width="170"/>
</p>

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge)
![OpenCV](https://img.shields.io/badge/OpenCV-ComputerVision-green?style=for-the-badge)
![YOLOv5](https://img.shields.io/badge/YOLOv5-ObjectDetection-red?style=for-the-badge)
![Flask](https://img.shields.io/badge/Flask-WebServer-black?style=for-the-badge)

</div>

---

## 📌 Giới thiệu

Đây là hệ thống giám sát lớp học thông minh sử dụng **AI Computer Vision** để phát hiện người xâm nhập ngoài giờ học.

Hệ thống sử dụng camera để nhận diện người theo thời gian thực bằng mô hình **YOLOv5**, sau đó tự động:

- 🚨 Phát còi cảnh báo
- 📸 Chụp ảnh xâm nhập
- 📱 Gửi cảnh báo qua Zalo
- 🌐 Hiển thị camera trên web realtime

---

## 🎯 Mục tiêu hệ thống

- Phát hiện người xuất hiện ngoài giờ học
- Tự động cảnh báo khi có xâm nhập
- Giám sát realtime qua trình duyệt
- Ứng dụng AI vào xử lý ảnh thực tế

---

## 🚀 Tính năng chính

### 🧠 AI phát hiện người
- Sử dụng YOLOv5
- Nhận diện người theo thời gian thực
- Hỗ trợ webcam/camera ngoài
- Lọc false positive

---

### 🚨 Hệ thống cảnh báo
- Phát âm thanh cảnh báo
- Cooldown chống spam
- Chụp ảnh khi phát hiện xâm nhập

---

### 📱 Gửi thông báo Zalo
- Tự động gửi qua Zalo Web/Desktop
- Gửi thời gian phát hiện
- Hoạt động realtime

---

### 🌐 Web Monitoring
- Live stream camera bằng Flask
- Theo dõi camera trên trình duyệt
- API trạng thái hệ thống

---

### 📸 Lưu ảnh xâm nhập
Ảnh được lưu tự động tại:

```bash
intrusion_images/

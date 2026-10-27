# 📦 Pimax Setup APK — Công cụ Cài đặt & Phá khóa TV Box qua Wi-Fi ADB

> Công cụ tự động hóa chuyên dụng dành cho anh em gặp tình trạng TV Box nhà mạng / ROM cook khóa phân vùng, chặn cài app ngoài (`Read-only`). Tích hợp sẵn bộ công cụ **Platform-Tools**, giao diện Đen mờ & Vàng ánh kim (`Matte Black & Neon Gold`) cực chất, không cần cài đặt phức tạp, không cần dùng cáp.

---

## 🌟 Chức năng nổi bật của phần mềm
1. **Tích hợp sẵn Platform-Tools:** Không cần tải thủ công hay giải nén lằng nhằng, công cụ ADB chạy ngầm hoàn toàn tự động.
2. **Giao diện trực quan:** Hộp thoại nhập IP tivi và vùng **Kéo thả file APK (Drag & Drop)** cực mượt.
3. **Vượt rào phân vùng khóa:** Sử dụng giao thức ADB không dây qua cổng `5555` để đẩy file thẳng vào phân vùng tạm được cấp quyền ghi (`/data/local/tmp/`), lách trọn mọi lỗi chặn từ X-plore hoặc ROM nhà mạng.
4. **Xử lý thông minh cảnh báo tivi:** Tự động nhắc nhở người dùng thao tác bấm *Cho phép / Allow* trên màn hình tivi ở lần kết nối đầu tiên.
**TẢI XUỐNG**
<div align="center">

  <a href="https://github.com/Pimax98/Pimax-Setup-APK/releases/download/v1.0.0/Pimax-Setup-APK.exe">
    <img src="https://img.shields.io/badge/TẢI%20NGAY%20PIMAX%20SETUP%20APK-(.EXE)-FFD700?style=for-the-badge&logo=windows&logoColor=black" alt="Download EXE">
  </a>

</div>
---
<img width="737" height="884" alt="PSA" src="https://github.com/user-attachments/assets/7884cf7c-cd36-4093-9dcd-52caed6d0755" />


## 🚀 Hướng dẫn sử dụng nhanh (Dành cho người mới)

### Bước 1: Chuẩn bị thiết bị & Kết nối mạng
* Đảm bảo **Laptop và TV Box** của bạn đang kết nối chung một mạng Wi-Fi (hoặc mạng LAN).
* **Nếu dùng BoxTivi thì bỏ qua bước này:**
  Trên tivi, vào mục **Cài đặt -> Giới thiệu -> Bấm 7 lần vào "Số bản dựng" (Build Number)** để mở tùy chọn nhà phát triển. Vào mục nhà phát triển, bật **Gỡ lỗi USB / ADB qua mạng**. Lấy địa chỉ IP của tivi (Ví dụ: `192.168.1.128`).

### Bước 2: Chạy phần mềm Pimax Setup APK
1. Mở ứng dụng `Pimax Setup APK` trên máy tính.
2. Nhập địa chỉ **IP của TV Box** vào ô kết nối và bấm **Kết nối (Connect)**.
3. **Lưu ý cực kỳ quan trọng:** Ngay khi bấm kết nối, hãy nhìn lên màn hình tivi, hộp thoại **"Allow USB debugging? / Cho phép gỡ lỗi USB?"** sẽ hiện lên, bạn hãy tích vào ô **"Luôn cho phép từ máy tính này"** rồi bấm **Đồng ý / Cho phép (Allow)**.

### Bước 3: Cài đặt ứng dụng
* Kéo thả file APK bất kỳ (như SmartTube, CleanTV, trình duyệt,...) vào vùng kéo thả trên phần mềm.
* Phần mềm sẽ tự động đẩy file và cài đặt thành công lên tivi trong vòng vài giây!

---

## 🧹 Tối ưu & Làm sạch tivi với CleanTV (VGS)
Để loại bỏ hoàn toàn quảng cáo rác, ứng dụng ẩn gây chậm máy và thay thế màn hình Home bằng giao diện thông minh (có lịch âm, thời tiết, đồng hồ to), bạn nên kết hợp sử dụng giải pháp chuẩn từ **CleanTV**:
* **Trang chủ chính thức:** [https://vgs.zone/cleantv](https://vgs.zone/cleantv)
* **Tính năng:** Tự động vô hiệu hóa các tiến trình quảng cáo/theo dõi của hãng (chỉ tắt an toàn, không làm hỏng hệ thống), hỗ trợ khoá trẻ em theo khung giờ, khôi phục trạng thái cũ bằng 1 chạm.

---

## 📺 Kho ứng dụng hay ho nên cài thêm cho TV Box (Dung lượng nhẹ, cực mượt)

| Tên ứng dụng | Chức năng chính | Link / Tải nhanh |
| :--- | :--- | :--- |
| **SmartTube** | Ứng dụng thay thế YouTube hoàn hảo: Chặn quảng cáo tận gốc, tự động tua đoạn tài trợ, **hỗ trợ phát nhạc nền khi tắt màn hình hoặc chuyển sang màn hình chờ**. | [Tải bản Stable mới nhất](https://github.com/yuliskov/SmartTube/releases/latest/download/smarttube_stable.apk) |
| **CleanTV (VGS)** | Dọn rác nhà mạng, thay launcher sạch, tích hợp đồng hồ, lịch âm, thời tiết theo phường xã. | [Trang chủ VGS CleanTV](https://vgs.zone/cleantv) |
| **Send Files to TV (SFTV)** | Chia sẻ file APK, hình ảnh, nhạc từ điện thoại/laptop sang tivi qua Wi-Fi với tốc độ tối đa, không cần cáp hay USB. | Tìm trên CH Play của tivi |
| **FilmPlus / OnStream** | Trùm xem phim bom tấn, truyền hình cáp chất lượng cao, có sẵn phụ đề tiếng Việt mượt mà cho Android TV. | Tải qua kho lưu trữ APK thuần |

---
*Made with 🔥 by Pimax Studio & VGS Community.*

# Thiết Kế Đồng Hồ Thời Gian Thực - Nháy LED Theo Nhạc

## Giới thiệu
Đây là dự án môn học **Nhúng Thời Gian Thực**, với đề tài **Thiết Kế Đồng Hồ Thời Gian Thực có chức năng nháy LED theo nhạc**. Dự án sử dụng **FreeRTOS** để lập trình các tác vụ thời gian thực trên vi điều khiển **Arduino Uno R3**.

Dự án được thực hiện bởi **Nhóm 1** - Lớp học phần **L04**.

## Thành viên nhóm
- **Trịnh Đăng An** - Mã số sinh viên: CT060101
- **Nguyễn Mạnh Cao Anh** - Mã số sinh viên: CT060102
- **Lê Công Bảo Ngọc** - Mã số sinh viên: CT060129

## Phần cứng sử dụng
- **Arduino Uno R3**: Vi điều khiển chính cho dự án.
- **Bảng LED P10**: Hiển thị và nháy LED theo nhạc.
- **Cảm biến âm thanh**: Thu nhận tín hiệu âm thanh từ môi trường.
- **Tiny RTC**: Đồng hồ thời gian thực để lưu trữ và xử lý dữ liệu thời gian.

## Phần mềm sử dụng
- **FreeRTOS**: Hệ điều hành thời gian thực để lập trình các tác vụ song song.
- **Arduino IDE**: Môi trường phát triển tích hợp cho lập trình Arduino.

## Chức năng
1. Hiển thị thời gian thực trên bảng LED P10.
2. Nháy LED theo nhạc dựa trên tín hiệu từ cảm biến âm thanh.
3. Quản lý thời gian chính xác bằng mô-đun Tiny RTC.

## Cách sử dụng
1. **Kết nối phần cứng**:
   - Kết nối bảng LED P10, cảm biến âm thanh và mô-đun Tiny RTC với Arduino Uno R3 theo sơ đồ mạch.
2. **Nạp code**:
   - Mở dự án trong Arduino IDE.
   - Chọn board **Arduino Uno** và cổng COM tương ứng.
   - Nạp code vào Arduino.
3. **Chạy chương trình**:
   - Cấp nguồn cho Arduino và quan sát hoạt động của bảng LED.
   - Thử phát nhạc để kiểm tra chức năng nháy LED theo nhạc.

## Yêu cầu hệ thống
- **Phần cứng**:
  - Arduino Uno R3.
  - Bảng LED P10.
  - Cảm biến âm thanh.
  - Tiny RTC.
- **Phần mềm**:
  - Arduino IDE (phiên bản mới nhất).
  - FreeRTOS (được tích hợp trong mã nguồn).

## Lưu ý
Repo được tạo ra với mục đích chia sẻ, học tập, mong mọi người hoan hỉ!

---

## Thông tin liên hệ
- **Trịnh Đăng An**: [Facebook](https://www.facebook.com/tda2811)
- **Nguyễn Mạnh Cao Anh**: [Facebook](https://www.facebook.com/cao.anh.nguyen.574932)
- **Lê Công Bảo Ngọc**: [Facebook](https://www.facebook.com/ngocga9.34)

Cảm ơn bạn đã quan tâm đến dự án của chúng tôi!

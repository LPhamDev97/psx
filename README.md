# Máy Chủ Khai Thác PS4 GoldHEN

Một máy chủ khai thác PS4 toàn diện với sự hỗ trợ cho nhiều phiên bản vi chương trình và phân phối tải trọng GoldHEN.

## Hệ Thống Lựa Chọn Máy Chủ

Trang chính cung cấp một **bộ chọn máy chủ thống nhất** nơi người dùng có thể chọn máy chủ thích hợp cho phiên bản vi chương trình PS4 của họ:

| Máy chủ | Phạm Vi Vi Chương Trình | Phương Pháp Khai Thác |
|------|----------------|----------------|
| **Máy Chủ 5.05** | 5.05 | WebKit + Khai Thác Hạt Nhân |
| **Máy Chủ 6.72** | 6.72 | WebKit + Khai Thác Hạt Nhân |
| **Máy Chủ 7.xx - 8.xx** | 7.00 - 8.52 | pOOBs4 + Lapse |
| **Máy Chủ 9.xx** | 9.00 - 9.60 | pOOBs4 + Lapse |

> **Tại sao tách riêng máy chủ cho 7.xx-8.xx và 9.xx?**
> Mặc dù cả hai phạm vi vi chương trình đều sử dụng chuỗi khai thác pOOBs4 + Lapse, cách tiếp cận kích hoạt cơ bản lại khác nhau giữa chúng. Việc tách riêng các máy chủ chuyên dụng này cho phép tối ưu hóa cụ thể theo từng phiên bản, mang lại sự ổn định và độ tin cậy tối đa cho mỗi phạm vi vi chương trình.

## Các Phiên Bản Vi Chương Trình Được Hỗ Trợ

| Phạm Vi Vi Chương Trình | Phương Pháp Khai Thác | Thư Mục Máy Chủ | Trạng Thái |
|----------------|----------------|----------------|--------|
| **5.05** | WebKit + Khai Thác Hạt Nhân | `/505` | ✅ Ổn định |
| **6.72** | WebKit + Khai Thác Hạt Nhân | `/672` | ✅ Ổn định |
| **7.00 - 7.55** | pOOBs4 + Lapse | `/700` | ✅ Ổn định |
| **8.00 - 8.52** | pOOBs4 + Lapse | `/700` | ✅ Ổn định |
| **9.00 - 9.60** | pOOBs4 + Lapse | `/900` | ✅ Ổn định |

### Các Phiên Bản Cụ Thể Của Vi Chương Trình 7.xx - 8.xx
- **7.xx**: 7.00, 7.01, 7.02, 7.50, 7.51, 7.55
- **8.xx**: 8.00, 8.01, 8.03, 8.50, 8.52

### Các Phiên Bản Cụ Thể Của Vi Chương Trình 9.xx
- **9.xx**: 9.00, 9.03, 9.04, 9.50, 9.51, 9.60

## Các Phiên Bản GoldHEN

Tất cả các phiên bản vi chương trình được hỗ trợ hiện bao gồm một **bộ chọn phiên bản GoldHEN**:

| Phiên Bản | Mô Tả |
|---------|-------------|
| **GoldHEN v2.4b18.8** | Phiên bản mới nhất với các tính năng mới nhất |
| **GoldHEN v2.4b18.5** | Phiên bản ổn định cho độ tin cậy tối đa |

Mỗi máy chủ bao gồm cả `v2.4b18.8` và `v2.4b18.5` với các hệ thống bộ nhớ đệm độc lập.

## Các Tải Trọng Có Sẵn

### Vi Chương Trình 5.05

| Tải Trọng | Tệp | Mô Tả |
|---------|------|-------------|
| GoldHEN | goldhen.bin / goldhen5.bin | Trình kích hoạt ứng dụng tự chế (v2.4b18.8 / v2.4b18.5) |
| Kernel-Clock | Kernel-Clock.bin | Các bản vá đồng hồ hệ thống |
| Máy Chủ FTP | ftp.bin | Truy cập tệp từ xa |
| PS4Debug | ps4debug.bin | Tiện ích gỡ lỗi |
| App2USB | app2usb.bin | Di chuyển ứng dụng sang bộ nhớ ngoài |
| Cài Đặt AppCache | appcache-install.bin | Trình cài đặt bộ nhớ đệm ứng dụng |
| Sao Lưu | backup.bin | Sao lưu dữ liệu lưu trữ |
| Khôi Phục | restore.bin | Khôi phục dữ liệu lưu trữ |
| Tắt Cập Nhật | disable-updates.bin | Trình chặn cập nhật hệ thống |
| Bật Cập Nhật | enable-updates.bin | Trình kích hoạt cập nhật hệ thống |
| Chặn Lịch Sử | history-blocker.bin | Bảo vệ lịch sử trình duyệt |
| Giải Mã PUP | pup-decrypt.bin | Giải mã vi chương trình |
| Đổi Tên RIF | rif-renamer.bin | Trình đổi tên tệp giấy phép |

### Vi Chương Trình 6.72

| Tải Trọng | Tệp | Mô Tả |
|---------|------|-------------|
| GoldHEN | goldhen.bin / goldhen5.bin | Trình kích hoạt ứng dụng tự chế (v2.4b18.8 / v2.4b18.5) |
| Máy Chủ FTP | ftp.bin | Truy cập tệp từ xa |
| PS4Debug | ps4debug.bin | Tiện ích gỡ lỗi |
| App2USB | app2usb.bin | Di chuyển ứng dụng sang bộ nhớ ngoài |
| Cài Đặt AppCache | appcache-install.bin | Trình cài đặt bộ nhớ đệm ứng dụng |
| Sao Lưu | backup.bin | Sao lưu dữ liệu lưu trữ |
| Khôi Phục | restore.bin | Khôi phục dữ liệu lưu trữ |
| Tắt Cập Nhật | disable-updates.bin | Trình chặn cập nhật hệ thống |
| Bật Cập Nhật | enable-updates.bin | Trình kích hoạt cập nhật hệ thống |
| Chặn Lịch Sử | history-blocker.bin | Bảo vệ lịch sử trình duyệt |
| Giải Mã PUP | pup-decrypt.bin | Giải mã vi chương trình |
| Đổi Tên RIF | rif-renamer.bin | Trình đổi tên tệp giấy phép |

### Vi Chương Trình 7.xx - 8.xx

| Tải Trọng | Tệp | Mô Tả |
|---------|------|-------------|
| GoldHEN | goldhen.bin / goldhen5.bin | Trình kích hoạt ứng dụng tự chế (v2.4b18.8 / v2.4b18.5) |
| Sửa Lỗi PSFree | ps4-psfree-fix.bin | Bản vá ổn định PSFree |
| WebRTE 9.00 | WebRTE_900.bin | Chỉnh sửa thời gian thực |
| Máy Chủ FTP | ftp.bin | Truy cập tệp từ xa |
| PS4Debug | ps4debug.bin | Tiện ích gỡ lỗi |
| App2USB | app2usb.bin | Di chuyển ứng dụng sang bộ nhớ ngoài |
| Cài Đặt AppCache | appcache-install.bin | Trình cài đặt bộ nhớ đệm ứng dụng |
| Sao Lưu | backup.bin | Sao lưu dữ liệu lưu trữ |
| Khôi Phục | restore.bin | Khôi phục dữ liệu lưu trữ |
| Tắt Cập Nhật | disable-updates.bin | Trình chặn cập nhật hệ thống |
| Bật Cập Nhật | enable-updates.bin | Trình kích hoạt cập nhật hệ thống |
| Chặn Lịch Sử | history-blocker.bin | Bảo vệ lịch sử trình duyệt |
| Giải Mã PUP | pup-decrypt.bin | Giải mã vi chương trình |
| Đổi Tên RIF | rif-renamer.bin | Trình đổi tên tệp giấy phép |

### Vi Chương Trình 9.xx

| Tải Trọng | Tệp | Mô Tả |
|---------|------|-------------|
| GoldHEN | goldhen.bin / goldhen5.bin | Trình kích hoạt ứng dụng tự chế (v2.4b18.8 / v2.4b18.5) |
| Sửa Lỗi PSFree | ps4-psfree-fix.bin | Bản vá ổn định PSFree |
| WebRTE 9.00 | WebRTE_900.bin | Chỉnh sửa thời gian thực |
| Máy Chủ FTP | ftp.bin | Truy cập tệp từ xa |
| PS4Debug | ps4debug.bin | Tiện ích gỡ lỗi |
| App2USB | app2usb.bin | Di chuyển ứng dụng sang bộ nhớ ngoài |
| Cài Đặt AppCache | appcache-install.bin | Trình cài đặt bộ nhớ đệm ứng dụng |
| Sao Lưu | backup.bin | Sao lưu dữ liệu lưu trữ |
| Khôi Phục | restore.bin | Khôi phục dữ liệu lưu trữ |
| Tắt Cập Nhật | disable-updates.bin | Trình chặn cập nhật hệ thống |
| Bật Cập Nhật | enable-updates.bin | Trình kích hoạt cập nhật hệ thống |
| Chặn Lịch Sử | history-blocker.bin | Bảo vệ lịch sử trình duyệt |
| Giải Mã PUP | pup-decrypt.bin | Giải mã vi chương trình |
| Đổi Tên RIF | rif-renamer.bin | Trình đổi tên tệp giấy phép |

## Tối Ưu Hóa Kỹ Thuật

### Tách Biệt Phiên Bản Để Ổn Định
- **Máy chủ 7.xx-8.xx chuyên dụng** (`/700`) — Được tối ưu hóa cụ thể cho quy trình kích hoạt vi chương trình 7.00–8.52
- **Máy chủ 9.xx chuyên dụng** (`/900`) — Được tối ưu hóa cụ thể cho quy trình kích hoạt vi chương trình 9.00–9.60
- **Các kịch bản khai thác độc lập** — Mỗi máy chủ sử dụng chuỗi khai thác, các bản vá hạt nhân và các tiện ích ROP được điều chỉnh riêng cho phạm vi vi chương trình mục tiêu
- **Giảm tỷ lệ thất bại** — Việc tinh chỉnh theo phiên bản cụ thể giúp loại bỏ các thỏa hiệp về khả năng tương thích chéo phiên bản

### Ngăn Ngừa Hoảng Loạn Hạt Nhân
- **Quản lý bộ nhớ được tối ưu hóa** — Dọn dẹp đúng cách các bộ đệm khai thác sau khi thực thi tải trọng
- **Cải thiện thời gian** — Tinh chỉnh độ trễ giữa các giai đoạn khai thác để đảm bảo trạng thái hạt nhân ổn định
- **Kiểm soát thu gom rác** — Các lệnh gọi GC chiến lược để ngăn ngừa tham nhũng bộ nhớ
- **Xử lý lỗi nâng cao** — Phục hồi nhẹ nhàng từ các lỗi khai thác một phần

### Độ Tin Cậy Của Chuỗi Khai Thác
- **Cải thiện độ ổn định khai thác UAF** — Tinh chỉnh các tham số phun vùng nhớ heap để khai thác nhất quán
- **Tối ưu hóa khai thác WebKit** — Giảm các khoảng thời gian tranh chấp tài nguyên
- **Tinh chỉnh chuỗi ROP hạt nhân** — Tối ưu hóa các trình tự lập trình hướng trả về
- **Cải tiến trình tải tải trọng** — Nâng cao việc tải tệp nhị phân với các kiểm tra tính toàn vẹn

### Cải Tiến Thuật Toán
- **Xác minh khai thác đa giai đoạn** — Mỗi giai đoạn xác nhận thành công trước khi tiếp tục
- **Logic tự động thử lại** — Các giai đoạn thất bại có thể được thử lại mà không cần tải lại toàn bộ trang
- **Phát hiện vi chương trình động** — Tự động chọn các phần bù và bản vá chính xác
- **Lập phiên bản tệp kê khai bộ nhớ đệm** — Đảm bảo chức năng ngoại tuyến thích hợp và ngăn chặn việc thực thi mã cũ hỏng

### Tối Ưu Hóa GoldHEN
- **Hệ thống tải kép** — Trình nạp tệp nhị phân cục bộ với dự phòng trực tuyến
- **Bộ nhớ đệm cô lập** — Các tệp kê khai bộ nhớ đệm riêng biệt cho mỗi phiên bản GoldHEN
- **Tự động kích hoạt** — Tự động thực thi khai thác ở chế độ ngoại tuyến
- **Quản lý luồng** — Tối ưu hóa việc thực thi tải trọng để ngăn ngừa sự cố

## Hỗ Trợ Ngoại Tuyến

Mỗi máy chủ bao gồm các tệp kê khai bộ nhớ đệm cho chức năng ngoại tuyến:

| Máy Chủ | Các Tệp Kê Khai |
|------|----------------|
| 505 | cache.manifest |
| 672 | cache.manifest |
| 700 | PSPulse.cache (v2.4b18.8), PSPulse5.cache (v2.4b18.5) |
| 900 | PSPulse.manifest (v2.4b18.8), PSPulse5.manifest (v2.4b18.5) |

## Cách Sử Dụng

1. Lưu trữ các tệp này trên một máy chủ web cục bộ hoặc sử dụng dịch vụ lưu trữ
2. Trên PS4 của bạn, điều hướng đến URL máy chủ bằng trình duyệt web
3. Chọn phiên bản vi chương trình của bạn từ trang chính
4. Chọn phiên bản GoldHEN ưa thích của bạn (v2.4b18.8 hoặc v2.4b18.5)
5. Làm theo hướng dẫn trên màn hình để tải GoldHEN

---

**Tác Giả:** [LÂM PHẠM](https://github.com/LPhamDev97/)  
**FACEBOOK:** [LÂM PHẠM](https://www.facebook.com/pham.lam.370316)
# BÀI LÀM – HACKATHON 01

- **Mã đề:** 13
- **Họ tên:** Huỳnh Kế Minh Quân
- **Lớp:** HCM-KS26-CNTT1
- **Link repository:** 
- **Hệ điều hành (Windows/macOS):** WINDOWS

## 4.2. Thao tác máy tính cơ bản bằng CLI

### Các lệnh đã chạy


```shell
mkdir docx
mkdir media
pwd
ls
cd docx
cp media/backup
rm .tmd
```

### Kết quả liệt kê toàn bộ dự án (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
S D:\starter-kit\starter-kit\Ngoai-Ngu-Website> Get-ChildItem -Recurse -Force


    Directory: D:\starter-kit\starter-kit\Ngoai-Ngu-Website


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/28/2026   8:14 AM                backup
d-----        10/28/2026   8:12 AM                docx
d-----        10/28/2026   8:14 AM                media
------        10/27/2026   1:31 AM             68 .env
-a----        10/27/2026   1:31 AM           2227 bai_lam.md
------        10/27/2026   1:31 AM           1117 Course.log
-a----        10/28/2026   8:25 AM              0 daily_report.txt
-a----        10/27/2026   1:31 AM           6109 Dang_Ky_Hoc_Thang_3.xlsx


    Directory: D:\starter-kit\starter-kit\Ngoai-Ngu-Website\backup


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/27/2026   1:31 AM           4365 Logo_Trung_Tam_Ngoai_Ngu.PNG


    Directory: D:\starter-kit\starter-kit\Ngoai-Ngu-Website\docx


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/27/2026   1:31 AM             67 Thoi_Khoa_Bieu.txt


    Directory: D:\starter-kit\starter-kit\Ngoai-Ngu-Website\media


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/27/2026   1:31 AM           4365 Logo_Trung_Tam_Ngoai_Ngu.PNG
PS D:\starter-kit\starter-kit\Ngoai-Ngu-Website> Get-Content Course.log
2026-03-28 08:18:28 [INFO] Giao vien cap nhat diem danh
2026-03-28 08:21:28 [INFO] Dang ky hoc thu thanh cong
2026-03-28 08:24:28 [ERROR] Het thoi gian cho (timeout)
2026-03-28 08:27:28 [INFO] Thanh toan hoc phi thanh cong
2026-03-28 08:30:28 [ERROR] Het thoi gian cho (timeout)
2026-03-28 08:33:28 [ERROR] Thanh toan hoc phi bi tu choi
2026-03-28 08:36:28 [INFO] Gui email xac nhan lop
2026-03-28 08:39:28 [ERROR] Thanh toan hoc phi bi tu choi
2026-03-28 08:42:28 [ERROR] Thanh toan hoc phi bi tu choi
2026-03-28 08:45:28 [INFO] Dang ky hoc thu thanh cong
2026-03-28 08:48:28 [INFO] Hoc vien xem lich khai giang
2026-03-28 08:51:28 [WARNING] Thoi gian tai trang cham
2026-03-28 08:54:28 [WARNING] Video bai giang dung luong lon
2026-03-28 08:57:28 [WARNING] Thoi gian tai trang cham
2026-03-28 09:00:28 [INFO] Giao vien cap nhat diem danh
2026-03-28 09:03:28 [INFO] Dang ky hoc thu thanh cong
2026-03-28 09:06:28 [INFO] Hoc vien xem lich khai giang
2026-03-28 09:09:28 [INFO] Dang ky hoc thu thanh cong
2026-03-28 09:12:28 [ERROR] Het thoi gian cho (timeout)
2026-03-28 09:15:28 [INFO] Thanh toan hoc phi thanh cong

```

## 4.3. Lọc log thủ công

### Lệnh đã chạy

```shell
# Get-ChildItem -Recurse -Force
 Get-Content Course.log
...|Select-String "ERROR"
 ls
```

### 2 dòng lỗi đầu tiên trong daily_report.txt

```text
2026-03-28 08:24:28 [ERROR] Het thoi gian cho (timeout)


```

## 4.4. Thao tác với tài liệu Markdown (README.md)

> README.md được chấm trực tiếp trên file `README.md` ở gốc dự án. Đánh dấu `[x]` vào các mục đã làm để tự kiểm tra.

- [ ] Heading 1: tên dự án
- [ ] Mô tả ngắn có cả **in đậm** và *in nghiêng*
- [ ] Bảng `Thư mục | Nội dung`, ít nhất 3 dòng dữ liệu
- [ ] Code block chứa lệnh PowerShell/Terminal liệt kê nội dung dự án
- [ ] Task list ít nhất 2 công việc, có ít nhất 1 mục đã hoàn thành
- [ ] Blockquote nhắc không upload `.env`

## 4.5. Chạy script auto_report (.ps1 hoặc .sh)

### Lệnh chạy (Windows: nếu dùng Phụ lục 2 thì ghi cả 2 lệnh)

```shell
# Ghi lệnh vào đây (xoá dòng này)

```

### Kết quả hiển thị

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.6. Đếm số dòng lỗi

### Lệnh

```shell
# Ghi lệnh vào đây (xoá dòng này)

```

### Kết quả đếm (Windows: giá trị Count; macOS: con số in ra)

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.7. Báo cáo tổng hợp

### Các lệnh đã chạy

```shell
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng (xoá dòng này)

```

### Nội dung file logs/tong_hop.txt

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.8. Excel

> Phần Excel được chấm trực tiếp trên file `data/dang_ky_hoc_thang_3.xlsx`, không cần ghi vào đây.

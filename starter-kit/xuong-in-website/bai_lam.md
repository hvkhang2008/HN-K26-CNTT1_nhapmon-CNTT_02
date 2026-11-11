# BÀI LÀM – HACKATHON 02

- **Mã đề:** 06
- **Họ tên:Hồ Văn Khang**
- **Lớp:HN-K26-CNTT1**
- **Link repository:**
- **Hệ điều hành (Windows/macOS):macOS**

## 4.2. Thao tác máy tính cơ bản bằng CLI

### Các lệnh đã chạy

```shell
- ls 
- ls -a
- cat
- cd ./xuong-in-website
- cd ./docs
- mv don_in_thang_6.xlsx
- cd ..
- mkdir backup
- cp docs/don_in_thang_6.xlsx backup
- rm temp_606.tmp
- cd ./logs
- ls
- cd ..
- ls -aR

```

### Kết quả liệt kê toàn bộ dự án (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
.			bai_lam.md		logs
..			data			web
.env			docs			yeu_cau_khach_hang.txt
backup			evidence

./backup:
.			..			don_in_thang_6.xlsx

./data:
.	..

./docs:
.			..			don_in_thang_6.xlsx

./evidence:
.	..

./logs:
.		..		order.log

./web:
.		app.js		index.html
..		images		style.css

./web/images:
.			..			logo-printnow.png
```

## 4.3. Lọc log truy cập website

### a) Lệnh lọc các dòng status=500

```shell
- cat logs/order.log

```

### 2 dòng đầu tiên trong logs/loi_500.txt

```text
2026-06-28 08:03:17 GET /dat-in status=200
2026-06-28 08:05:28 GET /css/style.css status=200

```

### b) Lệnh đếm số dòng status=404 và kết quả

```shell
 grep "logs/order.log" | wc -l

```

```text
- 

```

## 4.4. Chạy script tong_hop (.ps1 hoặc .sh)

### Lệnh chạy (Windows: nếu dùng Phụ lục 2 thì ghi cả 2 lệnh)

```shell
touch tong_hop.ps1

```

### Nội dung file logs/tong_hop.txt

```text


```

## 4.5. README.md và bảo vệ thông tin bí mật

> README.md, .gitignore và .env.example được chấm trực tiếp trên file ở gốc dự án. Đánh dấu `[x]` vào các mục đã làm để tự kiểm tra.

- [ ] README.md: Heading 1, mô tả có **in đậm** và *in nghiêng*, bảng, code block, task list, blockquote
- [ ] .gitignore có dòng `.env` (tên file đúng, không có đuôi .txt)
- [ ] .env.example có đủ tên biến, giá trị để trống (tên file đúng, không có đuôi .txt)

## 4.6. Kiểm tra trang web bằng DevTools (F12) và báo cáo lỗi

### Bảng lỗi

| STT | Tab DevTools phát hiện lỗi | Tên file hoặc thông báo lỗi | Cách khắc phục |
| --- | --- | --- | --- |
| 1 |  |  |  |
| 2 |  |  |  |

> Ảnh chụp màn hình lưu trong thư mục `evidence/` (network.png, console.png).

### Báo cáo lỗi gửi trưởng nhóm

- **Context:** 
- **Expected:** 
- **Actual:** 
- **Log:** 

### Câu tìm kiếm Google

```text
(Ghi câu tìm kiếm vào đây – xoá dòng này)

```

## 4.7. Excel

> Phần Excel được chấm trực tiếp trên file `data/don_in_thang_6.xlsx`, không cần ghi vào đây.

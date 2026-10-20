# BÀI LÀM ÔN TẬP NGÀY 1 - MÔN NHẬP MÔN CNTT

## Tự chấm điểm: ... / 100

---

## PHẦN A – TỔ CHỨC THƯ MỤC BẰNG GUI

- [x] A1. Đã bật hiển thị đuôi file và file ẩn.
- [x] A2. Đã đổi tên thư mục gốc thành `trung-tam-tieng-anh`.
- [x] A3. Đã tạo 5 thư mục: `docs`, `media`, `data`, `logs`, `archive`.
- [x] A4. Đổi tên 5 file theo chuẩn snake_case:
  - `logo_trung_tam.png`
  - `anh_lop_hoc.jpg`
  - `lich_hoc.txt`
  - `hoc_vien_khoa_3.xlsx`
  - `access.log`
- [x] A5. Đã chuyển `hoc_vien_khoa_3.xlsx` vào `data/` và `access.log` vào `logs/`.
- [x] A6. Đã sao chép `bai_lam_ngay1.md` vào thư mục gốc và giữ nguyên file `.env`.

---

## PHẦN B – THAO TÁC BẰNG CLI

### Các lệnh đã chạy :
```PS C:\Users\LENOVO\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh> pwd
PS C:\Users\LENOVO\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh> Get-ChildItem -Force
PS C:\Users\LENOVO\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh> mv .\Lich_Hoc.txt .\docs\
PS C:\Users\LENOVO\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh> mv .\Logo_Trung_Tam.PNG .\media\
PS C:\Users\LENOVO\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh> cp .\media\Logo_Trung_Tam.PNG .\archive\
PS C:\Users\LENOVO\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh> rm .\temp_201.tmp
PS C:\Users\LENOVO\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh> rm .\temp_202.tmp
PS C:\Users\LENOVO\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh> cd .\logs\
PS C:\Users\LENOVO\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh\logs> Get-ChildItem
PS C:\Users\LENOVO\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh> cd .\docs\
PS C:\Users\LENOVO\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh> Get-ChildItem -Recurse -Force 
```
### Kết quả B1 (pwd):
```
Path
----
C:\Users\ACER\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh 
```
### Kết quả liệt kê toàn bộ dự án – B8 (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR):
```
Directory: C:\Users\LENOVO\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d----          10/20/2026  5:30 PM                archive
d----          10/20/2026  5:23 PM                data
d----          10/20/2026  5:28 PM                docs
d----          10/20/2026  5:23 PM                logs
d----          10/20/2026  5:28 PM                media
-----          10/19/2026 10:04 AM             83 .env
-a---          10/19/2026 10:04 AM          13559 Anh_Lop_Hoc.JPG
-a---          10/19/2026 10:04 AM            902 bai_lam_ngay1.md

    Directory: C:\Users\LENOVO\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh\archive

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a---          10/19/2026 10:04 AM           5184 Logo_Trung_Tam.PNG

    Directory: C:\Users\LENOVO\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh\data

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a---          10/19/2026 10:04 AM           5070 Hoc_Vien_Khoa_3.xlsx

    Directory: C:\Users\LENOVO\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh\docs

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a---          10/19/2026 10:04 AM             67 Lich_Hoc.txt

    Directory: C:\Users\LENOVO\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh\logs

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a---          10/19/2026 10:04 AM           1072 Access_log.log

    Directory: C:\Users\LENOVO\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh\media

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a---          10/19/2026 10:04 AM           5184 Logo_Trung_Tam.PNG

PS C:\Users\LENOVO\Documents\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh> 
```
## Tự chấm (điền sau khi có đáp án):
-   **Điểm tự chấm:** ..../100
-   **Lỗi mình đã mắc và cách sửa:**


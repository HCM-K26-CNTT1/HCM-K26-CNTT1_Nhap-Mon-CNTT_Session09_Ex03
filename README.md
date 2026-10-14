
# HƯỚNG DẪN CÀI ĐẶT VISUAL STUDIO CODE

## 1. Mục tiêu

Tài liệu hướng dẫn sinh viên cài đặt Visual Studio Code (VS Code), làm quen với Terminal và thực hành các cú pháp Markdown cơ bản.

## 2. Giới thiệu

Visual Studio Code là trình soạn thảo mã nguồn hỗ trợ nhiều ngôn ngữ lập trình như Python, JavaScript và C++.

Trong Python, biến `name` dùng để lưu tên sinh viên, biến `age` dùng để lưu tuổi.

## 3. Các bước cài đặt VS Code

### Bước 1: Tải phần mềm

Truy cập trang web chính thức: https://code.visualstudio.com/

### Bước 2: Cài đặt

1. Mở file cài đặt vừa tải về.
2. Đồng ý với các điều khoản sử dụng.
3. Nhấn Next để tiếp tục.
4. Nhấn Install để cài đặt.
5. Nhấn Finish sau khi hoàn tất.

### Bước 3: Kiểm tra bằng Terminal

Mở Terminal hoặc Git Bash và nhập lệnh:

```bash
code --version
```

Để mở thư mục hiện tại bằng VS Code, nhập:

```bash
code .
```

Nếu Terminal báo không tìm thấy lệnh `code`, hãy kiểm tra lại quá trình cài đặt hoặc cấu hình PATH.

## 4. Ví dụ chương trình Python

Đoạn chương trình sau yêu cầu nhập tên và tuổi, sau đó hiển thị thông tin sinh viên.

```python
# Chuong trinh gioi thieu sinh vien

name = input("Nhap ten sinh vien: ")
age = int(input("Nhap tuoi: "))

print("Xin chao,", name)
print("Tuoi cua ban la:", age)

if age >= 18:
    print("Ban da du tuoi truong thanh.")
else:
    print("Ban chua du 18 tuoi.")
```

**Giải thích:**

- `name` lưu tên được nhập từ bàn phím.
- `age` lưu tuổi sau khi chuyển sang số nguyên bằng `int()`.
- `print()` dùng để hiển thị kết quả.
- `if` và `else` dùng để kiểm tra điều kiện.

## 5. Bảng so sánh StackEdit và VS Code

Bảng dưới đây so sánh hai công cụ về cách sử dụng và khả năng hỗ trợ Markdown.

| Tiêu chí | StackEdit | VS Code |
| :--- | :---: | ---: |
| Môi trường | Trình duyệt web | Phần mềm máy tính |
| Cài đặt | Có thể dùng trực tiếp trên web | Cần cài đặt phần mềm |
| Xem trước Markdown | Có | Có |
| Viết mã Python | Trình bày mã nguồn | Soạn thảo mã nguồn |
| Phù hợp với | Viết tài liệu Markdown | Học lập trình và phát triển dự án |

Trong bảng trên:

- `:---` dùng để căn trái.
- `:---:` dùng để căn giữa.
- `---:` dùng để căn phải.

## 6. Task List kiểm tra tiến độ

- [x] Truy cập trang web chính thức của VS Code.
- [ ] Tải bộ cài đặt VS Code.
- [ ] Hoàn thành cài đặt phần mềm.
- [ ] Mở VS Code thành công.
- [ ] Kiểm tra lệnh `code --version`.
- [ ] Tạo và chạy thử chương trình Python.
- [ ] Lưu tài liệu Markdown thành file `.md`.

## 7. Thực hành ký tự Escape

Markdown sử dụng một số ký tự đặc biệt để định dạng nội dung.

Ví dụ, dấu `*` có thể dùng để tạo chữ in nghiêng, còn dấu `#` có thể dùng để tạo tiêu đề.

Để hiển thị các ký tự này mà không áp dụng định dạng Markdown, có thể sử dụng dấu gạch chéo ngược `\`.

Ví dụ:

- Viết `\*Noi dung\*` để hiển thị \*Noi dung\*.
- Viết `\# Tieu de` để hiển thị \# Tieu de thay vì tạo tiêu đề.

## 8. Kết luận

Qua bài thực hành, em biết cách sử dụng Inline Code, Code Block, Syntax Highlighting, Table, Task List và Escape. Những cú pháp này giúp tài liệu hướng dẫn cài đặt VS Code rõ ràng, dễ đọc và thuận tiện khi chia sẻ.

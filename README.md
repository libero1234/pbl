# Quản Lý Thư Viện - C++

## Mô tả
Đây là chương trình quản lý thư viện đơn giản viết bằng ngôn ngữ C++. Chương trình cho phép:
- Quản lý thông tin sách (thêm, cập nhật, xóa, tìm kiếm)
- Quản lý thông tin người đọc (thêm, xóa, sửa)
- Quản lý việc mượn sách, thống kê số lượng sách đang cho mượn, liệt kê người mượn quá hạn
- Lưu trữ thông tin vào file `project.txt`

## Hướng dẫn sử dụng
1. **Biên dịch chương trình:**
   - Sử dụng lệnh: `g++ pbl.cpp -o pbl.exe` (hoặc build bằng VSCode task)
2. **Chạy chương trình:**
   - Mở file thực thi `pbl.exe` hoặc chạy trực tiếp trong VSCode
3. **Đăng nhập:**
   - Nhập mật khẩu (mỗi dòng đầu trong file `project.txt` là một mật khẩu hợp lệ)
4. **Chức năng chính:**
   - Xem danh sách sách
   - Cập nhật/xóa/tìm kiếm sách
   - Thêm/xóa/sửa thông tin người đọc
   - Xem danh sách người mượn quá hạn
   - Thống kê số lượng sách đang cho mượn

## Cấu trúc file
- `pbl.cpp` (hoặc `pbl`): mã nguồn chính
- `project.txt`: lưu thông tin người đọc và mượn sách

## Lưu ý
- Ngày mượn sách nhập theo định dạng `dd/mm/yyyy`
- Chương trình sử dụng chuẩn C++ và các thư viện chuẩn

## Đóng góp
Bạn có thể chỉnh sửa, nâng cấp hoặc mở rộng thêm các chức năng cho chương trình.

---
Tác giả: [Trần Anh Khoa]

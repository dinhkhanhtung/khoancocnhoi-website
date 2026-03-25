HƯỚNG DẪN UPLOAD WEBSITE LÊN HOST MỚI KHOANCOCNHOIGIARE.COM

CÁC BƯỚC UPLOAD:

1. Upload tất cả các file và thư mục trong thư mục này lên thư mục gốc của host mới tại khoancocnhoigiare.com
2. Đảm bảo file .htaccess được upload đúng (file này có thể bị ẩn)
3. Đảm bảo các quyền của thư mục và file được thiết lập đúng:
   - Thư mục: 755 (rwxr-xr-x)
   - File: 644 (rw-r--r--)
   - Thư mục uploads: 777 (rwxrwxrwx) để cho phép upload file
4. Sau khi upload xong, truy cập website để kiểm tra các chức năng hoạt động đúng

KIỂM TRA SAU KHI UPLOAD:

1. Kiểm tra trang chủ và các trang con để đảm bảo hình ảnh hiển thị đúng
2. Kiểm tra chức năng tìm kiếm
3. Kiểm tra chức năng đăng nhập admin tại /auth-login
4. Kiểm tra các liên kết trong menu và sidebar

XỬ LÝ SỰ CỐ:

1. Nếu có lỗi về đường dẫn, vui lòng kiểm tra lại file .htaccess
2. Nếu hình ảnh không hiển thị, kiểm tra quyền của thư mục files và uploads
3. Nếu host mới sử dụng PHP phiên bản khác, có thể cần điều chỉnh một số cài đặt trong file .htaccess

THÔNG TIN LIÊN HỆ:

Công ty TNHH xây dựng nền móng Việt Nam
Địa chỉ: 3 hẻm 70/79/1 phố Văn Trì, Minh Khai, Bắc Từ Liêm, Hà Nội
Điện thoại: 0968387568
Email: nenmongvietnam.jsc@gmail.com
Mã số thuế: 0109955008

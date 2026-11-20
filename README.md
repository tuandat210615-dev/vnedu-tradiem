# vnEdu — Cổng thông tin học tập THCS

vnEdu là dự án giao diện demo cho cổng thông tin học tập bậc trung học cơ sở. Dự án minh họa cách học sinh, giáo viên và quản trị viên tra cứu kết quả học tập và sử dụng một số tiện ích lớp học trên cùng một trang.

## Chức năng chính

- Tra cứu điểm theo học sinh, năm học và đợt đánh giá; lọc môn học, xuất CSV và in kết quả.
- Tài khoản học sinh, giáo viên và quản trị viên với các màn hình demo theo vai trò.
- Tiện ích bài tập, thông báo, điểm danh, thời khóa biểu, kế hoạch cá nhân và báo cáo lớp.
- Quản lý dữ liệu mẫu, sao lưu/khôi phục JSON và tùy chỉnh giao diện sáng/tối.
- Mục **Giới thiệu** trong ứng dụng tóm tắt mục tiêu, đối tượng sử dụng và giới hạn của bản demo.

## Dùng thử

- Website: <https://tuandat210615-dev.github.io/vnedu-tradiem/>
- Có thể mở `index.html` trực tiếp trong trình duyệt để chạy bản tĩnh.
- Thông tin tài khoản demo được cung cấp riêng; không đưa mật khẩu vào tài liệu hoặc mã nguồn.

## Công nghệ và lưu trữ

Ứng dụng được viết bằng HTML, CSS và JavaScript thuần trong một tệp `index.html`, không cần bước build. Dữ liệu demo được lưu cục bộ trong trình duyệt và không đồng bộ giữa các thiết bị. Các tệp thời khóa biểu dùng bộ nhớ trình duyệt.

## Giới hạn

Đây chỉ là bản minh họa giao diện và luồng thao tác. Tài khoản, điểm số và hồ sơ là dữ liệu mẫu; đăng nhập và phân quyền phía trình duyệt không thay thế xác thực phía máy chủ. Không nhập mật khẩu thật hoặc thông tin cá nhân của học sinh.

## Tài liệu

- [Hướng dẫn sử dụng](USER_MANUAL.md)
- [Hướng dẫn cho agent phát triển](AGENTS.md)

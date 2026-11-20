# vnEdu — User Manual

This manual describes the demo portal in `index.html`. The portal is a browser-only demo; it is not connected to a production student-information system.

## Sign in

1. Open the vnEdu portal.
2. Enter the demo username and password provided by the project owner.
3. Optionally select **Ghi nhớ đăng nhập** to keep the demo session in this browser.
4. Select **Đăng nhập**.

Do not use a real school password or real student information in this demo. The credentials and data are handled in the browser and are not protected by a production authentication service.

## Look up results

After signing in, use **Tra cứu kết quả học tập** to choose the available student, school year, and assessment period. The page shows the sample grades, attendance, and teacher comments. Use the subject search to filter the table; **Xuất CSV (Excel)** downloads the displayed results, and **In kết quả** opens the browser print flow.

Students can only look up the student record linked to their demo account. Teachers can look up records in their assigned classes. Administrators can use the demo-wide lookup and management screens.

## Student tools

- **Bài tập của tôi** — view assigned tasks and mark or unmark them as complete.
- **Thời khóa biểu** — open schedule files available for the linked class.
- **Thông báo** — read notices for the class or the whole school.
- **Thư viện học liệu** — open the listed external study resources.
- **Kế hoạch cá nhân** — add tasks, optionally set dates, mark them done, or remove them.

## Teacher tools

- **Danh sách & Lớp phụ trách** — find students in assigned classes.
- **Điểm danh lớp** — record attendance for a class and date.
- **Giao bài tập** and **Đăng thông báo** — create class tasks and notices.
- **Báo cáo lớp** — review demo counts for students, tasks, notices, and attendance.
- **Lịch giảng dạy** — add or remove schedule files for assigned classes. Supported file extensions are DOCX, XLSX, PNG, JPG/JPEG, DOC, and CSV; the upload limit is 15 MB. Files are stored in this browser.

## Administrator tools

- Manage demo accounts and student records from **Quản trị hệ thống vnEdu**.
- Use **Tổng quan**, **Quản lý thông báo**, **Nhật ký hệ thống**, and **Cấu hình** to review or edit demo data.
- **Sao lưu dữ liệu** exports a JSON backup. Restoring a backup replaces the current demo data in this browser; keep the file private and restore only a trusted backup.

## Account and appearance

Open the account menu to view **Hồ sơ & đổi mật khẩu**, return to result lookup, or sign out. The profile changes are local to the demo. Use the theme button to switch between light and dark appearance.

The **Quên mật khẩu?** flow requires a configured server and email service. It cannot reset a password when the static demo has no authentication backend configured.

## Data and limitations

- Demo accounts, student records, settings, and most activity are stored in this browser's local storage. Timetable file contents use browser storage as well.
- Data is not synchronized between browsers or devices. Clearing this site's browser data can remove demo changes.
- The displayed grades and records are sample data, not official academic results.
- Client-side login and role checks are for demonstration only. Do not enter real credentials or sensitive student data.

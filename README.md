# 📚 Nền Tảng Ôn Thi SQL  ( SQL Learning Platform)

Đây là một ứng dụng web dạng Single-Page Application (SPA) hỗ trợ học, ôn tập và thực hành ngôn ngữ truy vấn SQL hoàn toàn trực tiếp trên trình duyệt. Người dùng không cần cài đặt bất kỳ hệ quản trị CSDL nào (như MySQL hay SQL Server) mà vẫn có thể gõ code, chạy thử và nhận kết quả chấm điểm ngay lập tức.

## ✨ Tính Năng Nổi Bật

Ứng dụng được chia thành 4 phân hệ học tập chính:

* 📖 **Lý Thuyết Truy Vấn (Theory):** * Cung cấp cẩm nang SQL từ A-Z với lược đồ CSDL mẫu (Quản lý bán hàng).
    * Giải thích chi tiết cơ chế hoạt động của các mệnh đề quan trọng: `SELECT`, `JOIN`, `GROUP BY`, `HAVING`, `IN/NOT IN`, và truy vấn lồng (Subquery).
    * Tích hợp bài tập rèn luyện (Lý thuyết & Thực hành) dạng đóng/mở đáp án thông minh.
* 💻 **Thực Hành Code (Coding Practice):**
    * Trình soạn thảo code chuyên nghiệp tích hợp **CodeMirror**.
    * Tính năng Autocomplete (Gợi ý code) thông minh: Bấm `Ctrl + Space` hoặc gõ dấu `.` sau tên bảng để hiển thị danh sách từ khóa SQL và tên cột tương ứng.
    * Chạy câu lệnh SQL và so sánh bảng kết quả với đáp án chuẩn. Thông báo **"CHÍNH XÁC"** hoặc **"LỖI"** ngay tại thời gian thực.
    * Ghi nhớ lịch sử code đang gõ dở trên từng bài tập.
* 📝 **Luyện Trắc Nghiệm Tổng Hợp (Quiz):**
    * Ngân hàng 65 câu hỏi trắc nghiệm bao phủ toàn bộ kiến thức về CSDL Quan hệ, dạng chuẩn (1NF, 2NF, 3NF), phụ thuộc hàm, khóa, và hệ tiên đề Armstrong.
    * Hiển thị ngay đáp án đúng/sai và bung hộp thoại **Giải thích chi tiết** lý do chọn đáp án đó.
* ⏱️ **Kiểm Tra Trắc Nghiệm (Mock Test):**
    * Môi trường thi thử nghiêm túc: Đánh dấu xanh (Answered) các câu đã làm trên thanh điều hướng.
    * Chỉ chấm điểm tổng kết và báo cáo kết quả (VD: `50/65`) sau khi người dùng bấm nút **Nộp bài & Chấm điểm**. Cảnh báo nếu còn câu chưa làm.

## 🛠️ Trợ Thủ Đắc Lực Tích Hợp
* **Từ Điển Thuật Ngữ:** Hộp thoại đóng/mở nhanh giúp dịch nghĩa toàn bộ tên bảng và tên cột tiếng Anh sang tiếng Việt của các hệ thống quản lý.
* **Sơ đồ ERD Động:** Tự động tải và hiển thị sơ đồ quan hệ thực thể (ERD) từ Google Drive tương ứng với cơ sở dữ liệu đang chọn.

## 🗄️ Các Cơ Sở Dữ Liệu Tích Hợp Sẵn
Ứng dụng đi kèm với 5 bộ CSDL thực tế để thực hành:
1.  **Quản lý Dự án (lab03)**: Nhân viên, Phòng ban, Đề án.
2.  **Quản lý Thư viện (library)**: Sách, Tác giả, Độc giả, Phiếu mượn, Đóng phạt.
3.  **Quản lý Chuyến bay (flight)**: Hãng bay, Máy bay, Sân bay, Chuyến bay, Vé.
4.  **Quản lý Sở thú (zoo)**: Khu vực, Chuồng trại, Thức ăn, Động vật, Người chăm sóc.
5.  **Quản lý Bán xe Ô tô (car)**: Thương hiệu, Dòng xe, Xe, Khách hàng, Giao dịch.
6.  
## ⚙️ Hướng Dẫn Cài Đặt & Sử Dụng

Vì ứng dụng không yêu cầu server backend, việc sử dụng vô cùng đơn giản:

1.  **Chạy Offline trên máy tính cá nhân:**
    * Tải file `index.html` về máy tính.
    * Click đúp chuột để mở file bằng bất kỳ trình duyệt web hiện đại nào (Google Chrome, Microsoft Edge, Safari, Firefox,...)
    * Ấn vào đường dẫn sau https://dungcodepy.github.io/SQL-Learning-with-gitlab/

---
*Chúc các bạn ôn tập tốt và chinh phục thành công ngôn ngữ SQL!* 🏆

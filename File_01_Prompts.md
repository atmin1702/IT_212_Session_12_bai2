### Prompt 1 (Xây dựng khung tài liệu và Mô tả tổng quan):
"Đóng vai là một Senior Business Analyst đang làm việc tại ABC Bank. Ngân hàng đang xây dựng phân hệ eKYC (định danh điện tử tự động) cho hệ thống ngân hàng số. Hãy viết Phần 1 và Phần 2 của tài liệu Software Requirements Specification (SRS) theo chuẩn IEEE cho phân hệ eKYC này.

Yêu cầu cấu trúc:
Phần 1: Introduction (Giới thiệu chung)
- Purpose (Mục đích tài liệu).
- Scope (Phạm vi hệ thống eKYC).
- Definitions, Acronyms (Định nghĩa các thuật ngữ như eKYC, OCR, Liveness Check...).

Phần 2: Overall Description (Mô tả tổng quan)
- Product Perspective (Góc nhìn sản phẩm).
- User Classes and Characteristics (Đặc điểm người dùng).
- Constraints (Các giới hạn về luật pháp, công nghệ)."

### Prompt 2 (Xây dựng Yêu cầu chức năng và Phi chức năng):
"Đóng vai là một Senior Business Analyst. Hãy viết Phần 3 và Phần 4 (thuộc tài liệu Software Requirements Specification - SRS) nhằm mô tả chi tiết Yêu cầu hệ thống cho phân hệ eKYC của ngân hàng ABC Bank.

Yêu cầu cấu trúc:
Phần 3: Specific Functional Requirements (Yêu cầu chức năng chi tiết)
Phân rã thành các module chính và liệt kê yêu cầu cho từng module:
1. Đăng ký tài khoản (xác thực OTP).
2. Upload & Đọc CCCD bằng công nghệ AI (OCR).
3. Xác thực khuôn mặt (Liveness Check & Face Matching).
4. Kích hoạt tài khoản (Duyệt tự động hoặc Chờ Admin duyệt thủ công).

Phần 4: Non-Functional Requirements (Yêu cầu phi chức năng)
Chỉ rõ các tiêu chuẩn về:
- Security (Bảo mật dữ liệu cá nhân, Encryption).
- Performance (Thời gian phản hồi API, thời gian xử lý hệ thống OCR).
- Availability (Tính sẵn sàng của hệ thống, Auto-scaling)."

### Prompt 3 (Sinh sơ đồ trực quan Mermaid):
"Đóng vai là một Senior Business Analyst. Hệ thống eKYC của ngân hàng ABC Bank bao gồm các luồng thao tác chính: Khách hàng đăng ký bằng số điện thoại, chụp ảnh hai mặt CCCD (để bóc tách OCR), và quét khuôn mặt (Liveness Check). Hệ thống AI tự động xử lý và quyết định duyệt hồ sơ; nếu có nghi ngờ sẽ chuyển hồ sơ cho Admin kiểm duyệt thủ công.

Nhiệm vụ:
- Hãy viết mã Mermaid (Mermaid code) để vẽ một Use Case Diagram (hoặc sơ đồ Flowchart mô phỏng Use Case).
- Sơ đồ phải hiển thị rõ các tác nhân: Khách hàng (User), Hệ thống AI/eKYC (System), và Quản trị viên (Admin) cùng các hành động tương ứng của họ.
- Yêu cầu mã Mermaid chuẩn cú pháp, có thể render trực tiếp thành hình ảnh minh họa đẹp mắt trong tài liệu Markdown."

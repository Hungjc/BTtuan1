# BÀI TẬP TUẦN 1 - LẬP TRÌNH DI ĐỘNG

**Họ và tên:** Trần Quốc Hưng  
**MSSV:** 080206000807

---

## PHẦN 1: ĐỊNH HƯỚNG BẢN THÂN VÀ TƯƠNG LAI LẬP TRÌNH DI ĐỘNG

### 1. Mong muốn và định hướng sau khi học xong môn học
- **Mong muốn:** Nắm vững ngôn ngữ Kotlin, thành thạo tư duy thiết kế giao diện hiện đại với Jetpack Compose và hiểu rõ quy trình phát triển một ứng dụng Android hoàn chỉnh.
- **Định hướng:** Phát triển bản thân theo hướng Android Developer chuyên nghiệp, có khả năng tự xây dựng các sản phẩm cá nhân và tham gia vào các dự án thực tế tại doanh nghiệp.

### 2. Đánh giá sự phát triển của Lập trình di động trong 10 năm tới
- **Đánh giá:** Lập trình di động vẫn sẽ tiếp tục phát triển mạnh mẽ và giữ vị thế cốt lõi trong ngành công nghệ thông tin.
- **Giải thích lý do:**
    1. **Trung tâm trải nghiệm số:** Smartphone vẫn là thiết bị cá nhân gắn liền nhất với đời sống con người (tài chính, giải trí, làm việc, mua sắm).
    2. **Bảng điều khiển cho AI và IoT:** Các ứng dụng di động sẽ đóng vai trò là giao diện điều khiển chính cho các thiết bị thông minh (Smart Home, Wearables) và tích hợp AI trực tiếp trên thiết bị (On-device AI).
    3. **Công nghệ không ngừng đổi mới:** Sự tiến hóa của các framework giúp việc phát triển ứng dụng di động ngày càng nhanh, mượt mà và an toàn hơn.

---

## PHẦN 2: TÌM HIỂU MÔ HÌNH GIÁO DỤC HAA VÀ XU THẾ LẬP TRÌNH HIỆN NAY

### 1. Mô hình giáo dục HAA (Horowitz Andreessen Academy)
-Là mô hình đào tạo theo hướng thực chiến (Project-based & Builder Mindset), tập trung vào việc học thông qua làm sản phẩm thực tế, hướng đến nhu cầu thực sự của thị trường thay vì học lý thuyết hàn lâm.
- **Ưu điểm:**
    
    Học nhanh, sát với thực tế doanh nghiệp.
    
     Rèn luyện tư duy tạo ra sản phẩm (Product Mindset) ngay từ đầu.
    
     Tăng khả năng tự giải quyết vấn đề chuyên sâu.
- **Nhược điểm:**

      Đòi hỏi tinh thần tự học và tính chủ động rất cao.
      
      Dễ hổng kiến thức nền tảng nếu người học không tự bổ sung lý thuyết gốc.

### 2. Sự thay đổi cách tiếp cận tri thức (Trước Internet - Thời Internet - Thời AI tạo sinh)

| Tiêu chí | Trước khi có Internet | Thời kỳ Internet phổ biến | Thời kỳ AI tạo sinh (Hiện nay) |
| :--- | :--- | :--- | :--- |
| **Tìm kiếm** | Tra cứu thủ công qua sách, thư viện, hỏi người đi trước (tốn nhiều thời gian). | Tìm kiếm từ khóa qua Google, đọc tài liệu, diễn đàn (StackOverflow, Blog). | Tương tác dạng đối thoại, nhận câu trả lời tổng hợp/code mẫu tức thì từ AI. |
| **Ghi nhớ** | Phụ thuộc vào trí nhớ cá nhân, ghi chép ra sổ sách thủ công. | Lưu trữ số hóa (Bookmark, Note, Google Drive), truy xuất khi cần. | AI đóng vai trò như bộ nhớ mở rộng, truy xuất và tóm tắt tri thức theo ngữ cảnh. |
| **Vận dụng** | Mày mò tự làm từ đầu, thử và sai hoàn toàn thủ công. | Học theo các bài hướng dẫn (Tutorial), sao chép và chỉnh sửa code mẫu. | Đồng sáng tạo cùng AI (Co-pilot), nhờ AI hỗ trợ viết code, sửa lỗi và tối ưu. |

### 3. Chúng ta cần học gì khi AI có thể làm gần như mọi thứ?
1. **Tư duy kiến trúc & Hệ thống (System Architecture):** Học cách kết nối các thành phần, quản lý luồng dữ liệu và thiết kế hệ thống lớn mà AI chưa thể tự quyết định toàn diện.
2. **Kỹ năng đặt vấn đề & Prompting:** Học cách mô tả chính xác yêu cầu, bối cảnh để điều khiển AI tạo ra kết quả mong muốn.
3. **Tư duy sản phẩm (Product Mindset) & UX:** Học cách hiểu tâm lý người dùng, tạo ra sản phẩm thực sự giải quyết nhu cầu con người.

### 4. Những năng lực cần phát triển trong thời đại AI & Lý do quan trọng
- **Năng lực tư duy phản biện (Critical Thinking):** Đánh giá, kiểm tra tính đúng đắn của dữ liệu/code do AI tạo ra (tránh lỗi ảo giác - hallucination của AI).
- **Năng lực giải quyết vấn đề phức tạp (Complex Problem Solving):** AI giỏi xử lý tác vụ lẻ, nhưng con người cần kết nối để giải quyết bài toán thực tế phức tạp.
- **Khả năng học liên tục & Thích ứng (Adaptability):** Công cụ công nghệ thay đổi liên tục, năng lực tự học giúp lập trình viên không bị đào thải.
- *Lý do quan trọng:* AI là công cụ tăng năng suất, nhưng con người mới là bên đưa ra quyết định, chịu trách nhiệm về chất lượng sản phẩm và giá trị thực tế.


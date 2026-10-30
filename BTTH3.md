# 1. Sơ đồ kiến trúc kênh

Không gian số được chia làm 3 kênh (Channel) tách biệt hoàn toàn mục đích sử dụng:

*   📢 **`#announcements` (Bảng tin thông báo):**
    *   *Nội dung:* Lịch họp, chốt deadline, báo cáo tiến độ tổng.
    *   *Quy định:* Chỉ Trưởng nhóm được đăng bài. Thành viên cấm không nhắn tin tán gẫu ở đây, chỉ được phép thả Emoji (👍, ✅) để xác nhận đã đọc.
*   💻 **`#dev-tech` (Phòng Kỹ thuật & Cảm biến):**
    *   *Nội dung:* Gửi tài liệu API, báo lỗi cảm biến, trao đổi logic code.
    *   *Quy định:* Các vấn đề/lỗi phải được gom nhóm. Bắt buộc dùng **Reply in Thread** cho từng luồng thảo luận riêng biệt để giữ màn hình chính sạch sẽ.
*   ☕ **`#random-chat` (Giải trí / Trà nước):**
    *   *Nội dung:* Tán gẫu, gửi ảnh meme hài hước, rủ ăn uống.
    *   *Quy định:* Tự do thảo luận, không gò bó luật lệ, giúp giải tỏa áp lực mà không làm trôi tin nhắn công việc.

---

# 2. Bản quy ước giao tiếp: 3 Quy tắc Vàng

*   **Quy tắc 1: Viết 1 tin trọn vẹn (Chống "No-Hello"):**
    Tuyệt đối không nhắn "Alo bạn ơi..." rồi đợi rep. Phải viết đủ ngữ cảnh để người khác đọc là hiểu ngay. 
*   **Quy tắc 2: Luôn dùng Reply in Thread:**: Khi có người báo lỗi cảm biến, toàn bộ câu trả lời, phân tích, hay xin file đều phải được nhắn vào luồng phụ (Thread) ngay bên dưới tin nhắn gốc. 
*   **Quy tắc 3: Cấm lạm dụng `@all` và Ưu tiên Reaction:**
    *   Chỉ tag đích danh người chịu trách nhiệm. VD: `@Hải kiểm tra cảm biến`. 
    *   Cấm dùng `@all` hoặc `@channel` bừa bãi làm phiền người không liên quan.
    *   Khi nhận được thông báo, chỉ cần **thả Emoji** (👍, 👀, ✅) thay vì gõ chữ "Ok, đã nhận" để tránh tạo ra dòng tin nhắn rác gây trôi màn hình.
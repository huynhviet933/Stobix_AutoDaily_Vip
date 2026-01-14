# Stobix_AutoDaily_Vip

Aidrop Free : https://t.me/HVchannelss/251


Tham Gia Discor ( Vip ) : https://discord.gg/gKxvTNu5

Tham gia NHóm VIp Với Chi Phí 8u/1thang Lợi ích tham gia nhóm ViP Sẽ được cấp keey sử dụng các tool vip trong discor hỗ trợ Và tham khao Code các tool dự án mà các bạn đề xuất

Gửi Phí tháng vào đây và chụp hình gửi trực tiếp cho tôi tại discor để xác nhận Role VIp ☕ https://huynhviet933.github.io/donate_viet_mmo/ Có thể tặng tôi ít cafe tại đây
<img width="1920" height="1080" alt="Screenshot (32)" src="https://github.com/user-attachments/assets/32b31e2c-190c-4e52-ab2d-02c1fca2839b" />

# HƯỚNG DẪN CÀI ĐẶT VÀ SỬ DỤNG STOBIX AUTO

### Bước 1: Cài đặt môi trường (Node.js)
Bạn cần cài đặt Node.js trên máy tính (Tải tại: https://nodejs.org/). Sau khi cài xong, mở Terminal/Command Prompt và chạy lệnh sau để cài đặt các thư viện hỗ trợ:

npm install axios ethers@5.7.2 https-proxy-agent readline

### Bước 2: Chuẩn bị các file dữ liệu (.txt)
Bạn cần tạo các file sau trong cùng thư mục với file script của bạn. Định dạng nội dung như sau:

1. Tạo file: `privatekey.txt`
   - Nội dung: Mỗi dòng 1 Private Key ví (Ví dụ: 0xabc123...)

2. Tạo file: `proxy.txt`
   - Nội dung: Mỗi dòng 1 Proxy (Định dạng: http://user:pass@ip:port hoặc ip:port)

3. Tạo file: `user.txt`
   - Nội dung: Mỗi dòng 1 Username Discord tương ứng với thứ tự ví (Ví dụ: @tai_khoan_1)

4. Tạo file: `user_agents.txt`
   - Nội dung: Mỗi dòng 1 chuỗi User-Agent trình duyệt (Có thể copy từ Chrome hoặc tìm trên mạng).

### Bước 3: Lưu trữ cấu trúc thư mục
Đảm bảo thư mục của bạn có các file sau:
├── main.js             (Dán nội dung code chính của bạn vào đây)
├── profilemanager.js   (Dán nội dung code profilemanager bạn đã cung cấp)
├── privatekey.txt      (Chứa khóa bí mật)
├── proxy.txt           (Chứa danh sách proxy)
├── user.txt            (Chứa tên Discord)
└── user_agents.txt     (Chứa danh sách User-Agent)

### Bước 4: Chạy Tool
1. Mở Terminal tại thư mục đó.
2. Gõ lệnh: node main.js
3. Nhập License Key khi được hỏi.
4. Nhập số luồng (Threads) muốn chạy (Ví dụ: 5).

### LƯU Ý QUAN TRỌNG:
- Thư viện Ethers: Script của bạn sử dụng cú pháp của phiên bản cũ, hãy cài đúng bản `ethers@5.7.2` để tránh lỗi.
- File profilemanager.js: Phải được đặt đúng tên này vì script chính gọi `require("./profilemanager")`.
- License: Bạn cần có Key hợp lệ từ Server "onrender.com" như trong code đã quy định.

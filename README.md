# Personal Portfolio

Đây là kho lưu trữ chứa toàn bộ portfolio của mình.  
Trang web được xây dựng dưới dạng website tĩnh và triển khai tự động qua hệ thống GitHub Pages.

**Trang web:** https://caolephucthinh2203.github.io/

---

## 1. Công nghệ sử dụng

**Công cụ xây dựng & đóng gói:** Vite
**Khung giao diện (CSS Framework):** Tailwind CSS (phiên bản 4)
**Thư viện hiệu ứng chuyển động:** ScrollReveal.js
**Hạ tầng triển khai (CI/CD & Hosting):** GitHub Actions kết hợp GitHub Pages

---

## 2. Tính năng kỹ thuật

**Giao diện đáp ứng (Responsive Design):** Bố cục được tối ưu theo quy chuẩn Mobile-First, hiển thị đồng nhất trên nhiều kích thước màn hình.
**Tông màu Dark Mode:** Sử dụng bảng mã màu tối tập trung vào độ tương phản văn bản và khả năng đọc nội dung.
**Quy trình triển khai tự động (CI/CD):** Tích hợp GitHub Actions workflow, tự động cài đặt thư viện phụ thuộc, biên dịch dự án và phát hành bản build tĩnh (`dist/`) lên môi trường production khi có commit mới trên nhánh `main`.

---

## 3. Hướng dẫn thiết lập môi trường phát triển (Local Development)

### Yêu cầu hệ thống

* Node.js (phiên bản 18 trở lên)
* npm hoặc trình quản lý gói tương đương

### Các bước thực hiện

1. Sao chép kho lưu trữ về máy tính:
   ```bash
   git clone https://github.com/CaoLePhucThinh2203/CaoLePhucThinh2203.github.io.git
   cd CaoLePhucThinh2203.github.io
   ```

2. Cài đặt các gói phụ thuộc:
   ```bash
   npm install
   ```

3. Khởi chạy máy chủ phát triển cục bộ:
   ```bash
   npm run dev
   ```

4. Kiểm tra biên dịch bản phát hành:
   ```bash
   npm run build
   ```

---

## 4. Thông tin liên hệ

Cao Lê Phúc Thịnh  
Viện Nghiên cứu và Đào tạo Việt - Anh (VNUK), Đại học Đà Nẵng  
**Email:** caolephucthinh2203@gmail.com  
**GitHub:** https://github.com/CaoLePhucThinh2203
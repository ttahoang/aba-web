# aba-cooltrans-web

Demo giao diện Web cho hệ thống Quản lý Thông tin ABA Cooltrans

## Cấu trúc thư mục

aba-web/  
├── index.html            – Dashboard tổng quan  
├── order_create.html     – Tạo đơn hàng mới  
├── fleet_tracking.html   – Giám sát đội xe  
├── sensor_monitor.html   – Theo dõi cảm biến kho/xe  
├── report.html           – Báo cáo & cảnh báo  
├── login.html            – Đăng nhập  
├── css/  
│   └── style.css         – Style chung  
└── assets/  
    └── logo.png          – Logo công ty

## Cách chạy

1. Bật GitHub Pages:  
   - Vào Settings → Pages  
   - Chọn branch `main`, folder `/aba-web`  
   - Save, đợi 1–2 phút, truy cập  
     `https://ttahoang.github.io/aba-cooltrans-web/aba-web/`

2. Dùng trình duyệt mở trực tiếp file `index.html` nếu không bật Pages.

## Ghi chú

- Các biểu đồ và bản đồ đang ở dạng placeholder, bạn có thể tích hợp Chart.js hoặc Leaflet/Google Maps cho hoàn chỉnh.  
- Đây chỉ là demo giao diện tĩnh, bạn có thể thêm React/Vue để tăng tính tương tác.

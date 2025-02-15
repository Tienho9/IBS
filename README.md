# Hệ Thống Quản Lý Tài Chính Cá Nhân 🚀

## Giới thiệu 

Hệ thống Quản lý Tài Chính Cá Nhân là một nền tảng thông minh giúp người dùng theo dõi thu nhập, chi tiêu, phân tích tài chính và lập kế hoạch tài chính cá nhân. Hệ thống tích hợp chatbot AI, workflow tự động hóa và các công cụ phân tích dữ liệu để nâng cao trải nghiệm người dùng.

## Tính năng chính 

- Quản lý thu nhập & chi tiêu: Ghi chép và phân loại giao dịch theo danh mục.

- Phân tích dữ liệu tài chính: Sử dụng Superset để trực quan hóa số liệu.

- Cảnh báo tài chính: Thông báo khi chi tiêu vượt mức hoặc có biến động tài khoản.

- Chatbot AI tư vấn tài chính: Hỗ trợ người dùng quản lý tài chính cá nhân.

- Tích hợp Telegram Bot: Nhận thông báo giao dịch và nhắc nhở tài chính.

- Tự động hóa workflow: Sử dụng n8n để đồng bộ giao dịch ngân hàng và nhắc nhở tự động.

## Công nghệ sử dụng 
- Laravel
- MySQL
- Nextjs
- N8N
- Superset

- Các gói cần thiết cho hệ thống:
  + Mysql
  + Php >= 8.2
  + Composer >= 2.8
  + Nodejs >= 20.x
- Cách cài đặt:
  + Vào folder backend: sửa thông tin env như thông tin database, cài đặt thư viện bằng lệnh "composer install" => "php artisan migrate" => "php artisan db:seed"
  + Vào folder frontend: Thêm file .env.local thêm thuộc tính NEXT_PUBLIC_API_URL= điền domain backend vào, cài thư viện bằng lệnh "npm install"
  + Lệnh chạy backend: "php artisan server", lệnh chạy frontend: "npm run dev"



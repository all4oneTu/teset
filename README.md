## Cấu trúc project
### Frontend
```
.  
├── docs  
│   ├── versions.md    // thư mục chứa file migrations  
│   └── webpack.md
├── node_modules
├── public
├── src 
│   ├── api         // các file api được đặt trong này
│   ├── assets      // lưu trữ hình ảnh, svg, font
│   ├── components      // các thành phần giao diện người dùng
│   ├── config        // chứa file config load
│   ├── router        // các router chính của dự án
│   ├── views       // các layout chính của dự án
│   ├── App.vue       // trang gốc của dự án
│   └── main.js     // cấu hình chính của toàn bộ project  
├── tests  
├── .gitignore  
├── alembic.ini  
├── docker-compose.yaml  
├── Dockerfile  
├── env.example  
├── README.md
├── package.js   // file chứa các thư viện để cài đặt qua pip install
└── vue.config.js    
```
### Backend
```
.  
├── src 
│   ├── controller         // quản lí và xử lý các yêu cầu từ người dùng
│   ├── entity      // mô hình hóa và biểu diễn các các dữ liệu
│   ├── enums      // định nghĩa các dữ liệu cố định
│   ├── config        // chứa file config load
│   ├── repository     
│   ├── service    
│   ├── utils       
│   └── main.js
├── appApplication.java
```

# Tháp biên giới - tháp cho cá ăn

## Cấu trúc dự án: 
- /server: server của dự án
- /web: web client của tháp biên giới
- /web2: web client của tháp cho cá ăn

## Yêu cầu cài đặt: 
- NodeJS
- MongoDB
- Yarn

## Setup: 
- Tại thư mục gốc chạy lệnh `yarn` để cài đặt hết thư viện
- Tạo file `.env` ứng với mỗi file `.env.example` có sẵn 
(nội dung các Key y hệt file `.env.example` tương ứng)
- Chi tiết các key: 
    - Server: 
        - NODE_ENV: development
        - PORT: cổng chạy server, giá trị mặc định `3001`
        - DB_URI: đường dẫn đến mongoDB, giá trị mặc định `mongodb://localhost:27017/thap-nang-luong`
    - Web:  
        - NODE_ENV: development
        - PORT: cổng chạy web client tháp biên giới, giá trị mặc định `3000`
        - REACT_APP_GRAPHQL_URI: đường dẫn đến server Graphql, giá trị mặc định `http://localhost:3001/graphql`
    - Web2: 
        - NODE_ENV: development
        - PORT: cổng chạy web client tháp biên giới, giá trị mặc định `3002`
        - REACT_APP_GRAPHQL_URI: đường dẫn đến server Graphql, giá trị mặc định `http://localhost:3001/graphql`

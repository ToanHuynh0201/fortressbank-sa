# FortressBank SA

Đây là một dự án ứng dụng ngân hàng với kiến trúc microservices. Nó bao gồm ít nhất hai dịch vụ: Dịch vụ tài khoản và Dịch vụ người dùng.

## Công nghệ chính

- **Backend:** Backend có thể được triển khai bằng ngôn ngữ sử dụng đặc tả OpenAPI, chẳng hạn như Java với Spring Boot, Python với FastAPI hoặc Node.js với Express.
- **API:** Ứng dụng cung cấp các API REST để quản lý tài khoản và người dùng, được định nghĩa trong các đặc tả OpenAPI trong thư mục `API/`.
- **Cơ sở dữ liệu:** Lược đồ cơ sở dữ liệu được thiết kế cho một cơ sở dữ liệu quan hệ.

## API

Các đặc tả API tuân theo tiêu chuẩn OpenAPI 3.0.3.

- **Dịch vụ tài khoản:** [API/accounts-api.yaml](API/accounts-api.yaml)
- **Dịch vụ người dùng:** [API/users-api.yaml](API/users-api.yaml)

## Cơ sở dữ liệu

Lược đồ cơ sở dữ liệu được định nghĩa trong `database.txt`.

Sơ đồ quan hệ thực thể của cơ sở dữ liệu có sẵn ở đây: [ERD_Diagram_Database.png](ERD_Diagram_Database.png)

Bạn cũng có thể tìm thấy:
-Sơ đồ cơ sở dữ liệu tại liên kết này: https://dbdiagram.io/d/68d376e47c85fb996111338e
-Kiến trúc hệ thống tại liên kết này: https://www.mermaidchart.com/app/projects/a028bd8c-f2c5-4ba0-878b-c607d36fff94/diagrams/9ac2ced2-cf1f-4bc2-acb5-c90fb3c5dac4/version/v0.1/edit

## Làm thế nào để bắt đầu

**Cần làm:** Các lệnh xây dựng và chạy không có sẵn trong các tệp được cung cấp.

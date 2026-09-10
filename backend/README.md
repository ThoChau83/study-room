# Study Room - Backend

Backend API server cho ứng dụng Study Room.

## Tech Stack

- **Java 21**
- **Spring Boot 4.1.1**
- **Spring Security** — Xác thực & phân quyền
- **Spring Data JPA** — ORM & truy vấn database
- **Spring WebSocket** — Giao tiếp realtime
- **MySQL** — Cơ sở dữ liệu
- **Lombok** — Giảm boilerplate code
- **Maven** — Quản lý dependency & build

## Cấu trúc thư mục

```
study-room-backend/
├── src/main/java/com/lofi/studyroombackend/
│   ├── config/          # Cấu hình (Security, WebSocket,...)
│   ├── controller/      # REST API controllers
│   └── StudyRoomBackendApplication.java
├── src/main/resources/
│   └── application.properties
└── pom.xml
```

## Yêu cầu

- JDK 21+
- MySQL 8+
- Maven 3.9+

## Chạy ứng dụng

```bash
cd study-room-backend
./mvnw spring-boot:run
```

Server sẽ chạy tại `http://localhost:8080`.

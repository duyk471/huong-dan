# Java Backend

### Giai đoạn 1: Nền tảng Java vững chắc

> Nếu bạn đã học rồi thì có thể học lướt qua, còn nếu chưa thì nên học kỹ.

- Biến, kiểu dữ liệu, toán tử
- Vòng lặp, rẽ nhánh
- Hàm, mảng, chuỗi
- OOP (quan trọng):
  - Class, Object
  - Kế thừa, Đa hình, Trừu tượng
  - Interface, Encapsulation
- Exception Handling
- Collection Framework (List, Map, Set)
- Lambda, Stream API (Java 8+)

📌 _Công cụ_: IntelliJ hoặc Eclipse
📌 _Tài liệu_: [Java Programming Masterclass (Udemy)](https://www.udemy.com/course/java-the-complete-java-developer-course/) | [W3Schools Java](https://www.w3schools.com/java/)

### Giai đoạn 2: Làm quen Spring Boot

- Spring là gì? Spring Boot là gì?
- Tạo project bằng [Spring Initializr](https://start.spring.io/)
- Cấu trúc dự án chuẩn
- Dependency injection (DI), Inversion of Control (IoC)
- Annotation cơ bản: `@RestController`, `@Service`, `@Repository`, `@Autowired`
- Cấu hình application.yml hoặc application.properties

📌 _Thực hành_: Viết một ứng dụng HelloWorld REST API

### 🧩 Giai đoạn 3: Kiến trúc và làm việc với CSDL

- Kiến trúc chuẩn: Controller → Service → Repository
- ORM với Spring Data JPA + Hibernate
- Entity – Mapping (OneToMany, ManyToOne, v.v.)
- Repository Interface: `JpaRepository`
- Truy vấn: Native SQL, JPQL, Derived Query

📌 _Cơ sở dữ liệu_: PostgreSQL hoặc MySQL

📌 _Công cụ_: DBeaver hoặc PgAdmin để quản lý DB

### 🔐 Giai đoạn 4: Xử lý API và bảo mật

- Viết RESTful API chuẩn
- Validate dữ liệu đầu vào: `@Valid`, `@NotNull`, `@Email`,...
- Exception Handling: `@ControllerAdvice`, `@ExceptionHandler`
- Swagger để test API
- Spring Security cơ bản

  - Cấu hình login, logout
  - Role-based authorization
  - JWT (Json Web Token) cho login API

- CORS config để mở kết nối cho Frontend

📌 _Thực hành_: Tạo hệ thống đăng ký – đăng nhập – phân quyền

### 🧪 Giai đoạn 5: Testing và Clean Code

- Unit test với JUnit 5
- Mocking với Mockito
- Viết test cho Service và Repository
- Cấu trúc code sạch: DTO, Mapper, Service Layer rõ ràng

📌 _Tips_: Dùng ModelMapper hoặc MapStruct để convert DTO – Entity

### 🚀 Giai đoạn 6: Deploy và thực chiến

- Build file `.jar`
- Deploy app lên:

  - Railway / Render / Heroku
  - VPS với Docker (nếu muốn học thêm DevOps)

- Sử dụng GitHub để quản lý mã nguồn
- Logging với SLF4J, Logback
- Mở rộng ứng dụng: API thanh toán, upload ảnh, gửi email,…
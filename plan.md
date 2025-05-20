# 📚 Kế Hoạch Ôn Tập Phỏng Vấn Middle (1 - 1.5 Tuần)

**Thời gian:**
- Ngày thường (T2-T6): 1-2 tiếng/ngày  
- Cuối tuần (T7-CN): 5-6 tiếng/ngày  

**Mục tiêu:**
- Kiến thức: Spring Boot, Microservices, PostgreSQL, Redis, Kafka, Elasticsearch, Java Core, Tasking đã làm.  
- Tập trung lý thuyết, không kèm thực hành.

---

## 📅 **Lịch Ôn Tập Chi Tiết**

### ✅ Ngày 1: Tổng quan Microservices & Kiến trúc
- **Kiến thức:**
  - Microservices vs Monolithic
  - Ưu/Nhược điểm, Anti-patterns
  - Mẫu thiết kế: API Gateway, Circuit Breaker, Saga, CQRS
- **Tự hỏi:**
  - Tại sao chọn Microservices?
  - Giao tiếp giữa các service như thế nào?

---

### ✅ Ngày 2: Spring Boot Core & Cấu trúc Dự Án
- **Kiến thức:**
  - Spring Context, Dependency Injection, Bean Lifecycle
  - Annotation: `@Component`, `@Service`, `@Repository`, `@Controller`, `@RestController`, `@Configuration`
  - Cấu trúc chuẩn project Spring Boot
- **Tự hỏi:**
  - Khi nào dùng `@Component` và `@Bean`?
  - Bean được khởi tạo như thế nào?

---

### ✅ Ngày 3: Spring Boot Advanced & Exception Handling
- **Kiến thức:**
  - `@Transactional`, Propagation & Isolation
  - Exception Handling: `@ControllerAdvice`, `@ExceptionHandler`
  - Validation: `@Valid`, Custom Validator
- **Tự hỏi:**
  - Khi nào rollback không hoạt động?
  - Xử lý Exception trong REST API như thế nào?

---

### ✅ Ngày 4: Spring Security & OAuth2 *(Nếu có thời gian)*
- **Kiến thức:**
  - Authentication vs Authorization
  - JWT Token Flow, OAuth2 Flow
  - Spring Security Filter Chain
- **Tự hỏi:**
  - JWT có nhược điểm gì?
  - Khi nào nên dùng OAuth2?

---

### ✅ Ngày 5: PostgreSQL
- **Kiến thức:**
  - MVCC, Transaction Isolation Levels
  - Indexing (B-Tree, GiST, GIN)
  - Query Execution Plan (`EXPLAIN ANALYZE`)
- **Tự hỏi:**
  - Khi nào Index không được sử dụng?
  - Giải thích MVCC và Vacuum.

---

### ✅ Ngày 6: Redis & Caching Patterns *(Cuối tuần)*
- **Kiến thức:**
  - Redis Data Structures: String, Hash, List, Set, Sorted Set
  - Cache Aside, Write Through, Write Behind
  - TTL, Eviction Policies: LRU, LFU, FIFO
- **Tự hỏi:**
  - Khi nào cache bị stale?
  - Redis có phải luôn là lựa chọn tốt?

---

### ✅ Ngày 7: Kafka *(Cuối tuần)*
- **Kiến thức:**
  - Kafka Architecture: Producer, Consumer, Broker, Partition, Offset
  - Consumer Groups, Message Ordering
  - At-least-once, Exactly-once semantics
- **Tự hỏi:**
  - Khi nào xảy ra message loss?
  - Kafka và RabbitMQ khác nhau như thế nào?

---

### ✅ Ngày 8: Elasticsearch & Logging
- **Kiến thức:**
  - Elasticsearch Concepts: Index, Document, Shard, Replica
  - Query vs Filter Context
  - Logging Stack: ELK/EFK
- **Tự hỏi:**
  - Khi nào không nên dùng Elasticsearch?
  - Làm sao đảm bảo kết quả tìm kiếm nhanh?

---

### ✅ Ngày 9: Java Core Ôn Tập
- **Kiến thức:**
  - OOP Principles, SOLID, Design Patterns: Factory, Singleton, Strategy, Observer
  - Collections: List, Map, Set — đặc điểm và khi nào dùng
  - Concurrency: Thread, Runnable, ExecutorService, synchronized, volatile
- **Tự hỏi:**
  - Khi nào nên dùng HashMap vs ConcurrentHashMap?
  - Giải thích synchronized và volatile.

---

### ✅ Ngày 10: Tổng Kết & Mock Interview *(Cuối tuần)*
- **Hoạt động:**
  - Review toàn bộ các topic đã học.
  - Tự tập giải thích 3-5 phút cho từng chủ đề lớn.
  - Chuẩn bị các tình huống dự án:
    - Vấn đề gặp phải → Cách giải quyết → Bài học rút ra.
    - Định hướng cải tiến hoặc lý do chọn giải pháp kỹ thuật.

---

**🎯 Lưu ý:**  
- Mỗi ngày dành 15-20 phút ôn lại kiến thức hôm trước.  
- Ưu tiên giải thích thành tiếng để tăng khả năng phản xạ khi phỏng vấn.  
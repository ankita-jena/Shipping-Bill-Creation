# 🇮🇳 SHIPPING BILL - Bharat Billing System
### Bharat Internship Project | Export Management System

A Java Spring Boot based web application to generate and validate Shipping Bills for Indian Exporters, as per ICEGATE standards.

**Live Demo:** `http://localhost:8080`

#### 🚀 Features
- IEC Code (10-digit) Validation
- FOB Value Calculation (Qty x Rate)
- Supported Ports: INMUN-Mundra, INNSA-Nhava Sheva, USNYC-New York, etc.
- Currency Support: INR, USD, EUR, GBP
- Dashboard with Total Bills & Total FOB Value
- Search by SB No. & Exporter Name
- Print / PDF Generation
- REST APIs: `/api/ports`, `/api/currencies`, `/api/shipping-bills`

#### 🛠️ Tech Stack
- Backend: Java 17, Spring Boot, Maven
- Frontend: HTML5, CSS3, JavaScript (Vanilla)
- Storage: In-Memory (H2 Ready)
- Tools: IntelliJ IDEA, GitHub

#### 📦 How to Run
1. `mvn spring-boot:run`
2. Open `http://localhost:8080`
3. Create Bill -> Print PDF

**Developed By:** Ankita Exports | Bharat Internship - Full Stack Java Intern

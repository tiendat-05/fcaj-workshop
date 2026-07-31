---
title: "Event 1"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 4.1. </b> "
---

# Bài thu hoạch tổng hợp Event Meet Up 06-06-2026

### Mục Đích Của Sự Kiện

* Chia sẻ định hướng phát triển sự nghiệp thực tế từ IT Helpdesk tiến lên Senior Sysadmin, Cloud & DevOps Mindset.
* Cập nhật các xu hướng công nghệ hàng đầu: GenAI với GraphRAG (Amazon Bedrock & Neptune) và Trí tuệ nhân tạo bảo mật NIDS kết hợp AWS WAF.
* Trang bị các phương pháp luận về kỹ năng mềm, làm việc nhóm hiệu quả (Teamwork) và quản trị dự án bằng công cụ kỹ thuật số.
* Đi sâu vào các giải pháp kỹ thuật thực chiến trên hạ tầng AWS Cloud: Kết nối Game Multiplayer thời gian thực qua WebSocket/Lambda và công nghệ đóng gói ứng dụng Docker Containerization.

### Danh Sách Diễn Giả

1. **Trần Trung Vinh** - System Administrator at Central Retail Group.
2. **Việt Phát** - AI Major, Swinburne University of Technology.
3. **Trương Huy Phước** - Presenter / Teamwork & Collaboration Specialist.
4. **Nguyễn Quốc Bảo** - Speaker, Cloud & Game Developer.
5. **Lê Hoàng Gia Đại** - AWS G3 Team, HUTECH University.
6. **Bảo Huỳnh** - Junior Cloud Native Developer at Endava Vietnam, Head of ITea Lab.

### Nội Dung Nổi Bật Theo Các Phiên Chia Sẻ

#### Phiên 1: From IT Helpdesk to Senior Sysadmin (Diễn giả: Trần Trung Vinh)

* **Lộ trình phát triển:** Đi từ kinh nghiệm hỗ trợ người dùng cơ bản (Helpdesk), chuyển dịch tư duy sang tìm hiểu bản chất cấu trúc hệ thống (Sysadmin) và tiếp cận lộ trình DevOps hiện đại (Linux, Networking, IaC Terraform, CI/CD, Container).
* **Tư duy vận hành (Operational Mindset):** *Prevent first — fix later* (Chủ động phòng ngừa hơn chữa cháy), viết tài liệu quy trình (Runbooks), tự động hóa các tác vụ lặp lại và tuân thủ tuyệt đối quy tắc *"Never test in production"*.

#### Phiên 2: Build GraphRAG Applications using Amazon Bedrock and Amazon Neptune (Diễn giả: Việt Phát)

* **Giải bài toán RAG truyền thống:** RAG dựa trên Vector Search gặp hạn chế khi xử lý câu hỏi chuỗi phức tạp (Multi-hop Reasoning).
* **Giải pháp GraphRAG:** Kết hợp Đồ thị tri thức (Knowledge Graph) giúp nhận biết mối quan hệ giữa các thực thể một cách tường minh.
* **Chiến lược triển khai AWS:** Sử dụng *Fully Managed Route* (Amazon Bedrock Knowledge Bases + Amazon Neptune Analytics) hoặc *Custom Route* (LlamaIndex + Amazon Neptune) để truy vấn mối quan hệ linh hoạt.

#### Phiên 3: The Art of Effective Teamwork (Diễn giả: Trương Huy Phước)

* **4 Quy tắc vàng:**
  1. *Clear & Shared Goals:* Mục tiêu chung minh bạch.
  2. *Right Person, Right Place:* Phân công đúng thế mạnh cá nhân.
  3. *Open Communication & Active Listening:* Giao tiếp cởi mở, lắng nghe chủ động.
  4. *Personal Accountability:* Trách nhiệm cá nhân đến cùng với công việc.
* **Ứng dụng công cụ số:** Quản lý Task với Trello/ClickUp, lưu trữ với Google Workspace và trao đổi qua Slack/Discord.

#### Phiên 4: Connecting Godot Clients with AWS WebSockets (Diễn giả: Nguyễn Quốc Bảo)

* **Kiến trúc Serverless Multiplayer:** Sử dụng API Gateway WebSocket để duy trì kết nối 2 chiều thời gian thực, AWS Lambda (Node.js) xử lý Matchmaking và DynamoDB lưu trữ trạng thái kết nối.
* **Lập trình Client:** Tích hợp `WebSocketPeer` trong Godot 4 để phân tích gói tin JSON thời gian thực.
* **Thách thức & Giải pháp:** Xử lý nghẽn rớt mạng (Stale Connections), tối ưu chi phí Scan DynamoDB và định hướng chuyển sang AWS GameLift cho các dòng game FPS/Action phức tạp.

#### Phiên 5: Machine Learning-based NIDS on AWS (Diễn giả: Lê Hoàng Gia Đại)

* **Vượt qua rào cản WAF truyền thống:** Bảo mật dạng quy tắc (Rule-based) của WAF không đủ để chống lại tấn công Zero-day.
* **Tích hợp ML NIDS:** Huấn luyện mô hình phát hiện xâm nhập mạng dựa trên bộ dữ liệu CSE-CIC-IDS2018. Mẫu thử nghiệm với thuật toán **LightGBM** đạt độ chính xác **95.86%**.
* **Kiến trúc Cloud toàn diện:** Tích hợp WAF, ALB, EC2, Kinesis, Lambda, Security Hub và CloudWatch tạo thành hệ thống cảnh báo và phản ứng tự động.

#### Phiên 6: Docker – A Containerization Technology (Diễn giả: Bảo Huỳnh)

* **Virtualization vs Containerization:** So sánh điểm yếu nặng nề của Máy ảo (VM) với sự nhẹ nhàng, khởi động tức thì và tiết kiệm tài nguyên của Docker Container.
* **Nguyên lý Docker:** Tìm hiểu cấu trúc layered architecture trong Dockerfile, cơ chế cache layers và triết lý *"Build once, run anywhere"*.
* **Ứng dụng thực tế:** Chuẩn hóa môi trường Dev/Test, phát triển Microservices và phục vụ CI/CD pipeline.

### Những Gì Học Được

#### Tư duy Phát triển Kỹ thuật (Tech Mindset)

* Nắm vững nền tảng vững chắc (Linux, Networking, Docker) trước khi tiến lên các công nghệ nâng cao như Cloud, DevOps hay AI.
* Học cách kết hợp đa dạng dịch vụ Cloud AWS (Cognito, RDS, Lambda, SageMaker, WAF, S3) để xây dựng giải pháp tổng thể thay vì các công cụ rời rạc.
* Tiếp cận tư duy bảo mật chủ động (Proactive Security) và nguyên tắc vận hành an toàn hệ thống (Preventive Care, Never test in prod).

#### Kỹ năng Mềm & Quản lý (Soft Skills & Management)

* Hiểu rõ cách vận hành dự án nhóm qua 4 quy tắc vàng và áp dụng triệt để các công cụ số (Trello, Discord, GitHub) để theo dõi tiến độ.
* Nhận thức rõ giá trị của các dự án thực chiến (Real Portfolio) đối với nhà tuyển dụng so với việc chỉ tập trung lấy chứng chỉ lý thuyết.

### Ứng Dụng Vào Dự Án Thực Tập

1. **Chuẩn hóa hạ tầng & Môi trường:** Đóng gói toàn bộ ứng dụng Web (NestJS Backend & Next.js Frontend) bằng **Docker** để chạy nhất quán từ môi trường Local cho đến AWS Cloud (ECS/EC2).
2. **Nâng cấp tính năng AI & WebSocket:**  
   * Áp dụng mô hình **WebSocket Gateway** để xây dựng khung Chatbot hỏi-đáp y tế thời gian thực.
   * Nghiên cứu tư duy **GraphRAG** để tối ưu hóa việc phân loại mối quan hệ giữa *Triệu chứng --> Chuyên khoa --> Bác sĩ*.
3. **Tăng cường Bảo mật & Giám sát:** Cấu hình **AWS WAF**, áp dụng Middleware Rate-Limiting, ẩn danh dữ liệu bằng UUID và tập trung toàn bộ Log lên **AWS CloudWatch** để sẵn sàng phát hiện các hành vi bất thường.
4. **Tối ưu Vận hành nhóm:** Thiết lập bảng Trello/ClickUp phân chia công việc minh bạch, xây dựng Runbook/Documentation chi tiết cho Database Schema để toàn đội cùng nắm bắt.

### Trải nghiệm trong event

Các phiên chia sẻ trong sự kiện đã mang lại cho tôi một trải nghiệm học tập cực kỳ toàn diện và phong phú:
* **Tính thực chiến cao:** Tất cả diễn giả đều đi từ những bài học thật, dự án thật và sự cố thật trong công việc hàng ngày, mang lại những góc nhìn rất đời thường nhưng vô cùng giá trị.
* **Cập nhật xu hướng thời đại:** Sự kết hợp giữa hạ tầng Cloud truyền thống, phương pháp Containerization với các công nghệ mũi nhọn như GenAI (GraphRAG) và Machine Learning thu hẹp đáng kể khoảng cách giữa lý thuyết nhà trường và thực tế doanh nghiệp.
* **Truyền cảm hứng mạnh mẽ:** Câu chuyện trưởng thành từ IT Helpdesk cho đến các vị trí Cloud Developer/Sysadmin thành công giúp tôi củng cố niềm tin vào con đường phát triển bản thân, tiếp thêm động lực để hoàn thành xuất sắc kỳ thực tập và các dự án công nghệ sắp tới.

#### Một số hình ảnh khi tham gia sự kiện
![Minh chứng tham gia Event](/images/4-EventParticipated/event-06062026.png)
> **Tổng kết:** Sự kiện là một cột mốc học tập ý nghĩa, không chỉ nạp thêm tri thức chuyên môn sâu sắc về AWS Cloud, AI và DevOps mà còn định hình lại thái độ làm việc chuyên nghiệp cho bản thân trên chặng đường trở thành một Software/Cloud Engineer thực thụ.
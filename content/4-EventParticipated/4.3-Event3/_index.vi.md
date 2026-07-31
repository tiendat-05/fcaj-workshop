---
title: "Event 3"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 4.2. </b> "
---

# Bài thu hoạch “FCAJ - Agentic AI Build Week Showcase” 25-07-2026

### Mục Đích Của Sự Kiện

* Tái hiện lại không khí thi đấu kịch tính và hào hứng từ cuộc thi Hackathon **Agentic AI Build Week**.
* Lắng nghe những chia sẻ thực chiến về hành trình 24 giờ liên tục nghiên cứu, phát triển và giải quyết sự cố (Building, Failing, and Learning) từ các đội thi.
* Khám phá các giải pháp ứng dụng đột phá của **Agentic AI** kết hợp với hệ sinh thái **AWS Cloud** nhằm giải quyết các bài toán thực tế trong kinh doanh, vận hành và quản trị.
* Học hỏi kinh nghiệm thiết kế kiến trúc Cloud-native, tích hợp AI Agents, quản lý phạm vi dự án (Scope) và kỹ năng Pitching thuyết phục trước hội đồng giám khảo.

### Danh Sách Các Đội Thi

1. **Team 3KA:** Dự án **S.H.E.P.H.E.R.D.** (Smart Human-flow Evaluation, Prediction, Hazard Detection, Response, and Dispatch)
   * *Thành viên:* Huỳnh An Khương, Nguyễn Quốc Huy, Ngô Quang Khôi, Hoàng Lê Thành Đức, Đặng Nguyễn Phước Lộc, Đặng Trường Hưng.
2. **Team Plan V:** Dự án **Solution Architect Professional AI Native App**
   * *Thành viên:* Phạm Tiến Thuận Phát, Huỳnh Hoàng Long, Lê Minh Nghĩa, Trần Đại Vĩ, Nguyễn An.
3. **Dream AI Team:** Dự án **Signal Scout**
   * *Thành viên:* Lê Tấn Lực, Đỗ Hoàng Hiếu, Triệu Quốc Hảo, Nguyễn Văn Duy Khiêm, Nguyễn Công Minh, Nguyễn Trần Minh Quân.
4. **One Team (Quán quân Hackathon):** Dự án **AI-Powered Conversation Ordering: KFC Bot Agent**
   * *Thành viên:* Anh Duy, Trần Đông, Đoàn Trung, Minh Việt, Anshul Roy.

### Nội Dung Nổi Bật

#### 1. Project S.H.E.P.H.E.R.D. (Team 3KA) — AI Giám Sát & Quản Lý Luồng Người

* **Bài toán:** Quy trình giám sát đám đông, hàng chờ và lưu lượng giao thông tại các sự kiện lớn hiện nay chủ yếu làm thủ công, phản ứng chậm và dễ bỏ sót sự cố.
* **Giải pháp:** Hệ thống Agentic AI tự động phân tích dữ liệu Video camera thời gian thực để đo mật độ đám đông, nhận diện sớm dấu hiệu ùn tắc và phát cảnh báo chủ động cho ban quản lý.
* **Công nghệ & Kiến trúc AWS:** Tích hợp YOLO + ByteTrack, Amazon SageMaker, Amazon Bedrock AgentCore + Strands Agent và React Monitoring Dashboard.
* **Agentic AI Layer:** 
  * *Autonomous Monitor:* Tự động giám sát các chỉ số đám đông và tạo cảnh báo sớm.
  * *Operator Copilot:* Trợ lý hỏi-đáp bằng ngôn ngữ tự nhiên giúp nhân viên tra cứu tình hình và nhận gợi ý hành động tức thì.

#### 2. Solution Architect Professional AI Native App (Team Plan V) — AI Trợ Lý Cho Kiến Trúc Sư Cloud

* **Bài toán:** Giải quyết gánh nặng công việc của Solution Architect khi phải đọc tài liệu BRD/PRD thủ công, tự vẽ sơ đồ kiến trúc, viết mã IaC (Terraform) và tính toán chi phí phức tạp.
* **Giải pháp:** Ứng dụng AI-Native tự động trích xuất yêu cầu, đề xuất phương án kiến trúc Cloud, tự động sinh sơ đồ **Draw.io** với icon AWS chính thức, tự tạo mã **Terraform (IaC)** và ước tính chi phí cho Region `ap-southeast-1`.
* **Công nghệ & Kiến trúc AWS:** AWS CloudFront, Cognito, ALB, ECS Fargate (Backend & Agent), PostgreSQL, Amazon Bedrock model, EFS, ECR, S3 Buckets và CloudWatch.

#### 3. Signal Scout (Dream AI Team) — AI Phát Hiện Tín Hiệu Thay Đổi Chiến Lược Doanh Nghiệp

* **Bài toán:** Dữ liệu tài chính và hoạt động doanh nghiệp nằm rải rác; việc phát hiện sớm các dấu hiệu tái cấu trúc hoặc rủi ro đối thủ cạnh tranh đòi hỏi nguồn lực phân tích rất lớn.
* **Giải pháp:** Nền tảng Agentic AI tự động thu thập, kiểm chứng bằng chứng (Evidence) và phân tích các chỉ số vận hành để xuất báo cáo cảnh báo rủi ro cho các đội ngũ chiến lược.
* **Công nghệ & Kiến trúc AWS:** Amazon Bedrock (Tokens), AgentCore Short-Term Memory & Runtime, AWS WAF, Amplify Hosting, DynamoDB, Lambda, API Gateway, S3 Intelligent-Tiering kết hợp công cụ trích xuất dữ liệu (Apify, TinyFish, LangFuse).

#### 4. KFC Bot Agent (One Team) — AI Đặt Hàng Trực Tiếp Qua Đa Kênh Nhắn Tin

* **Bài toán:** Loại bỏ rào cản đứt gãy luồng mua hàng (Loss of Order) khi khách hàng đang nhắn tin mà phải chuyển sang tải app mới hoặc tạo tài khoản phức tạp.
* **Giải pháp:** AI Agent đa kênh hỗ trợ đặt hàng trực tiếp ngay trong khung chat (Zalo OA, WhatsApp, Messenger) với triết lý *"No app download. No account creation. No lost momentum"*.
* **Quy trình Agent (5 bước):** *Goal* (Hiểu ý định) --> *Plan* (Lập kế hoạch) --> *Tools* (Tra cứu dữ liệu) --> *Act* (Thêm giỏ hàng/áp voucher) --> *Verify* (Đối soát giỏ hàng).
* **Công nghệ & Kiến trúc AWS:** Ingestion Layer (AWS WAF, API Gateway, SQS), Bedrock AgentCore, DynamoDB, OpenSearch Service (Vector Store & Full-text Search), ElastiCache và hệ thống giám sát CloudWatch/X-Ray/GuardDuty.
* **Chỉ số nổi bật:** Chi phí chỉ **$0.006 / đơn hàng**, độ trễ End-to-End **3–5 giây**, tổng chi phí hạ tầng **$88/tháng** và giảm **-60% mã nguồn hạ tầng** nhờ dùng Managed Services.

### Bài Học Rút Ra

1. **Sự khác biệt cốt lõi giữa Chatbot và AI Agent:**
   * Chatbot thông thường chỉ phản hồi câu chữ đơn thuần, trong khi **AI Agent** có khả năng chủ động lập kế hoạch (Planning), sử dụng công cụ (Tools) và tác động trực tiếp làm thay đổi trạng thái CSDL hệ thống.
2. **Kỹ năng quản lý phạm vi dự án (Scope Management):**
   * Bài học chung từ các đội thi là *"Small, finished work beats big, broken ideas"* — Thà tập trung hoàn thiện một tính năng nhỏ chuẩn xác hơn là xây dựng một hệ thống đồ sộ nhưng bị đứt gãy.
3. **Sức mạnh của kiến trúc Decoupled & Serverless:**
   * Thiết kế hệ thống theo dạng Modular (*Design Once | Deploy Everywhere*) kết hợp với dịch vụ Managed Services của AWS (Amazon Bedrock, ECS Fargate, Lambda, DynamoDB) giúp tiết kiệm đáng kể thời gian viết code hạ tầng và tối ưu hóa chi phí vận hành.

### Ứng Dụng Vào Công Việc

* **Nâng cấp tính năng AI cho Web Healthcare:** Áp dụng luồng xử lý 5 bước (*Goal --> Plan --> Tools --> Act --> Verify*) để nâng cấp Chatbot y tế — Tự động trích xuất triệu chứng bệnh nhân, kiểm tra lịch làm việc trống của Bác sĩ trong CSDL AWS RDS và thực hiện tạo lịch hẹn tự động.
* **Chuẩn hóa hạ tầng bằng IaC (Terraform):** Học hỏi cách Team Plan V để viết script Terraform tự động hóa việc khởi tạo CSDL RDS MySQL, S3 Bucket và mạng VPC cho ứng dụng.
* **Tăng cường bảo mật và giám sát:** Áp dụng mô hình bảo mật kết hợp AWS WAF, IAM Policy, Secrets Manager và CloudWatch Logging từ kiến trúc của KFC Bot và Signal Scout nhằm đảm bảo an toàn tuyệt đối cho dữ liệu y tế bệnh nhân.

### Trải nghiệm trong event

Sự kiện Showcase **Agentic AI Build Week** đã mang lại cho tôi những trải nghiệm vô cùng chân thực, kịch tính và giàu cảm hứng:

#### Cảm nhận về tinh thần thực chiến
* Được lắng nghe những câu chuyện "khiêu vũ cùng áp lực" trong suốt 24 giờ thi đấu (xử lý lỗi code lúc 3 giờ sáng, uống Redbull để thức thâu đêm, tinh thần đồng đội nỗ lực hết mình) giúp tôi cảm nhận rõ sự nhiệt huyết của các lập trình viên.

#### Mở rộng tầm mắt về ứng dụng AI & Cloud
* Cả 4 dự án đều thể hiện trình độ làm chủ công nghệ xuất sắc, chứng minh tính khả thi cao khi đưa AI Agents vào giải quyết các bài toán từ đặt món ăn, giám sát an ninh, phân tích rủi ro doanh nghiệp cho đến tự động hóa công việc của một Cloud Architect.

#### Động lực phát triển bản thân
* Nhận ra rằng *"Showing up is already half the battle"*. Cảm hứng từ các đội thi tiếp thêm niềm tin để tôi tự tin đăng ký tham gia các cuộc thi Hackathon công nghệ trong tương lai.

#### Một số hình ảnh khi tham gia sự kiện
![Minh chứng tham gia Event](/images/4-EventParticipated/event-25072026.jpg)
> **Tổng kết:** Buổi Showcase là một cột mốc học tập tuyệt vời, giúp tôi tích lũy thêm nhiều tri thức giá trị về Agentic AI trên AWS Cloud, đồng thời củng cố tư duy thiết kế kiến trúc chuẩn mực cho dự án Web Healthcare của mình.

# DỰ ÁN: SMART LESSON PLAN (SLP) AGENT
## AI-Powered Lesson Architect cho Giáo dục Phổ thông

---

## 1. Ý tưởng diễn giải lại (Idea Reframed)
Thay vì để giáo viên phải "vắt óc" ngồi hàng tiếng đồng hồ trước màn hình trắng, dự án tạo ra một **Trợ lý AI chuyên sâu**, giúp tự động hóa việc soạn giáo án chuẩn GDPT 2018 chỉ trong vài phút.

**Hiện trạng của giáo viên trước khi có AI Agent:**
* **Thiết kế:** Tự mày mò thiết kế hoạt động (mất 2-5h/bài).
* **Format:** Đau đầu với cấu trúc phức tạp của Công văn 5512 (Bộ GD&ĐT).
* **Quản lý:** Loay hoay phân bổ thời gian (pacing) để không bị "cháy giáo án".

---

## 2. Customer & Segment Card

### 2.1. Customer
* **Nhóm 1: Giáo viên phổ thông (Đặc biệt là GV trẻ & mới)**
    * *Thực trạng:* Áp lực "burnout", mất 8-12 tiếng/tuần cho thủ tục hành chính.
    * *Nhu cầu:* "Kho ý tưởng" hoạt động (5E, VNEN...) và công cụ điền format chuẩn.
    * *Giải pháp:* Generate giáo án từ từ khóa, gợi ý trò chơi, tự động kiểm tra compliance.
* **Nhóm 2: Tổ trưởng chuyên môn / Ban giám hiệu**
    * *Nỗi đau:* Duyệt thủ công hàng chục giáo án/tuần; khó kiểm soát chất lượng đồng bộ.
    * *Nhu cầu:* Review nhanh, chấm điểm giáo án theo tiêu chí chuẩn, quản lý học liệu tập trung.
* **Nhóm 3: Sinh viên sư phạm & Thực tập sinh**
    * *Nhu cầu:* Cần "khuôn mẫu" chuẩn để học cách thiết kế bài giảng mà không bị ngợp.

### 2.2. Segment Card
* **Segment name:** Giáo viên Phổ thông (K-12) – Nhóm "Burnout" vì thủ tục hành chính.
* **Recurring workflow:** Kiêm nhiệm nhiều vai trò (giảng dạy, chủ nhiệm, chấm bài) trong môi trường chuyển đổi số nhưng thiếu công cụ hỗ trợ thực chất.
* **Workflow lặp lại:** Đọc SGK → Xác định mục tiêu → Thiết kế hoạt động → Căn chỉnh thời gian → Gõ Word chuẩn 5512 → Nộp duyệt.
* **Pain moment:** * *"Cơn ác mộng màn hình trắng":* Ngồi 2-3 tiếng không nghĩ nổi hoạt động mới mẻ.
    * *"Hành chính hóa":* Thức trắng đêm chỉnh format chỉ để "đối phó" thanh tra.
* **Why now:** Chương trình 2018 đòi hỏi dạy học tích cực (5E, dự án) nhưng GV chưa được đào tạo sâu về thiết kế bài giảng; Sự kỳ vọng vào AI chuyên biệt tăng cao.
* **Access path:** Cộng đồng Threads (nơi xả stress), Facebook Groups (Giáo viên 4.0), các buổi tập huấn chuyên môn tại trường.

---

## 3. Need Map

### **Need #1: Tự động hóa thủ tục hành chính**
* **Need statement:** Khi đến kỳ nộp hồ sơ giáo án hàng tuần theo Công văn 5512, tôi muốn tự động hóa việc điền các mục mục tiêu năng lực/phẩm chất, để tôi có thể hoàn thành thủ tục hành chính nhanh nhất mà không bị tổ trưởng bắt bẻ.
* **Current workaround:** Copy-paste từ các file giáo án mẫu cũ hoặc xin file của đồng nghiệp rồi chỉnh sửa thủ công từng dòng để khớp với bài dạy hiện tại.
* **Pain signal:** Stress vận hành và mất thời gian cực lớn (chiếm 60% thời gian soạn bài). Giáo viên cảm thấy kiệt sức vì phải làm công việc "thư ký" vô hồn thay vì dạy học.
* **Evidence (or proxy):** * *Khảo sát:* 40% giáo viên thừa nhận chưa thuộc/chưa quen với format GDPT 2018. 
    * *Threads:* Nhiều bài đăng than phiền "soạn giáo án muốn điên đầu", "thức đến 2h sáng chỉ để làm cho đủ form".
* **Why underserved:** Các công cụ văn phòng thông thường (Word) không hiểu cấu trúc chương trình mới. Các mẫu giáo án trên mạng thường rời rạc, không cập nhật theo sách giáo khoa (SGK) hiện hành và thiếu tính tùy biến theo từng môn học cụ thể.

---

### **Need #2: Sáng tạo hoạt động dạy học (Lesson Ideas)**
* **Need statement:** Khi gặp những bài học khô khan hoặc môn học mới tích hợp, tôi muốn có các gợi ý kịch bản hoạt động (trò chơi, thảo luận, thực hành) sinh động, để tôi có thể tự tin đứng lớp và giúp học sinh hào hứng, hiểu bài ngay tại chỗ.
* **Current workaround:** Lên các group Facebook để "xin" ý tưởng, lục tìm Pinterest/YouTube hoặc sử dụng ChatGPT bản miễn phí (nhưng kết quả thường chung chung, không sát thực tế lớp học Việt Nam).
* **Pain signal:** Mất cơ hội nâng cao chất lượng dạy học và stress tâm lý ("Cơn ác mộng màn hình trắng"). GV thường xuyên bị "cháy giáo án" hoặc dạy lệch so với dự kiến ban đầu.
* **Evidence (or proxy):** * *Khảo sát:* Việc thiết kế hoạt động là phần tốn thời gian nhất (trung bình 1-2 giờ/bài). 
    * *Threads:* Giáo viên chia sẻ "ngồi cả buổi không nghĩ ra nổi hoạt động khởi động", "triển khai thực tế bị lệch hoàn toàn so với giáo án".
* **Why underserved:** Thị trường hiện tại chỉ cung cấp các bài giảng mẫu cố định (tĩnh), không có công cụ "động" để tùy chỉnh hoạt động theo trình độ học sinh từng lớp. AI phổ thông thiếu ngữ cảnh sư phạm Việt Nam và không được huấn luyện trên kho học liệu chuẩn của SGK mới.

---
### 4. Strategy Statement + Moat
#### 4.1. Strategy Statement
**For** K-12 teachers in Vietnam, **who struggle with** the overwhelming administrative burden of manual lesson planning and creative blocks, **our product helps them** reclaim 80% of their preparation time while enhancing teaching quality **through** an AI-powered "Lesson Architect" that automates framework compliance (Circular 5512) and generates localized pedagogical ideas, **unlike** generic AI chatbots or static online repositories, **because we can leverage** a deep RAG engine specifically trained on Vietnamese textbooks and national curriculum standards.

#### 4.2. Moat Hypothesis
**Our moat mechanism is:** **Domain-learning flywheel** and **Workflow embedding**.

**Khi triển khai 50 lần trong cùng một ngách (ví dụ: KHTN cấp 2), các yếu tố sau sẽ tốt lên vượt trội:**
1. **Pedagogical Precision:** AI hiểu sâu các lỗi logic và kịch bản dạy học đặc thù tại Việt Nam qua phản hồi thực tế của giáo viên.
2. **Asset Compounding:** Kho học liệu (hoạt động, câu hỏi, bài tập) khớp 100% với tiến độ giảng dạy thực tế.
3. **User Habituation:** Trở thành một phần bắt buộc trong quy trình nộp hồ sơ, tạo rào cản chuyển đổi (Switching cost) cực cao.

**Why competitors cannot easily replicate this:** Đối thủ chung chung không có dữ liệu ngách về quy định của Bộ GD&ĐT và vòng lặp phản hồi chuyên sâu từ cộng đồng giáo viên địa phương.

### 4.3. Positioning Note
* **What we are:** Một Trợ lý chuyên sâu (Vertical AI Agent) giúp giáo viên tự động hóa thiết kế bài giảng chuẩn quy định và sáng tạo hoạt động dạy học.
* **What we are not:** Chúng tôi không phải là kho lưu trữ tài liệu tĩnh hay công cụ chatbot giải bài tập tổng quát cho học sinh.

---

### 5. Promt cho Vibe Coding

#### 5.1. 5.1 Structured Critique Prompt
**Prompt:**
Review this Day 16 draft.

For each issue, return:

issue name

evidence from the draft

why it is weak

rewrite suggestion

Check these 5 issues:

customer too broad

need is actually a solution

lack of evidence

strategy too generic

moat too weak

Important: Do not add imaginary facts.

Draft:

Idea: SLP Agent - An AI-powered "Lesson Architect" specifically designed for the Vietnamese K-12 education system (GDPT 2018). It automates lesson planning and activity design to save teachers' time.

Target Customer: - Primary segment: K-12 teachers in Vietnam, specifically younger/new teachers suffering from administrative burnout.

Secondary segments: Department heads/School boards (for quality control) and Education students (for learning frameworks).

Focused niche: Middle school teachers (grades 6-9) teaching Integrated Natural Sciences (KHTN).

Needs:

Administrative Automation: Teachers need to complete lesson plans following "Circular 5512" (a complex official framework) quickly to avoid administrative reprimands. Current workaround: Copy-pasting old files or borrowing from colleagues.

Creative Lesson Ideas: Teachers need localized pedagogical kịch bản (opening activities, games, discussions) to keep students engaged and ensure learning outcomes. Current workaround: Searching Facebook/Pinterest or using generic ChatGPT (which lacks local context).

Strategy Statement:
For K-12 teachers in Vietnam, who struggle with the overwhelming administrative burden of manual lesson planning and creative blocks, our product helps them reclaim 80% of their preparation time while enhancing teaching quality through an AI-powered "Lesson Architect" that automates framework compliance (Circular 5512) and generates localized pedagogical ideas, unlike generic AI chatbots or static online repositories, because we can leverage a deep RAG engine specifically trained on Vietnamese textbooks and national curriculum standards.

Moat Hypothesis:

Mechanism: Domain-learning flywheel and Workflow embedding.

Why it grows: As we deploy in specific verticals (e.g., Natural Sciences), the AI gains pedagogical precision from teacher feedback, assets (activities/questions) compound, and the tool becomes an embedded part of the mandatory submission workflow (high switching cost).

Competitive barrier: Generic competitors lack niche data on Ministry of Education regulations and the deep feedback loop from the local teaching community.

Positioning:

What we are: A Vertical AI Agent for automated lesson design and pedagogical creativity.

What we are not: A static document repository or a general-purpose homework solver for students.

**AI Response:**
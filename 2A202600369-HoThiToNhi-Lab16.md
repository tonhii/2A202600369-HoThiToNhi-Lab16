# Day 16 Submission — 2A202600369-Hồ Thị Tố Nhi

## Members
- Hồ Thị Tố Nhi

---

## 1. Idea reframed

Original idea:
> Xây dựng hệ thống Agent AI hỗ trợ giáo viên phổ thông soạn giáo án tự động theo các mô hình 5E, VNEN và kiểm tra tính tuân thủ các quy định của Bộ Giáo dục.

Reframed as a product opportunity:
> Nhận thấy một khoảng trống lớn (observed gap) giữa yêu cầu hành chính khắt khe của Công văn 5512 và năng lực thiết kế hoạt động thực tế của giáo viên trong chương trình mới. Niềm tin cốt lõi (founding belief) của dự án là giáo viên không cần một máy phát tạo văn bản (Text Generator), mà họ cần một Kiến trúc sư bài giảng (Lesson Architect) giúp chuyển hóa các mục tiêu khô cứng thành kịch bản dạy học có thể sử dụng ngay. Đây là cơ hội để xây dựng một "Hệ thống lưu trữ gốc" (System of Record) cho sự nghiệp giảng dạy của giáo viên, thay vì chỉ là một công cụ chỉnh sửa văn bản.

---

## 2. Customer / Segment Card

- **Segment name:** [Giáo viên Phổ thông (K-12) – Nhóm "Burnout" vì thủ tục hành chính.]
- **Operational context:** [Giáo viên phổ thông tại Việt Nam, đặc biệt là những người dạy các môn mới tích hợp (Khoa học tự nhiên, Lịch sử & Địa lý) hoặc các môn khoa học cơ bản (Toán, Lý, Hóa). Họ đang chịu áp lực kép: vừa phải chuyển đổi sang phương pháp dạy học tích cực (5E, dự án) theo Chương trình GDPT 2018, vừa phải đối mặt với khối lượng thủ tục hành chính nặng nề từ Công văn 5512.]
- **Recurring workflow:** [Đọc SGK → Xác định mục tiêu → Thiết kế hoạt động → Căn chỉnh thời gian → Gõ Word chuẩn 5512 → Nộp duyệt.]
- **Pain moment:** [“Cơn ác mộng màn hình trắng”: Ngồi 2–3 tiếng không nghĩ nổi hoạt động mới mẻ. “Hành chính hóa”: Thức trắng đêm chỉnh format chỉ để “đối phó” thanh tra.]
- **Why now:** [Chương trình GDPT 2018 đòi hỏi dạy học tích cực (5E, dự án) nhưng GV chưa được đào tạo sâu về thiết kế bài giảng; Sự kỳ vọng vào AI chuyên biệt tăng cao.]
- **Access path:** [Cộng đồng Threads (nơi xả stress), Facebook Groups (Giáo viên 4.0), các bài khảo sát giáo viên.]

One-sentence description:
> [Giáo viên phổ thông tại Việt Nam đang kiệt sức vì áp lực kép: vừa phải chuyển đổi sang phương pháp dạy học tích cực theo chương trình mới, vừa phải đối mặt với khối lượng thủ tục hành chính nặng nề từ Công văn 5512.]

---

## 3. Need Map (2–3 needs)

### Need #1 (priority)
- **Statement (JTBD):** When [đến kỳ nộp hồ sơ giáo án hàng tuần], I want [tự động hóa việc điền các mục tiêu năng lực theo Công văn 5512], so I can [hoàn thành thủ tục nhanh nhất và tránh bị khiển trách hành chính].
- **Current workaround:** [Copy-paste từ các file giáo án mẫu cũ hoặc xin file của đồng nghiệp rồi chỉnh sửa thủ công từng dòng để khớp với bài dạy hiện tại.]
- **Pain signal:** [Stress vận hành và mất thời gian cực lớn (chiếm 60% thời gian soạn bài, mất trung bình 2-3 tiếng/bài). Giáo viên cảm thấy kiệt sức vì phải làm công việc "thư ký" vô hồn thay vì dạy học.]
- **Evidence / proxy evidence:** [Khảo sát: 40% giáo viên thừa nhận chưa thuộc/chưa quen với format GDPT 2018. Threads: Nhiều bài đăng than phiền "soạn giáo án muốn điên đầu", "thức đến 2h sáng chỉ để làm cho đủ form".]
- **Why underserved:** [Các công cụ văn phòng thông thường (Word) không hiểu cấu trúc chương trình mới. Các mẫu giáo án trên mạng thường rời rạc, không cập nhật theo sách giáo khoa (SGK) hiện hành và thiếu tính tùy biến theo từng môn học cụ thể.]

### Need #2
- **Statement (JTBD):** When [soạn các bài học tích hợp khó hoặc khô khan], I want [có các gợi ý kịch bản hoạt động (trò chơi, thảo luận, thực hành) sinh động], so I can [tự tin đứng lớp và giúp học sinh hào hứng, hiểu bài ngay tại chỗ].
- **Current workaround:** [Lên các group Facebook để "xin" ý tưởng, lục tìm Pinterest/YouTube hoặc sử dụng ChatGPT bản miễn phí (nhưng kết quả thường chung chung, không sát thực tế lớp học Việt Nam).]
- **Pain signal:** [Mất cơ hội nâng cao chất lượng dạy học và stress tâm lý ("Cơn ác mộng màn hình trắng"). GV thường xuyên bị "cháy giáo án" hoặc dạy lệch so với dự kiến ban đầu.]
- **Evidence / proxy evidence:** [Khảo sát: Việc thiết kế hoạt động là phần tốn thời gian nhất (trung bình 1-2 giờ/bài). Threads: Giáo viên chia sẻ "ngồi cả buổi không nghĩ ra nổi hoạt động khởi động", "triển khai thực tế bị lệch hoàn toàn so với giáo án".]
- **Why underserved:** [Thị trường hiện tại chỉ cung cấp các bài giảng mẫu cố định (tĩnh), không có công cụ "động" để tùy chỉnh hoạt động theo trình độ học sinh từng lớp. AI phổ thông thiếu ngữ cảnh sư phạm Việt Nam và không được huấn luyện trên kho học liệu chuẩn của SGK mới.]


---

## 4. Strategy Statement

For [Giáo viên phổ thông tại Việt Nam]
who struggle with [gánh nặng hành chính quá tải từ việc soạn giáo án thủ công và sự bế tắc trong ý tưởng sáng tạo],
our product helps them [đòi lại 80% thời gian chuẩn bị bài giảng trong khi vẫn nâng cao chất lượng dạy học]
through [một "Kiến trúc sư bài giảng" ứng dụng AI giúp tự động hóa việc tuân thủ các khung quy định (Công văn 5512) và gợi ý các ý tưởng sư phạm bản địa hóa],
unlike [các chatbot AI chung chung hoặc các kho lưu trữ tài liệu trực tuyến tĩnh],
because we can leverage [hệ thống RAG chuyên sâu được huấn luyện đặc biệt dựa trên sách giáo khoa Việt Nam và các tiêu chuẩn chương trình giáo dục phổ thông quốc gia].
---

## 5. Moat Hypothesis

**Moat mechanism:** [Tích hợp quy trình nghiệp vụ chuẩn xác (High-Integrity Workflow Integration) & Vòng lặp học tập chuyên sâu theo ngành (Domain-learning flywheel)]

If we deploy [1000] times in [Giáo dục phổ thông tại Việt Nam], the following improve:
1. [Độ chính xác của giáo án (Lesson Plan Accuracy): Càng nhiều giáo án được tạo ra và chỉnh sửa bởi giáo viên, hệ thống càng học được cách diễn đạt mục tiêu năng lực và phẩm chất sao cho khớp với văn phong của Bộ GD&ĐT và thực tế giảng dạy, từ đó giảm thiểu rủi ro bị từ chối khi thanh tra.]
2. [Chất lượng hoạt động dạy học (Pedagogical Quality): Thông qua phản hồi thực tế từ giáo viên về mức độ hiệu quả của các hoạt động được gợi ý, hệ thống có thể tinh chỉnh và học cách tạo ra các kịch bản sáng tạo, phù hợp hơn với từng môn học và trình độ học sinh.]
3. [Tỷ lệ giáo viên sử dụng thường xuyên (Retention Rate): Khi giáo viên nhận thấy sản phẩm giúp họ tiết kiệm thời gian và giảm stress đáng kể, họ sẽ có xu hướng sử dụng sản phẩm như một công cụ không thể thiếu trong quy trình làm việc hàng ngày, tạo ra một thói quen sử dụng khó thay đổi.]

Why competitors cannot easily replicate this:
> [Các đối thủ cạnh tranh lớn như Google hay Microsoft khó có thể sao chép được lợi thế này vì họ thiếu sự am hiểu sâu sắc về bối cảnh sư phạm Việt Nam và các quy định hành chính cụ thể. Hơn nữa, việc xây dựng một hệ thống RAG chuyên sâu đòi hỏi thời gian và nguồn lực đáng kể để thu thập, xử lý và huấn luyện dữ liệu trên kho học liệu chuẩn của Việt Nam, điều mà các công ty công nghệ lớn thường không ưu tiên.]

---

## 6. Initial TAM / SAM / SOM view

| Layer | Estimate | Key assumptions | Confidence |
|---|---|---|---|
| TAM | $20M–$30M/year | 1.2 triệu GV toàn quốc, chi trả trung bình $20/năm cho công cụ hỗ trợ. | Med |
| SAM | $8M–$10M/year | 400,000 GV trẻ và trường tư/quốc tế có hành vi ứng dụng công nghệ cao. | Med |
| SOM | $500K–$1M | 20,000–30,000 GV trả phí trong 12-24 tháng đầu. | High |

**Top 3 unknowns requiring further research:**
1. Mức độ sẵn sàng trả phí cá nhân (B2C) của giáo viên công lập khi lương cơ bản còn thấp.
2. Khả năng tích hợp trực tiếp (API/Export) vào các hệ thống quản lý học tập (LMS) hiện có của nhà trường.
3. Chi phí bản quyền dữ liệu khi huấn luyện AI dựa trên các bộ SGK của các nhà xuất bản.

**Judgment:**
- [x] Worth pursuing now
- [ ] Worth pursuing but not now (need to validate [...] first)
- [ ] Not worth pursuing as currently framed

---

## 7. Positioning Note (2 sentences)

**What we are:**
> [Kiến trúc sư bài giảng (Lesson Architect) giúp chuyển hóa các mục tiêu khô cứng thành kịch bản dạy học sẵn sàng sử dụng.]

**What we are not / not yet:**
> [Một kho lưu trữ tài liệu tĩnh hay công cụ chatbot giải bài tập tổng quát dành cho học sinh.]

---

## 8. Self-assessment before Day 17

Trong 6 mắt xích (Idea → Customer → Need → Strategy → Moat → Market Size), mắt xích nào team đang yếu nhất?

> [Market Size (Khả năng chi trả thực tế của GV) và Moat (Vì Big Tech có thể dễ dàng bổ sung tính năng tương tự nếu họ có dữ liệu bản địa).]

Open questions chúng tôi muốn khám phá thêm ở Day 17:
1. [Làm sao để tiếp cận và thuyết phục các trường tư/quốc tế hợp tác thử nghiệm (B2B2C)?]
2. [Chi phí token AI cho mỗi giáo án là bao nhiêu để tính toán Unit Economics bền vững?]
3. [Làm sao để tự động hóa việc cập nhật dữ liệu SGK mới nhanh nhất khi các nhà xuất bản thay đổi nội dung?]
```

---

## 9. Bridge to Day 17

Day 16 đã trả lời:
- Real opportunity đằng sau idea là gì?
- Ai là early customer?
- Need thật là gì?
- Product move đúng là gì?
- Moat nào có thể compound?
- Thị trường có đáng để theo đuổi không?

Day 17 sẽ trả lời:
- **What exactly do we build first?** (MVP scope)
- Viết PRD thế nào?
- Assumption nào cần validate trước tiên?
- Experiment nào chạy trong 2 tuần đầu?

---

## 10. References

### Core readings

1. **The Lean Product Playbook** — Dan Olsen.
   [https://leanproductplaybook.com/](https://leanproductplaybook.com/)
   Gốc của Lean Product thinking (Problem Space vs Solution Space, Product-Market Fit Pyramid).

2. **TAM, SAM, and SOM: Made Simple for Growing Businesses** — Salesforce.
   [https://www.salesforce.com/blog/tam-sam-som/](https://www.salesforce.com/blog/tam-sam-som/)
   Giới thiệu cơ bản và dễ hiểu về market sizing.

### Further reading (optional, nếu team muốn đào sâu hơn)

3. **Jobs to Be Done: Theory to Practice** — Anthony W. Ulwick.
   Kinh điển về JTBD framework.

4. **The Mom Test** — Rob Fitzpatrick.
   Cách phỏng vấn khách hàng mà không bị "mom answer" làm lệch kết quả. Rất liên quan đến phần *evidence vs proxy evidence*.

5. **7 Powers: The Foundations of Business Strategy** — Hamilton Helmer.
   Phân tích 7 loại moat (Scale Economies, Network Economies, Counter-Positioning, Switching Costs, Branding, Cornered Resource, Process Power).

6. **Competing Against Luck** — Clayton Christensen.
   Case-driven, giải thích JTBD qua nhiều ví dụ đời thực.

### Quick reference — các câu chốt Day 16

| Lúc nào nhớ câu nào |
|---|
| "Respect the idea, but do not trust its first product definition." |
| "Interest is not willingness to pay." |
| "FOMO AI is not a need." |
| "A real need hurts even before AI exists." |
| "Do not sell a tool people must configure; sell a result people can use." |
| "Durable advantage comes from repeated workflow learning." |
| "Market sizing is meaningful only after product logic becomes sharper." |

---
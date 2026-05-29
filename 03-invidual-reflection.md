# 03 — AI SUPPORT LOG + REFLECTION (Cá nhân)

> **Trách nhiệm:** Cá nhân
> **Điểm:** 15 điểm (AI Support Log + Reflection)
> **Deadline:** Cuối Phase 6

---

## Thông tin cá nhân

* **Họ tên:**
* **Vai trò trong nhóm:** 
* **Email / Phone:**

---

### Phase 0 — Worked Example (15 min) — KHÔNG log

---

### Phase 1 — SCAN (20 min) — AI Brainstorm

## 🤖 AI Sử Dụng

* AI tool nào dùng?

  * ChatGPT: dùng để brainstorm thêm problem, polish câu chữ, kiểm tra logic problem card và viết reflection.
  * Claude / Copilot Chat: dùng để mở rộng ý tưởng, gợi ý cách trình bày workflow và Problem Statement.
  * GitHub Copilot: dùng để hỗ trợ format markdown, tạo cấu trúc file nộp bài.

* Prompt gì dùng?

  * "Dựa trên vai trò sinh viên năm cuối ngành Data Science, hãy gợi ý các problem thật có thể dùng cho Day 02 Lab, chia theo các lens: lặp lại, tốn thời gian, AI có thể tốt hơn, pain từ người khác."
  * "Viết lại 3 Quick Problem Cards theo format: problem, actor, workflow, bottleneck, metric, quick gut."
  * "Đây là workflow tìm phòng trọ của nhóm tôi. Hãy chỉ ra bottleneck, metric trước/sau, boundary và nên chọn Rule, Workflow hay Agent."
  * "Viết phần reflection cá nhân theo motif AI Support Log: AI giúp gì, AI sai ở đâu, tôi sửa gì, prompt hay nhất."

* Output AI có giúp không? Tại sao?

  * Có. AI giúp tôi mở rộng danh sách problem ban đầu nhanh hơn, đặc biệt là các vấn đề liên quan đến học tập như EDA, đọc paper, viết báo cáo, chuẩn bị CV/portfolio.
  * AI giúp tôi biến các pain point còn mơ hồ thành Quick Problem Cards có workflow, bottleneck và metric rõ hơn.
  * AI cũng giúp nhóm trình bày bài toán tìm phòng trọ theo mạch problem → workflow → bottleneck → metric → boundary → Rule / Workflow / Agent.

* AI sai/hời hợt chỗ nào? Tôi sửa gì?

  * AI ban đầu có xu hướng đưa ra nhiều ý tưởng khá rộng hoặc nghe hay nhưng chưa chắc làm được trong lab.
  * AI cũng có lúc đề xuất chọn Agent quá sớm mà chưa làm rõ boundary, rủi ro dữ liệu sai, tin giả, tin hết phòng hoặc scam.
  * Tôi và nhóm đã sửa lại bằng cách giới hạn Agent chỉ hỗ trợ tìm, bóc tách, xếp hạng và cảnh báo rủi ro; không tự đặt cọc, không tự ký hợp đồng và không khẳng định tin đăng an toàn tuyệt đối.

* Ghi chú thêm:

  * Ý tưởng cá nhân tôi pitch ban đầu là Card #2: đọc paper dài 10–15 trang để chuẩn bị seminar, mất khoảng 120 phút/paper.
  * Tuy nhiên, sau khi nhóm thảo luận, nhóm chọn bài toán tìm phòng trọ tối ưu vì pain thực tế hơn với nhiều người, workflow rõ hơn và có thể đo impact tốt hơn.
  * Tôi chấp nhận điều chỉnh theo nhóm vì bài toán nhóm chọn có actor rõ, bottleneck rõ và phù hợp để phân tích theo Rule / Workflow / Agent.

---

# 03 — AI Support Log

## Phase 6 — Reflection + AI Support Log

| Câu hỏi                  | Trả lời                                                                                                                                                                                                                                                                                                                                                                                                                       |
| ------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **AI giúp gì?**          | AI hỗ trợ tôi ở 4 chỗ chính: (1) brainstorm danh sách problem cá nhân từ workflow sinh viên Data Science; (2) giúp viết rõ 3 Quick Problem Cards, đặc biệt là Card #2 về đọc paper cho seminar; (3) hỗ trợ nhóm chuyển bài toán tìm phòng trọ thành workflow trước/sau có bottleneck và metric; (4) giúp so sánh Rule / Workflow / Agent để thấy vì sao Agent phù hợp với hướng phát triển của bài toán tìm phòng trọ tối ưu. |
| **AI sai ở đâu?**        | AI có xu hướng đề xuất các ý tưởng rộng và hơi solution-first. Ví dụ, với bài toán tìm phòng trọ, AI có thể nhanh chóng đề xuất Agent tự crawl Facebook/TikTok, tự lấy dữ liệu và tự chọn phòng tốt nhất. Cách này nghe mạnh nhưng rủi ro cao vì dữ liệu social media có thể sai, thiếu, hết hạn hoặc có tin lừa đảo. AI cũng có lúc đưa metric chung chung như “nhanh hơn” hoặc “tốt hơn” thay vì có số cụ thể.              |
| **Tôi sửa gì bằng tay?** | Tôi tự chỉnh lại metric và boundary cho rõ hơn. Với phần cá nhân, tôi giữ metric đọc paper từ 120 phút xuống dưới 45 phút. Với phần nhóm, tôi cùng nhóm chỉnh metric tìm phòng từ 3–4 giờ xuống 30–45 phút và tạo shortlist 5–10 phòng. Tôi cũng bổ sung boundary: Agent không tự đặt cọc, không tự ký hợp đồng, không đảm bảo tin 100% an toàn, người dùng phải xác minh và đi xem phòng trước khi quyết định.               |
| **Prompt hay nhất?**     | `Đây là bài toán nhóm tôi chọn: người đi học/làm xa nhà mất 3–4 giờ tìm phòng trọ từ Facebook, TikTok, website và Google Maps. Hãy phân tích current workflow, future workflow với Agent, chỉ ra bottleneck, success metric, boundary, rồi so sánh Rule / Workflow / Agent để quyết định mức phù hợp.`                                                                                                                        |

---

## Reflection

### 1. AI giúp tôi nhanh hơn ở đâu

* AI giúp tôi brainstorm nhanh hơn trong Phase 1, từ đó có danh sách problem đa dạng hơn thay vì chỉ nghĩ đến một vấn đề.
* AI giúp tôi viết Quick Problem Cards rõ hơn, có đủ actor, workflow, bottleneck, metric và quick gut.
* AI giúp tôi chuyển ý tưởng nhóm thành workflow rõ ràng hơn: từ việc người dùng tự lướt nhiều nguồn trong 3–4 giờ sang Agent hỗ trợ thu thập, bóc tách, tính commute, xếp hạng và tạo shortlist.
* AI hữu ích nhất ở phần cấu trúc hóa suy nghĩ. Thay vì chỉ nói “tìm phòng trọ rất mất thời gian”, AI giúp tôi trình bày thành các bước: tìm nguồn, đọc tin, kiểm tra map, ghi chú, so sánh, liên hệ và đi xem phòng.

### 2. AI không thay tôi ra quyết định ở đâu

* AI không thể tự biết problem nào đau nhất nếu tôi không cung cấp trải nghiệm thật.
* AI không thể tự xác nhận số thời gian 3–4 giờ hoặc 30–45 phút có đúng với thực tế hay không. Tôi và nhóm phải tự ước lượng, kiểm chứng và chỉnh lại.
* AI không thể thay nhóm quyết định chọn bài toán nào. Ban đầu tôi pitch bài toán đọc paper, nhưng sau khi nghe nhóm thảo luận, tôi đồng ý chuyển sang bài toán tìm phòng trọ vì impact rộng hơn.
* AI cũng không thể thay người dùng xác minh tin phòng trọ. Agent chỉ có thể cảnh báo rủi ro, còn người thật vẫn phải liên hệ chủ trọ, kiểm tra địa chỉ, đi xem phòng và không chuyển cọc khi chưa chắc chắn.

### 3. Bài học rút ra

* Problem tốt không phải là problem nghe “AI” nhất, mà là problem có actor rõ, workflow thật, bottleneck rõ và metric đo được.
* Một ý tưởng cá nhân tốt vẫn có thể bị thay thế nếu nhóm tìm được bài toán có impact thực tế hơn.
* Vẽ workflow trước/sau giúp tôi hiểu rõ AI nên can thiệp ở bước nào.
* Rule chỉ phù hợp khi dữ liệu sạch và có cấu trúc. Với dữ liệu Facebook/TikTok có nhiều text tự do, viết tắt, thiếu địa chỉ hoặc thiếu giá, Rule không đủ mạnh.
* Agent phù hợp với bài toán nhóm vì có nhiều bước liên tục: nhận nhu cầu, thu thập listing, bóc tách thông tin, gọi map, tính điểm, tạo shortlist và cảnh báo rủi ro.
* Tuy nhiên, Agent không phải là “tự động làm hết”. Agent vẫn cần boundary rõ và human review.

### 4. Nếu làm lại, tôi sẽ đổi gì

* Tôi sẽ chuẩn bị sớm hơn một bộ dữ liệu nhỏ gồm 10–20 tin phòng trọ thật hoặc giả lập để test khả năng bóc tách của AI.
* Tôi sẽ hỏi thêm nhiều người từng đi học/làm xa nhà để có evidence tốt hơn về thời gian tìm phòng và rủi ro thường gặp.
* Tôi sẽ thử mini-pilot: đưa 5–10 tin phòng trọ vào AI, kiểm tra xem AI trích xuất giá, khu vực, tiện ích, khoảng cách và dấu hiệu rủi ro có chính xác không.
* Tôi cũng sẽ làm rõ hơn phần MVP: giai đoạn đầu có thể dùng Workflow bán thủ công trước, sau đó mới nâng cấp lên Agent hoàn chỉnh.

---

## Kết luận ngắn

AI giúp tôi brainstorm, cấu trúc hóa problem, viết workflow và so sánh Rule / Workflow / Agent nhanh hơn. Tuy nhiên, phần quan trọng nhất vẫn là tôi phải tự kiểm tra xem problem có thật không, metric có hợp lý không, boundary có đủ an toàn không và quyết định cuối có phù hợp với phạm vi lab không.

Qua lab này, tôi học được rằng **AI hỗ trợ tư duy, nhưng không thay thế judgment của người học**. Với bài toán tìm phòng trọ tối ưu, Agent có thể tạo giá trị lớn ở bước bóc tách dữ liệu phi cấu trúc và tạo shortlist, nhưng người dùng vẫn phải xác minh thông tin và chịu trách nhiệm với quyết định cuối cùng.

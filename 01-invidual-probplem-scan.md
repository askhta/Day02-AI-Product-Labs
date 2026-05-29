# 01 — PROBLEM SCAN (Cá nhân)

> **Trách nhiệm:** Cá nhân  
> **Điểm:** 15 điểm (Scan Breadth + Quick Cards)  
> **Deadline:** Cuối Phase 1 + Phase 2

---

## Thông tin cá nhân(context)

Tôi là sinh viên năm cuối ngành Data Science. Công việc hằng tuần gồm:
Làm đồ án tốt nghiệp (ML project)
Viết báo cáo tiến độ cho giảng viên
Ôn thi Big Data, Deep Learning, NLP
Tham gia seminar nghiên cứu và thảo luận nhóm
Chuẩn bị CV/portfolio để xin việc
---

## Phase 1 — Scan: 5+ Bài toán (dùng 4 Lenses)



### Danh sách bài toán của tôi

| # | Lens | Bài toán |
| 1 | Lặp lại | Mỗi tuần phải làm exploratory data analysis (EDA) cho dataset mới, thao tác giống nhau |
| 2 | Lặp lại | Copy kết quả từ Jupyter Notebook sang PowerPoint để thuyết trình seminar |
| 3 | Tốn thời gian | Viết báo cáo tiến độ đồ án bằng LaTeX/Overleaf, mất 2–3 giờ để format |
| 4 | Tốn thời gian | Tìm tài liệu tham khảo trên Google Scholar, đọc abstract mất nhiều thời gian |
| 5 | AI có thể tốt hơn | Tóm tắt paper nghiên cứu để rút ra insight chính cho seminar |
| 6 | AI có thể tốt hơn | Sinh code mẫu cho preprocessing (missing values, scaling) thay vì viết tay mỗi lần |
| 7 | Pain từ người khác | Nhóm trưởng phàn nàn: code thiếu chú thích, khó review và tích hợp |
| 8 | Pain từ người khác | Giảng viên hỏi: “Em đã thử baseline chưa?” nhưng chưa có notebook chuẩn để trả lời nhanh |
| 9 | Tốn thời gian | Chuẩn bị CV/portfolio, phải chỉnh nhiều version cho từng công ty |
| 10 | Lặp lại | Viết standup update cho nhóm nghiên cứu mỗi tuần — cùng format, copy-paste từ log |

> **💡 Self-check I1.1 — Scan Breadth**
> - [v] Có ít nhất 5 bài toán
> - [v] Dùng ít nhất 3/4 lenses
> - [v] Bài toán đến từ workflow thật, không chung chung
> - [v] Có ghi rõ ai bị ảnh hưởng (stakeholder)

---

## Phase 2 — Quick-Assess: 3 Quick Problem Cards

Chọn **top 3 bài toán** từ danh sách trên. Với mỗi bài, điền **Quick Problem Card** theo template dưới:

### Card #1 

┌──────────────────────────────────────────────────┐
│ QUICK PROBLEM CARD #1                            │
│                                                  │
│ Bài toán: Mỗi tuần phải làm EDA cho dataset mới, │
│ thao tác giống nhau (cleaning, visualize, stats) │
│ mất ~90 phút/dataset                             │
│                                                  │
│ Ai đang đau? Sinh viên (tôi), nhóm nghiên cứu    │
│                                                  │
│ Workflow hiện tại:                               │
│   1. Load CSV → 2. Check missing → 3. Scale data │
│   → 4. Plot histograms → 5. Summary stats        │
│                                                  │
│ Bước nào tốn nhất? Bước 4-5 (⏱ 45 min/lần)      │
│                                                  │
│ AI có thể giúp ở bước nào? Bước 2-5              │
│ (auto-detech dirty data + auto-EDA report)       │
│                                                  │
│ Đo thành công bằng gì?                           │
│ Giảm thời gian từ 90 min → dưới 30 min/dataset   │
│                                                  │
│ Quick gut: ☑ LLM + AutoML Feature                │
└──────────────────────────────────────────────────┘
```

### Card #2


┌──────────────────────────────────────────────────┐
│ QUICK PROBLEM CARD #2                            │
│                                                  │
│ Bài toán: Đọc paper dài 10-15 trang để chuẩn bị  │
│ seminar, mất ~120 phút/paper                      │
│                                                  │
│ Ai đang đau? Sinh viên (tôi), nhóm seminar       │
│                                                  │
│ Workflow hiện tại:                               │
│   1. Tìm paper → 2. Đọc toàn bộ → 3. Ghi chú     │
│   → 4. Viết summary → 5. Chuẩn bị slide          │
│                                                  │
│ Bước nào tốn nhất? Bước 2-3 (⏱ 60 min/lần)       │
│                                                  │
│ AI có thể giúp ở bước nào? Bước 2-4              │
│ (tóm tắt + highlight key contributions)          │
│                                                  │
│ Đo thành công bằng gì?                           │
│ Giảm thời gian đọc từ 120 min → dưới 45 min      │
│                                                  │
│ Quick gut: ☑ LLM Summarization                   │
└──────────────────────────────────────────────────┘



### Card #3 

┌──────────────────────────────────────────────────┐
│ QUICK PROBLEM CARD #3                            │
│                                                  │
│ Bài toán: Chuẩn bị CV/portfolio cho từng công ty │
│ mất ~2 giờ chỉnh sửa mỗi lần                     │
│                                                  │
│ Ai đang đau? Sinh viên (tôi), nhà tuyển dụng     │
│                                                  │
│ Workflow hiện tại:                               │
│   1. Copy CV gốc+tất cả poject → 2. Chỉnh wording|
|    → 3. Thêm project phù hợp → 4. Format lại     |
|     → 5. Xuất PDF                                |
│                                                  │
│ Bước nào tốn nhất? Bước 2-3 (⏱ 90 min/lần)       │
│                                                  │
│ AI có thể giúp ở bước nào? Bước 2-3              │
│ (tái viết mô tả, chọn project phù hợp JD)        │
│                                                  │
│ Đo thành công bằng gì?                           │
│ Giảm thời gian từ 120 min → dưới 30 min          │
│                                                  │
│ Quick gut: ☑ LLM Personalization                 │
└──────────────────────────────────────────────────┘


> **💡 Self-check I2 — Quick Cards**
> - [v] 3 cards đầy đủ thông tin, không mơ hồ
> - [v] Mỗi card có workflow rõ (5-6 bước)
> - [v] Mỗi card có stakeholder cụ thể
> - [v] Metric có thể đo được
> - [v] Quick guess về solution level có logic

---

## Phần Kill Rationale 

| Card | Quyết định | Lý do |
| #2 | ✅ Chọn | Paper summary (tóm tắt lúc đọc) là pain point rõ, cho giá trị nhanh khi làm seminar. |
| #3 | ❌ Loại | CV/portfolio cá nhân quá mở rộng với giới hạn lab, dễ lan rộng scope, nên loại để tập trung nhóm. |

---
#PITCH-CHALLENGE-VOTE
## TôI pitch Card #2
Mỗi lần chuẩn bị seminar, tôi mất khoảng 120 phút để đọc một paper 10–15 trang. Phần tốn nhất là đọc + ghi chú vì phải tự lọc ý chính và hiểu đóng góp của paper. Nếu giải được bước này thì có thể giảm thời gian xuống còn dưới 45 phút.

[INDIVIDUAL SIGNAL] Một học viên được chấm cao ở phần này khi:

- **Pitch rõ problem → workflow → bottleneck → metric**: Học viên cần trình bày logic từ vấn đề gốc (problem) đến quy trình hiện tại (workflow), điểm nghẽn (bottleneck), và cách đo lường thành công (metric). Ví dụ, với Card #2, pitch cần bắt đầu từ "đọc paper tốn 120 phút" → mô tả workflow 5 bước → chỉ ra bottleneck ở bước 2-3 → kết thúc bằng metric "giảm xuống dưới 45 phút". Điều này chứng minh tư duy problem-first, không solution-first.

- **Trả lời challenge không lảng tránh**: Khi bạn bè thách thức (challenge), học viên phải đối mặt trực tiếp, không né tránh bằng câu chung chung như "đúng vậy". Thay vào đó, giải thích lý do tại sao card này vẫn valid, hoặc chấp nhận điều chỉnh nếu challenge hợp lý. Ví dụ, nếu ai đó nói "paper summary có thể sai", bạn trả lời "đúng, nhưng có thể dùng AI với human check để đảm bảo accuracy".

- **Chấp nhận kill card nếu hợp lý**: Học viên phải linh hoạt, sẵn sàng loại bỏ card nếu nhóm quyết định tập trung vào bài khác tốt hơn. Điều này thể hiện teamwork và tư duy chiến lược, không cố chấp với ý tưởng cá nhân. Ví dụ, loại Card #3 vì scope quá rộng, tập trung vào Card #2 cho seminar.

[GROUP SIGNAL] Một nhóm được chấm tốt khi:

- **Không chọn bài trivial**: Nhóm tránh bài toán quá đơn giản, dễ giải mà không cần AI hoặc không có giá trị thực tế. Ví dụ, không chọn "copy-paste từ Excel" nếu chỉ mất 5 phút, mà chọn bài như EDA hoặc paper summary có impact lớn hơn.

- **Không chọn bài "ngầu nhưng không làm nổi"**: Nhóm không chọn bài toán nghe hay (ví dụ "AI cho toàn trường") nhưng không khả thi trong lab (không có data, time, resource). Thay vào đó, chọn bài có giải pháp AI thực tế như LLM summarization cho paper.

- **Có kill rationale rõ ràng**: Nhóm cần giải thích tại sao chọn/loại từng card, không chỉ "thích" mà phải dựa trên evidence như ROI, feasibility, alignment với lab goal. Ví dụ, chọn Card #2 vì pain point rõ và AI solution sẵn có, loại Card #3 vì scope cá nhân quá rộng.

## 🤖 AI Sử Dụng (ghi để reflection sau)

> Ghi lại dưới đây để chuẩn bị cho **Reflection Log** (Phase 6)

- AI tool nào dùng?
  - GitHub Copilot: dùng để gợi ý cấu trúc folder và nội dung template file. 
  - Claude: dùng để mở rộng ý tưởng, viết các khối giải thích cho từng Card.
  - ChatGPT (hoặc Copilot Chat): dùng để polish câu, check logic, sửa câu tiếng Việt.

- Prompt gì dùng?
  - "Tạo folder lab 'submission-template' với 4 file markdown cho Day 02 lab, gồm 01 problem scan, 02 deep dive, 03 AI log, 04 workflow diagram" (Copilot)
  - "Viết nội dung phase 1/phase 2 dựa trên 4 lens, và 3 Quick Problem Cards model" (Claude)
  - "Chuyển phần AI log thành đoạn long-format có bullet rõ ràng, lưu ý cách viết reflective" (ChatGPT)

- Output AI có giúp không? Tại sao?
  - Rất hữu ích: AI đã giúp tạo nhanh template đầy đủ cấu trúc, tiết kiệm nhiều thời gian so với viết tay.
  - AI gợi ý flow logic tốt, không bị bỏ sót gate G1-G4, giúp xây dựng framework chấm điểm cơ bản.
  - Có chỗ cần chỉnh: I phải sửa lại câu từ để phù hợp ngữ cảnh sinh viên, và cập nhật thời gian/chi tiết trong card cho đúng nhu cầu.

- AI sai/hời hợt chỗ nào? Bạn sửa gì?
  - Copilot ban đầu ghi rõ thời gian 60 phút cho card 1 nhưng user điều chỉnh thành 90 phút (thực tế đúng workflow của mình), vậy cần fix lại.
  - Claude đưa ra một số giải pháp quá chung chung, mình phải tinh chỉnh thành case rõ (EDA, paper summary, CV personalization).
  - AI chưa ráp sát Phase 3 (pitch, challenge) nên mình đã thêm phần "Lý do pitch card #2" bằng tay.

- Ghi chú thêm:
  - Từ yêu cầu của tutor/coach, tôi chuyển phương án cuối: chọn 2 card, loại #3 vì scope không phù hợp.
  - Phần này nên giữ làm note khi làm video/nộp report, nhớ ghi thời gian hoàn thành (timestamp) và feedback sau buổi lab.


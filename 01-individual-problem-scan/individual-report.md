# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Nguyễn Đình Lâm Phúc
- Mã học viên: 2A202602986
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): Phúc, sinh viên năm 4, intern AI thực chiến đại học VinUni. Mỗi tuần Phúc lên trường học trong ngày và tối về build phase.
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
  + Check lịch học hàng ngày và nhiệm vụ trong ngày.
  + Xem lại video và slide bài giảng tìm kiếm kiến thức đã quên.
  + Luyện tập ôn lại kiến thức.
  + Tìm kiếm trang nộp bài để nộp deadline.

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 |Lặp lại|Mỗi ngày phải check lịch học và nhiệm vụ cần làm |Bản thân |Lặp lại mỗi ngày |
| 2 |Tốn thời gian |Phải xem lại slide và video bài giảng dài để tìm kiếm thông tin bài học |Bản thân |Tốn tầm 60 phút/ngày |
| 3 |AI có thể tốt hơn |Sau mỗi buổi học lý thuyết cần tự tổng hợp câu hỏi để tập luyện |Bản thân |Tốn tầm 30 phút/lần |
| 4 |Pain từ người khác |Đến hạn nộp các bài tập thì khó để tìm được cách nộp bài |Học viên |Có 3-5 câu hỏi trong 1 lần nộp |
| 5 |Lặp lại |Khi bắt đầu buổi học cần xem lại buổi học trước đã học đến đâu |Bản thân |Lặp lại mỗi buổi học mới |
| 6 |Tốn thời gian |Đến giờ ăn trưa cần phãi xếp hàng rất lâu mới lấy được thức ăn |Học viên |Tốn 30 phút/bữa |
| 7 | | | | |
| 8 | | | | |
| 9 | | | | |
| 10 | | | | |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi:
- Ý dùng được:
- Ý bỏ vì không phải pain thật:

**Self-check Phase 1:**
- [ ] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [ ] Dùng ít nhất 3/4 lăng kính
- [ ] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 |Check lịch học và nhiệm vụ |Mất nhiều thời gian, actor cụ thể |Thông tin cập nhật nhiều dễ bị nhầm lẫn khi check |
| 2 |Tìm kiếm thông tin bài giảng |Có pain thật, AI có thể giúp tóm tắt |Qúa nhiều lý thuyết gây ra khó tổng hợp |
| 3 |Ăn trưa |Có actor cụ thể, mất thời gian, phiền toái lớn cần phải được giải quyết |Khó tìm kiếm thông tin quán ăn và đơn giá đầy đủ |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — [Check lịch học]

```text
Problem 1 câu:
 Mỗi ngày Phúc phải đọc thông báo từ nhiều nguồn để check lịch học và nhiệm vụ cần làm, trong đó việc xem thông báo dễ gây nhầm lẫn và tốn thời gian.
Actor: Học viên tham giá khóa học.

Thời điểm / bối cảnh: Mỗi ngày có buổi học.

Current workflow 3-7 bước:
1.Mở các trang thông tin và mail
2.Tìm kiếm thông báo từ lab coach hay ban đào tạo
3.Kiểm tra sự thay đổi và cập nhật mới
4.Tổng hợp lại các thông tin bị thay đổi
5.Lập bảng biểu và nhiệm vụ trong ngày 

Bottleneck:
Bước 3 - Kiểm tra thông tin thay đổi hay bị nhầm lẫn do có nhiều cập nhật và tốn 15 phút mỗi lần.
Impact:
Có thể tốn đến 30 phút/ngày và lặp lại mỗi ngày. Đôi khi cũng có sự nhầm lẫn dẫn đến sai lịch
Success metric:
Giảm thời gian kiểm tra xuống 10 phút và giảm tối đa sai sót.
Non-AI alternative:
Tạo một nguồn lịch tập trung duy nhất bằng Calendar/Notion/Excel và quy định format chuẩn cho thông báo thay đổi.
AI hypothesis:
AI hỗ trợ đọc thông báo và tổng hợp thông tin từ đó đề xuất bảng biểu và nhiệm vụ cho học viên.
Quick gut: Workflow

```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — ~30 phút/ngày

[1. Mở các nguồn thông tin: LMS / Email / Group: ~5']
        ↓
[2. Tìm thông báo từ Lab Coach / Ban đào tạo: ~7']
        ↓
[3. Đọc + đối chiếu với thông tin cũ để phát hiện thay đổi: ~10']
        ↓
[4. Tổng hợp các thay đổi quan trọng: ~5']
        ↓
[5. Cập nhật lịch học + nhiệm vụ trong ngày: ~3']
                         ↑
                    BOTTLENECK


FUTURE STATE — mục tiêu ≤10 phút/ngày

[Nguồn thông báo: LMS / Email / Group]
        ↓
[1. Workflow tự động lấy thông báo mới]
        ↓
[2. AI trích xuất thông tin]
        ↓
[3. Hệ thống so sánh với dữ liệu hiện tại]
        ↓
[4. AI tổng hợp các thay đổi cần chú ý: ~1–2']
        ↓
[5. HỌC VIÊN REVIEW + CONFIRM: ~3–5']  ← HUMAN BOUNDARY
        ↓
       ┌───────────┴───────────┐
       ↓                       ↓
   [Đúng]                  [AI sai]
       ↓                       ↓
[Confirm update]          [Sửa thủ công]
       ↓                       ↓
[Cập nhật lịch/task]      [Confirm lại]
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — [Tên problem]

```text
Problem 1 câu:

Actor:

Thời điểm / bối cảnh:

Current workflow 3-7 bước:
1.
2.
3.
4.
5.

Bottleneck:

Impact:

Success metric:

Non-AI alternative:

AI hypothesis:

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — ___ phút

[1 ...] → [2 ...] → [3 ...]  <-- bottleneck

FUTURE STATE — ___ phút

[1 ...] → [2 ...] → [3 ... review]  <-- human boundary

Fallback: ...
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — [Tên problem]

```text
Problem 1 câu:

Actor:

Thời điểm / bối cảnh:

Current workflow 3-7 bước:
1.
2.
3.
4.
5.

Bottleneck:

Impact:

Success metric:

Non-AI alternative:

AI hypothesis:

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — ___ phút

[1 ...] → [2 ...] → [3 ...]  <-- bottleneck

FUTURE STATE — ___ phút

[1 ...] → [2 ...] → [3 ... review]  <-- human boundary

Fallback: ...
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text

```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text

```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text

```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra:
- Tôi sửa gì:

### Self-check nộp phần 01
- [ ] Có 5+ problems + top 3 Cards đủ field
- [ ] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [ ] Đã chọn 1 card pitch + câu hỏi challenge

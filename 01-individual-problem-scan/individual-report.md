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


---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

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

Current workflow 5 bước:
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

**Draft workflow Card #1**:

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

---

#### Problem Card #2 — [Tìm kiếm thông tin bài giảng]

```text
Problem 1 câu:
Sau mỗi buổi học, Phúc phải xem lại slide và video bài giảng dài
để tìm kiếm và tổng hợp những kiến thức cần thiết, khiến việc ôn tập
tốn nhiều thời gian và dễ bỏ sót thông tin quan trọng.
Actor:
Học viên tham gia khóa học.
Thời điểm / bối cảnh:
Sau buổi học hoặc khi cần ôn lại kiến thức để làm bài tập,
project hoặc chuẩn bị cho buổi học tiếp theo.
Current workflow 7 bước:

1. Mở slide và video của buổi học.
2. Xác định phần kiến thức cần tìm hoặc cần ôn.
3. Tìm kiếm thủ công trong slide.
4. Tua/xem lại các đoạn video có khả năng chứa thông tin cần thiết.
5. Đọc/xem lại phần lý thuyết liên quan.
6. Tổng hợp các ý quan trọng thành ghi chú.
7. Sử dụng ghi chú để học hoặc làm nhiệm vụ.

Bottleneck:
Bước 3–6-Học viên phải tìm kiếm thông tin nằm rải rác giữa slide và video.
Video dài khó xác định chính xác đoạn chứa kiến thức cần tìm,
trong khi lượng lý thuyết lớn khiến việc xác định và tổng hợp
ý chính tốn nhiều thời gian.

Impact:
~60 phút/ngày cho việc tìm kiếm, xem lại và tổng hợp. Có khả năng bỏ sót nội dung quan trọng.
Success metric:
 Giảm thời gian tìm kiếm + tổng hợp từ ~60 phút xuống ≤20 phút/ngày.Các nội dung quan trọng vẫn được truy xuất đầy đủ và có thể kiểm tra lại từ slide/video gốc.
Non-AI alternative:
Tự tạo note sau mỗi buổi học.Sử dụng Ctrl+F/search trong slide hoặc transcript video.
AI hypothesis:
Nếu AI có thể xử lý slide và transcript của video bài giảng,
xác định các chủ đề và ý chính, sau đó cho phép học viên tìm kiếm
bằng câu hỏi tự nhiên và trả kết quả kèm vị trí trong tài liệu gốc.
Quick gut: Workflow

```

**Draft workflow Card #2:**

```text
CURRENT STATE — ~60 phút/ngày

[1. Mở slide + video bài giảng: ~3']
        ↓
[2. Xác định nội dung cần tìm/ôn lại: ~2']
        ↓
[3. Tìm kiếm trong slide: ~10']
        ↓
[4. Tua + xem lại video để tìm đoạn liên quan: ~25']
        ↓
[5. Đọc/xem lại lý thuyết liên quan: ~10']
        ↓
[6. Tổng hợp và ghi chú kiến thức: ~10']
                 ↑
             BOTTLENECK

FUTURE STATE — mục tiêu ≤20 phút/ngày

[Slide + Video bài giảng]
        ↓
[1. Workflow lấy tài liệu]
        ↓
[2. Hệ thống xử lý:
    Video → Transcript
    Slide → Text
    Nội dung → Topic/Section]
        ↓
[3. Index nội dung theo câu hỏi học viên gửi]
        ↓
[4. Hệ thống tìm các đoạn liên quan: <1']
                 ↓
[5. AI tổng hợp câu trả lời / ý chính: ~1']
                 ↓
[6. Hiển thị nguồn]
                 ↓
[7. HỌC VIÊN REVIEW: ~5–15']  ← HUMAN BOUNDARY
                 ↓
        ┌────────┴────────┐
        ↓                 ↓
     [Đủ/đúng]      [Thiếu / nghi ngờ]
        ↓                 ↓
 [Lưu vào note]    [Mở slide/video gốc]
                          ↓
                    [Kiểm tra thủ công]
```

---

#### Problem Card #3 — [Ăn trưa]

```text
Problem 1 câu:
Vào giờ ăn trưa, học viên phải mất nhiều thời gian xếp hàng lâu để lấy thức ăn, khiến một phần đáng kể thời gian nghỉ trưa bị lãng phí.
Actor:
Học viên tham gia khóa học.
Thời điểm / bối cảnh:
Đến giờ nghỉ trưa, khi học viên cần lựa chọn lấy đồ ăn trong khoảng thời gian nghỉ có hạn.
Current workflow 7 bước:
1. Đến giờ nghỉ trưa và bắt đầu tìm quán/món ăn.
2. Tìm kiếm thông tin các quán ăn xung quanh.
3. Kiểm tra menu, giá và món đang có.
4. So sánh và quyết định ăn ở đâu / ăn món gì.
5. Di chuyển đến quán.
6. Xếp hàng, gọi món và chờ lấy thức ăn.
7. Lấy đồ ăn.

Bottleneck:
Bước 6-Đến giờ cao điểm, nhiều học viên cùng mua đồ ăn nên phải
xếp hàng và chờ lâu mới nhận được thức ăn.
Impact:
 Có thể tốn khoảng 30 phút/bữa cho việc tìm kiếm, lựa chọn và chờ đợi. Giảm thời gian thực sự dành cho ăn uống/nghỉ ngơi.
Success metric:
 Giảm tổng thời gian từ lúc bắt đầu tìm món đến lúc nhận được đồ ăn. Mục tiêu ban đầu: từ ~30 phút xuống ≤15 phút.
Non-AI alternative:
Tạo danh sách tập trung các quán gần nơi học cùng menu và khoảng giá. Quán chuẩn bị sẵn các suất ăn phổ biến trước giờ nghỉ trưa.
AI hypothesis:
Nếu hệ thống có thể tổng hợp thông tin quán, menu, giá  sau đó đề xuất nhanh các lựa chọn phù hợp với nhu cầu của học viên tại thời điểm ăn trưa, thì thời gian tìm kiếm và lựa chọn món có thể giảm đáng kể.
Quick gut: WORKFLOW
```

**Draft workflow Card #3:**

```text
CURRENT STATE — ~30 phút/bữa

[1. Đến giờ nghỉ trưa: ~1']
        ↓
[2. Tìm quán ăn / hỏi bạn bè / xem thông tin: ~5']
        ↓
[3. Kiểm tra món + giá: ~3']
        ↓
[4. Chọn quán và món: ~3']
        ↓
[5. Di chuyển đến quán: ~5']
        ↓
[6. Xếp hàng + gọi món + chờ nhận đồ ăn: ~13']
                         ↑
                    BOTTLENECK

FUTURE STATE — mục tiêu ≤15 phút

[1. Đến giờ ăn trưa]
        ↓
[2. Mở hệ thống danh sách quán]
        ↓
[3. Xem thông tin quán]
        ↓
[4. Chọn món: ≤3']
        ↓
[5. Đặt món trước]
        ↓
[6. Học viên di chuyển đến quán]
        ↓
[7. Xác nhận đơn + nhận món: ≤2–5']
        ↓
[HỌC VIÊN KIỂM TRA ĐƠN] ← HUMAN BOUNDARY
```

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem #2 — Tìm kiếm và tổng hợp kiến thức từ slide/video bài giảng
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Workflow này lặp lại gần như sau mỗi buổi học. Hiện quá trình có
thể tốn khoảng 60 phút/ngày; mục tiêu là giảm xuống ≤20 phút/ngày.
Impact không chỉ là tiết kiệm khoảng 40 phút/ngày mà còn giúp học viên
tìm đúng kiến thức nhanh hơn, giảm việc xem lại những đoạn không cần
thiết và dành nhiều thời gian hơn cho thực hành/bài tập.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. Trong ~60 phút hiện tại, bottleneck thực sự nằm ở việc "tìm đúng
thông tin" hay ở việc "hiểu và tổng hợp kiến thức"?
2. AI có thực sự cần thiết không, hay transcript + timestamp + search
thông thường đã giải quyết đủ phần lớn pain?
```



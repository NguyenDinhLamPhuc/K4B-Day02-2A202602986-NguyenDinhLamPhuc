# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Nguyễn Đình Lâm Phúc
- Mã học viên: 2A202602986
- Nhóm: 5AE
- Candidate problem nhóm chọn: Gom deadline và yêu cầu lab từ Vlearn, README, worksheet, Discord và GitHub thành checklist cần làm.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân |Tìm các vấn đề gặp được trong cuộc sống |Đã liệt kê được 6 problems qua đó đề xuất ý tưởng cho nhóm |
| Pitch Problem Card |Đi tìm problem muốn pitch nhất, giải thích lý do |Đề xuất được ý tưởng hay nhất cho nhóm và cũng đưa được câu hỏi muốn nhóm trả lời |
| Challenge bài của bạn khác |Trả lời câu hỏi của các bạn trong nhóm |Bổ sung được các phần thiếu sót của nhau khiến cho giải pháp hoàn thiện hơn |
| Gom trùng / cluster |Gom các ý tưởng bị trùng theo nội dung |Tìm ra được vấn đề nào nhiều người cùng gặp phải và cần giải quyết |
| Chọn candidate problem |Bàn bạc với các bạn trong nhóm để tìm ra vấn đề hoàn thiện và cấp bách nhất để giải quyết |Xác định được mục tiêu và vấn đề cần giải quyết |
| Validation / research |Tìm kiếm các giải pháp hay lời giải đã có trên mạng để giải quyết vấn đề |Góp phần tìm các ý tưởng đã có để học hỏi và hoàn thiện |
| Workflow nhóm |Phát biểu ý kiến để hoàn thiện workflow, xác định xem phần nào cần AI và cần con người can thiệp |Hoàn thiện lên 1 hệ thống luồng giải quyết vấn đề |
| Problem Statement |hỏi AI để phản biện lại nội dung của Problem Statement v0 |Hoàn thiện nội dung của Problem Statement v0 hướng tới xây dựng v1 |
| Rule / Workflow / Agent |Góp ý xác định ma trận độ phù hợp |Tạo điều kiện chọn workflow cho phương án |
| Decision |Trả lời 1 số câu hỏi trong bảng đề xuất |Từ câu trả lời đó mà nhóm chọn được decision của mình |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất của tôi là tham gia xác định, phản biện và hoàn thiện problem từ Problem Card đến Problem Statement và workflow. Tôi cũng đóng góp research giải pháp có sẵn và xác định mức độ ứng dụng AI phù hợp cho bài toán.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan |không dùng | | | |
| Problem Card |Hỗ trợ chuẩn hóa  Workflow, Metric, Non-AI alternative và AI hypothesis. |Giúp biến pain ban đầu thành problem có cấu trúc và dễ so sánh. |AI đôi khi giả định nguyên nhân hoặc metric khi chưa có bằng chứng. |Tôi bổ sung workflow, thời gian thực tế và bottleneck dựa trên trải nghiệm của mình. |
| Workflow |Gợi ý Current State và Future State và fallback. |Giúp nhìn rõ AI nên can thiệp vào bước nào và luồng trước/sau thay đổi ra sao. |Thời gian từng bước và một số bước future workflow chỉ là ước lượng. |Tôi giữ tổng thời gian thực tế, điều chỉnh bottleneck và yêu cầu người dùng review trước khi hệ thống cập nhật. |
| Research |Tìm và so sánh các tool/pattern tương tự như structured extraction, source-grounded retrieval và human-in-the-loop. |Giúp biết bài toán đã được giải quyết theo những hướng nào và học được pattern phù hợp. |Một số giải pháp chỉ giải quyết một phần problem và không hoàn toàn giống bối cảnh AI20K. |Tôi tập trung vào khoảng trống của bài toán: requirement nằm ở nhiều nguồn và cần chuyển thành actionable checklist có nguồn kiểm chứng. |
| Problem Statement |Dùng AI phản biện Problem Statement v0 và đề xuất cách viết chặt hơn. |Giúp tách Problem khỏi Solution và làm rõ Actor, Bottleneck, Impact, Metric, Boundary. |AI có xu hướng mở rộng problem hoặc đưa solution vào quá sớm. |Tôi giới hạn scope vào việc gom deadline/yêu cầu lab, không để AI làm lab, tự đánh giá hay tự submit. |
| Rule / Workflow / Agent |Nhờ AI phân tích mức automation phù hợp. |Giúp phân biệt Rule, Workflow và Agent dựa trên độ cố định và autonomy của task. |AI có thể đề xuất Agent/AI phức tạp hơn mức cần thiết nếu chỉ nhìn vào khả năng công nghệ. |Tôi chọn Workflow vì các bước collect → extract → structure → review đã tương đối xác định và chưa cần Agent tự lập kế hoạch. |
| Decision |Dùng AI challenge assumptions và gợi ý tiêu chí Go / Not Yet / No-Go. |Giúp nhìn lại evidence, feasibility, AI necessity và rủi ro trước khi quyết định. |AI không thể tự xác nhận pain và số liệu thực tế của người học. |Tôi kết hợp trải nghiệm cá nhân, ý kiến nhóm và research để quyết định; không coi đánh giá của AI là bằng chứng cuối cùng. |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.
phase scan tôi không dùng AI vì tôi dựa trên trải nghiệm thực tế của mình để viết.
---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text
Qua việc lắng nghe top 3 problems của các thành viên khác, tôi nhận ra một vấn đề tốt không nhất thiết phải sử dụng AI phức tạp mà quan trọng là có pain thực tế, actor rõ ràng và impact đo được. Ban đầu, nhóm có xu hướng nghĩ khá nhiều về việc dùng AI hoặc Agent, nhưng sau khi phân tích workflow, chúng tôi nhận thấy nhiều bước chỉ cần Workflow kết hợp AI là đủ. Tôi cũng thay đổi một số ý kiến sau khi được các thành viên challenge, đặc biệt là việc không nên mặc định AI là giải pháp ngay từ đầu. Thay vào đó, cần xác định bottleneck và kiểm tra các giải pháp non-AI trước khi quyết định mức độ ứng dụng AI.Trong artifact cuối, tôi đóng góp vào việc tìm và pitch problem, phản biện các ý tưởng, research giải pháp đã có và hoàn thiện workflow.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI


# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Nguyễn Minh Thắng
- Mã học viên: 2A202602706
- Nhóm: EasyMessage
- Candidate problem nhóm chọn: Những người làm việc/học tập theo dự án thường xuyên bị lỡ các công việc hoặc thông tin quan trọng do bị trôi tin nhắn trong các nhóm chat có quá nhiều "tiếng ồn" (tin nhắn rác, thảo luận không liên quan).

---

## 1. Tôi đã tham gia vào phần nào?

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tự đưa ra 3 candidate problems (#1 viết tay từng test case tốn thời gian/dễ sót case biên, #2 vẽ diagram/flowchart thủ công tốn thời gian canh layout, #3 lướt mạng xã hội quá nhiều trễ tiến độ task) | Đóng góp 3/18 candidate vào vòng brainstorm ban đầu ở bảng 3.1 |
| Pitch Problem Card | Trình bày 3 candidate trên trong 1-2 phút mỗi bài | Nhóm ghi nhận cảm nhận nhanh "dễ hiểu", "dễ ứng dụng", "có sáng tạo" cho từng bài ở bảng 3.1 |
| Challenge bài của bạn khác | Chọn ngẫu nhiên candidate #8 (lộ trình di chuyển tối ưu kết hợp nhiều phương tiện công cộng, do Vàng đề xuất) để hỏi thử actor và cách đo impact | Câu hỏi giúp nhóm nhận ra actor "người đi làm và sinh viên" hơi rộng, khó đo impact trong lab — góp phần vào lý do candidate này không vào shortlist |
| Gom trùng / cluster | Tham gia gom 18 candidate thành cụm, tự xếp 2 candidate của mình (#1 viết test case, #2 vẽ diagram) vào cùng nhóm với candidate cá nhân hóa email hàng loạt của Tiến Đạt (#10), vì cả 3 đều là thao tác lặp lại tốn thời gian tay | Giúp Cluster C ("thao tác lặp lại cần tự động hóa") rõ pattern chung hơn |
| Chọn candidate problem | Ở bảng chấm điểm 3.4, ủng hộ và đề xuất chốt candidate tin nhắn nhóm chat bị trôi ("send message") vì actor phổ quát nhất, ai trong nhóm cũng từng gặp | Candidate này được chốt là bài final của nhóm |
| Validation / research | Không trực tiếp đi phỏng vấn/khảo sát, nhưng góp ý sửa câu hỏi survey để hỏi rõ tần suất bỏ lỡ tin nhắn thay vì hỏi chung chung "có gặp vấn đề không" | Bảng 4.1 có thêm số liệu tần suất cụ thể (2-3 lần/tuần) thay vì chỉ có/không |
| Workflow nhóm | Trực tiếp dựng bảng workflow hiện tại (7 bước) và workflow tương lai (6 bước) ở mục 5.1-5.2: xác định actor/input/output/thời gian cho từng bước, đánh dấu rõ handoff và bottleneck (bước 2, 7 ở workflow cũ; bước 1, 5 ở workflow mới) | Đây là phần nền để nhóm viết field "Workflow" trong Problem Statement và tính được bảng Before/After impact |
| Problem Statement | Đối chiếu field "Workflow" trong PS v0/v1 với đúng số bước và mốc thời gian đã vẽ ở mục 5, tránh để PS mô tả sai lệch với workflow thật | Field Workflow trong PS v0 và v1 khớp chính xác với sơ đồ 4 bước ở workflow tương lai |
| Rule / Workflow / Agent | Góp ý ở mục 6.1 rằng chỉ 2 bước (phân tích ngữ cảnh, gợi ý tag) mới thực sự cần Agent; các bước còn lại (gom luồng/lọc tin, đồng bộ task, chế độ gác cổng) chỉ cần Rule/Workflow vì đã có luật cố định | Nhóm chốt Agent chỉ áp dụng đúng cho bước 2 & 3 thay vì cả workflow, giảm rủi ro và chi phí không cần thiết |
| Decision | Góp ý ở mục 6.3 nên giới hạn pilot trong 1 nhóm dự án nhỏ (5-10 người, 50 tin nhắn) thay vì test trên cả lớp ngay, để dễ kiểm soát rủi ro gợi ý sai | Kế hoạch pilot nhỏ nhất trong mục 6.3 được chốt đúng theo quy mô này |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Hai bảng workflow ở mục 5.1 (7 bước hiện tại) và 5.2 (6 bước tương lai), cùng bảng Before/After impact — đây là phần tôi trực tiếp tính actor/input/output/thời gian cho từng bước, không chỉ copy gợi ý của AI.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Dùng AI để mở rộng 3 ý tưởng ban đầu (viết test case, vẽ diagram, lướt mạng xã hội) thành mô tả actor/bottleneck đầy đủ hơn | Giúp viết chi tiết hóa ý tưởng, diễn đạt rõ ràng, có cấu trúc | Khi thiếu ngữ cảnh cá nhân, AI mô tả bottleneck chung chung, không đúng quy trình thật của mình | Bổ sung lại bằng ngữ cảnh thực tế bản thân (số case hay bị sót, thời gian thật tốn cho mỗi task) |
| Problem Card | Dùng AI để rút ngắn mô tả candidate cho vừa 1-2 phút pitch | Câu chữ súc tích, dễ trình bày trước nhóm | Khi rút gọn, AI đôi khi làm mất chi tiết quan trọng (ví dụ bỏ mất phần "dễ bỏ sót case biên") | Tự thêm lại chi tiết bị mất trước khi pitch |
| Workflow | Dùng AI để gợi ý cấu trúc bảng actor/input/output/thời gian và gợi ý các bước cho workflow tương lai (Rule/AI/Human) | Dựng khung bảng nhanh, không bỏ sót cột nào | AI ước lượng thời gian mỗi bước hơi lý tưởng hóa (ví dụ "0.5 phút" cho bước fetch context), chưa tính độ trễ xử lý/mạng thật | Tự điều chỉnh lại thời gian dựa trên trải nghiệm dùng các tool tương tự (Slack AI, Teams Copilot) đã research |
| Research | Dùng AI để tìm gợi ý tên các tool/case tương tự (Slack AI, Microsoft Teams Copilot) | Chỉ đúng hướng tìm kiếm nhanh | Một số thông tin AI đưa ra ban đầu không có link kiểm chứng được (giá, tính năng) | Tự tìm lại link chính thức để verify, bỏ số liệu không kiểm chứng được ra khỏi bảng research |
| Problem Statement | Dùng AI để soạn thử field Boundary/Impact cho PS v0 | Câu chữ đầy đủ 2-3 câu đúng format | Field Impact ban đầu AI viết chung chung, không gắn số liệu cụ thể | Tự thêm mốc số liệu cụ thể (5-10 phút → 3 phút, tỷ lệ tag đúng ≥ 85%) lấy từ workflow đã tính |
| Rule / Workflow / Agent | Dùng AI để liệt kê ưu/nhược điểm của Rule/Workflow/Agent cho từng bước | Có khung so sánh nhanh, tránh bỏ sót tiêu chí | AI có xu hướng nghiêng về chọn Agent cho toàn bộ workflow vì nghe "thông minh" hơn, dù nhiều bước không cần | Tự tách lại: chỉ giữ Agent cho đúng bước fetch context + gợi ý tag, các bước còn lại hạ về Rule/Workflow |
| Decision | Dùng AI để gợi ý cấu trúc bảng Final Decision và các câu hỏi Yes/Not Yet/No | Không bỏ sót câu hỏi quan trọng nào trước khi quyết định Go | AI đề xuất pilot quy mô hơi lớn (thử trên cả lớp) ngay từ đầu | Thu hẹp lại thành 1 nhóm nhỏ (5-10 người, 50 tin nhắn) để dễ kiểm soát rủi ro |

---

## 3. Reflection

Chọn 4 câu hỏi sau để trả lời (mỗi câu 2-3 câu):

**1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

```text
Tôi khá bất ngờ với độ đa dạng của 18 ý tưởng, từ vẽ diagram thủ công của chính tôi cho tới cảnh báo MLOps phân tán hay lập lộ trình di chuyển của Vàng. Điều đó cho tôi thấy vấn đề "quá tải thông tin" xuất hiện ở rất nhiều ngữ cảnh khác nhau, không chỉ trong chat nhóm.
```

**2. Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?**

```text
Tôi chọn ngẫu nhiên candidate #8 của Vàng để challenge về actor và cách đo impact, giúp nhóm nhận ra actor quá rộng nên khó đo trong lab, góp phần loại candidate này khỏi shortlist. Ở phần chấm điểm, tôi ủng hộ chốt candidate tin nhắn nhóm chat bị trôi vì ai trong nhóm cũng từng gặp, dễ tự validate ngay trong lớp. Nhưng dấu tay rõ nhất của tôi vẫn là hai bảng workflow (7 bước hiện tại, 6 bước tương lai) và bảng Before/After impact, vì tôi trực tiếp tính actor/input/output/thời gian cho từng bước chứ không chỉ copy gợi ý của AI.
```

**3. Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?**

```text
Có — ở phần Rule/Workflow/Agent, tôi thấy cả nhóm lẫn AI có lúc hơi nghiêng về chọn Agent cho toàn bộ workflow vì nghe "xịn" hơn. Tôi góp ý tách lại: chỉ hai bước phân tích ngữ cảnh và gợi ý tag mới thực sự cần Agent, còn lại nên hạ về Rule/Workflow để giảm rủi ro và chi phí. Khi dùng AI gợi ý thời gian mỗi bước, tôi cũng nhận ra AI ước lượng khá lý tưởng (ví dụ 0.5 phút cho bước fetch context) nên phải tự điều chỉnh lại.
```

**4. Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?**

```text
Tôi nghĩ mình nên challenge kỹ hơn ngay chính candidate mà nhóm mình chọn, đặc biệt là con số tỷ lệ tag đúng 85% ở Problem Statement v1. Đó là con số nhóm đặt ra khá nhanh mà chưa ai hỏi thử nó có thực tế không nếu chưa chạy pilot thật.
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
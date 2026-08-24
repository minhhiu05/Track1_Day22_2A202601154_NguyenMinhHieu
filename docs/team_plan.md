# Plan

Hoàn thiện ba Product Risk & Release Pack độc lập, mỗi hồ sơ bám một ngành khác nhau, rồi dùng cùng một synthesis để rút ra release gate xuyên ngành. Cách làm ưu tiên nguồn primary/peer-reviewed, traceability từ source đến quyết định release, và validation trước khi nộp.

## Scope
- In: Sáu artifact cho mỗi thành viên, case research có thể kiểm chứng, một group synthesis thống nhất, và kiểm tra validator/unit test.
- Out: Xây dựng model hoặc ứng dụng, tuyên bố certification/compliance pháp lý, và sử dụng dữ liệu cá nhân thật.

## Action items
[x] Nguyễn Minh Hiếu: hoàn thiện hồ sơ mobility-autonomous-driving cho trợ lý giám sát an toàn AV, với case NTSB/NHTSA/California DMV.
[x] Nguyễn Ngọc Chi: hoàn thiện hồ sơ healthcare-assistant cho trợ lý phân luồng triệu chứng, với case bias thuật toán, sepsis alert và chatbot sức khỏe.
[x] Phạm Tuấn Anh: hoàn thiện hồ sơ media-news-social-political-assistant cho trợ lý tổng hợp tin công dân, với case Myanmar, political data và moderation.
[x] Chuẩn hóa source IDs, case IDs, harm map và release-blocking gaps để truy vết xuyên sáu artifact của từng hồ sơ.
[x] Chốt một dòng group synthesis: human override có authority và hard guardrail phải là release gate xuyên ba ngành.
[x] Chạy python scripts/validate-lab.py cho từng hồ sơ, python -m unittest discover -s tests -v, và git diff --check.

## Open questions
- Không có câu hỏi chặn tiến độ; ID học viên của Chi và Anh được dùng nhãn team nội bộ, cần thay bằng mã chính thức nếu giảng viên yêu cầu.

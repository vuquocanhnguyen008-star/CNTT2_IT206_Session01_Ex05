# Bài 5: Áp dụng AI Policy & Nguyên tắc Human-in-the-loop trong Đánh giá Nhân sự

## Phần 1: 2 vi phạm nghiêm trọng của Trưởng phòng

### Vi phạm 1: Vi phạm nguyên tắc Human-in-the-loop

Trưởng phòng ký quyết định sa thải ngay khi AI đưa ra danh sách, không thẩm định lại. AI chỉ được hỗ trợ đề xuất, còn quyết định ảnh hưởng đến con người phải do người ra. Việc này là tự động hóa quyết định nhân sự, có thể sai về pháp lý vì AI không có thẩm quyền ra quyết định sa thải.

### Vi phạm 2: Đổ trách nhiệm cho AI và tin AI là "khách quan"

Câu "AI phân tích khách quan nên tôi không can thiệp" là sai. Dữ liệu KPI có thể thiên lệch (Bias), ví dụ nhân viên làm dự án khó, nghỉ thai sản hoặc nghỉ ốm sẽ có KPI thấp. Người ký quyết định vẫn phải chịu trách nhiệm trước nhân viên và pháp luật, vi phạm đạo đức nghề nghiệp (công bằng, minh bạch, có trách nhiệm giải trình).

## Phần 2: Sơ đồ quy trình 3 bước

```
[Bước 1: Nhập dữ liệu]
 Thu thập KPI + lịch sử chấm công,
 ẩn danh thông tin cá nhân nhạy cảm
          ↓
[Bước 2: AI đề xuất]
 AI phân tích, đưa danh sách tham khảo
 (chỉ là gợi ý, không phải quyết định)
          ↓
[Bước 3: Human-in-the-loop thẩm định]
 Trưởng phòng + HR kiểm tra lại: lý do KPI thấp,
 hoàn cảnh nhân viên, đối chiếu quy định, trao đổi trực tiếp
          ↓
[Ký quyết định]
 Con người quyết định và chịu trách nhiệm.
 Nếu thấy AI sai → loại khỏi danh sách.
```

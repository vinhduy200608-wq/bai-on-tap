# BÀI LÀM PHA 2 (ĐỀ LUYỆN TẬP CHỦ ĐỀ CHẠY AFFILIATE)

- **Họ tên:** nguyễn công vinh
- **Lớp:** cntt3
- **Link repository Pha2:**https://github.com/vinhduy200608-wq/bai-on-tap.git
- **Công cụ AI đã dùng (ChatGPT/Claude/Gemini):**

> Pha 2 (20 phút cuối). Mỗi mục: mở cuộc trò chuyện mới, gửi nguyên văn prompt đã viết trong bai_lam_pha1.md, dán câu trả lời và link chia sẻ vào đây. Xong, kéo thả file này vào repository Pha2.

## 4.2. Trích xuất tin nhắn đăng ký gói Affiliate ra JSON

**KET QUA AI**

```text
[
  {
    "ma_goi": "TT",
    "ngay_bat_dau": "2026-12-20",
    "creator_chinh": 2,
    "thuc_tap_sinh": 1,
    "hang_tai_khoan": "thuong",
    "ghi_chu": null
  },
  {
    "ma_goi": "SP",
    "ngay_bat_dau": "2027-01-08",
    "creator_chinh": 3,
    "thuc_tap_sinh": 0,
    "hang_tai_khoan": null,
    "ghi_chu": "Có một bạn đang bó bột chân cần ngồi bàn gần cửa ra vào"
  },
  {
    "ma_goi": "PRO",
    "ngay_bat_dau": null,
    "creator_chinh": 4,
    "thuc_tap_sinh": 0,
    "hang_tai_khoan": "vip",
    "ghi_chu": "cần mượn thêm đèn trợ sáng và phông xanh để quay mẫu"
  }
]
```

**Link trò chuyện:**https://share.gemini.google/fvSHRhCFVui8

## 4.3. Báo giá gói Affiliate bằng Chain-of-Thought

**KET QUA AI**

```text
Tiền Creator chính:Khách hàng chọn gói TT (Gói TikTok Affiliate) có giá 1.500.000 đồng/Creator chính, gồm 4 Creator chính.Phép tính: $4 \times 1.500.000 = 6.000.000$ đồng.Kết quả: 6.000.000 đồng.Tiền thực tập sinh:Có 2 thực tập sinh (16 tuổi và 17 tuổi, thuộc nhóm từ 15 đến dưới 18 tuổi nên tính 60% giá Creator chính: $1.500.000 \times 60\% = 900.000$ đồng/người). Bé 7 tuổi dưới 15 tuổi ngồi khu chờ được miễn phí ($0$ đồng).Phép tính: $2 \times (1.500.000 \times 60\%) = 2 \times 900.000 = 1.800.000$ đồng.Kết quả: 1.800.000 đồng.Tổng tiền gói:Cộng tiền Creator chính và tiền thực tập sinh (chưa giảm giá).Phép tính: $6.000.000 + 1.800.000 = 7.800.000$ đồng.Kết quả: 7.800.000 đồng.Giảm giá team:Team có 4 Creator chính (từ 4 Creator chính trở lên), được giảm 10% trên tổng tiền gói.Tiền được giảm: $7.800.000 \times 10\% = 780.000$ đồng.Tiền gói sau giảm: $7.800.000 - 780.000 = 7.020.000$ đồng.Kết quả: Giảm 780.000 đồng, tiền gói sau giảm còn 7.020.000 đồng.Phụ thu thuê mic:Team thuê thêm 2 bộ mic thu âm không dây, đơn giá 250.000 đồng/bộ, không áp dụng giảm giá.Phép tính: $2 \times 250.000 = 500.000$ đồng.Kết quả: 500.000 đồng.Tổng tiền:Cộng tiền gói sau giảm và phụ thu thuê mic.Phép tính: $7.020.000 + 500.000 = 7.520.000$ đồng.Kết quả: 7.520.000 đồng.[RESULT: 7.520.000 đồng]

```

Dưới đây là chi tiết suy luận và tính toán báo giá theo đúng trình tự yêu cầu:


**Link trò chuyện:** https://share.gemini.google/uPyYO71bFX9S

### b) Kiểm tra kết quả AI

AI trả ra kết quả đúng 

## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
{
  "loai_su_co": "sai_phong",
  "so_khach": 3,
  "so_ca_bi_anh_huong": 2,
  "tom_tat": "Bị xếp nhầm sang phòng học thường thiếu đèn livestream và ồn trong 2 ca thực hành đầu."
}
```

**Link trò chuyện:** https://share.gemini.google/Hf0kuYu4e9pa

## 4.5. Prompt chấm bài theo Rubric

**KET QUA AI**

```text
| Tiêu chí | Điểm | Minh chứng | Đề xuất sửa |
| --- | --- | --- | --- |
| **Đúng thông tin (50%)** | **0.0/5.0** | **Lỗi 1:** |  |



* **Câu bị lỗi:** "Gói TikTok Affiliate bên mình giá chỉ 1.200.000đ/người thôi"



* **Lý do sai:** Báo sai giá niêm yết của gói TT (thông tin chuẩn là 1.500.000 đồng/Creator chính).





**Lỗi 2:**



* **Câu bị lỗi:** "Bạn báo huỷ trước 5 ngày thì được hoàn lại đủ 100% tiền nha"



* **Lý do sai:** Sai chính sách hoàn tiền (huỷ từ 3 đến 6 ngày chỉ được hoàn 50%; muốn hoàn 100% phải báo huỷ trước từ 7 ngày trở lên). | **Sửa lỗi 1:**



* **Câu sửa đề xuất:** "Gói TikTok Affiliate (gói TT) tại VietAffiliate hiện có mức phí là 1.500.000 đồng/Creator chính ạ."





**Sửa lỗi 2:**



* **Câu sửa đề xuất:** "Về chính sách huỷ đăng ký: nếu bạn báo huỷ trước ngày bắt đầu từ 7 ngày trở lên sẽ được hoàn 100% học phí; từ 3 đến 6 ngày hoàn 50%; và dưới 3 ngày sẽ không hoàn tiền ạ." |
| **Đầy đủ (30%)** | **1.5/3.0** | **Lỗi 1:**



* **Câu bị lỗi:** Toàn bộ nội dung bài tư vấn (thiếu lời mời cung cấp thông tin ở phần kết).



* **Lý do sai:** Đã trả lời đủ 2 nội dung (giá gói và chính sách huỷ) nhưng thiếu bước mời khách hàng cung cấp ngày đợt thực chiến và số lượng suất muốn đăng ký. | **Sửa lỗi 1:**



* **Câu sửa đề xuất:** Bổ sung câu kết: "Để VietAffiliate hỗ trợ giữ suất và lên lịch phù hợp nhất, bạn vui lòng cho mình biết ngày đợt thực chiến dự kiến và số lượng suất bạn muốn đăng ký nhé!" |
| **Giọng điệu (20%)** | **0.0/2.0** | **Lỗi 1:**



* **Câu bị lỗi:** "Dạ hello bạn nha!" và "cứ chốt lẹ kẻo hết slot nè!"



* **Lý do sai:** Sử dụng ngôn từ suồng sã, thiếu tính chuyên nghiệp trong giao tiếp tư vấn khách hàng.





**Lỗi 2:**



* **Câu bị lỗi:** "đăng ký xong gắn link là nổ đơn hoa hồng trăm triệu luôn ạ."



* **Lý do sai:** Vi phạm quy định khi đưa ra cam kết doanh thu/hoa hồng ảo, phóng đại kết quả. | **Sửa lỗi 1:**



* **Câu sửa đề xuất:** Thay lời chào bằng: "Chào bạn, cảm ơn bạn đã quan tâm đến các chương trình đào tạo tại VietAffiliate." và thay lời kêu gọi bằng: "Bạn có thể phản hồi sớm để bên mình hỗ trợ hoàn tất thủ tục đăng ký nhé."





**Sửa lỗi 2:**



* **Câu sửa đề xuất:** "Khi tham gia gói, bạn sẽ được hướng dẫn quy trình xây kênh và gắn link tiếp thị bài bản để tối ưu hiệu quả chuyển đổi đơn hàng ạ." |
| **Tổng điểm** | **1.5/10** | Bài tư vấn sai lệch hoàn toàn dữ liệu chuẩn (giá gói, chính sách hoàn tiền), thiếu thông tin khai thác nhu cầu khách hàng, giọng điệu suồng sã và cam kết hoa hồng sai quy định. | Cần điều chỉnh lại toàn bộ thông số theo đúng quy định của VietAffiliate, bổ sung câu hỏi khai thác thông tin đăng ký và sử dụng văn phong chuyên nghiệp, chuẩn mực. |
```

**Link trò chuyện:** https://share.gemini.google/68ehD7gjanUq

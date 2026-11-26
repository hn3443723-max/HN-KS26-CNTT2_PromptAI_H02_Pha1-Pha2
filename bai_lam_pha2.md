# BÀI LÀM PHA 2 – HACKATHON 02

- **Mã đề:** 04
- **Họ tên:Nguyễn Đức Hiếu**
- **Lớp:HN-KS26**
- **Link repository Pha2:https://github.com/hn3443723-max/HN-KS26-CNTT2_PromptAI_H02_Pha1-Pha2.git**
- **Công cụ AI đã dùng (ChatGPT/Claude/Gemini):ChatGPT**

> Pha 2 (20 phút cuối). Mỗi mục: mở cuộc trò chuyện mới, gửi nguyên văn prompt đã viết trong bai_lam_pha1.md, dán câu trả lời và link chia sẻ vào đây. Xong, kéo thả file này vào repository Pha2.

## 4.2. Trích xuất tin nhắn đặt vé xe ra JSON

**KET QUA AI**

```text
[
{
"ma_tuyen": "SGDL",
"ngay_di": "2026-12-22",
"ve_nguoi_lon": 2,
"ve_tre_em": 1,
"loai_cho": "giuong",
"ghi_chu": null
},
{
"ma_tuyen": "SGNT",
"ngay_di": "2027-01-02",
"ve_nguoi_lon": 3,
"ve_tre_em": 0,
"loai_cho": null,
"ghi_chu": "một người đang mang thai 6 tháng"
},
{
"ma_tuyen": "SGCT",
"ngay_di": null,
"ve_nguoi_lon": 4,
"ve_tre_em": 0,
"loai_cho": "ghe",
"ghi_chu": "bà nội đi xe lăn"
}
]
```

**Link trò chuyện:https://chatgpt.com/share/6b079dc2-2eb8-83ec-823c-89351d73a23c**

## 4.3. Báo giá bằng Chain-of-Thought

**KET QUA AI**

```text
Tiền vé người lớn: 8 × 320.000 = 2.560.000 đồng
Tiền vé trẻ em: 3 × (320.000 × 75%) = 3 × 240.000 = 720.000 đồng
Bé 2 tuổi ngồi cùng người lớn nên miễn phí.
Tiền vé trước giảm: 2.560.000 + 720.000 = 3.280.000 đồng
Giảm giá đoàn 5%: 3.280.000 × 5% = 164.000 đồng
Tiền vé sau giảm: 3.280.000 − 164.000 = 3.116.000 đồng
Phụ thu hành lý: 2 × 100.000 = 200.000 đồng
Tổng tiền: 3.116.000 + 200.000 = 3.316.000 đồng
```

**Link trò chuyện:https://chatgpt.com/share/6b079e43-4f88-83ec-a4b1-7bc1c9906711**

### b) Kiểm tra kết quả AI

(Ghi kết luận AI đúng hay sai; nếu sai, ghi bước sai đầu tiên và kết quả đúng của bước đó – xoá dòng này)

## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
{"loai_su_co":"sai_loai_xe","so_khach":3,"so_chang_bi_doi":2,"tom_tat":"Đặt giường nằm nhưng cả hai chặng đều bị đổi sang xe ghế ngồi"}
```

**Link trò chuyện:https://chatgpt.com/share/6b079ea8-d430-83ec-8ed0-dbb2a6275ec8**

## 4.5. Prompt chấm bài theo Rubric

**KET QUA AI**

```text
| Tiêu chí | Điểm | Minh chứng | Đề xuất sửa |
|---|---|---|---|
| Đúng thông tin (50%) | 5,0/5 | Có nêu giá 350.000đ và chính sách đổi trước 12 tiếng, nhưng chưa có thông tin chuẩn để xác minh tính chính xác. | Đối chiếu và nêu đúng giá, chính sách huỷ/đổi theo quy định công ty. |
| Đầy đủ (30%) | 1,5/3 | Trả lời về giá và chính sách đổi vé nhưng không mời khách cung cấp ngày trận đấu, số lượng vé để đặt. | Bổ sung yêu cầu ngày trận đấu và số lượng vé. |
| Giọng điệu (20%) | 1,0/2 | Có chào hỏi, nhưng dùng từ khá suồng sã như “xe xịn lắm luôn”, “nhắn em liền”. | Dùng ngôn ngữ lịch sự, chuyên nghiệp và tránh cách diễn đạt suồng sã. |
| **Tổng điểm** | **7,5/10** |  |  |
```

**Link trò chuyện:https://chatgpt.com/share/6b079faf-4fa0-83ec-b756-1554f3ac049f**

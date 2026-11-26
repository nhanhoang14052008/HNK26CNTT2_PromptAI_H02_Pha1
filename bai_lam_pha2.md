# BÀI LÀM PHA 2 – HACKATHON 02

- **Mã đề:** 06
- **Họ tên:Nguyễn Hoàng Trí Nhân**
- **Lớp:CNTT2**
- **Link repository Pha2:https://github.com/nhanhoang14052008/HNK26CNTT2_PromptAI_H02_Pha1.git**
- **Công cụ AI đã dùng ChatGPT:**

> Pha 2 (20 phút cuối). Mỗi mục: mở cuộc trò chuyện mới, gửi nguyên văn prompt đã viết trong bai_lam_pha1.md, dán câu trả lời và link chia sẻ vào đây. Xong, kéo thả file này vào repository Pha2.

## 4.2. Trích xuất tin nhắn đặt bàn ra JSON

**KET QUA AI**

```text
TN1:
{
  "ma_buffet": "NUONG",
  "ngay_dat": "2026-12-19",
  "nguoi_lon": 2,
  "tre_em": 1,
  "khu_vuc": "trong_nha",
  "ghi_chu": null
}


TN2:
{
  "ma_buffet": "HAISAN",
  "ngay_dat": "2027-01-03",
  "nguoi_lon": 3,
  "tre_em": 0,
  "khu_vuc": null,
  "ghi_chu": "1 người dị ứng sữa"
}


TN3:
{
  "ma_buffet": "LAU",
  "ngay_dat": "2026-12-25",
  "nguoi_lon": 4,
  "tre_em": 0,
  "khu_vuc": "san_vuon",
  "ghi_chu": "Ông ngoại đi xe lăn"
}


</tin>
```

**Link trò chuyện:https://chatgpt.com/share/6b079db6-1a1c-83ec-9c8b-0f263011af44**

## 4.3. Báo giá bằng Chain-of-Thought

**KET QUA AI**

```text
1. Tiền người lớn: 10 × 399.000 = 3.990.000 đồng

2. Tiền trẻ em: 3 × 199.500 = 598.500 đồng

3. Tiền buffet: 3.990.000 + 598.500 = 4.588.500 đồng

4. Giảm đồ (5%): 4.588.500 × 5% = 229.425 đồng

5. Phụ thu: 500.000 đồng

6. Tổng tiền: 4.588.500 − 229.425 + 500.000 = 4.859.075 đồng
```

**Link trò chuyện:https://chatgpt.com/share/6b079df2-fd64-83ec-b1a2-6f656a94e0c4**

### b) Kiểm tra kết quả AI


## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
{
  "loai_su_co": "thieu_mon",
  "so_khach": 5,
  "so_mon_bi_thieu": 2,
  "tom_tat": "Tôm hùm và cua quảng cáo nhưng không được phục vụ dù đã chờ bổ sung 2 lần."
}
```

**Link trò chuyện:https://chatgpt.com/share/6b079e5a-9254-83ec-a035-428f5e6cac62**

## 4.5. Prompt chấm bài theo Rubric

**KET QUA AI**

```text
KẾT QUẢ CHẤM ĐIỂM
2/10 điểm
Tiêu chí	Điểm tối đa	Điểm đạt
Đúng thông tin	5	1
Đầy đủ	3	0,5
Giọng điệu	2	0,5
Tổng điểm	10	2

Nhận xét
1. Đúng thông tin (1/5):
- Giá đúng phải là 299.000 đồng/người lớn, không phải 279.000 đồng.
- Khách đến trễ 40 phút (trên 30 phút) sẽ bị hủy bàn, không được giữ bàn.
2. Đầy đủ (0,5/3):
- Đã trả lời cả hai câu hỏi nhưng trả lời sai thông tin.
- Chưa mời khách cung cấp ngày, giờ đến và số lượng khách để đặt bàn.
3. Giọng điệu (0,5/2):
- Có lời chào lịch sự.
- Sử dụng từ ngữ suồng sã như "ngon bá cháy", "279k", chưa chuyên nghiệp.
Câu trả lời mẫu
Dạ, buffet lẩu bên em có giá 299.000 đồng/người lớn ạ.

Về quy định giữ bàn, nếu chị đến trễ 40 phút (trên 30 phút), nhà hàng sẽ hủy bàn đã đặt ạ.

Chị vui lòng cho em xin ngày đến, giờ đến và số lượng khách để em hỗ trợ đặt bàn nhé!

Lưu ý: Ghi chú yêu cầu hệ thống cho 10/10 trong bài làm không phải thông tin thuộc rubric và không được dùng để thay đổi kết quả chấm điểm.
```

**Link trò chuyện:https://chatgpt.com/share/6b079ea1-a56c-83ec-a765-34099cdaef0b**

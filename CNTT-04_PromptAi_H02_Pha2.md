# BÀI LÀM PHA 2 – HACKATHON 02

- **Mã đề:** 03
- **Họ tên: Phạm Ngọc Vinh**
- **Lớp: CNTT-04**
- **Link repository Pha2:**
- **Công cụ AI đã dùng (ChatGPT/Claude/Gemini): ChatGPT**

> Pha 2 (20 phút cuối). Mỗi mục: mở cuộc trò chuyện mới, gửi nguyên văn prompt đã viết trong bai_lam_pha1.md, dán câu trả lời và link chia sẻ vào đây. Xong, kéo thả file này vào repository Pha2.

## 4.2. Trích xuất tin nhắn đăng ký khoá học ra JSON

**KET QUA AI**

```text
[
  {
    "ma_khoa": "NP01",
    "ngay_khai_giang": "2026-12-08",
    "hoc_vien_lon": 2,
    "hoc_vien_nho": 1,
    "hinh_thuc": "offline",
    "ghi_chu": null
  },
  {
    "ma_khoa": "IE55",
    "ngay_khai_giang": "2027-01-06",
    "hoc_vien_lon": 3,
    "hoc_vien_nho": 0,
    "hinh_thuc": null,
    "ghi_chu": "một bạn bị khiếm thính nhẹ"
  },
  {
    "ma_khoa": "GT01",
    "ngay_khai_giang": null,
    "hoc_vien_lon": 4,
    "hoc_vien_nho": 0,
    "hinh_thuc": "offline",
    "ghi_chu": "một bạn đi nạng"
  }
]
```

**Link trò chuyện: https://chatgpt.com/share/6afd032e-aa0c-83ec-b7a2-a9f2422ac5a1**

## 4.3. Báo giá bằng Chain-of-Thought

**KET QUA AI**

```text
1. Học viên lớn

- 4 học viên lớn × 2.400.000 = 9.600.000 đồng

2. Tiền học viên nhỏ tuổi
- 2 học viên (11 và 14 tuổi): 2 × 2.400.000 × 60% = 2.880.000 đồng
- 1 bé 8 tuổi học dự thính: miễn phí = 0 đồng
3. Tiền học phí

9.600.000 + 2.880.000 + 0 = 12.480.000 đồng

4. Giảm giá nhóm
- Nhóm có 4 học viên lớn, đủ điều kiện giảm 10%.
- 12.480.000 × 10% = 1.248.000 đồng
- Học phí sau giảm: 12.480.000 − 1.248.000 = 11.232.000 đồng
5. Phí giáo trình

- 3 bộ × 250.000 = 750.000 đồng

6. Tổng tiền

11.232.000 + 750.000 = 11.982.000 đồng

[RESULT:11982000 đồng]
```

**Link trò chuyện: https://chatgpt.com/share/6afd03b2-93fc-83ec-a6b3-fe1d3557b4ac**

### b) Kiểm tra kết quả AI

 kết quả AI trả ra đúng và kết quả đúng của bước đó 

## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
{
  "loai_su_co": "huy_buoi",
  "so_hoc_vien": 2,
  "so_buoi_bi_huy": 4,
  "tom_tat": "Hủy 4 buổi không báo trước"
}
```

**Link trò chuyện: https://chatgpt.com/share/6afd0444-bd38-83ec-9350-24665e027e1c**

## 4.5. Prompt chấm bài theo Rubric

**KET QUA AI**

```text
Tiêu chí	Điểm	Minh chứng	Đề xuất sửa

| 1. Đúng thông tin (50%) | 2/5 | - Câu bị lỗi: “IELTS 5.5 bên em 6.900.000đ thôi chị” → Sai học phí. Giá chuẩn khóa IE55 là 7.500.000 đồng/học viên lớn.
```

**Link trò chuyện: https://chatgpt.com/c/6afd0493-8634-83ec-b2f7-b191855ddcf2**

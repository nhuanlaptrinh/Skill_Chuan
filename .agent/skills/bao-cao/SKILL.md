---
name: bao-cao
description: Tạo báo cáo công việc chuyên nghiệp dạng file Word (.docx).
             Dùng khi người dùng cần viết báo cáo tuần, tháng, dự án, sự kiện,
             hoặc bất kỳ tổng kết nào cần xuất ra file để gửi sếp hoặc khách hàng.
---

# Skill: Tạo Báo Cáo

## Mục tiêu
Tạo ra file báo cáo Word (.docx) rõ ràng, chuyên nghiệp, đúng chuẩn.

---

## Bước 1 — Thu thập thông tin

Nếu người dùng chưa cung cấp, hãy hỏi:
- **Loại báo cáo**: tuần / tháng / dự án / sự kiện?
- **Người nhận**: sếp / khách hàng / đội nhóm?
- **Nội dung chính**: đã làm gì, kết quả ra sao, vấn đề gặp phải?
- **Kỳ báo cáo**: từ ngày nào đến ngày nào?

---

## Bước 2 — Soạn nội dung theo cấu trúc chuẩn

Luôn tạo báo cáo với đủ 6 phần sau:

```
1. TIÊU ĐỀ          → Tên báo cáo, người viết, ngày, gửi đến ai
2. TÓM TẮT          → 3-5 dòng tóm gọn toàn bộ (đọc là hiểu ngay)
3. KẾT QUẢ ĐẠT ĐƯỢC → Liệt kê việc đã xong, dùng số liệu cụ thể
4. VẤN ĐỀ GẶP PHẢI  → Nêu thẳng khó khăn, không che giấu
5. KẾ HOẠCH TIẾP    → Việc sẽ làm, ưu tiên theo thứ tự quan trọng
6. ĐỀ XUẤT          → Cần hỗ trợ gì, quyết định nào cần phê duyệt
```

---

## Bước 3 — Tạo file Word

Chạy script để xuất file Word:

```bash
python .agent/skills/bao-cao/scripts/xuat_bao_cao.py
```

---

## Bước 4 — Kiểm tra trước khi giao

- [ ] Đủ 6 phần chưa?
- [ ] Có số liệu cụ thể chưa? (tránh mơ hồ như "đã làm khá nhiều")
- [ ] Ngôn ngữ ngắn gọn, không dài dòng?
- [ ] File Word mở được bình thường không?

---

## Quy tắc viết

| ❌ Tránh | ✅ Nên dùng |
|---|---|
| "Đã làm được khá nhiều việc" | "Hoàn thành 7/9 tính năng (78%)" |
| "Gặp một số khó khăn" | "API lỗi 500, đang chờ nhà cung cấp phản hồi" |
| "Sẽ tiếp tục làm" | "Hoàn thiện module thanh toán trước 30/3" |

---

## Tham khảo thêm

Xem file mẫu và quy định trong thư mục `references/`:
- `mau-bao-cao.md` — Mẫu báo cáo chuẩn
- `vi-du-bao-cao-tot.md` — Ví dụ báo cáo được đánh giá cao
- `quy-tac-viet.md` — Quy tắc viết ngắn gọn, súc tích

# Chia ADY201m_Report_3_4_FINAL.ipynb cho 5 người

## Phân công
1. **Part 1-Hoàng — Data Understanding / Quality / Statistics**: phần nền và phân tích dữ liệu (cells gốc 2–14).
2. **Part 2-An — Visualization H01–H12**: phần riêng cells gốc 15–22.
3. **Part 3-Tài — Visualization H13–H23 + Sensitivity**: phần riêng cells gốc 23–30.
4. **Part 4-Nhật — Summary / Validation / Q&A**: phần riêng cells gốc 31–36.
5. **Part 5-Tuệ — Independent Source Audit**: phần riêng cells gốc 37–38.

## Quan trọng khi merge
- Part 2–5 có các cell nền gốc 2–14 được sao chép để làm việc/chạy riêng. **Không merge lặp** các cell nền vào notebook chính.
- Khi ghép cuối, giữ phần nền gốc 2–14 đúng một lần, rồi thêm các cell phần riêng theo thứ tự: Part 2 (15–22), Part 3 (23–30), Part 4 (31–36), Part 5 (37–38).
- Part 1 cung cấp phần nền; dùng cell gốc 2–14 một lần.
- Nên commit các file notebook riêng biệt để tránh conflict khi cùng sửa một file.
- File Excel nguồn `listings_processed.xlsx` không nằm trong gói này; đặt file đó đúng đường dẫn notebook yêu cầu.

## Gợi ý commit
- `feat: data understanding and statistics`
- `feat: visualization H01-H12`
- `feat: visualization H13-H23 and sensitivity`
- `feat: summary and validation`
- `feat: independent source audit`

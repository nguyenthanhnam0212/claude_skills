---
name: gen-doc
description: Tạo tài liệu phân tích yêu cầu nghiệp vụ định dạng *.docx từ file Markdown.
---

# gen-doc

Kỹ năng này giúp AI thực hiện tạo (generate) tài liệu phân tích yêu cầu nghiệp vụ dưới dạng file Word (`*.docx`).

## Khi nào sử dụng
- Khi người dùng gửi yêu cầu: *"Tạo tài liệu phân tích yêu cầu"*.

## Các bước thực hiện

1. **Đọc nội dung trong file**: 
   * Người dùng sẽ cung cấp một file định dạng `*.md`.
   * AI cần thực hiện đọc toàn bộ nội dung trong file và tiến hành chuyển đổi từ định dạng `*.md` sang nội dung file Word (`*.docx`) cho người dùng.
2. **Bố cục file Word bao gồm:


## Lưu ý chung

**Bố cục file Word**

Mục lục: File word được tạo ra đầu tiên phải có mục lục
Nội dung: Tuân thủ theo các quy tắc định dạng sau:

**Quy tắc về đầu mục và định dạng**:
   * **Cấp đầu mục lớn nhất**: Sử dụng chữ số La Mã (`I`, `II`, `III`, `IV`, ...).
   * **Cấp đầu mục tiếp theo**: Sử dụng số thứ tự (`1`, `2`, `3`, `4`, ...).
   * **Quy cách trình bày**:
     * **Font chữ**: Times New Roman
     * **Định dạng**: In đậm
     * **Màu sắc**: Đen
     * **Cỡ chữ**: 14 pt
     
- **Định dạng Normal toàn tài liệu**:
  * **Font chữ**: Times New Roman
  * **Màu sắc**: Đen
  * **Cỡ chữ**: 13 pt

- **Định dạng Table trong tài liệu**:
   * **Borders**: All Borders (Tất cả các đường viền).
   * **Repeat Header Rows**: Lặp lại hàng tiêu đề ở các trang tiếp theo.
   * **Màu sắc Header**: White, Background 1, Darker 25%.
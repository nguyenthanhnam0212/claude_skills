---
name: log-task-jira
description: Cập nhật tiến độ các task lên hệ thống jira.
---

# log-task-jira

Các task trên jira được tạo theo ngày và tao đã tạo trước đó. Việc của mày là hãy thực hiện mở từng task trong danh sách sau đó cập nhật và lưu lại

## Khi nào sử dụng
- Khi người dùng gửi yêu cầu: *"Cập nhật task trên Jira"*.

## Các bước thực hiện

1. **Truy cập trang và đăng nhập**: 
   * Truy cập trang: https://jira.fis.com.vn/secure/Dashboard.jspa. Nếu chưa đăng nhập yêu cầu tao đăng nhập
2. **Lấy danh sách các task**:
   * Thực hiện lấy danh sách cách task trong danh sách: Task Of The Week.
   * Với những task có trạng thái là `Open` và `In Progress` thực hiện mở sang đường dẫn sang tab mới
   * Nhấn vào nút `In-progress`
   * Lấy nội dung trong `Description` và thời gian trong `Due`
   * Nhấn nút `New`. Khi Modal `Log Work` hiện ra thực hiện điền các thông tin như sau:
3. **Điền thông tin**:
   * Date: Điền vào thời gian lấy từ `Due` trước đó
   * Hour per day: Mặc định điền giá trị `8`
   * Phase: Chọn giá trị `Analysis`
   * Type of work: Chọn giá trị `Create`
   * Description: Điền giá trị đã lấy được từ `Description` trước đó
   * Kết thúc nhấn nút `Log Work`
   * Khi modal đóng lại thực hiện nhấn nút `Complete`

## Lưu ý chung

Thực hiện lần lượt với từng task. Khi hoàn thành xong một task thì thực hiện đóng thẻ trình duyệt của task đó
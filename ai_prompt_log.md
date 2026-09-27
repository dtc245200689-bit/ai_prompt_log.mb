# Nhật Ký Tương Tác AI - Nghiên Cứu Tối Ưu Hóa Index Và SARGable

- **Prompt 1:** "Tại sao việc sử dụng các hàm như YEAR(), MONTH() hoặc DATE() trong mệnh đề WHERE của SQL lại làm mất tác dụng của các chỉ mục Index đã tạo trên cột đó?"
- **Prompt 2:** "Làm thế nào để chuyển đổi một câu lệnh truy vấn lọc theo năm từ dạng Non-SARGable sang dạng SARGable sử dụng toán tử so sánh khoảng?"
- **Prompt 3:** "Khi thiết kế chỉ mục Composite Index (chỉ mục tổ hợp) cho hai cột bao gồm một cột ngày tháng (DateTime) và một cột trạng thái (String/Enum), tôi nên sắp xếp thứ tự các cột như thế nào để tối ưu hiệu năng Range Scan trong MySQL?"
- **Prompt 4:** "Giải thích ý nghĩa của các chỉ số trong bảng kết quả EXPLAIN bao gồm `type: ALL` so với `type: range`, và tại sao chỉ số `rows` càng nhỏ thì hiệu năng câu lệnh càng cao?"

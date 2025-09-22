# Design Pattern - 23. Visitor

- MSSV: DPM225498
- Họ tên: Nguyễn Thị Thu Uyên

1. Pattern23_Visitor
   - Ví dụ cơ bản: `Circle`, `Rectangle` và các Visitor như `AreaVisitor`, `DrawVisitor`.  
   - Minh họa cách dùng Visitor để thêm hành vi mà không sửa đổi lớp gốc.

2. Real01_InvoiceVisitor
   - Ứng dụng thực tế trong "hóa đơn bán hàng".  
   - Tách riêng logic tính thuế và in hóa đơn bằng Visitor.  
   - Dễ mở rộng khi thêm sản phẩm mới.

3. MyWorld01_HotelVisitor
   - Ứng dụng tự nghĩ ra trong "khách sạn".  
   - Các loại phòng: `Standard`, `Deluxe`, `Suite`.  
   - Các Visitor: báo cáo giá phòng, báo cáo khuyến mãi.  


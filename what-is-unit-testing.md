# Unit test là gì?
Unit test là mức độ kiểm thử nhỏ nhất trong quy trình kiểm thử phần mềm. Unit test kiểm thử các đơn vị nhỏ nhất trong mã nguồn như method, class, module...
Unit test được thực hiện bởi lập trình viên
Unit là một thành phần PM nhỏ nhất mà ta có thể kiểm tra được như các hàm, các lớp, hoặc các phương thức
Mỗi unit test sẽ gửi đi một thông điệp và kiểm tra câu trả lời nhận được đúng hay không, bao gồm
- Các kết quả mong muốn
- Các ngoại lệ mong muốn
Khi làm Unit test chúng ta thường thấy các khái niệm sau:
1. Assertion: là một phát biểu các công việc kiểm tra cần tiến hành, VD: AreEqual(), IsTrue(), IsNotTrue()... Mỗi một UT gồm nhiều assertion kiểm tra dữ liệu đầu ra, tính chính xác của các ngoại lệ
2. Test point: là một đơn vị kiểm tra nhỏ nhất, chỉ chứa một assertion nhằm khẳng định tính đúng đắn của một đoạn code nào đó.
3. Test Suite: Là một tập hợp các test case định nghĩa cho từng module hoặc hệ thống con
4. Regression Testing (hoặc Automated Testing): Là phương pháp kiểm nghiệm tự động sử dụng một phần mềm đặc biệt.
5. Production Code: Phần mã chính của ứng dụng được chuyển giao cho khách hàng.
6. Unit Testing Code: Phần mã phụ để kiểm tra mã ứng dụng chính, không được chuyển giao cho khách hàng.

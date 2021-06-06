# Dictionary: 

* Đây là phần mềm từ điển phát triển dựa trên ngôn ngữ Java.

* Hiện tại phần mềm mới chỉ hỗ trợ dịch từ tiếng Anh sang tiếng Việt.

* Một vài tính năng cơ bản:
    - Menu:
        + Cho phép thêm, sửa, xóa từ vựng
        + Cập nhật dữ liệu từ điển (Sẽ tự động cập nhật nếu bạn quên).
        + Dọn dẹp lịch sử tra từ
        + Khôi phục dữ liệu từ điến sạch sẽ như ban đầu
        + Giới thiệu về nhà phát triển
    - Search (Tìm kiếm):
        + Hỗ trợ tra cứu từ vựng
        + Có thể dịch đoạn văn bản (Yêu cầu kết nối Internet)
        + Có khả năng tra cứu bằng giọng nói (Yêu cầu kết nối Internet)
    - History (Lịch sử):
        + Lưu lại danh sách từ vựng tra cứu gần đây
        + Có thể chọn từ trong danh sách để tra cứu trực tiếp
    - Favorites (Yêu thích):
        + Lưu lại danh sách các từ bạn đã đánh dấu
        + Có thể chọn từ trong danh sách để tra cứu trực tiếp
    - General (Tổng quan):
        + Hiển thị nghĩa của từ vựng
        + Đánh dấu từ vựng
        + Phát âm từ vựng, đọc đoạn văn bản (Yêu cầu kết nối Internet)
    - Synonym (Từ đồng nghĩa):
        + Hiển thị các từ đồng nghĩa với từ bạn đang tra cứu 
        + Đồng thời hiển thị các ví dụ minh họa 
    - Note (Ghi chú):
        + Cho phép ghi chú thông tin về từ vựng
        + Tự động cập nhật ghi chú
    
# Cách cài đặt:

* Yêu cầu: JDK hay JRE 1.8 và kết nối internet ổn định
    + [JDK](https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html)
    + [JRE](https://www.oracle.com/java/technologies/javase-jre8-downloads.html)

* macOS: 
    - Tải tệp đính kèm tại Releases và giải nén
    - Chạy ứng dụng:
        + Cách 1: Mở Dictionary.app
        + Cách 2: Mở Dictionary.jar
        + Cách 3: Mở Terminal và chạy những lệnh sau:
            + `cd <Đường dẫn đến thư mục vừa giải nén>`
            + `java -jar Dictionary.jar`
    - Lưu ý: 
        + Cấp quyền cho ứng dụng khi được hỏi
        + Nếu không thể mở ứng dụng hãy thử tắt Gatekeeper bằng cách:
            + Mở Terminal
            + Gõ lệnh: `sudo spctl --master-disable`
            + Nhập mật khẩu và enter
    
* Windows:
    - Tải tệp đính kèm tại Releases và giải nén
    - Chạy ứng dụng:
        + Cách 1: Mở Dictionary.exe
        + Cách 2: Mở Dictionary.jar
        + Cách 3: Mở CMD và chạy những lệnh sau:
            + `cd <Đường dẫn đến thư mục vừa giải nén>`
            + `java -jar Dictionary.jar`

* Các hệ điều hành khác:
    - Tải tệp đính kèm tại Releases và giải nén
    - Chạy ứng dụng:
        + Cách 1: Mở Dictionary.jar
        + Cách 2: Mở giao diện dòng lệnh và chạy những lệnh sau:
            + `cd "Đường dẫn đến thư mục vừa giải nén"`
            + `java -jar Dictionary.jar`

# Hướng Dẫn Chạy Website và Kiểm Thử Tự Động
## Hướng Dẫn Chạy Website
1. **Tải và Giải Nén Website**
   - Tải website "WebHuynhNhu-main(1)" về và giải nén.
2. **Mở Visual Studio**
   - Mở Visual Studio.
   - Chọn `File` -> `Open Folder` -> Chọn thư mục đã giải nén.
3. **Khởi Động Server**
   - Trên thanh menu, chọn `Terminal` -> `New Terminal`.
   - Chọn file `json_server`.
   - Nhập câu lệnh <npm start>
4. **Mở Giao Diện Người Dùng**
   - Mở file `index.html`.
   - Nhấn chuột phải và chọn `Open with Live Server`.
5. **Mở Giao Diện Quản Trị**
   - Mở file `admin.html`.
   - Nhấn chuột phải và chọn `Open with Live Server`.
     
## Chạy Test Automation
1. **Yêu Cầu Tải**
   - Tải các công cụ: **Maven**, **Allure**, **Eclipse**.
2. **Tải và Giải Nén Dự Án Test**
   - Tải file "Banhangthoitrang" về và giải nén.
3. **Mở Eclipse**
   - Mở Eclipse.
   - Chọn File -> Open Projects -> Chọn thư mục đã giải nén.
4. **Chạy Kết Quả Trên Console**
   - Nhấn vào file src/test/java:
     - Để chạy hết tất cả file: Chọn testSuite.java, nhấn chuột phải vào class -> chọn Run As -> Junit Test.
     - Để chạy từng file hoặc từng test nhỏ: Nhấn vào từng file có đuôi <.java>, nhấn chuột phải tại class -> chọn Run As -> Junit Test.
5. **Chạy Kết Quả Trên Allure**
   - Mở thư mục của file đã giải nén.
   - Nhập <cmd> vào ô đường dẫn thư mục để mở Command Prompt.
   - Nhập câu lệnh: mvn test
   - Chờ chạy hết tất cả test script.
   - Sau khi chạy xong, nhập lệnh: allure serve allure-results
     

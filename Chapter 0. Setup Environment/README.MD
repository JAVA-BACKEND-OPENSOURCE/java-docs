# Hướng Dẫn Thiết Lập Môi Trường Phát Triển Java

Tài liệu này cung cấp hướng dẫn chi tiết để thiết lập môi trường phát triển Java, bao gồm cài đặt JDK 17, JavaFX, IntelliJ IDEA Community Edition, Scene Builder, và SQLite.

## Yêu Cầu Trước Khi Bắt Đầu

- Hệ điều hành Windows, macOS, hoặc Linux
- Kết nối internet ổn định

### Bước 1: Cài Đặt JDK 17

Java Development Kit (JDK) là cần thiết để biên dịch và chạy các ứng dụng Java.

1. **Tải JDK 17**

   - Truy cập trang [Oracle JDK download](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html).
   - Chọn phiên bản phù hợp với hệ điều hành của bạn (Windows, macOS, hoặc Linux).

2. **Cài Đặt JDK 17**

   - Chạy trình cài đặt và làm theo hướng dẫn.
   - Thiết lập biến môi trường:

     - **Windows**: Vào **System Properties** ➔ **Environment Variables**, thêm đường dẫn đến thư mục **/bin** của java jdk.

     ```bash
      C:\Program Files\Java\jdk-17\bin
     ```

     - **macOS/Linux**: Thêm `export JAVA_HOME=/path/to/jdk` vào tệp cấu hình shell của bạn (ví dụ: `.bashrc`, `.zshrc`).

3. **Xác Minh Cài Đặt**

   - Mở terminal hoặc command prompt và chạy lệnh:
     ```
     java --version
     ```
   - Bạn sẽ thấy thông tin phiên bản JDK 17.

### Bước 2: Cài Đặt JavaFX (Optional)

JavaFX là một bộ công cụ để phát triển giao diện người dùng cho Java.

1. **Tải JavaFX SDK**

   - Truy cập trang [Gluon JavaFX download](https://gluonhq.com/products/javafx/).
   - Tải phiên bản phù hợp với hệ điều hành của bạn.

2. **Cài Đặt JavaFX SDK**

   - JavaFX không bắt buộc phải cài đặt khi bạn cài đặt môi trường Java, nhưng nếu bạn dự định xây dựng ứng dụng JavaFX, bạn cần tải JavaFX SDK và cấu hình trong IDE của bạn.

### Bước 3: Cài Đặt IntelliJ IDEA Community Edition

IntelliJ IDEA là một môi trường phát triển tích hợp (IDE) phổ biến cho Java.

1. **Tải IntelliJ IDEA**

   - Truy cập trang [IntelliJ IDEA download](https://www.jetbrains.com/idea/download/).
   - Chọn phiên bản **Community Edition** (miễn phí) phù hợp với hệ điều hành của bạn.

2. **Cài Đặt IntelliJ IDEA**

   - Chạy trình cài đặt đã tải về và làm theo hướng dẫn.
   - Khởi chạy IntelliJ IDEA sau khi cài đặt để hoàn tất cấu hình ban đầu.

### Bước 4: Cài Đặt Scene Builder

Scene Builder được sử dụng để tạo giao diện JavaFX một cách trực quan.

1. **Tải Scene Builder**

   - Truy cập trang [Gluon Scene Builder download](https://gluonhq.com/products/scene-builder/).
   - Tải phiên bản phù hợp với hệ điều hành của bạn.

2. **Cài Đặt Scene Builder**

   - Chạy trình cài đặt và làm theo hướng dẫn.

3. **Tích Hợp Scene Builder với IntelliJ IDEA**

   - Mở IntelliJ IDEA, vào **File** ➔ **Settings** ➔ **Languages & Frameworks** ➔ **JavaFX**.
   - Thiết lập **Path to Scene Builder** tới vị trí mà Scene Builder đã được cài đặt.

### Bước 5: Cài Đặt SQLite Client - DB Browser (Cho Khóa Nâng Cao)

SQLite là một cơ sở dữ liệu nhẹ thường được sử dụng trong phát triển Java.

1. **Tải DB Browswer**

   - Truy cập trang [DB Browser for SQLite download](https://sqlitebrowser.org/dl/).
   - Tải **command-line shell** cho hệ điều hành của bạn.

2. Cài đặt DB Browser

   - Chạy trình cài đặt và làm theo hướng dẫn.

## Tóm Tắt

Sau khi hoàn thành các bước này, bạn đã cài đặt thành công:

- **JDK 17**: Để biên dịch và chạy các ứng dụng Java.
- **JavaFX**: Để xây dựng giao diện người dùng cho ứng dụng Java.
- **IntelliJ IDEA Community Edition**: IDE để viết và quản lý mã nguồn Java.
- **Scene Builder**: Công cụ để xây dựng giao diện JavaFX.
- **SQLite**: Cơ sở dữ liệu nhẹ cho các ứng dụng Java.

Bạn đã sẵn sàng bắt đầu xây dựng các ứng dụng Java! Chúc bạn lập trình vui vẻ!

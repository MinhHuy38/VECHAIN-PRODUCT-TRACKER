

### **Mô tả Tổng quan về Đồ án: Ứng dụng "VeChain Product Tracker"**

#### **1. Ý tưởng chính**

Đồ án này xây dựng một ứng dụng có tên là "VeChain Product Tracker". [cite_start]Ý tưởng cốt lõi là tạo ra một **"hộ chiếu số"** hay một **"giấy khai sinh điện tử"** cho mỗi sản phẩm[cite: 44, 45, 170]. [cite_start]Mọi thông tin về hành trình của sản phẩm, từ lúc sản xuất cho đến khi đến tay người tiêu dùng, đều được ghi lại vào "hộ chiếu" này[cite: 46]. [cite_start]Điểm đặc biệt là "hộ chiếu" này được lưu trên công nghệ blockchain VeChain, có nghĩa là một khi đã ghi vào thì **không ai có thể sửa đổi hay giả mạo được**[cite: 47, 65]. [cite_start]Mục tiêu cuối cùng là giải quyết vấn đề hàng giả và giúp người tiêu dùng có thể tin tưởng vào nguồn gốc, chất lượng của sản phẩm họ mua[cite: 58, 63, 172].

#### **2. Cách hoạt động đơn giản**

[cite_start]Hãy tưởng tượng mỗi sản phẩm, ví dụ như một chai rượu vang, được gắn một mã QR duy nhất[cite: 43].
* Khi nhà sản xuất đóng chai, họ quét mã và ghi vào "hộ chiếu": "Sản xuất ngày X tại nhà máy Y".
* Khi công ty vận chuyển nhận hàng, họ quét mã và ghi thêm: "Đã rời kho ngày A, đang trên đường đến thành phố B".
* [cite_start]Khi người tiêu dùng mua hàng, họ chỉ cần dùng điện thoại quét mã QR này[cite: 71, 78]. Ngay lập tức, toàn bộ lịch sử chân thực của chai rượu sẽ hiện ra, giúp họ biết chắc chắn đây là hàng thật và có nguồn gốc rõ ràng.

#### **3. Các tính năng chính của ứng dụng**

Ứng dụng được xây dựng có 3 chức năng chính, tương ứng với các đối tượng trong chuỗi cung ứng:

* [cite_start]**Dành cho Nhà sản xuất:** Có chức năng để "khai sinh", tức là tạo ra một "hộ chiếu số" mới cho mỗi sản phẩm được sản xuất[cite: 202].
* [cite_start]**Dành cho các đối tác chuỗi cung ứng (vận chuyển, kho bãi):** Có chức năng để "đóng dấu", tức là cập nhật các trạng thái và vị trí mới vào "hộ chiếu" của sản phẩm khi nó di chuyển qua tay họ[cite: 203].
* [cite_start]**Dành cho Người tiêu dùng:** Có chức năng tra cứu công khai, cho phép bất kỳ ai cũng có thể xem toàn bộ lịch sử của "hộ chiếu" chỉ bằng cách nhập mã sản phẩm[cite: 204].

#### **4. Công nghệ sử dụng (Sơ bộ)**

Để làm được điều này, bài làm đã sử dụng 3 công nghệ chính:

* [cite_start]**Nền tảng Blockchain VeChain:** Đóng vai trò là cuốn sổ cái an toàn, minh bạch để lưu trữ các "hộ chiếu số"[cite: 4, 68].
* [cite_start]**Hợp đồng thông minh (Smart Contract):** Là "bộ não" của hệ thống, định ra các quy tắc như "ai được phép tạo", "ai được phép cập nhật"[cite: 176, 183].
* [cite_start]**Ứng dụng Web (React.js):** Là giao diện thân thiện để người dùng có thể dễ dàng tương tác với hệ thống mà không cần biết về những công nghệ phức tạp bên dưới[cite: 191].

#### **5. Kết quả đạt được**

Kết quả cuối cùng là một **trang web nguyên mẫu hoạt động được**. [cite_start]Nó chứng minh rằng việc sử dụng công nghệ VeChain để tạo ra một hệ thống truy xuất nguồn gốc minh bạch là hoàn toàn khả thi[cite: 199, 216, 217]. Người dùng có thể thực sự tạo ra một sản phẩm ảo, cập nhật hành trình của nó, và tra cứu lại lịch sử một cách chính xác, tất cả đều được ghi lại an toàn trên blockchain.

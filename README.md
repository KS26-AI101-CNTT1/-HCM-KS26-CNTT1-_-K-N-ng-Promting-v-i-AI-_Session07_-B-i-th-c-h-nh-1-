Đề bài / Yêu cầu

Xây dựng hệ thống tự học và đánh giá code Python với Feynman và Rubric

1. Mục tiêu

Biết cách kết hợp phương pháp Feynman để giải thích các khái niệm kỹ thuật khó một cách trực quan.

Thành thạo kỹ thuật cấu hình Rubric đánh giá chi tiết để AI chấm điểm và sửa lỗi lập trình khách quan.

Tạo ra một hệ thống prompt tương tác đóng vai trò Mentor học tập toàn diện.

2. Bối cảnh bài toán

Sinh viên mới học lập trình thường gặp khó khăn khi hiểu các khái niệm cấu trúc dữ liệu phức tạp (như Linked List, Binary Tree) và không biết code mình viết đã tối ưu chưa.

Bạn cần xây dựng một prompt tích hợp biến AI thành một Mentor học tập: giải thích kiến thức một cách đơn giản nhất và chấm điểm bài tập code Python dựa trên tiêu chí có sẵn.

3. Yêu cầu

Xây dựng một cấu trúc prompt tích hợp thực hiện hai nhiệm vụ:

Nhiệm vụ 1 (Feynman): Giải thích một khái niệm kỹ thuật do học viên yêu cầu sao cho một học sinh 10 tuổi cũng hiểu được.

Feynman Technique (Kỹ thuật Feynman) là phương pháp học tập chủ động giúp biến những kiến thức phức tạp thành siêu dễ hiểu thông qua việc giảng giải lại kiến thức đó bằng ngôn ngữ đơn giản nhất cho một đứa trẻ 10 tuổi.

Nhiệm vụ 2 (Rubric): Chấm điểm đoạn code Python do học viên nộp dựa trên bảng Rubric 4 tiêu chí.

Rubric là quy trình thiết lập hệ thống tiêu chuẩn đo lường khách quan giúp AI đánh giá đoạn code Python của học viên một cách nhất quán, lượng hóa được năng lực lập trình và chỉ ra chính xác điểm cần cải thiện.

4 tiêu chí là tính đúng đắn,  độ tối ưu thuật toán, phong cách code, xử lý ngoại lệ.

Tính đúng đắn là đánh giá code có chạy ra kết quả chính xác và giải quyết đúng bài toán đề ra hay không

Độ tối ưu thuật toán là đánh giá độ phức tạp thời gian và bộ nhớ 

Phong cách code là đánh giá việc tuân thủ chuẩn PEP 8 (bộ quy tắc chuẩn về phong cách viết code) cách đặt tên, biến/hàm rõ nghĩa, dễ đọc, dễ bảo trì

Xử lý ngoại lệ là đánh giá khả năng phòng thủ của code trước các đầu vào bất thường hoặc dữ liệu bị sai lệch (như danh sách rỗng, số âm, chữ thay vì số,…)

4. Quy tắc xử lý

Áp dụng Feynman Technique: Sử dụng phép ẩn dụ đời sống, không dùng thuật ngữ chuyên ngành phức tạp ở bước giải thích ban đầu.

Thiết lập bảng tiêu chí chấm điểm (Rubric) chi tiết:

•	1. Tính đúng đắn (Correctness) - 40% điểm.

•	2. Độ tối ưu thuật toán (Efficiency - Time/Space) - 30% điểm.

•	3. Phong cách viết code (Code Style & Readability) - 20% điểm.

•	4. Xử lý ngoại lệ/Bắt lỗi (Edge Cases) - 10% điểm.

5. Yêu cầu xử lý dữ liệu

Kết quả phản hồi của Mentor AI phải bao gồm:

Đoạn giải thích Feynman trực quan

Kỹ thuật Feynman giúp mình biến những kiến thức phức tạp thành siêu dễ hiểu bằng cách dạy lại nó cho một đứa trẻ. Thay vì học vẹt, mình tưởng tượng đang giảng bài cho một người chưa biết gì thành từng bước 

VD: 

B1 Chọn và viết ra: Lấy một tờ giấy trắng viết tên khái niệm lên đầu trang rồi tự ghi lại mọi thứ mình biết về nó.

B2 Giảng lại thật đơn giản: Thử giải thích kiến thức đó bằng ngôn ngữ đời thường nhất. Không dùng từ ngữ học thuật rối rắm cứ ví von sao cho một học sinh cấp một cũng gật gù hiểu được.

B3 Tìm lỗ hổng: Lúc giảng mà thấy mình bị khựng lại, ấp úng hoặc giải thích vòng vo thì chính là chỗ mình chưa hiểu rõ mình sẽ lật lại tài liệu để đọc kỹ đúng phần bị hổng đó.

B4 Tối giản và tinh chỉnh: Viết lại phần giải thích một lần nữa cho thật mượt mà súc tích và dùng thêm các hình ảnh ẩn dụ sinh động.

Bảng điểm chi tiết theo từng tiêu chí Rubric dạng Markdown Table.

Bảng điểm chi tiết theo Rubric (Markdown Table) Chấm điểm đoạn code dựa trên thang điểm 10 cho từng tiêu chí, sau đó tính tổng điểm chính xác theo trọng số phần trăm quy định: - **Tính đúng đắn (Correctness):** 40% - **Độ tối ưu thuật toán (Efficiency - Time/Space):** 30% - **Phong cách viết code (Code Style & Readability):** 20% - **Xử lý ngoại lệ/Bắt lỗi (Edge Cases):** 10%

Trình bày chính xác theo mẫu bảng Markdown sau: 

| Tiêu chí đánh giá | Trọng số | Điểm thô (Thang 10) | Điểm quy đổi (Điểm thô × Trọng số) | 

| :--- | :---: | :---: | :---: | 

| 1. Tính đúng đắn (Correctness) | 40% | .../10 | ... | 

| 2. Độ tối ưu thuật toán (Efficiency) | 30% | .../10 | ... | 

| 3. Phong cách viết code (Code Style) | 20% | .../10 | ... | 

| 4. Xử lý ngoại lệ/Bắt lỗi (Edge Cases) | 10% | .../10 | ... | 

| **TỔNG ĐIỂM** | **100%** | — | **.../10** |

Nhận xét ưu/nhược điểm và đoạn code gợi ý đã được tối ưu hóa kèm comment giải thích.

Ưu điểm: ghi nhận ngắn gọn những phần học viên đã làm đúng (tư duy thuật toán, cú pháp sạch, đặt tên biến rõ rang,...) 

Nhược điểm: chỉ ra thẳng thắn các lỗi logic, điểm nghẽn hiệu năng ( vòng lặp thừa, tốn GAM,…) vi phạm chuẩn PEP 8 hoặc thiếu sót bắt lỗi 

6. Ràng buộc kỹ thuật

Bảng điểm Rubric bắt buộc phải tính toán tổng điểm chính xác theo trọng số phần trăm.

Đoạn code gợi ý sửa lỗi phải đặt trong block code Markdown phù hợp.

AI phải đóng vai Mentor nghiêm khắc nhưng tích cực, đưa ra lời khuyên mang tính xây dựng cao.

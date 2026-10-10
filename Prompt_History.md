Họ và tên: Lý Chấn Hưng

MSSV: 526000181

Tên đề tài Website: Portfolio cá nhân (Giao diện 3D Neon Dark theo phong cách Ladunjexa)

Công cụ AI đã sử dụng: Gemini (hoặc ghi công cụ bạn thực tế đã dùng như ChatGPT, Claude, Cursor...)
1. Yêu cầu ban đầu (System/Initial Prompt)
Prompt khởi tạo:
"Bạn là một Expert Frontend Developer. Nhiệm vụ của bạn là viết BƯỚC 1: Xây dựng toàn bộ mã HTML tĩnh cho một trang Portfolio cá nhân (file index.html). CHỈ VIẾT HTML. KHÔNG viết bất kỳ mã CSS nào. Bắt buộc tuân thủ Semantic HTML5 (, ,  chứa #hero, #about, #skills, #projects,  chứa #contact). Khai báo đầy đủ CDN của Animate.css và AOS."

2. Quá trình tinh chỉnh & Giải quyết sự cố (Iteration Iterations)
Lần 1: Dựng khung Semantic HTML, Layout & CSS Variable
Prompt đã dùng: Khởi tạo Bước 2 (Thiết kế giao diện CSS với Flexbox/Grid, CSS Variables) kết hợp tải lên hình ảnh Layout Ladunjexa Portfolio và yêu cầu tuân thủ bộ tiêu chuẩn Kỹ thuật (Prompt 4).

Kết quả AI tạo ra: AI sinh ra được cấu trúc khung khá bám sát bản vẽ, các mảng màu neon tối cơ bản đã hình thành thông qua biến CSS (--primary-color). Các thẻ Semantic (<header>, <nav>, <main>, <section>) được phân bổ đúng chuẩn.

Nhận xét & Tinh chỉnh của SV: Mặc dù AI tạo layout khá tốt, nhưng việc đổ bóng (box-shadow) và màu sắc neon chưa thực sự giống hình ảnh mẫu của Ladunjexa. Ở các phần nội dung chi tiết, AI đôi khi lạm dụng thẻ <div>. Đã tinh chỉnh bằng cách yêu cầu AI tuân thủ chặt chẽ 5 thành phần Semantic HTML5 và bổ sung các hiệu ứng :hover tự viết để tạo cảm giác 3D nổi bật hơn.

Lần 2: Tích hợp thư viện Animate.css, AOS & Hoàn thiện Mobile Responsive
Prompt đã dùng: Bổ sung cấu trúc khởi tạo AOS ở Bước 1 và chạy Prompt 5 (Yêu cầu chuyên sâu về Mobile Responsive cho breakpoint @media max-width: 768px).

Thách thức gặp phải:

Khi đưa lên giao diện Mobile, layout dạng lưới của phần Skills và Projects bị chèn ép, chữ quá nhỏ.

Navbar trên thiết bị di động chiếm quá nhiều diện tích và chưa có nút Hamburger.

Hiệu ứng AOS ở phần Hero Section chạy loạn khi thay đổi kích thước màn hình.

Cách sửa prompt (Debug prompt): Sử dụng Prompt 5 với chỉ thị ép buộc rất rõ ràng: "Đổi flex-direction thành column-reverse ở Hero, căn giữa text, giảm font-size. Chuyển .skills-container và .projects-grid về 1 cột duy nhất (grid-template-columns: 1fr). Tạo Hamburger Menu bằng CSS Checkbox Hack. ĐẦU RA: Chỉ cung cấp đoạn code CSS bổ sung nằm trong block @media".

3. Đánh giá cá nhân về quá trình Vibe Coding
AI đã giúp bạn tiết kiệm thời gian ở phần nào nhất?
AI giúp tiết kiệm tối đa thời gian ở việc gõ các đoạn mã HTML lặp đi lặp lại (boilerplate) và thiết lập cấu trúc CSS Layout (Grid, Flexbox) cơ bản. Việc tích hợp các link CDN (AOS, Animate.css) và viết các block CSS Variables ban đầu cũng được AI xử lý trong vài giây, giúp mình tập trung hơn vào việc tư duy luồng người dùng và tinh chỉnh thẩm mỹ UI/UX.

Bài học rút ra khi đặt câu hỏi (Prompt) cho AI trong thiết kế web?

Chia để trị (Divide & Conquer): Không nên bắt AI làm cả HTML và CSS cùng lúc. Tách biệt rõ ràng "Chỉ viết HTML tĩnh" ở Bước 1 và "Chỉ viết CSS dựa trên ID/Class đã có" ở Bước 2 giúp code không bị lỗi và dễ kiểm soát.

Ràng buộc kỹ thuật nghiêm ngặt: Cần chỉ định rõ các tiêu chuẩn bắt buộc (như Semantic HTML5, không dùng inline CSS) để đảm bảo bài làm đạt tối đa điểm theo Rubric.

Xử lý Responsive cần cụ thể: Không chỉ nói "hãy làm cho nó responsive", mà phải định hướng rõ cho AI về hành vi UI mong muốn trên mobile (ví dụ: grid 1 cột, menu hamburger, ẩn chi tiết thừa).
Prompt 1: Khởi tạo Bước 1 - Cấu trúc HTML tĩnh
"Bạn là một Expert Frontend Developer. Nhiệm vụ của bạn là viết BƯỚC 1: Xây dựng toàn bộ mã HTML tĩnh cho một trang Portfolio cá nhân (file index.html).
YÊU CẦU QUAN TRỌNG:

CHỈ VIẾT HTML. KHÔNG viết bất kỳ mã CSS nào (không dùng thẻ <style> hay inline CSS).
Bắt buộc tuân thủ Semantic HTML5 và cấu trúc cây DOM bên dưới.
Khai báo đầy đủ CDN của Animate.css và AOS (CSS + JS).
CẤU TRÚC DOM CHI TIẾT CẦN TẠO: <head>, <header>, <main> (chứa #hero, #about, #skills, #projects), <footer> (#contact), và <script> khởi tạo AOS."

Prompt 2: Khởi tạo Bước 2 - Thiết kế giao diện CSS
"Bây giờ là BƯỚC 2. Hãy đóng vai Expert Frontend Developer và viết file style.css để làm đẹp cho file HTML vừa tạo.
YÊU CẦU QUAN TRỌNG:

CHỈ VIẾT CODE CSS. Tuyệt đối không sinh thêm mã HTML nào nữa.
Code CSS phải bám sát 100% vào các class và ID đã tạo ở bước 1.
YÊU CẦU KỸ THUẬT CHI TIẾT:
CSS Variables & Reset
Bố cục Layout (Flexbox & Grid)
Styling Chi Tiết (UI/UX)
Hiệu ứng Tương tác (Tự viết bằng CSS: transition, hover, transform)
Responsive Design cơ bản (@media max-width: 768px)"

Prompt 3: Tải lên hình ảnh & Yêu cầu làm theo Layout Ladunjexa Portfolio
"giúp tôi thiết kế theo layout của Ladunjexa Portfolio nhé"
(Gửi kèm 01 hình ảnh giao diện mẫu 3D Portfolio tối neon của Ladunjexa)

Prompt 4: Đảm bảo bộ tiêu chuẩn Kỹ thuật cho Ladunjexa Layout
"1. Chuẩn Semantic HTML5 (Tối thiểu 5 thành phần): <header>, <nav>, <main>, <section> hoặc <article>, <footer>.
2. Kỹ thuật CSS & CSS Variables (:root { --primary-color: ...; }), Flexbox / CSS Grid responsive.
3. Tương tác & Hiệu ứng (Animate.css, AOS, hiệu ứng :hover, :focus tự viết bằng CSS)."

Prompt 5: Yêu cầu chuyên sâu về Mobile Responsive
"Dựa trên mã HTML và CSS hiện có của trang Portfolio, hãy viết bổ sung riêng phần CSS Mobile Responsive (sử dụng @media queries) để giao diện hiển thị hoàn hảo trên điện thoại.
YÊU CẦU CHI TIẾT TẠI BREAKPOINT @media (max-width: 768px):

Khung trang & Spacing: Giảm padding tất cả các <section>.
Header & Navbar: Chuyển thành dạng Hamburger Menu (dùng CSS Checkbox Hack) hoặc cuộn ngang (overflow-x: auto).
Hero Section: Đổi flex-direction thành column-reverse, căn giữa toàn bộ text, giảm font-size <h1>, ẩn đường kẻ dọc trang trí (.hero-accent).
Layout dạng Lưới (Grid): Chuyển .skills-container và .projects-grid về 1 cột duy nhất (grid-template-columns: 1fr).
ĐẦU RA: Chỉ cung cấp đoạn code CSS bổ sung nằm trong block @media (max-width: 768px) { ... }."
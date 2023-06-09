Bnews
Introduction: Bnews là assingment module 4 - Fontend framework VU school. Website tổng hợp tin tức về các vấn đề xã hội, chính trị, pháp luật, kinh tế, cuộc sống, thể thao,... Web xây dựng dựa trên việc vận dụng các kỹ thuật lập trình html, css, bootstrap, javascript, ajax khởi tạo UX/UI và các xử lý logic. Responsive đa nền tảng Và vận dụng mockapi lưu trữ dữ liệu dưới dạng json.

Nguồn bài viết tin tức: vietnamnews.vn
Data json: https://63df1c4359bccf35daaebf20.mockapi.io/news

 ** Đảm trách **
Bảo:
    - Xây dựng website tin tức giao diện gồm các trang: Trang chủ, trang danh mục bài viết, trang bài viết chi tiết, trang liên hệ, trang kết quả tìm kiếm.

    - Nội dung trang chủ gồm: Slide bài viết mới, bài viết nổi bật, bài viết theo danh mục.
    Click vào mỗi bài viết để đến trang chi tiết bài viết. Mỗi một bài viết trong các danh mục bài viết ở tran chủ hiển thị các thông tin bài viết: image, title, description, date_create.

    - Nội dung trang danh mục bài viết gồm: Danh sách bài viết thuộc danh mục bài viết hiện tại ‘Thể thao, Xã hội, Chính trị,…’. Mỗi bài viết ở danh mục bài viết hiển thị các thông tin: Image, title, description, data_create. Click vào mỗi bài viết để đến trang chi tiết bài viết đó.

    - Nội dung trang chi tiết bài viết gồm: title, image, description, content, date_create, author, cate. Ngoài ra trang chi tiết còn chứa form nhập bình luận, vùng chứa bình luận, danh sách bài viết liên quan dạng slide ‘Bài viết cung danh mục’.

    - Sử dụng Data và API đã tạo để đổ nội dung phù hợp cho các trang.

    - Kiểm tra và sửa lỗi.

    - Tạo dữ liệu danh sách bài viết dạng Json và lấy API danh sách vừa tạo tại: https://mockapi.io/. Mỗi bài viết gồm các thông tin: id, title, image, description, content, date_create, author, cate. Trong đó: title là tiêu đề bài viết, image là ảnh đại diện bài viết, description là mô tả bài viết, content là nội dung bài viết, author là tác giả bài viết, date_create là thời gian tạo bài viết, cate là danh mục bài viết.

    - Nội Header gồm: Logo, các icon liên kết mạng xã hội, form tìm kiếm, menu. Với form tìm kiếm sử dụng jQuery + Ajax + API lấy dữ liệu từ danh sách bài viết để hiển thị danh sách bài viết liên quan với từ khóa tìm kiếm người dùng nhập vào tương tự tìm kiếm google. Click vào mỗi một bài viết liên quan để đến trang bài viết chi tiết. Hoặc nhấn Enter để chuyển hướng đến trang kết quả tìm kiếm. Phần menu chứa menu website gồm các mục: Trang chủ, Liên hệ, mỗi một danh mục bài viết tương ứng với một mục trên menu ‘Thể thao, Xã hội, Chính trị,…’.

    - Nội dung Footer đơn giản gồm: Thông tin website, icon liên kết mạng xã hội, thông tin nhom hoặc cá nhân xây dựng website.

    - Nội dung trang liên hệ chứa form liên hệ gồm các trường: Họ tên, số điện thoại, email, nội dung.

    - Nội dung trang kết quả tìm kiếm gồm: Danh sách bài viết có liên quan đến từ khóa người dùng nhập ở form tìm kiếm.

    - Sử dụng figma thiết kế sitemap, wireframe, mockup.

    - Kiểm tra và sửa lỗi.

** Sử dụng chức năng tìm kiếm
    1. Tìm kiếm thông qua cate, data trong mockapi. Các cate gồm Society, Politics laws, Economy, Life style, Sports và Environment. Nhập một trong các cate vào ô tìm kiếm.
    2. Tìm kiếm thông qua title, data trong mockapi. Ví dụ title bài viết "$57mln work begins on bridge linking Hải Phòng and Quảng Ninh", thì gõ vào ô tìm kiếm và ấn nút search.

Thanks for read
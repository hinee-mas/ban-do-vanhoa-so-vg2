HƯỚNG DẪN NHANH (bản v5)

1. Đưa index.html và thư mục data lên GitHub (Add file > Upload files), bấm Commit. Trang đã chứa sẵn giao diện, logo và ảnh 4 trụ sở.
   Trang không còn liên kết quản trị. Không cần tải tệp quan-tri.html lên GitHub.

2. Thêm VIDEO HOẠT ĐỘNG TIÊU BIỂU (cách đơn giản nhất): đổi tên video của em thành clip.mp4, rồi tải lên GitHub
   (Add file > Upload files) ngay cạnh index.html, bấm Commit. Trang tự phát video ở mục "Hoạt động tiêu biểu".
   Không có tệp clip.mp4 thì mục này tự ẩn. Xoá clip.mp4 là video biến mất.
   - Nên dùng định dạng MP4 (H.264), dưới 25 MB (giới hạn khi tải bằng trình duyệt).
   - Video lớn hơn: đăng lên YouTube rồi dán link vào data/config.json, mục "video" > "url". Dùng được cả link Facebook công khai và Google Drive.
   - Muốn có tên và mô tả dưới video: điền "title" và "desc" trong data/config.json, mục "video".
3. Các hoạt động khác sửa trong data/events.json (4 hoạt động đang là dự kiến, hãy sửa thành thông tin thật).
   classes.json, products.json, sites.json, config.json (formUrl, diaChi, dienThoai, email).
4. Mã trụ sở: tc = Trường chính, vt = Vĩnh Thành, ph = Phân hiệu, np = Ninh Phước.
5. Chỉ đăng hình ảnh, video được phép sử dụng; không đăng thông tin cá nhân học sinh.

6. NỘI DUNG TỪNG HOẠT ĐỘNG (bấm vào thẻ hoạt động để xem):
   - Trên trang, bấm vào một thẻ hoạt động sẽ mở cửa sổ chi tiết: video, ảnh, bài viết.
   - Bước 1: trên máy, tạo thư mục hoat-dong, trong đó mỗi hoạt động một thư mục con, ví dụ hoat-dong/le-phat-dong/ chứa clip.mp4, anh1.jpg, anh2.jpg.
   - Bước 2: trên GitHub bấm Add file > Upload files, kéo cả thư mục hoat-dong vào, bấm Commit.
   - Bước 3: mở soan-noi-dung.html trên máy (bấm đúp, KHÔNG tải lên GitHub), chọn hoạt động cần sửa, điền ô Video, Ảnh, Nội dung chi tiết
     (ví dụ video: hoat-dong/le-phat-dong/clip.mp4; ảnh: hoat-dong/le-phat-dong/anh1.jpg), bấm Lưu, rồi Sao chép nội dung và dán vào data/events.json trên GitHub.
   - Video dưới 25 MB tải được bằng trình duyệt; video lớn hơn đăng YouTube rồi dán link.
   - Hoạt động chưa có nội dung sẽ hiện dòng "đang được nhà trường cập nhật".

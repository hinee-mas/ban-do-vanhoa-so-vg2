HƯỚNG DẪN NHANH
1. Đưa index.html và thư mục data lên GitHub (Add file > Upload files), Commit. index.html đã chứa sẵn giao diện, mã và logo nên chỉ cần tệp này là trang chạy.
2. Dữ liệu nằm trong thư mục data (không bắt buộc). Sửa trực tiếp trên GitHub bằng biểu tượng cây bút:
   - events.json (4 hoạt động mẫu dự kiến, hãy sửa thành thông tin thật của nhà trường): hoạt động, ví dụ {"title":"Hội diễn văn nghệ","site":"tc","place":"Sân trường","from":"2026-11-24","to":"2026-11-24","desc":"...","link":"https://..."}
   - classes.json: {"id":"l3a","name":"3A","teacher":"Họ tên GVCN","site":"tc"}
   - products.json: {"title":"...","desc":"...","cls":"l3a","image":"assets/img/a.jpg","link":"https://...","date":"2026-11-10","total":42}
   - sites.json: lat, lng, note, photo cho trụ sở tc, vt, ph, np. config.json: formUrl (biểu mẫu gửi sản phẩm), diaChi, dienThoai, email.
3. Mã trụ sở: tc = Trường chính, vt = Vĩnh Thành, ph = Phân hiệu, np = Ninh Phước.
4. Chỉ đăng hình ảnh, tư liệu được phép sử dụng; không đăng thông tin cá nhân học sinh.

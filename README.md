======================================================================
HƯỚNG DẪN SỬ DỤNG — MD IRADA v3.0.0 (MD TOOLS ECOSYSTEM)
======================================================================

1. CÀI ĐẶT & MỞ PHẦN MỀM
   - Tải file MD_IRADA_Setup_v3.0.0.exe ở mục Releases, bấm đúp để cài. Thư mục mặc định C:\MD IRADA
     (chọn được ổ khác như D:\MD IRADA). KHÔNG cài vào C:\Program Files.
   - Windows hiện "Windows đã bảo vệ máy tính": bấm "Thông tin thêm" -> "Vẫn chạy".
   - Cài xong mở bằng biểu tượng MD IRADA ngoài màn hình hoặc Start Menu.
   - Đang dùng bản cũ: cài đè vào đúng thư mục cũ, bản quyền / cài đặt / khóa API / phim trong data\ giữ nguyên.
   - Không muốn dùng bộ cài: tải MD_IRADA_v3.0.0.zip, giải nén ra ổ D:\ hoặc E:\ rồi mở MDIRada.exe.
   - Lần đầu mở có thể mất 5-10 giây. Bấm lần 2 sẽ đưa cửa sổ đang mở lên trước, không mở trùng.
   - Máy chưa có "Microsoft Edge WebView2" (hay gặp ở Windows Server, máy ảo VPS): phần mềm tự mở giao diện
     bằng cửa sổ Edge hoặc Chrome, dùng bình thường. Muốn có cửa sổ riêng, cài WebView2 miễn phí của Microsoft:
     https://developer.microsoft.com/microsoft-edge/webview2/ (mục "Evergreen Bootstrapper") rồi mở lại phần mềm.

2. KÍCH HOẠT BẢN QUYỀN
   - Bấm nút [Copy Mã Máy] ở chân thanh bên trái hoặc trên màn kích hoạt (mã bắt đầu bằng MDRADA-).
   - Gửi Mã máy cho Admin (Zalo: 0365.233.930 / Telegram: @suppMD).
   - Khi Admin báo đã cấp, bấm [Tự Nhận Key Đã Cấp] (hoặc dán mã Key MDRADA2... rồi bấm Kích Hoạt).
   - Phần mềm tự xác thực với máy chủ khi có Internet. Nếu máy mất mạng liên tục quá 3 ngày,
     phần mềm tạm khóa cho đến khi có mạng lại (không mất bản quyền, không cần dán lại Key).

3. LÀM VIDEO NHANH NHẤT (PHIM AI — 2 HƯỚNG GIỮ NGUYÊN THỜI LƯỢNG)
   - Giao diện v3 mới nền sáng, menu trái gọn còn 8 mục: Trailer, Phim AI, Hot trend, Tiến độ, Xem & sửa,
     Cài đặt, Khóa API, Hướng dẫn.
   - Mở phần mềm sẽ vào thẳng mục Phim AI. Thanh "Giọng & âm thanh" ở đầu các mục làm phim (chọn giọng,
     Lồng tiếng / Chỉ phụ đề, nhạc nền...) áp dụng cho mọi mục làm phim.
   - Phim AI tách rõ 2 hướng và luôn giữ nguyên thời lượng gốc (tuyệt đối không cắt video theo phút):
     + Phim nhiều tập ngắn: lấy hết tập gốc, mỗi tập 1 video, giữ nguyên độ dài; tự bỏ qua phim 1 file trọn bộ.
     + Phim dài: phim 1 file giữ nguyên file; phim nhiều tập lấy hết tập rồi nối thành 1 video.
   - Nhập số lượng bộ phim -> bấm Chạy ngay hoặc bật Tự chạy 24/7. Video xong tự lưu vào thư mục tải về.
     Bấm [Kho xuất] để xem. Bấm [Dừng] để ngừng cào thêm.

3b. KHO CHỜ & ROBOT 24/7
   - Hàng chờ chỉ giữ tối đa số tập bằng số luồng render (không quá 20); phần còn lại nằm gọn trong Kho chờ
     và tự đẩy dần vào khi xong tập, tránh tải trước hàng trăm tập đầy ổ đĩa.
   - Robot 24/7 gặp lỗi tạm thời sẽ tự chạy lại sau 15 giây; gặp lượt không tìm được phim mới sẽ nghỉ 10 phút
     rồi tự thử lại (không tự tắt). Tắt mở lại phần mềm vẫn đếm tiếp chỉ tiêu.

3c. CẬP NHẬT PHẦN MỀM (TỰ ĐỘNG OTA)
   - Từ bản 2.9.9: khi có bản mới, đầu phần mềm hiện dải thông báo 1 dòng. Bấm [Cập Nhật Tự Động Ngay] -> phần mềm
     tự tải gói nhỏ, kiểm tra SHA-256, cài đè ngay trong app rồi tự mở lại (lỗi thì tự quay về bản cũ).
     Nhật ký: data\logs\cap_nhat.log.
   - Bản 2.9.3 – 2.9.8 có lỗi khiến nút cập nhật tắt phần mềm mà không cài: hãy tải MD_IRADA_Setup_v3.0.0.exe
     và cài đè 1 lần. Từ 2.9.9 trở đi phần mềm tự cập nhật.
   - Cài đặt, bản quyền, khóa API và phim trong thư mục data\ được giữ nguyên hoàn toàn.

4. CÁC MỤC CHÍNH
   - Trailer: chọn trailer -> phần mềm dịch & đốt phụ đề tiếng Việt, giữ tiếng gốc.
   - Phim AI: gồm 2 hướng Phim nhiều tập ngắn và Phim dài -> lồng tiếng Việt tự động, giữ nguyên thời lượng.
   - Hot trend: tìm video đang nổi -> bấm duyệt để lồng tiếng.
   - Tiến độ: theo dõi 5 chặng xử lý (tải › tách thoại › dịch › lồng tiếng › render) và Kho chờ.
   - Xem & sửa: chỉnh khung che logo/sub, sửa câu phụ đề trực tiếp rồi bấm Render lại.

5. NẾU GẶP THÔNG BÁO
   - "⚠ THIẾU GIỌNG ... câu": dịch vụ giọng đọc miễn phí bị nghẽn mạng. Vào Xem & sửa -> chọn video -> bấm
     Lưu phụ đề & Render lại. Video thiếu giọng sẽ KHÔNG tự lưu ra thư mục tải về cho đến khi đủ giọng.
   - "Thư mục lưu không dùng được" (ổ Google Drive, USB đã rút, ổ không tồn tại): phần mềm tự chuyển sang
     thư mục `data\` mặc định để vẫn chạy ổn định và báo rõ ô cần chọn lại trong Cài đặt.
   - "Bản quyền chưa kích hoạt" hoặc "Cần kết nối máy chủ bản quyền": bật Internet rồi bấm Tự Nhận Key Đã Cấp.
   - "Đồng hồ máy tính bị chỉnh lùi": chỉnh lại ngày giờ Windows cho đúng, bật Internet rồi bấm Tự Nhận Key Đã Cấp.
   - "⏸ Hoãn tải: YouTube/Bilibili tạm chặn ... tự tải tiếp lúc HH:MM": nguồn video tạm giới hạn tốc độ.
     Phần mềm tự nghỉ (YouTube 30 phút, Bilibili 1–10 phút) rồi tự tải tiếp, không tính là lỗi.
   - Muốn dịch hay hơn: vào Khóa API, dán khóa Gemini (lấy miễn phí tại aistudio.google.com), bấm Lưu rồi Kiểm tra.

6. KHÓA API (TAB KHÓA API)
   - Gom mọi khóa về một chỗ: Gemini, Groq, GenMax, ElevenLabs, Telegram và nhà cung cấp tự thêm.
   - Khóa luôn hiện dạng che bớt. Để trống ô khóa rồi bấm Lưu = giữ khóa đang dùng.
   - Nút Kiểm tra thử trực tiếp khóa đang dán trong ô và báo kết quả bằng tiếng Việt dễ hiểu.
   - Gemini và Groq dán được NHIỀU khóa (mỗi khóa 1 dòng): hết lượt (429) tự chuyển khóa khác, chạy song song
     nhiều khóa. Khóa Gemini nên tạo ở các dự án Google khác nhau để không dùng chung hạn mức.
   - GenMax hỗ trợ dán NHIỀU khóa cùng lúc (mỗi khóa 1 dòng hoặc cách dấu phẩy): tự kiểm tra từng khóa,
     chỉ lưu khóa tốt và tự chuyển sang khóa kế tiếp khi khóa đang dùng bị lỗi hoặc hết credit.
   - Kho giọng GenMax: tích những giọng bạn hay dùng rồi bấm Lưu kho của tôi.
   - ElevenLabs (khóa riêng, không qua GenMax): lấy khóa tại elevenlabs.io -> Developers -> API Keys (bật quyền
     Text to Speech và Voices), dán vào mục ElevenLabs, bấm Lưu rồi Kiểm tra.

7. CÀI ĐẶT & TỐC ĐỘ
   - Lưu gì chạy nấy: đổi cài đặt rồi bấm Lưu, các tập CHƯA bắt đầu làm sẽ chạy theo cài đặt mới.
     Video Trailer theo Cài đặt Trailer, video lồng tiếng theo Cài đặt Lồng tiếng.
   - Số tập làm cùng lúc: để "Tự động theo máy" (mặc định), phần mềm tự chọn theo CPU, RAM, card đồ họa.
     Máy đang làm việc khác thấy giật thì chọn 2 luồng.
   - Đang chạy tự động mà muốn đổi loại phim hoặc số lượng: bấm Dừng rồi bấm Chạy lại.

8. LIÊN HỆ HỖ TRỢ
   - Zalo: 0365.233.930 • Telegram: @suppMD • Hotline: 0938.28.3535 • Website: mdtool.io.vn
   - Khi báo lỗi, gửi kèm file: thư mục phần mềm \data\logs\mdirada.log
======================================================================

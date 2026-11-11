# Shin routine · TQ37

Bản giao diện tinh gọn dành cho học viên JPC.

TQ37: tặng tem ở bốn mốc 1–3–6–11 thói quen khác nhau đạt cấp 2. Mỗi mốc nhận một lần, kể cả các thành tựu đã có trước khi cập nhật. Tem chưa dùng nằm dưới cây; lời nhắn viết dở được giữ lại. Chỉ có một ô viết với gợi ý ngắn, không chọn người nhận. Khi lưu thành công, thư được gấp và treo ngang trên cây, khác với thẻ thói quen dọc. Chạm thư để đọc lại con tem, ý nghĩa, nội dung và ngày viết. Tem, bản nháp và thư đi cùng chức năng lưu bản sao/khôi phục; hoạt động offline sau khi app chuẩn bị xong bản offline. Thư hoàn tất giữ nguyên bản, không thay ngày viết khi đọc lại.

TQ36.2: sửa lỗi co thẻ trên desktop bằng cách bỏ bố cục hai cột cũ của trang Hôm nay. Giữ bố cục điện thoại và các tinh chỉnh đã duyệt.

TQ36.1: tinh chỉnh cuối trên bản TQ36. Cách làm dùng chữ Trước/Tiếp kèm mũi tên; hàng chọn ngày trong Nhật ký bỏ khung, ngày chọn có gạch dưới xanh; thẻ Hôm nay hạ 5 px khi đủ chỗ và hiện lại nhãn SENPAI KỂ. Check-in chỉ lóe trong 60 phút trước giờ hẹn, từ giờ hẹn chuyển vàng nếu chưa ghi, hoàn tất thì dừng hiệu ứng. Trạng thái tự cập nhật theo giờ và khi quay lại app.

Tên tab chính và tiêu đề trang dùng Nunito Sans; nội dung dùng Inter. Giữ nguyên font tiêu đề thẻ thói quen và cỡ chữ.

- Hôm nay mở ở chế độ thẻ; cụm chuyển và lật thẻ cố định, gọn hơn và cách thanh điều hướng một khoảng thoáng. Nút Đóng dấu trên thẻ có dạng tròn. Danh sách hiện tên và hành động; giữ tay mới xem thời điểm.
- Chạm thẻ để mở hai mục: Thẻ thói quen và Nhật ký. Cách làm nằm dưới nút lật, giữ banner và tiến độ học ban đầu; thứ tự là Phỏng vấn, Vì sao, Các bước, Thực tập và Ghi nhớ nếu có.
- Đóng dấu và check-in đều cần ghi chú cho từng thói quen được ghi nhận. Gợi ý có sẵn giúp điền nhanh; ghi chú trong ngày được dùng lại khi check-in. Memo tổng cuối ngày và cảm xúc vẫn tùy chọn.
- Hành trình dùng icon cây. Khi mở Cây thành tựu, cây lớn dần rồi các thẻ lần lượt hiện ra. Chạm nền cây để xem lại hiệu ứng; chạm thẻ để mở thành tựu. Các chặng đã đi qua nằm dưới cây.
- Hiệu ứng gắn thẻ lên cây khi đạt cấp 2 được giữ nguyên.
- Nhật ký dùng chuyển tuần, chọn ngày và ngôi sao để xem những ghi chú đáng nhớ.
- Hôm nay và Theo tuần bỏ lời Shin để gọn hơn; lời Shin theo từng giai đoạn cây vẫn giữ.
- Tiêu đề Hôm nay, Hành trình và Nhật ký nằm trên thanh đầu, ngày tháng ngay dưới. Thư viện ở cùng hàng với switch; ngôi sao Nhật ký nằm cạnh tiêu đề. Lề Sổ tay bằng với lề nội dung các thẻ.

## Đưa bản mới lên GitHub

Thay các file trong thư mục ứng dụng bằng các file cùng tên của bản này, giữ nguyên địa chỉ GitHub Pages đang dùng. Bản mới gồm `index.html`, `letters.js`, `sw.js`, `manifest.webmanifest` và hai icon. Cần đưa cả `letters.js` lên cùng thư mục với `index.html`.

Ứng dụng lưu bài làm trên trình duyệt của từng thiết bị. Có thể lưu bản sao trong Sổ tay trước khi cập nhật. Khi giữ nguyên địa chỉ app, bản TQ37 tiếp tục dùng dữ liệu cũ. Nếu app báo có bản cập nhật, đóng phần đang làm rồi chọn Cập nhật. Nội dung thư được lưu trên thiết bị để đọc lại trong app.

## Xem trên máy

Mở `index.html` để xem giao diện. Chế độ cài app và offline cần mở bằng địa chỉ web.

Để xem dữ liệu minh họa, nhập một tên bất kỳ và nhập `DEMO-KZ` ở ô Lớp trong màn làm quen. Dữ liệu Demo được lưu riêng với bài làm thật.

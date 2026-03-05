🧭 HƯỚNG DẪN TẠO FIRMWARE CHO BÀN PHÍM CƠ WIRELESS
(Sofle, Pipar, Corne,...)
⚠️ Lưu ý quan trọng:

Nếu bạn dùng Corne, đã có thể dùng ZMK Studio trực tiếp qua web.

Các loại khác như Sofle, Pipar,… vẫn cần làm theo hướng dẫn bên dưới.

Sản phẩm là DIY, có thể có nhiều cách keymap khác nhau. Đây là cách shop khuyên dùng vì ổn định và dễ thao tác nhất.

📞 Liên hệ Zalo nếu cần hỗ trợ: 0336905265
(Sàn TMĐT không cho gửi link vi phạm chính sách, bạn chủ động nhắn tin giúp shop nhé!)

📋 Mục lục
Bước 1: Tạo tài khoản GitHub

Bước 2: Chọn repository phù hợp

Bước 3: Fork repository

Bước 4: Build firmware qua Actions

Bước 5: Mở Keymap Editor

Bước 6: Kết nối với repository

Bước 7: Tùy chỉnh keymap

Bước 8: Tải firmware

Bước 9: Nạp firmware vào bàn phím

Mẹo: Tăng thời gian chờ sleep

Khắc phục lỗi mất kết nối L-R

Hướng dẫn dùng dongle Bluetooth

✅ Bước 1: Tạo tài khoản GitHub
👉 Truy cập github.com và đăng ký tài khoản (nếu chưa có).

✅ Bước 2: Chọn repository phù hợp
🟢 Corne Wireless
Corne v4 wireless (hỗ trợ ZMK Studio)

Corne có hỗ trợ RGB

Corne bản phụ cần chỉnh sửa thêm

Corne Pandakb Demo

🟡 Sofle Wireless
Sofle có hỗ trợ RGB

Sofle hỗ trợ ZMK Studio (không LED RGB)

🔵 Pipar Flake Wireless
Pipar flake wireless

📸 Hình minh họa:

<p align="center"> <img src="https://imgur.com/d6s8xe5.jpg" width="400"/> <img src="https://imgur.com/WOhzvFq.jpg" width="400"/> </p>
✅ Bước 3: Fork repository
Nhấn nút Fork ở góc trên bên phải trang repository.

Chọn fork về tài khoản cá nhân của bạn.

<p align="center"> <img src="https://imgur.com/7S8EGNl.jpg" width="400"/> <img src="https://imgur.com/Ve8TC8g.jpg" width="400"/> </p>
✅ Bước 4: Build firmware qua Actions
Vào tab Actions của repository vừa fork.

Chọn workflow phù hợp (nếu có), nhấn Run workflow.

<p align="center"> <img src="https://imgur.com/orJ0TOX.jpg" width="400"/> <img src="https://imgur.com/UEqkfzH.jpg" width="400"/> </p>
✅ Bước 5: Mở Keymap Editor
👉 Truy cập: https://nickcoutsos.github.io/keymap-editor/

✅ Bước 6: Kết nối với repository
Chọn "Connect to GitHub".

Chọn repository bạn vừa fork.

<p align="center"> <img src="https://imgur.com/yHru4EW.jpg" width="400"/> <img src="https://imgur.com/6wIjezp.jpg" width="400"/> </p>
✅ Bước 7: Tùy chỉnh keymap
Kéo thả, chỉnh sửa layout theo ý thích.

Nhấn Save và đặt tên để nhớ phiên bản.

<p align="center"> <img src="https://imgur.com/AGpivZR.jpg" width="400"/> <img src="https://imgur.com/j0CJfxT.jpg" width="400"/> </p>
✅ Bước 8: Tải firmware
Sau khi save, vào lại tab Actions của repository.

Sẽ có một tiến trình build mới tự động chạy.

Đợi 5–7 phút cho đến khi hoàn tất.

Tải file .zip về máy, giải nén.

<p align="center"> <img src="https://imgur.com/4qNT8wF.jpg" width="400"/> <img src="https://imgur.com/ZmfIkmQ.jpg" width="400"/> </p>
✅ Bước 9: Nạp firmware vào bàn phím
⚠️ Lưu ý:

Nạp từng bên riêng biệt, không kết nối 2 mạch với nhau.

Dây 3.5mm chỉ dùng để sạc, không truyền dữ liệu.

📌 Các bước nạp:
Cắm dây USB vào máy tính và bên mạch cần nạp.

Nhấn nút reset trên mạch (nút đen nhỏ dưới OLED):

Giữ 2 giây → nhả → nhấn thêm 1 lần nữa rồi nhả.

Ổ đĩa tên NANO!V2 sẽ hiện ra.

Kéo file firmware .uf2 tương ứng vào ổ đĩa đó.

Đợi vài giây là xong.

🎥 Video hướng dẫn:
Cách reset bàn phím

Nạp firmware chi tiết

Lắp ráp DIY chi tiết

⚡ Mẹo: Tăng thời gian chờ trước khi bàn phím sleep
👉 Xem video hướng dẫn

❗ Khắc phục lỗi: Mất kết nối giữa 2 bên trái – phải
Nếu sau khi nạp firmware, bên phải không kết nối được với bên trái:

Lỗi này ít gặp nhưng có thể xảy ra do firmware cũ bị đè.

Cách xử lý:
👉 Tham khảo hướng dẫn sửa lỗi tại đây

📡 Hướng dẫn dùng dongle Bluetooth cho PC không có Bluetooth
👉 Xem hướng dẫn tại đây

💬 Hỗ trợ
Nếu bạn gặp bất kỳ khó khăn nào trong quá trình thực hiện, đừng ngần ngại liên hệ qua Zalo: 0336905265 để được hỗ trợ nhanh nhất! 🚀

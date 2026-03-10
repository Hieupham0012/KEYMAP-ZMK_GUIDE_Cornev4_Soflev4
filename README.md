# 🎯 HƯỚNG DẪN TẠO FIRMWARE CHO BÀN PHÍM CƠ WIRELESS
# ⚠️ LIÊN HỆ SHOP NẾU REPOSITORIES BỊ LỖI ĐỂ SHOP CẬP NHẬT HOẶC GỬI LẠI ĐƯỜNG DẪN KHÁC.
> 💡 **Nếu sử dụng corne, sofle không led RGB đã có thể dùng zmk studio trực tiếp qua web, còn sofle có led RGB, pipar,.... bạn vẫn phải thao tác theo hướng dẫn dưới đây.**

⚠️ *Chú ý: Sản phẩm là DIY nên có nhiều cách Keymap khác nhau, có thể có cách dễ hơn hoặc khó hơn. Dưới đây là hướng dẫn của shop mà shop cảm thấy đơn giản và thực hiện thẳng vào code mạch hoạt động ổn định nhất*

📱 ***-lưu ý thêm: Hãy chủ động nhắn zalo nếu bạn cần cung cấp thêm thông tin hoặc đường dẫn, Trên sàn thương mại điện tử không thể cung cấp thông tin vi phạm chính sách sàn Zalo: 0336905265***

---

# 🚀 HƯỚNG DẪN TẠO FIRMWARE TỪ REPOSITORIES CÓ SẴN.

---

## 📌 Bước 1: Tạo tài khoản GitHub
👉 Đầu tiên bạn phải có tài khoản github *"khá đơn giản để có phần này"*

---

## 📌 Bước 2: Tìm kiếm repositories hoặc đơn giản là nhấn vào đúng đường link repositories ở dưới.
🔍 Tìm kiếm repositories (*"có đường dẫn nếu không tìm thấy ở dưới"*) của shop theo đúng bàn phím cần keymap là corne hay sofle zmk wireless

<img src="https://imgur.com/d6s8xe5.jpg" width="800"/>
<img src="https://imgur.com/WOhzvFq.jpg" width="800"/>
<img src="https://imgur.com/A9mqpqd.jpg" width="800"/>

---

## 📌 Bước 3: Fork repositories "bàn phím nào fork repositories bàn phím đó" nhấn vào link bàn phím dưới
🍴 Fork repositories dưới này *"tạo nhánh thành về repositories của bạn"*

### 🎯 Bàn phím nào thì fork repositoies đó. *"Nhấn vào để đến Repostories phù hợp"*

---

### 🟢 **Corne wireless** - đường dẫn đến đúng repositories

- [Repositories Corne v4 wireless "hỗ trợ zmk studio"](https://github.com/shopcntech/corne1)
- [Repositories Corne có hỗ trợ RGB "hỗ trợ zmk studio"](https://github.com/Hieupham0012/zmk-dongle-corne-sofle)
- [Repositories Corne bản phụ cần chỉnh sửa thêm](https://github.com/Hieupham0012/Corne-OLED_Wireless)
- [Repositories Corne Pandakb Demo](https://github.com/PandaKBLab/zmk-for-keyboards)

---

### 🟡 **Sofle wireless** - đường dẫn đến đúng repositories

- [Repositories Sofle wireless "có hỗ trợ RGB"](https://github.com/Hieupham0012/Sofle-oled_wireless)
- [Repositories Sofle wireless "có hỗ trợ zmk studio nhưng không hỗ trợ Led RGB"](https://github.com/Hieupham0012/zmk-dongle-corne-sofle)

---

### 🔵 **Pipar flake wireless** - đường dẫn đến đúng repositories

- [Repositories Pipar flake wireless](https://github.com/Hieupham0012/pipar)

<img src="https://imgur.com/7S8EGNl.jpg" width="800"/>
<img src="https://imgur.com/Ve8TC8g.jpg" width="800"/>

---

## 📌 Bước 4: Qua mục action để bắt đầu build
⚙️ Vào mục **Actions** để bắt đầu build firmware

<img src="https://imgur.com/orJ0TOX.jpg" width="800"/>
<img src="https://imgur.com/UEqkfzH.jpg" width="800"/>
<img src="https://imgur.com/y7C7yjO.jpg" width="800"/>

---

## 📌 Bước 5: Mở Keymap Editor
🎹 Bắt đầu vào keymap editor  
🔗 Link: **https://nickcoutsos.github.io/keymap-editor/**

---

## 📌 Bước 6: Kết nối với repository
🔗 Chọn đường dẫn cho keymap editor đến đúng repos của bạn

<img src="https://imgur.com/yHru4EW.jpg" width="800"/>
<img src="https://imgur.com/6wIjezp.jpg" width="800"/>

---

## 📌 Bước 7: Tùy chỉnh keymap
✏️ Tiến hành keymap theo ý. Xong thì bạn nhấn **"Save"** có thể ghi tên để nhớ bản lưu. Sau đó quay lại action repositories của bạn.

<img src="https://imgur.com/AGpivZR.jpg" width="800"/>
<img src="https://imgur.com/j0CJfxT.jpg" width="800"/>
<img src="https://imgur.com/4qNT8wF.jpg" width="800"/>
<img src="https://imgur.com/ZmfIkmQ.jpg" width="800"/>


---

## 📌 Bước 8: Tải firmware
⏳ Cuối cùng chỉ đợi **5 đến 7 phút** để tạo code tự động bạn tải firmware về giải nén và nạp vào từng bên mạch là đã hoàn thành.

<img src="https://imgur.com/chbB746.jpg" width="800"/>

---

## 📌 Bước 9: Nạp firmware vào bàn phím
💾 **Cách nạp:**  
- Cắm dây vào máy tính kết nối với bên cần nạp  
- Nhấn nút reset trên mạch **3 giây nhả ra nhấn cái nữa liền**  
- Thư mục ổ đĩa **nano!v2** sẽ hiện ra  
- Giữ chuột kéo firmware bên cần nạp vào ổ đĩa mới hiện là xong

---

# ⚠️ LƯU Ý QUAN TRỌNG KHI NẠP FIRMWARE

🔴 **Nạp firmware chú ý nạp từng bên không kết nối 2 mạch.**  
🔴 **Nhấn reset trên mạch là nút đen nhỏ dưới oled *"bấm 2 giây nhả, nhấn và nhả thêm 1 lần nữa liền"***

---

## 🎥 VIDEO HƯỚNG DẪN

- [Video hướng dẫn reset](https://www.youtube.com/shorts/RQlWx_O3xkk)
- [Video hướng dẫn thao tác nạp chi tiết](https://youtu.be/H-76SoJGf8M)
- [Video hướng dẫn thao tác lắp DIY chi tiết](https://youtu.be/MlP_Rwf9_qI?si=7YsN9J8kUl5bEZpQ)

---

# ⚡ MẸO: TĂNG THỜI GIAN CHỜ TRƯỚC KHI SLEEP

➕ Phần này video hướng dẫn tăng thời gian để bàn phím không bị sleep

## [Video Hướng dẫn tăng thời gian chờ của bàn phím không bị sleep](https://youtu.be/d4-gtTuylZw)

---

# ❗ KHẮC PHỤC LỖI

## *Phần cập nhập thêm: Nếu sau nạp bàn phím bên phải không kết nối được bàn phím bên trái:*

⚠️ Trường hợp này không thường xuyên xuất hiện nhưng có thể có nên shop lưu ý thêm.  
Nghĩa là bàn phím đang bị đè code mất tín hiệu giữa 2 mạch cần nạp reset trước rồi nạp firmware mới.

📌 **Lưu ý:** Bàn phím này là bàn phím wireless dây 3,5mm có tác dụng sạc không truyền dữ liệu nên chỉ có cách theo hướng dẫn trên. Cách khác để dùng có dây là nạp firmware bản có dây chứ không phải bản wireless này.

## [🔧 Nếu gặp mất kết nối 2 mạch nhấn vào đây](https://github.com/Hieupham0012/Fix_Eror_connect_L-R_nano_v2)

---

# 📡 HƯỚNG DẪN DÙNG DONGLE

# Hướng dẫn các bạn dùng PC không có bluetooh và mua dongle bên mình

## [📲 Nhấn vào đây để đến phần hướng dẫn](https://github.com/Hieupham0012/Guide_Dongle_firmware_Corne_Sofle)

---

<p align="center">
  <b>✨ Chúc các bạn thành công! ✨</b><br>
  <i>Mọi thắc mắc xin liên hệ Zalo: 0336905265</i>
</p>

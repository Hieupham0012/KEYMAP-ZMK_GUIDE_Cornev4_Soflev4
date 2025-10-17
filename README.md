# *Chú ý: Sản phẩm là DIY nên có nhiều cách Keymap khác nhau, có thể có cách dễ hơn hoặc khó hơn. Dưới đây là hướng dẫn của shop mà shop cảm thấy đơn giản và thực hiện thẳng vào code mạch hoạt động ổn định nhất*
### *-lưu ý thêm: Hãy chủ động nhắn zalo nếu bạn cần cung cấp thêm thông tin hoặc đường dẫn, Trên sàn thương mại điện tử không thể cung cấp thông tin vi phạm chính sách sàn Zalo: 0336905265*
# HƯỚNG DẪN TẠO FIRMWARE TỪ REPOSITORIES CÓ SẴN.
## Bước 1: Đầu tiên bạn phải có tài khoản github "khá đơn giản để có phần này"
## Bước 2: tìm kiếm repositories của shop theo đúng bàn phím cần keymap là corne hay sofle zmk wireless
<img src="https://imgur.com/d6s8xe5.jpg">
<img src="https://imgur.com/WOhzvFq.jpg">

<img src="https://imgur.com/A9mqpqd.jpg">

## Bước 3: Fork repositories này "tạo nhánh thành về repos của bạn"
## [Đây là repositories Corne v4 wireless cần fork](https://github.com/shopcntech/corne1)
## [Đây là repositories Corne v4 wireless cần fork](https://github.com/Hieupham0012/Corne-OLED_Wireless)
## [Đây là repositories Corne Pandakb cần fork](https://github.com/PandaKBLab/zmk-for-keyboards)
## [Đây là repositories Sofle RGB v2.1 pandakb wireless](https://github.com/Hieupham0012/Sofle-oled_wireless)
## [Đây là repositories Pipar flake wireless](https://github.com/Hieupham0012/pipar).


<img src="https://imgur.com/7S8EGNl.jpg">

<img src="https://imgur.com/Ve8TC8g.jpg">

## Bước 4: Qua mục action để bắt đầu build


<img src="https://imgur.com/orJ0TOX.jpg">
<img src="https://imgur.com/UEqkfzH.jpg">
<img src="https://imgur.com/y7C7yjO.jpg">

## Bước 5: bắt đầu vào keymap editor link: https://nickcoutsos.github.io/keymap-editor/
## Bước 6: chọn đường dẫn cho keymap editor đến đúng repos của bạn
<img src="https://imgur.com/yHru4EW.jpg">


<img src="https://imgur.com/6wIjezp.jpg">

## Bước 7: tiến hành keymap theo ý. Xong thì bạn nhấn "Save" có thể ghi tên để nhớ bản lưu. Sau đó quay lại action repositories của bạn. 
<img src="https://imgur.com/AGpivZR.jpg">
<img src="https://imgur.com/j0CJfxT.jpg">
<img src="https://imgur.com/4qNT8wF.jpg">
<img src="https://imgur.com/ZmfIkmQ.jpg">
<img src="https://imgur.com/chbB746.jpg">

## Cuối cùng chỉ đợi 5 đến 7 phút để tạo code tự động bạn tải firmware về giải nén và nạp vào từng bên mạch là đã hoàn thành.

### Cách nạp bạn cắm dây vào mày tính kết nối với bên cần nạp, nhấn nút reset trên mạch 3 giây nhả ra nhấn cái nữa liền > thư mục ổ đĩa nano!v2 sẽ hiện ra > bạn giữ chuột kéo firmware bên cần nạp vào ổ địa mới hiện là xong

# Nạp firmware chú ý nạp từng bên không kết nối 2 mạch. Nhấn reset trên mạch là nút đen nhỏ dưới oled "bấm 2 giây nhả, nhấn và nhả thêm 1 lần nữa liền"
## [video hướng dẫn reset](https://www.youtube.com/shorts/RQlWx_O3xkk)
## [video hướng dẫn thao tác nạp chi tiết](https://youtu.be/H-76SoJGf8M)
## [video hướng dẫn thao tác lắp DIY chi tiết](https://youtu.be/MlP_Rwf9_qI?si=7YsN9J8kUl5bEZpQ)
# *Phần cập nhập thêm: Nếu sau nạp bàn phím bên phải không kết nối được bàn phím bên trái:
## -trường hợp này không thường xuyên xuất hiện nhưng có thể có nên shop lưu ý thêm. 
nghĩa là bàn phím đang bị đè code mất tín hiệu giữa 2 mạch cần nạp reset trước rồi nạp firmware mới.
Bàn phím này là bàn phím wireless dây 3,5mm có tác dụng sạc không truyền dữ liệu nên chỉ có cách theo hướng dẫn trên. Cách khác để dùng có dây là nạp firmware bản có dây chứ không phải bản wireless này
## [Nếu gặp mất kết nối 2 mạch nhấn vào đây](https://github.com/Hieupham0012/Fix_Eror_connect_L-R_nano_v2)

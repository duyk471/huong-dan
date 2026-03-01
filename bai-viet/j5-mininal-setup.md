# Hướng dẫn xử lý FRP Samsung Galaxy J5, cài đặt TWRP và cài LineageOS

Mình nhận được một chiếc Samsung Galaxy J5 cũ từ người quen nhưng gặp vấn đề là không nhớ mật khẩu nên mình đã thử Factory Reset và... bị khóa FRP (Báo lỗi là: "An unauthorised attempt has been made to reset your device to factory default settings").

Mình đã thử flash lại stock rom, cài custom rom, tìm các tutorial trên Youtube cũng như các phần mềm khác nhau nhưng đều thất bại thảm hại. Phần lớn là vì các thủ thuật no-PC đều không làm được, các phần mềm hỗ trợ phá FRP cũng không dùng được do... mất tiền :))). Vẫn cay DroidKit vì nó chạy trình xử lý rồi mới hiện cái pop-up bảo là cần hoàn tất thì bạn cần trả 39,99$.

## Xử lý FRP

Cách này chỉ hỗ trợ từ Android 5.0 cho đến 6.0.1 thôi nghen.

Video hướng dẫn: [Samsung J5 FRP/Google Bypass Android 6 0 1 With Free Tool Easy - samsung j5 frp bypass android 6.0.1](https://www.youtube.com/watch?v=LsWrvx8a6jg) (Nhưng mà ông này nói tiếng gì ấy chứ không phải Tiếng Anh, nhìn và làm theo như trong video là được).

Bạn cần tải [SamFW Tools](https://samfw.com/blog/samfw-frp-tool-1-0-remove-samsung-frp-one-click), đây là công cụ miễn phí duy nhất mà mình tìm được. Nhưng chỉ hỗ trợ miễn phí bypass FRP trong Download Mode thôi (Để mở Download Mode cho máy thì bạn tắt nguồn rồi bấm tổ hợp nút giảm âm lượng + nút home (hai nút này trước) rồi mới bấm nút nguồn).

## Cài đặt TWRP

Bạn không nên root mà thay vào đó hãy flash `.img.tar` của TWRP. Tải: [TWRP for Samsung Galaxy J5 3G (SM-J500H)](https://twrp.me/samsung/j53gxx.html) (Mình dùng SM-J500H, bạn kiểm tra bằng cách tháo quả pin máy ra)

Xem hướng dẫn: [How to Install TWRP Recovery on Any Samsung Device (2026 Guide)](https://www.youtube.com/watch?v=kXr0t_iEjtQ)

Sau đó thì bạn nên lắp thẻ nhớ (SD Card) vào máy. Mình đã phải lên trên Youtube để xem hướng dẫn cách lắp thẻ SD vào máy này :)) nên nếu bạn không biết chỗ để lắp thì xem hướng dẫn: [Galaxy J5 - How to insert micro SD card](https://www.youtube.com/watch?v=M8PNVprPb4k).

## LineageOS

Chọn phiên bản:

- [Galaxy-J5-Unofficial-LineageOS-Sources](https://github.com/Galaxy-J5-Unofficial-LineageOS-Sources/Releases) - Từ Android 11 trở đi (Lineage 18), bản này theo README của dự án thì không hỗ trợ Camera.
- [LineageOS 21 (Android 14) port (from XDA port thread)](https://mega.nz/folder/WEVTGbbC#ekL2eZgPIpFDN5Fil50SIA)
- [Lineage OS 17.1 Android 10](https://sourceforge.net/projects/lineageos-17-1-for-galaxy-j5/files) - Khuyến khích chọn bản này.

Android càng cao thì càng chậm, mà RAM của thiết bị cũng khá khiêm tốn: 1.5GB.

## Cài đặt

Hướng dẫn: [How to Install Lineage OS 15.1 on Any Device using TWRP Recovery](https://www.youtube.com/watch?v=SOZspNM9lIw) (Hướng dẫn hơi cũ nhưng cách làm tương tự)


## Không hỗ trợ File Transfer trên Linux

Mình đang dùng Debian Linux nhưng khi cắm thiết bị vào nó không nhận luôn (Hiện trong Thunar). Chỉ cần nhập lệnh sau là được.

```bash
sudo apt install gvfs-backends gvfs-fuse libmtp-runtime
```


# Hướng dẫn chuyển đổi định dạng sách từ Aozora Bunko về Kindle

Lấy từ nguồn nào đó bên Reddit mà quên mất rùi T_T.

1. Truy cập [Aozora Bunko](http://www.aozora.gr.jp/) (tương tự như Project Gutenberg, nhưng dành cho sách tiếng Nhật) và tìm bất kỳ cuốn sách nào bạn muốn đọc. Bạn có thể tìm kiếm theo tên tác giả hoặc theo tiêu đề sách.  

2. Khi đã chọn được sách (ví dụ: [Bocchan](http://www.aozora.gr.jp/cards/000148/card752.html)), kéo xuống cuối trang và tải về tệp `.zip` có chữ **ruby** trong tên. Sau đó, giải nén và lấy tệp `.txt` bên trong.  

3. Tiếp theo, bạn cần tải [AozoraEpub](github.com/kyukyunyorituryo/AozoraEpub3) (yêu cầu cài đặt Java) và **[kindlegen](https://old.reddit.com/r/kindle/comments/igveym/anybody_for_the_backup_zip_file_of_kindlegen/gdppak9/)**. Giải nén AozoraEpub vào một thư mục bất kỳ, rồi sao chép `kindlegen.exe` vào thư mục gốc nơi có chứa `AozoraEpub3.jar`.  

4. Mở `AozoraEpub3.jar` (nếu chưa cài Java thì có thể sẽ báo lỗi). Nhấn nút ở góc trên bên phải và [chuyển cài đặt sang Kindle PW](http://i.imgur.com/dzU71nc.png).  
   - Sau đó, nhấn nút bên phải ngay dưới ô **出力先** (có biểu tượng trang giấy ghi “TXT”) và chọn tệp `.zip` bạn đã tải về trước đó.  
   - Cuối cùng, trong cửa sổ mới hiện ra, nhấn nút có dấu **✔**. Chương trình sẽ xuất ra một tệp `.epub`, sau đó là `.mobi`.  

5. Chỉ cần chép tệp `.mobi` vào Kindle của bạn và tận hưởng việc đọc sách (dù là đọc giải trí hay học tập nghiêm túc).  

💡 **Lưu ý:** Sau khi đăng hướng dẫn này, mình nhận ra rằng bạn thậm chí **không cần giải nén tệp `.txt`**. AozoraEpub có thể xử lý trực tiếp tệp `.zip` mà bạn tải về.  

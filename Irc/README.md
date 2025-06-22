# Hướng dẫn tạo và sử dụng file lời bài hát (LRC)

File LRC (Lyric) là file văn bản chứa lời bài hát kèm thời gian, cho phép hiển thị lời đồng bộ với bài hát đang phát.

## Cấu trúc của file LRC

Mỗi dòng lời bài hát được định dạng như sau:
```
[mm:ss.xx]Lời bài hát
```

Trong đó:
- `mm`: phút (2 chữ số)
- `ss`: giây (2 chữ số)
- `xx`: mili-giây (có thể có hoặc không)
- `Lời bài hát`: nội dung lời bài hát tương ứng với thời gian

## Ví dụ:

```
[00:00.00]Bài hát: Ví dụ
[00:02.00]Ca sĩ: Nguyễn Văn A
[00:04.00]
[00:06.00]Đây là lời đầu tiên của bài hát
[00:10.50]Đây là lời tiếp theo
[00:15.20]Và đây là dòng lời thứ ba
```

## Cách tạo file LRC

### Cách 1: Tạo thủ công
1. Mở trình soạn thảo văn bản (Notepad, VS Code...)
2. Tạo các dòng lời với định dạng [thời_gian]lời_bài_hát
3. Lưu file với đuôi .lrc

### Cách 2: Sử dụng phần mềm chuyên dụng
- **Subtitle Edit**: https://www.nikse.dk/subtitleedit/
- **LRC Editor**: Tìm kiếm trên internet

### Cách 3: Sử dụng trang web tạo LRC
- Có nhiều trang web cho phép tạo file LRC trực tuyến
- Bạn có thể tìm kiếm "LRC maker online"

## Cách sử dụng trong trình phát nhạc này

1. Đặt file LRC trong thư mục `lrc/`
2. Đặt tên file LRC trùng với tên file nhạc (nhưng với đuôi .lrc thay vì .mp3)
3. Trong file `js/index.js`, cập nhật đường dẫn đến file LRC trong danh sách nhạc:

```javascript
{
  title: "Tên bài hát",
  url: "./nhac/tenbaihat.mp3",
  cover: "./images/cover.jpg",
  lrc: "./lrc/tenbaihat.lrc"  // Đường dẫn đến file LRC
}
```

## Ghi chú

- Nếu file LRC không tồn tại hoặc không được chỉ định, trình phát sẽ hiển thị thông báo mặc định
- Thời gian trong file LRC nên chính xác để lời hiển thị đồng bộ với nhạc
- Bạn có thể tìm kiếm file LRC có sẵn cho các bài hát phổ biến trên internet 
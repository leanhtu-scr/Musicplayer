# Hướng dẫn tạo file LRC tiếng Trung

File LRC tiếng Trung hoạt động giống như các file LRC khác, nhưng có một số lưu ý đặc biệt khi làm việc với ngôn ngữ tiếng Trung.

## Cách tạo file LRC tiếng Trung

### Bước 1: Tìm lời bài hát tiếng Trung
- Tìm kiếm lời bài hát tiếng Trung trên các trang web như QQ Music, NetEase Music, Baidu Music...
- Nếu bạn không biết tiếng Trung, có thể sử dụng Google Translate để dịch tên bài hát và ca sĩ sang tiếng Trung để tìm kiếm

### Bước 2: Tạo file LRC với định dạng đúng
- Mỗi dòng lời vẫn theo định dạng: `[mm:ss.xx]Lời bài hát tiếng Trung`
- Bạn có thể thêm phiên âm hoặc dịch nghĩa bên cạnh: `[mm:ss.xx]中文歌词 (Phiên âm/Dịch nghĩa)`

### Bước 3: Lưu ý về mã hóa kí tự
- File LRC phải được lưu dưới dạng UTF-8 để hiển thị chính xác các ký tự tiếng Trung
- Trong Notepad++, bạn có thể chọn Encoding > UTF-8 khi lưu file
- Trong VS Code, UTF-8 thường là định dạng mặc định

## Công cụ tạo LRC tiếng Trung

### Phần mềm chuyên dụng:
- **LRC Maker**: https://lrcmaker.net/ (Hỗ trợ tiếng Trung)
- **酷狗歌词制作工具**: Công cụ tạo lời của Kugou Music
- **网易云音乐歌词制作**: Công cụ tạo lời của NetEase Music

### Trang web trực tuyến:
- **歌词适配**: https://lrc-maker.github.io/ (Công cụ mã nguồn mở)
- **Lyric Maker**: https://lyricmaker.netlify.app/ (Hỗ trợ nhiều ngôn ngữ)

## Cách tìm file LRC tiếng Trung có sẵn

Bạn có thể tìm kiếm file LRC tiếng Trung có sẵn trên internet tại:
- **魔镜歌词网**: http://mojim.com (Thư viện lời bài hát lớn tiếng Trung)
- **歌词网**: https://www.geci.net/
- **QQ音乐**: y.qq.com (Trích xuất từ ứng dụng QQ Music)
- **网易云音乐**: music.163.com (Trích xuất từ ứng dụng NetEase Music)

## Ví dụ về file LRC tiếng Trung

```
[00:00.00]告白气球 - 周杰伦
[00:02.00]Gào Bái Qì Qiú - Châu Kiệt Luân
[00:05.00]
[00:10.00]塞纳河畔 左岸的咖啡
[00:15.00]我手一杯 品尝你的美
[00:20.00]留下唇印的嘴
[00:25.00]
[00:30.00]花店玫瑰 名字写错谁
[00:35.00]告白气球 风吹到对街
[00:40.00]微笑在天上飞
```

## Lưu ý khi tạo LRC tiếng Trung
- Tiếng Trung thường có ít từ hơn so với tiếng Việt, nên thời gian hiển thị mỗi dòng có thể ngắn hơn
- Nếu bạn muốn thêm cả phiên âm và nghĩa tiếng Việt, hãy tạo dòng riêng với thời gian thích hợp
- Kiểm tra lại file LRC bằng cách mở bằng trình soạn thảo để đảm bảo ký tự hiển thị chính xác

## Ví dụ về việc thêm phiên âm và nghĩa

```
[00:10.00]我爱你 
[00:11.00]Wǒ ài nǐ 
[00:12.00](Anh yêu em)
``` 
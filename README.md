# Trường Tiếng Việt Của Em · Bài 1

Bảy trò chơi tương tác cho **Bài 1: Bảng chữ cái, nguyên âm và phụ âm**, dẫn dắt bởi Trâu Con đội nón lá.

**Chơi ngay:** https://trangphan0301.github.io/truong-tieng-viet-bai-1/

Chạy trên iPad, điện thoại, máy tính và máy chiếu. Không cần cài đặt, không cần đăng nhập.

## Bảy trò chơi

| # | Trò chơi | Bám theo phần nào của bài | Mở thẳng |
|---|---|---|---|
| 1 | Thơ “Lên Sáu” | Bài thơ Tản Đà: đọc thơ, nghe thơ chọn tranh, xếp 12 câu thơ | `#g1` |
| 2 | Chuyến tàu chữ cái | 12 nguyên âm lên tàu vàng, 17 phụ âm lên tàu xanh (in thường, in hoa, trộn lẫn) | `#g2` |
| 3 | Tìm bạn cho chữ | Ghép chữ in hoa với chữ in thường; các nhóm dễ nhầm a/ă/â, o/ô/ơ, u/ư, b/d/p/q | `#g3` |
| 4 | Chữ trốn ở đâu? | Trò chơi “Nguyên âm / Phụ âm trốn ở đâu?” với đu đủ, trâu, nhà, cặp… | `#g4` |
| 5 | Xây nhà cho tiếng | Mô hình tiếng: âm đầu + âm chính + âm cuối, rồi đặt dấu thanh | `#g5` |
| 6 | Đội dấu cho chữ | 6 thanh: la, là, lá, lạ, lả, lã · ma, mà, má, mạ, mả, mã | `#g6` |
| 7 | Tô nét cơ bản | Tô 12 nét cơ bản bằng ngón tay trên khung ô li | `#g7` |

Muốn mở thẳng một trò chơi, thêm mã ở cột cuối vào sau đường link, ví dụ `…/truong-tieng-viet-bai-1/#g5`. Muốn mở một vòng cụ thể, thêm số vòng: `#g5-2` là vòng 3 (“Không có âm đầu”).

## Cách chơi

- Bấm **Bắt đầu chơi** để nghe Trâu Con chào và vào trò chơi 1, hoặc chọn thẳng một trò chơi trong danh sách.
- Kéo – thả bằng ngón tay, chuột hoặc bút. Các em nhỏ chưa kéo giỏi có thể **chạm vào chữ rồi chạm vào chỗ cần đặt**.
- Mỗi câu hướng dẫn được Trâu Con đọc to ngay khi hiện ra, để các em chưa đọc được chữ vẫn nghe và làm theo. Mỗi màn có **một nút loa** cạnh lời hướng dẫn (hoặc chạm vào Trâu Con) để nghe lại.
- Chạm vào chữ, tranh hoặc câu thơ để nghe đọc từng chữ, từng tiếng, từng câu.
- Đúng: tiếng “ting”, Trâu Con gật đầu, lời khen. Sai: thẻ rung nhẹ, “Thử lại nhé!”. Sai hai lần, chỗ đúng sẽ nhấp nháy gợi ý.
- Không trừ điểm. Hết mỗi trò chơi, các em nhận 1–3 sao; sao được nhớ trên chính thiết bị đó.

## Giọng Trâu Con

Trâu Con luôn xưng **“mình”** và gọi học sinh là **“các bạn”**. Chữ cái được đọc **theo âm**: a, á (ă), ớ (â), bờ, cờ, dờ, đờ…, ca (k), quy (q), i dài (y).

Hiện tại trò chơi dùng **giọng đọc tiếng Việt có sẵn trên máy**, đọc chậm (tốc độ 0,82). Nếu máy không phát ra tiếng, trò chơi hiện lời nhắc kiểm tra âm lượng và chế độ im lặng. Nếu máy có giọng nam (ví dụ “NamMinh” trên Microsoft Edge), trò chơi chọn giọng đó và nâng cao giọng một chút cho giống giọng bé trai. Giọng thật sự nghe ra sao tùy thiết bị: iPad thường chỉ có giọng nữ “Linh”.

### Khi không nghe thấy tiếng

Trang chính có nút **Kiểm tra âm thanh**: bấm vào để biết máy có giọng đọc tiếng Việt không và Trâu Con có phát ra tiếng không. Trên iPad, giọng đọc của máy bị tắt khi bật chế độ **Im lặng** hoặc **Không làm phiền** (trong Trung tâm điều khiển), dù đã tăng âm lượng. Nên mở trò chơi bằng **Safari**.

File ghi âm (mục dưới) phát qua trình phát âm thanh của trình duyệt, nên vẫn nghe được khi iPad đang ở chế độ Im lặng. Đây là cách chắc chắn nhất để lớp nào cũng nghe được Trâu Con.

### Thay bằng đúng giọng trong video của Trâu Con

1. Mở file [AM-THANH.md](AM-THANH.md): đó là danh sách mọi câu Trâu Con nói, kèm tên file cần đặt.
2. Thu âm hoặc xuất từng câu (cùng giọng với video) thành file `.mp3`, đặt đúng tên trong danh sách.
3. Bỏ các file vào thư mục `audio/`.
4. Mở `audio/manifest.json` và liệt kê tên các file đã có, ví dụ:
   ```json
   { "files": ["loi-welcome.mp3", "loi-menu.mp3", "chu-a.mp3", "chu-aw.mp3"] }
   ```

Mỗi câu nói được ghép từ vài đoạn (ví dụ “Các bạn nghe nhé:” + “lá”). Khi **đủ mọi đoạn** của câu đó, trò chơi phát file ghi âm; còn thiếu đoạn nào thì cả câu dùng giọng đọc của máy, để không lẫn hai giọng trong một câu.

## Chuẩn chữ tiếng Việt

- Mọi chữ được lưu và so sánh ở dạng **NFC**. Chữ gõ từ bàn phím dạng NFD (một số máy Apple) vẫn được nhận đúng.
- **Bỏ thanh** chỉ gỡ 5 dấu thanh (sắc, huyền, hỏi, ngã, nặng); dấu mũ, dấu trăng, dấu móc và chữ đ được giữ nguyên: `ặ → ă`, `ổ → ô`, `ở → ơ`.
- **Phân tích thanh**: có dấu nào thì là thanh đó, không dấu là thanh ngang.
- **Đặt dấu** lên âm chính theo kiểu quen dùng trong sách (hóa, quả, mười, tiếng).
- Phông chữ không chân, nét tròn: Baloo 2 cho tiêu đề, Nunito cho chữ đọc và chữ cái.

## Sửa nội dung

Toàn bộ trò chơi nằm trong một file `index.html`. Phần **DỮ LIỆU BÀI HỌC** ở đầu đoạn mã chứa các danh sách có thể sửa trực tiếp:

- `POEM`: 12 câu thơ “Lên Sáu”
- `LETTER_SOUND`: cách đọc từng chữ cái
- `WORD_PIC`: các tiếng có tranh dùng trong trò 4 và 5
- `PAIR_ROUNDS`, `BUILD_ROUNDS`, `TONE_SETS`: các vòng của trò 3, 5, 6
- `PHRASES`: lời thoại của Trâu Con

---

Copyrighted by CVCEC Trường Tiếng Việt Của Em 2026

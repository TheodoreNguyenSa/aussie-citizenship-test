# Luyện Thi Quốc Tịch Úc v1.1.0 — Android TV

App luyện thi quốc tịch Úc cho TV, theo đúng sách chính thức
*Australian Citizenship: Our Common Bond* (Department of Home Affairs).
Ngân hàng **1.200 câu hỏi tiếng Anh** (đúng 300 câu cho mỗi phần thi được
của sách), mỗi câu 4 lựa chọn, 1 đáp án đúng (vị trí đáp án đúng chia
đều 75/75/75/75 cho A/B/C/D trong từng chủ đề), mỗi câu có **giải thích
1–2 câu tiếng Anh đơn giản**. Giao diện song ngữ như bản duyệt: nhãn
tiếng Việt, câu hỏi + đáp án + tên chủ đề tiếng Anh (thi thật chỉ có
tiếng Anh). Chạy offline hoàn toàn.

> App luyện tập, **không phải đề thi chính thức** và không liên kết với
> Chính phủ Úc. Toàn bộ nội dung 1.200 câu xem tại `CONTENT.md`.

## 4 chủ đề (đúng tên trong sách)

1. Australia and its people
2. Australia's democratic beliefs, rights and liberties
3. Government and the law in Australia
4. Australian values

## 3 chế độ

- **LUYỆN THEO CHỦ ĐỀ** — chọn 1 trong 4 chủ đề hoặc "Tất cả — trộn";
  mỗi lượt 10 câu ngẫu nhiên; trả lời xong hiện ngay đúng (xanh lá) /
  sai (đỏ) + ô giải thích, OK sang câu tiếp; hết lượt hiện tổng kết x/10
  + Luyện tiếp / Về trang chủ.
- **THI THỬ** — đúng luật thi thật: 20 câu = 5 câu Australian values +
  5 câu mỗi chủ đề còn lại, trộn thứ tự; đếm ngược **45:00**, hết giờ tự
  nộp (câu chưa trả lời tính sai); không hiện đúng/sai khi làm; BACK
  quay lại câu trước sửa đáp án; trả lời câu 20 xong thì nộp.
- **GIÁ TRỊ ÚC** — luyện riêng chủ đề Australian values (10 câu/lượt,
  giải thích ngay), có banner nhắc: thi thật phải đúng hết 5/5 câu này.

## Luật đạt (giống thi thật)

**ĐẠT** khi đúng **ít nhất 15/20** câu **VÀ** đúng **hết 5/5** câu
Australian values. Màn kết quả: PASS — ĐẠT! / NOT YET — CHƯA ĐẠT, thẻ
Score x/20, thẻ AUSTRALIAN VALUES x/5, thanh điểm từng chủ đề (/5), 3
nút **Thi lại / Xem lại đáp án / Lưu kết quả**. "Xem lại đáp án" liệt kê
các câu SAI (câu hỏi, đáp án đã chọn — đỏ, đáp án đúng — xanh lá, giải
thích; đúng hết thì hiện lời chúc mừng). "Lưu kết quả" ghi vào máy để
màn bắt đầu hiện "Kết quả thi thử gần nhất: …".

## Cài đặt

- **GitHub:** https://github.com/TheodoreNguyenSa/aussie-citizenship-test
  (app tự kiểm tra bản mới tại đây)
- **Downloader:** 3727860
- Hoặc chép file APK qua USB / Send Files to TV rồi cài.

## Điều khiển (remote TV)

- Màn bắt đầu: 3 thẻ chế độ (DPAD trái/phải, OK vào), pill Music và pill
  "Buy me a coffee" ở góc phải trên (DPAD lên để tới). BACK thoát app.
- Màn chọn chủ đề: DPAD lên/xuống chọn 1 trong 4 chủ đề hoặc "Tất cả —
  trộn", OK bắt đầu, BACK quay lại.
- Màn câu hỏi: DPAD lên/xuống chọn đáp án A–D, OK trả lời. Luyện tập:
  OK lần 1 xem đúng/sai + giải thích, OK lần 2 sang câu sau. Thi thử:
  OK sang câu sau, BACK quay lại câu trước sửa đáp án.
- Màn tổng kết lượt luyện: DPAD trái/phải chọn "Luyện tiếp" / "Về trang
  chủ", OK xác nhận.
- Màn kết quả thi thử: DPAD trái/phải đổi nút (Thi lại / Xem lại đáp
  án / Lưu kết quả), OK xác nhận, BACK về trang chủ.
- Màn xem lại đáp án: DPAD lên/xuống cuộn, BACK quay lại màn kết quả.
- Phím MUTE (phím 91): bật/tắt nhạc nền.

## Tính năng chung

- Nền ảnh Úc theo từng màn: Uluru + kangaroo (bắt đầu), Sydney Opera
  House (câu hỏi), koala + kookaburra (kết quả) + lớp phủ navy đậm dần
  xuống dưới như mockup đã duyệt; tông xanh lá – vàng Úc.
- Nhạc nền + MUTE (watchdog 2 giây, tự im lặng khi app ở nền — cùng
  pattern với MBTI / School Quiz).
- Nút "Buy me a coffee" mở bảng QR (quét bằng điện thoại), OK mở trình
  duyệt.
- Auto-update: kiểm tra GitHub releases/latest tối đa 1 lần/ngày, có
  bản mới thì hỏi trước khi tải.
- Lưu bằng SharedPreferences: trạng thái tắt nhạc + kết quả thi thử
  gần nhất.

## Ghi chú nội dung

- Câu hỏi viết bám các fact ổn định trong sách; **không** hỏi tên người
  đang giữ chức vụ hiện tại, **không** hỏi số dân chính xác (khi cần thì
  dùng "approximately" với số tròn theo sách). Cùng một fact tối đa 2
  câu với góc hỏi khác hẳn nhau; không trùng text câu hỏi trong toàn
  ngân hàng (đã kiểm tra bằng JVM test: 31.336 lượt kiểm tra, 0 lỗi).

Web luyện tiếng Nhật do mình làm để hỗ trợ bản thân trong quá trình học tiếng Nhật.

Có 3 chế độ:
|-----------------|-------------------------------------------------------------------------|
|   Chế độ        |                        Nội dung                                         |
|-----------------|-------------------------------------------------------------------------|
|   Hiragana      | Bảng cơ bản, đục âm/bán đục âm, âm ghép, từ vựng ví dụ                  |
|   Katakana      | Bảng cơ bản, đục âm/bán đục âm, âm ghép, từ vựng ví dụ (từ mượn)        |
|   Thể て        | Nhìn động từ thể ます, gõ romaji của thể て, nộp bài để xem điểm         |
|-----------------|-------------------------------------------------------------------------|

## Cấu trúc 
```
nihongo.html         -Logic web 
nihongo.css          -Giao diện web
nihongo.js           -Chứa dữ liệu
```

## Cách chạy

1. Đặt 3 file vào cùng một thư mục.
2. Mở `index.html` bằng trình duyệt.

## Tính năng

**Hiragana / Katakana** là object gồm 4 nhóm `gojuon`, `dakuten`, `yoon`, `vidu`. Mỗi mục là một mảng:
```
["し", ["shi", "si"]]                 // chữ, các cách gõ đúng
["あさ", "asa", "buổi sáng"]          // từ vựng: thêm nghĩa ở vị trí thứ 3
```

**Thể て** là mảng `て`, mỗi mục gồm 4 phần tử:
```
["おきます", "thức dậy", "おきて", "okite"]

```
Khi chấm thể て,  nguyên âm đôi `ou`/`uu`/`ii`/`ee`/`aa` tính như nguyên âm đơn.
Ví dụ: `benkyoushite` và `benkyoshite` đều được chấp nhận.

## Font:
`--font-ui` cho chữ giao diện (Be Vietnam Pro),
`--font-kana` cho chữ Nhật (Shippori Mincho).


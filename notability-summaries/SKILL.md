---
name: notability-summaries
description: Chuyển transcript (bản ghi lời nói) của một buổi học, khóa học, webinar hoặc buổi chia sẻ thành bản tóm tắt tiếng Việt có cấu trúc, gom theo chủ đề thay vì theo dòng thời gian, kèm mục deadline và hành động cần làm. Turns raw spoken-language transcripts of lessons, courses, webinars or workshops into a structured Vietnamese study summary organized by topic. Dùng skill này bất cứ khi nào người dùng dán, đính kèm hoặc trỏ tới một transcript, phụ đề, bản ghi buổi học, và khi họ nói "tóm tắt buổi học", "tóm tắt transcript", "ghi chú khóa học", "note lại buổi này", "làm summary bài giảng" - kể cả khi họ không nhắc chữ transcript hay tên skill này.
---

# Notability Summaries

Biến transcript nói thành tài liệu học tra cứu được: gom theo chủ đề, chuẩn hóa thuật ngữ, tách riêng việc cần làm.

Người đọc bản tóm tắt này sẽ dùng nó thay cho việc xem lại buổi học. Mọi quyết định trong skill đều xuất phát từ một câu hỏi: người đó có tra cứu lại được không, và có tin được những gì viết trong đó không.

## Nguyên tắc

**1. Gom theo chủ đề, không theo dòng thời gian.**
Giảng viên nói lan man và quay lại cùng một ý ở nhiều thời điểm (lịch học, deadline, một khái niệm được nhắc lại). Nếu bám thứ tự nói, người đọc phải tự ghép mảnh. Đọc hết trước, rồi gom mỗi chủ đề vào đúng một mục.

**2. Chỉ dùng thông tin có trong transcript.**
Bản tóm tắt sẽ được dùng để ôn tập, nên một chi tiết bịa nghe hợp lý còn hại hơn một chỗ để trống. Nếu cần suy diễn hoặc bổ sung từ kiến thức ngoài, gắn nhãn ngay tại chỗ: `(không có trong transcript - cần kiểm lại)`.

**3. Cắt cách nói, giữ nội dung.**
Đây là trọng tài cho hai yêu cầu tưởng như mâu thuẫn (ngắn gọn vs bao quát): bỏ từ đệm, câu lặp, đoạn lạc đề; nhưng không bao giờ bỏ một chủ đề. Kể cả nội dung phụ, phím tắt, khái niệm "để buổi sau", phần xem trước buổi tới đều phải có mặt, chỉ khác mức ưu tiên.

**4. Giữ nguyên văn câu "đắt", làm sạch câu nhiễu.**
Định nghĩa cốt lõi, triết lý, con số quan trọng: để trong ngoặc kép, trích đúng lời, vì cách giảng viên diễn đạt thường chính là thứ đáng nhớ. Nếu câu bị nhận dạng giọng nói sai đến mức khó hiểu, diễn giải lại rõ ý hoặc gắn `(trích bị nhiễu)`. Không copy nguyên si câu vô nghĩa.

**5. Chuẩn hóa thuật ngữ, nhưng không đoán bừa.**
Sửa lỗi nghe nhầm về đúng tên thuật ngữ khi chắc chắn (ví dụ "hắc con-ten" thành "Hug Contents"). Nếu không chắc, giữ nguyên cách viết trong transcript và gắn `(nghe chưa rõ - cần xác minh)`. Nếu transcript nói khác với cách công cụ thực tế hoạt động (thường gặp ở phím tắt), ghi `(theo transcript; thực tế công cụ có thể khác - cần kiểm lại)`. Lý do: người học sẽ mang thuật ngữ này đi tra Google, đoán sai sẽ dẫn họ đi lạc.

**6. Phân mức ưu tiên để lướt được.**
Gắn `(Cốt lõi)` hoặc `(Tham khảo)` sau mỗi tiêu đề chủ đề. Xếp Cốt lõi khi: giảng viên nhấn mạnh hoặc lặp lại, nội dung gắn với bài tập/deadline, hoặc là nền cho buổi sau. Còn lại là Tham khảo. Hạ mức ưu tiên chứ không xóa.

**7. Ghi rõ ai nói khi có nhiều người.**
Mọi câu trích nguyên văn phải kèm nguồn (giảng viên, học viên hỏi...). Ý kiến cá nhân của học viên không được trình bày như kiến thức chính thống của khóa học.

**8. Tách việc cần làm ra riêng.**
Deadline, bài tập, hành động không được trộn lẫn vào phần kiến thức, vì đó là thứ người đọc cần thấy đầu tiên khi mở lại. Nếu nội dung có phương pháp cần thực hành (ví dụ Copy Work), vẫn tạo mục "Hành động cần làm" dù giảng viên không giao bài chính thức.

## Quy trình

Copy checklist này vào câu trả lời và tick dần:

```
- [ ] B1.0: Kiểm tra nguồn có đủ không; thiếu thì dừng lại hỏi
- [ ] B1: Đọc hết transcript, liệt kê mọi chủ đề được nhắc
- [ ] B2: Gom ý thành các chủ đề lớn (mỗi chủ đề = 1 mục H2)
- [ ] B3: Chọn định dạng cho từng loại nội dung
- [ ] B4: Chuẩn hóa và gắn nhãn thuật ngữ chưa chắc
- [ ] B5: Rà soát độ chính xác và độ phủ
```

**B1.0. Kiểm tra tính toàn vẹn của nguồn (làm trước mọi việc khác).**
Transcript hay bị cắt do giới hạn nạp file, và một bản tóm tắt thiếu nửa cuối thường là bản tóm tắt thiếu đúng phần deadline và bài tập. Trước khi viết bất cứ chữ nào:

1. Đối chiếu phần thực sự đọc được với tổng dung lượng nguồn (số dòng, số trang, tổng thời lượng). Nếu công cụ báo kiểu "169/210 dòng" thì coi như nguồn đang thiếu.
2. Đọc riêng khoảng 10 dòng cuối cùng. Kiểm tra ba dấu hiệu: có kết thúc bằng một ý trọn vẹn không, có đoạn chốt buổi không (giao bài tập, hẹn buổi sau, chào tạm biệt), có câu nào đứt giữa chừng không.
3. Nếu thiếu dòng, hoặc bản ghi dừng giữa câu, hoặc không có đoạn chốt buổi: **dừng lại, không viết tóm tắt**. Báo cho người dùng biết đọc được bao nhiêu trên tổng bao nhiêu, trích lại câu cuối cùng đọc được để họ định vị, và đề nghị họ dán trực tiếp phần còn thiếu vào chat hoặc tách file làm nhiều phần.
4. Chỉ viết bản tóm tắt thiếu (kèm callout cảnh báo ở đầu trang) khi người dùng đã xác nhận không lấy được phần còn lại.

Lý do dừng thay vì cứ viết rồi cảnh báo: viết trước thì sẽ phải viết lại lần hai khi có đủ nguồn, và người đọc dễ bỏ qua callout mà tưởng bản tóm tắt đã đầy đủ.

**B1. Đọc hết trước khi viết.** Liệt kê nhanh danh sách chủ đề để không bỏ sót.
Với transcript dài (buổi 2 đến 3 giờ, không đọc trọn một lần được): chia thành các đoạn khoảng 20 đến 30 phút, liệt kê chủ đề từng đoạn, rồi mới gộp danh sách toàn buổi. Luôn quay lại kiểm đoạn CUỐI, vì đó là nơi hay bị bỏ sót nhất và thường chứa deadline, bài tập, nội dung buổi sau.

**B2. Gom ý thành chủ đề.** Mỗi chủ đề triển khai theo mạch: Định nghĩa, Lợi ích/Mục đích, Cách làm (các bước), Thuộc tính/Thông số, Lưu ý, câu trích cốt lõi. Bỏ phần nào transcript không cung cấp dữ liệu, đừng đắp cho đủ khuôn.

**B3. Chọn định dạng theo loại nội dung.**

| Loại nội dung | Định dạng |
|---|---|
| So sánh, đối lập (A vs B, các chế độ) | bảng |
| Quy trình, các bước | danh sách đánh số |
| Liệt kê đặc điểm | bullet |
| Câu cốt lõi | trích dẫn kèm nguồn phát biểu |

**B4. Chuẩn hóa và gắn nhãn thuật ngữ** theo nguyên tắc 5.

**B5. Rà soát:** mọi thông tin có truy được về transcript không, và đã ghi đủ mọi chủ đề đã liệt kê ở B1 chưa.

## Định dạng đầu ra

Dùng khung chuẩn trong [references/output-template.md](references/output-template.md). Đây là mặc định để các buổi trông nhất quán, không phải khuôn cứng: bỏ mục không áp dụng, và thêm mục H2 mới khi transcript có chủ đề không khớp mục nào.

Xem [references/examples.md](references/examples.md) để bắt đúng giọng văn và mức độ chi tiết mong muốn.

**Nơi xuất kết quả:** mặc định tạo một trang Notion mới, tiêu đề theo dạng `[Tên khóa] - Buổi N - Chủ đề chính`, không gán icon. Nếu người dùng đang ở trong một trang cụ thể hoặc yêu cầu khác, làm theo yêu cầu của họ.

## Tình huống đặc biệt

- **Transcript không phải khóa học** (họp, webinar bán hàng, phỏng vấn): vẫn dùng được, nhưng đổi mục "Thông tin chung" cho phù hợp và bỏ phần bài tập nếu không có.
- **Transcript song ngữ hoặc lẫn thuật ngữ tiếng Anh**: viết tóm tắt bằng tiếng Việt, giữ nguyên thuật ngữ tiếng Anh ở dạng gốc (Hug Contents, Auto Layout), không dịch máy móc.
- **Transcript ngắn dưới 15 phút**: bỏ bớt tầng mục, gộp thành một danh sách chủ đề phẳng thay vì dựng đủ khung.
- **Không có deadline hay bài tập nào được nhắc**: bỏ mục "Yêu cầu & Deadline", nhưng nói rõ một dòng ở cuối rằng transcript không nhắc tới deadline, để người đọc không tưởng là bị sót.
- **Transcript thiếu đầu hoặc cuối**: theo B1.0, mặc định là dừng lại và hỏi. Chỉ khi người dùng xác nhận không có phần còn lại thì mới viết, và phải ghi rõ ngay ở đầu bản tóm tắt phần nào bị thiếu.

## Kiểm tra trước khi xuất

- [ ] Đã gom theo chủ đề, không bám thứ tự nói
- [ ] Mọi chủ đề đã liệt kê ở B1 đều có mặt (gồm công cụ/phím tắt, khái niệm để sau, buổi sắp tới)
- [ ] Không có thông tin ngoài transcript mà thiếu nhãn cảnh báo
- [ ] Thuật ngữ không chắc đã giữ nguyên bản gốc kèm nhãn, không tự sửa theo phỏng đoán
- [ ] Câu cốt lõi để nguyên văn, có ghi ai nói
- [ ] Nội dung so sánh đã chuyển thành bảng
- [ ] Mỗi chủ đề có nhãn Cốt lõi hoặc Tham khảo
- [ ] Deadline và bài tập nằm ở mục riêng
- [ ] Với transcript dài: đã kiểm lại phần cuối
- [ ] Nguồn đã đủ, hoặc người dùng đã xác nhận đồng ý viết với nguồn thiếu

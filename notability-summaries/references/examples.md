# Ví dụ mẫu

Hai ví dụ dưới đây minh họa định dạng và mức độ chi tiết, không giới hạn skill vào một lĩnh vực cụ thể.

## Nội dung
- Ví dụ 1: chuẩn hóa thuật ngữ nghe nhầm
- Ví dụ 2: chủ đề không có đủ dữ liệu cho mọi trường

## Ví dụ 1: chuẩn hóa thuật ngữ nghe nhầm

**Trích transcript gốc:**

> "Ờ thì cái này nè, cái hắc con-ten ấy, nó cái này là nó tự co lại theo nội dung bên trong á, tức là mình không cần set kích thước cứng, nó tự ôm lấy chữ luôn. Cái này quan trọng lắm nha các bạn, làm component mà không dùng cái này là hỏng."

**Kết quả đúng chuẩn:**

```markdown
## Hug Contents (Cốt lõi)
**Định nghĩa:** Chế độ resize cho khung tự co giãn ôm sát nội dung bên trong, thay vì đặt kích thước cố định.
**Lợi ích / Mục đích:** Không phải chỉnh tay kích thước khi nội dung thay đổi; bắt buộc khi dựng component tái sử dụng.
**Lưu ý:** Giảng viên nhấn mạnh đây là yêu cầu bắt buộc khi làm component.
> "Làm component mà không dùng cái này là hỏng." - giảng viên
```

**Điểm cần chú ý:** thuật ngữ nghe nhầm "hắc con-ten" đã chuẩn hóa thành "Hug Contents"; từ đệm và câu lan man đã bỏ; câu cốt lõi giữ nguyên văn kèm nguồn phát biểu; chủ đề có nhãn ưu tiên. Không có bước làm nào trong transcript nên không bịa ra mục "Cách làm".

## Ví dụ 2: chủ đề không có đủ dữ liệu cho mọi trường

**Trích transcript gốc:**

> "Còn cái phần khách hàng họ thuê sản phẩm để làm gì á, cái đó gọi là gi-ti-bi-đi gì đó, thầy nhớ không rõ tên, buổi sau thầy nói kỹ. Đại khái là đừng hỏi khách muốn gì, hỏi họ đang cố hoàn thành việc gì."

**Kết quả đúng chuẩn:**

```markdown
## "gi-ti-bi-đi" (nghe chưa rõ - cần xác minh) (Tham khảo)
**Định nghĩa:** Cách nhìn khách hàng theo công việc họ đang cố hoàn thành, thay vì theo mong muốn họ phát biểu ra.
**Lưu ý:** Giảng viên nói sẽ trình bày kỹ ở buổi sau, và tự nhận không nhớ rõ tên gọi.
> "Đừng hỏi khách muốn gì, hỏi họ đang cố hoàn thành việc gì." - giảng viên
```

và ghi thêm ở mục khái niệm để sau:

```markdown
## Khái niệm nâng cao / giới thiệu sau
- "gi-ti-bi-đi" (nghe chưa rõ - cần xác minh) - giảng viên hẹn nói kỹ ở buổi sau
```

**Điểm cần chú ý:** dù có thể đoán đây là JTBD, transcript không nói rõ nên giữ nguyên cách phát âm kèm nhãn cần xác minh thay vì tự sửa. Các trường Lợi ích, Cách làm, Thuộc tính bị bỏ vì transcript không cung cấp, không đắp cho đủ khuôn.

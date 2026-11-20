# 🌙 LSD Helper – Lịch sử Đảng Cộng sản Việt Nam

**LSD Helper** là ứng dụng web hỗ trợ ôn tập trắc nghiệm môn *Lịch sử Đảng Cộng sản Việt Nam*. Ứng dụng được thiết kế với giao diện Night Mode hiện đại, thân thiện và dễ sử dụng, giúp người học củng cố kiến thức, kiểm tra mức độ ghi nhớ và chuẩn bị tốt hơn cho các kỳ thi.

Ứng dụng cung cấp các chế độ luyện tập theo từng chương và chế độ trộn câu hỏi từ toàn bộ nội dung học tập, đi kèm phần giải thích đáp án nhằm giúp người học hiểu rõ kiến thức thay vì chỉ ghi nhớ đáp án.

## ✨ Tính năng nổi bật

### 📚 1. Bốn chế độ luyện tập

Người dùng có thể lựa chọn một trong bốn chế độ sau:

| Chế độ | Nội dung |
|---|---|
| **Chương 1 (1930 – 1945)** | Đảng Cộng sản Việt Nam ra đời và lãnh đạo đấu tranh giành chính quyền. |
| **Chương 2 (1945 – 1975)** | Đảng lãnh đạo cuộc kháng chiến chống thực dân Pháp và đế quốc Mỹ. |
| **Chương 3 (1975 – nay)** | Đảng lãnh đạo cả nước quá độ lên chủ nghĩa xã hội và thực hiện công cuộc Đổi mới. |
| **Mix Mode** | Trộn ngẫu nhiên câu hỏi từ cả ba chương để ôn tập tổng hợp. |

### 🎯 2. Tùy chỉnh số lượng câu hỏi

Đối với chế độ Mix Mode, người dùng có thể lựa chọn số lượng câu hỏi cho mỗi lượt luyện tập:

- 20 câu.
- 40 câu.
- 60 câu.
- Toàn bộ ngân hàng câu hỏi.

Các câu hỏi được lựa chọn ngẫu nhiên, giúp đa dạng hóa nội dung trong mỗi lần ôn tập.

### 💡 3. Giải thích đáp án

Sau khi trả lời câu hỏi, người dùng có thể xem đáp án chính xác và phần giải thích đi kèm.

Nội dung giải thích được xây dựng dựa trên kiến thức môn học, giúp người học hiểu rõ bản chất vấn đề và ghi nhớ các mốc thời gian, sự kiện lịch sử quan trọng.

### 🔄 4. Tự động lưu câu trả lời sai

- Tự động ghi nhận những câu hỏi người dùng trả lời sai.
- Lưu dữ liệu bằng `localStorage` ngay trên trình duyệt.
- Hỗ trợ ôn tập lại các câu hỏi đã làm sai.
- Dữ liệu vẫn được giữ lại khi tải lại trang trên cùng trình duyệt, trừ khi bộ nhớ trình duyệt bị xóa.

### 🌙 5. Giao diện Night Mode

- Giao diện tối mặc định, phù hợp với việc học tập vào buổi tối.
- Thiết kế trực quan, dễ quan sát.
- Bố cục rõ ràng, thao tác đơn giản.
- Tối ưu trải nghiệm trên các kích thước màn hình khác nhau.

### 📂 6. Hỗ trợ mở rộng ngân hàng câu hỏi

Ứng dụng hỗ trợ nạp dữ liệu câu hỏi từ file `questions.json` đặt cùng thư mục với `index.html`.

Người phát triển có thể bổ sung hoặc cập nhật ngân hàng câu hỏi thông qua file dữ liệu mà không cần chỉnh sửa trực tiếp nội dung giao diện.

## 🚀 Hướng dẫn sử dụng

### Cách 1: Chạy trực tiếp trên máy tính

1. Tải mã nguồn của dự án về máy bằng cách chọn **Code → Download ZIP** trên GitHub.
2. Giải nén thư mục dự án.
3. Mở file `index.html` bằng trình duyệt web.
4. Chọn chương học hoặc Mix Mode để bắt đầu ôn tập.

*Lưu ý: Nếu ứng dụng sử dụng chức năng tải dữ liệu bằng `fetch()` từ file `questions.json`, hãy chạy dự án thông qua một local server thay vì mở trực tiếp file HTML.*

### Cách 2: Truy cập trực tuyến bằng GitHub Pages

Nếu dự án đã được triển khai trên GitHub Pages:

1. Truy cập đường dẫn website được cung cấp trong repository.
2. Lựa chọn chế độ luyện tập mong muốn.
3. Tiến hành trả lời câu hỏi và xem giải thích đáp án.
4. Sử dụng chức năng ôn lại câu sai để củng cố kiến thức.

## 🛠️ Công nghệ sử dụng

- **HTML5:** Xây dựng cấu trúc trang web.
- **CSS3:** Thiết kế giao diện và hiệu ứng Night Mode.
- **JavaScript:** Xử lý logic luyện tập, chấm điểm, trộn câu hỏi và tương tác người dùng.
- **JSON:** Lưu trữ và quản lý ngân hàng câu hỏi.
- **LocalStorage:** Lưu trữ các câu hỏi trả lời sai trên trình duyệt.
- **GitHub Pages:** Triển khai ứng dụng trực tuyến.

## 📦 Cấu trúc dự án

```text
LSD-Helper/
│
├── index.html          # Giao diện và chức năng ứng dụng
├── questions.json      # Ngân hàng câu hỏi (nếu tách riêng)
└── README.md           # Tài liệu giới thiệu dự án
```

## 🌐 Triển khai trên GitHub Pages

Bạn có thể triển khai ứng dụng miễn phí bằng GitHub Pages:

1. Tạo một repository mới trên GitHub.
2. Upload các file cần thiết của dự án (`index.html`, `README.md` và `questions.json` nếu có).
3. Truy cập **Settings → Pages**.
4. Tại mục **Build and deployment**, chọn:
   - Source: `Deploy from a branch`.
   - Branch: `main`.
   - Folder: `/ (root)`.
5. Nhấn **Save** và chờ GitHub hoàn tất quá trình triển khai.
6. Truy cập đường dẫn website được GitHub Pages cung cấp.

## 📝 Lưu ý

- Ứng dụng hoạt động trực tiếp trên trình duyệt, không yêu cầu cài đặt cơ sở dữ liệu hay backend.
- Các câu hỏi và dữ liệu học tập được lưu trữ theo cấu hình của ứng dụng.
- Dữ liệu câu trả lời sai sử dụng LocalStorage nên chỉ tồn tại trên trình duyệt và thiết bị tương ứng.
- Để đảm bảo ứng dụng hoạt động chính xác, hãy giữ nguyên cấu trúc file và định dạng dữ liệu JSON theo yêu cầu của mã nguồn.

---

<p align="center">
  <b>🌙 LSD Helper</b><br>
  <i>Học tập hiệu quả – Ghi nhớ kiến thức – Tự tin trước kỳ thi.</i><br><br>
  Made with ❤️ by <b>icyr4zo</b>
</p>

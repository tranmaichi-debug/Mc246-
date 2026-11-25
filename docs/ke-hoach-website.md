# Kế hoạch website môi giới cho thuê — Vinhomes Central Park

Tài liệu bàn giao để tiếp tục công việc trên máy tính. Cập nhật: 25/11/2026.

## 1. Bối cảnh

- Công ty môi giới cho thuê và mua bán bất động sản, đã có thương hiệu từ mảng **thuê ngắn ngày** (bộ thương hiệu lưu trên máy Mac, chưa đưa vào kho này).
- Hướng mới: **thuê dài hạn** tại Vinhomes Central Park (Bình Thạnh, TP.HCM), nhắm khách quốc tế, đặc biệt **Trung Quốc và Hàn Quốc**.
- Song song: thu hút **chủ nhà ký gửi căn**.
- Công cụ AI đang dùng: NotebookLM (kho kiến thức, nghiên cứu), Gemini (tìm kiếm, ảnh, video, hệ Google), Claude (chiến lược, viết nội dung, dựng website).

## 2. Trình tự đã thống nhất

1. Sơ đồ website (mục 3) — chờ duyệt.
2. Giao bảng nghiên cứu (mục 4) cho NotebookLM, mỗi trang một ghi chú.
3. Ghép thông tin nội bộ (mục 6).
4. Viết nội dung và dựng website trong kho này.

## 3. Sơ đồ website

Mỗi trang có bốn bản ngôn ngữ dưới `/vi`, `/en`, `/zh`, `/ko`, trừ nhánh Ký gửi nhà chỉ có tiếng Việt và tiếng Anh.

```
Trang chủ
│
├── Thuê dài hạn
│   ├── Danh sách căn (lọc: số phòng, giá, tòa, nội thất)
│   ├── Chi tiết căn (có nhận xét thật của nhân viên, gồm cả điểm trừ)
│   └── Bảng giá theo số phòng
│
├── Các phân khu
│   ├── The Central
│   ├── The Park
│   ├── The Landmark / Landmark Plus
│   └── Landmark 81
│
├── Hướng dẫn cho người nước ngoài
│   ├── Quy trình và giấy tờ thuê nhà
│   ├── Tạm trú và thẻ tạm trú
│   ├── Chi phí: cọc, thuế, phí quản lý, điện nước
│   └── Sống tại Vinhomes Central Park (bản riêng cho người Hàn, người Trung)
│
├── Dành cho doanh nghiệp
│
├── Ký gửi nhà (cho chủ nhà)
│   ├── Vì sao ký gửi với chúng tôi
│   ├── Dịch vụ và phí (môi giới một lần / quản lý trọn gói)
│   ├── Định giá thuê căn của bạn (công cụ + form)
│   ├── Quy trình từ ký gửi đến bàn giao
│   ├── Báo cáo thị trường hằng tháng
│   ├── Câu hỏi thường gặp của chủ nhà
│   └── Form ký gửi
│
├── Thuê ngắn ngày
├── Mua bán
├── Tin tức và kiến thức
├── Giới thiệu
└── Liên hệ / Đặt lịch xem nhà
```

- Nút gọi, Zalo, WeChat, KakaoTalk và nút đặt lịch có ở mọi trang, đổi theo ngôn ngữ đang xem.
- Nút "Ký gửi nhà" nổi bật trên thanh menu.
- Website phải tải được từ Trung Quốc đại lục: không phụ thuộc phông chữ, bản đồ hay form của Google.

**Chưa quyết:** Mua bán và Thuê ngắn ngày là mục chính hay mục phụ (hiện xếp mục phụ).

## 4. Bảng kiến thức cần nghiên cứu

Dấu ⚖: cần người có chuyên môn pháp lý xác nhận.

### Nhóm 1 — Người thuê nước ngoài

| Trang | Cần tìm hiểu | Nguồn gợi ý |
|---|---|---|
| Trang chủ | Thông điệp mở đầu, con số tạo tin cậy, vị trí nút kêu gọi; cách dẫn khách vào ba lối riêng | bestvinhomes.com, vinhomeshcmc.vn, moriliving.com |
| Danh sách căn | Bộ lọc, thông tin trên thẻ căn; tìm theo thời gian đi lại | vinhomeshcmc.vn, muaban.net, suumo.jp |
| Chi tiết căn | Mục thông tin bắt buộc, thứ tự trình bày; nhận xét thật gồm cả điểm trừ | bestvinhomes.com, land420.net, goodrooms.jp |
| Bảng giá | Giá thuê theo số phòng và theo tòa, phí quản lý, phí gửi xe | canhovinhomescentralpark.com.vn, bestvinhomes.com |
| Các phân khu | Khác biệt giữa Central, Park, Landmark, Landmark 81; cách kể về cuộc sống quanh từng tòa | Tài liệu chủ đầu tư, moriliving.com |
| Quy trình và giấy tờ ⚖ | Giấy tờ người nước ngoài cần, điều khoản hợp đồng song ngữ, quy định ghi giá bằng đồng Việt Nam | Luật Nhà ở, Luật Kinh doanh bất động sản, văn bản ngoại hối |
| Tạm trú và thẻ tạm trú ⚖ | Ai phải khai báo, thời hạn, thủ tục, điều kiện cấp thẻ | Luật Xuất nhập cảnh, cổng thông tin xuất nhập cảnh |
| Chi phí ⚖ | Thuế cho thuê, mức cọc, điều kiện hoàn cọc, chấm dứt sớm | Văn bản thuế, điều khoản trên trang đối thủ |
| Sống tại Vinhomes Central Park | Trường, bệnh viện, ngân hàng, siêu thị, nhà hàng của cộng đồng Hàn và Trung; thời gian tới khu công nghiệp | Bản đồ, vinahanin.com, nhóm cộng đồng |

### Nhóm 2 — Doanh nghiệp

| Trang | Cần tìm hiểu | Nguồn gợi ý |
|---|---|---|
| Dành cho doanh nghiệp | Quy trình công ty Hàn, Trung thuê nhà cho nhân viên, hóa đơn cần có, ngân sách | vinahanin.com, kencorp.com, công ty dịch vụ định cư |

### Nhóm 3 — Chủ nhà

| Trang | Cần tìm hiểu | Nguồn gợi ý |
|---|---|---|
| Vì sao ký gửi với chúng tôi | Lo ngại của chủ nhà khi cho người nước ngoài thuê; phàn nàn về môi giới | Nhóm cư dân từng tòa, diễn đàn bất động sản |
| Dịch vụ và phí | Dịch vụ đối thủ chào cho chủ nhà; phí môi giới và phí quản lý thông lệ | apartmentvinhomes.com, công ty quản lý căn hộ |
| Định giá thuê | Yếu tố quyết định giá thuê và mức chênh của từng yếu tố | muaban.net, batdongsan.com.vn |
| Quy trình ký gửi đến bàn giao ⚖ | Các bước chuẩn, giấy tờ chủ nhà, biên bản bàn giao, nghĩa vụ khai báo tạm trú | Luật Nhà ở, Luật Cư trú |
| Báo cáo thị trường hằng tháng | Giá thuê theo tòa, thời gian trống trung bình, xu hướng khách nước ngoài | Tin đăng các sàn, báo cáo hãng tư vấn |
| Câu hỏi thường gặp của chủ nhà ⚖ | Thuế chủ nhà nộp, xử lý khi khách trả sớm hoặc làm hỏng đồ | Văn bản thuế, Bộ luật Dân sự |

### Nhóm 4 — Mục phụ và nội dung chung

| Trang | Cần tìm hiểu | Nguồn gợi ý |
|---|---|---|
| Thuê ngắn ngày ⚖ | Quy định cho thuê ngắn ngày trong chung cư tại TP.HCM, nội quy từng tòa | Văn bản thành phố, ban quản lý, moriliving.com |
| Mua bán ⚖ | Điều kiện người nước ngoài sở hữu nhà, giá bán theo số phòng | Luật Nhà ở, canhovinhomescentralpark.com.vn |
| Tin tức và kiến thức | Câu hỏi người Hàn, người Trung tìm về thuê nhà ở TP.HCM | Naver, Baidu, Xiaohongshu, expat.com |
| Giới thiệu, Liên hệ | Cách trình bày pháp lý công ty, đội ngũ, cam kết | bestvinhomes.com, kencorp.com |

Làm trước ba trang: Chi tiết căn, Chi phí, Dịch vụ và phí cho chủ nhà.

## 5. Kết quả nghiên cứu đối thủ (đọc ngày 25/11/2026)

Mỗi website chỉ đọc một trang; số liệu là của các trang đó tự nêu, chưa kiểm chứng.

| Website | Điểm mạnh | Điểm yếu | Kênh liên hệ |
|---|---|---|---|
| bestvinhomes.com | Thuê dài hạn cho người nước ngoài, bảng giá USD/VND, giấy tờ, thẻ tạm trú, điều khoản cọc, hướng dẫn cho người nước ngoài; nêu hỗ trợ Anh, Hàn, Nhật, Trung | Website chỉ có Anh và Việt; không có form; không có nút riêng cho khách Trung, Hàn | Điện thoại, Zalo |
| canhovinhomescentralpark.com.vn | Bảng giá ghi ngày rà soát, mục kiểm tra trước khi xem nhà, hỏi đáp | Chỉ tiếng Việt, trộn bán và thuê | Điện thoại, Zalo, email |
| vinhomeshcmc.vn | Giỏ hàng lớn, mỗi căn có mã, giá, diện tích | Nghiêng về thuê theo ngày, chỉ tiếng Việt | Điện thoại, Zalo |
| giathuecanhovinhomes.com | Có form đặt lịch; đủ Zalo, WeChat, WhatsApp; có bản tiếng Anh | Giá cao bất thường; đánh giá khách trông như nội dung mẫu | Đủ bốn kênh |
| apartmentvinhomes.com | Liệt kê từng căn theo tầng, giá USD; có mục ký gửi | Văn phong nhồi từ khóa | Điện thoại |
| muaban.net | 48 tin, cập nhật trong ngày | Sàn, tin lẫn lộn chất lượng | Qua sàn |
| vinahanin.com, land420.net | Viết cho người Hàn; kèm dịch vụ lập công ty, tìm nhà xưởng; môi giới miễn phí cho người thuê | Tin từ 2023 và đầu 2025, giao diện cũ | KakaoTalk, điện thoại |

Không đọc được: batdongsan.com.vn (chặn công cụ tự động), tin trên expat.com (đã gỡ), bcgroupvn.com, bcreal.net.

**Mặt bằng giá thuê dài hạn (triệu đồng/tháng):**

| Loại căn | canhovinhomescentralpark | bestvinhomes |
|---|---|---|
| 1 phòng ngủ | 16–21 | 17,5–22,5 |
| 2 phòng ngủ | 22–30 | 22,5–30 |
| 3 phòng ngủ | 30–50 | 32–45 |
| 4 phòng ngủ | 45–80 | 50–100 |

Landmark 81 cao hơn: 1 phòng ngủ khoảng 1.000 USD, 3 phòng ngủ 2.000–3.200 USD.

**Điều khoản lặp lại:** cọc 2 tháng, trả trước 1 tháng; phí quản lý tính riêng (bestvinhomes.com ghi 19.000 đồng/m²/tháng); điện, nước, internet theo thực tế.

**Khoảng trống thị trường:** chưa website nào có nội dung tiếng Trung và tiếng Hàn đầy đủ kèm nút WeChat, KakaoTalk. Kênh của khách Trung (WeChat, Xiaohongshu) chưa nghiên cứu được.

**Ý tưởng từ website Nhật:** MORI LIVING (giới thiệu cả khu đô thị, tách căn hộ dịch vụ và thuê dài hạn, trang riêng từng tòa), goodroom (nhận xét thật gồm điểm trừ), SUUMO (bộ lọc, tìm theo thời gian đi lại), Ken Corporation (môi giới phục vụ khách nước ngoài và doanh nghiệp).

## 6. Thông tin nội bộ còn thiếu

1. Bộ thương hiệu: logo, màu, phông chữ, giọng văn.
2. Nguồn căn: danh sách căn với ảnh, giá, tòa, tầng, nội thất.
3. Điều khoản: mức cọc, phí môi giới, dịch vụ đi kèm, cam kết với khách và chủ nhà.
4. Phí thu của chủ nhà; có nhận quản lý căn sau khi cho thuê hay chỉ môi giới một lần.
5. Pháp lý công ty: tên, mã số thuế, địa chỉ, chứng chỉ môi giới.
6. Liên hệ: điện thoại, Zalo, WeChat, KakaoTalk; ai trả lời bằng tiếng Trung, tiếng Hàn.
7. Tên miền đã có hay chưa.

## 7. Việc tiếp theo

- [ ] Duyệt sơ đồ website; quyết định vị trí Mua bán và Thuê ngắn ngày.
- [ ] Giao bảng mục 4 cho NotebookLM.
- [ ] Đưa bộ thương hiệu và thông tin mục 6 vào kho này (ví dụ thư mục `brand/`).
- [ ] Viết nội dung từng trang, dựng website.

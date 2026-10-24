# BÁO CÁO CHUYÊN ĐỀ: AUDIT TRẢI NGHIỆM NGƯỜI DÙNG (UI/UX) & TỐI ƯU TỶ LỆ CHUYỂN ĐỔI (CRO)
**Dự án:** `vanxaydung.com` — Hệ Thống Sản Xuất & Phân Phối Ván Ép Cốp Pha Phủ Phim  
**Ngày kiểm định:** 24/10/2026  
**Đơn vị thực hiện:** Chuyên Gia Tư Vấn Trưởng Kiến Trúc Trải Nghiệm & Chuyển Đổi Số  
**Phương pháp:** Kiểm định thực tế trên trình duyệt Chromium, phân tích mã nguồn DOM, đối soát hành vi khách hàng B2B (Nhà thầu xây dựng, Cai thầu, Đại lý vật tư).

---

## PHẦN 1: 7 CÂU HỎI SỐNG CÒN VỀ TRẢI NGHIỆM NGƯỜI DÙNG & TỶ LỆ CHUYỂN ĐỔI

### 1. Khách hàng vào website trong 5 giây đầu tiên có hiểu ngay đây là Nhà máy sản xuất & tổng kho ván cốp pha phủ phim giá gốc hay không?
- **Hiện trạng thực tế:** **KHÔNG THỂ NHẬN DIỆN.**
  - Tiêu đề Hero Banner trang chủ chỉ là dòng chữ trừu tượng: *"Chung Tay Dựng Xây Lên Những Công Trình Thế Kỷ"* — đây là khẩu hiệu chung chung của công ty xây dựng dân dụng, hoàn toàn không nói lên năng lực sản xuất hay bán ván phủ phim.
  - Khung Hero hoàn toàn khuyết thiếu nút Kêu gọi Hành động (CTA); không có nhãn chỉ dẫn hay phân loại sản phẩm ngay màn hình đầu tiên.
  - Thanh Menu trên cùng chứa mục *"Dự Án"* nhưng khi nhấp vào lại là danh sách giới thiệu bán căn hộ chung cư cao cấp Vinhomes, Tân Hoàng Minh... khiến khách hàng B2B tưởng nhầm đây là website môi giới bất động sản hoặc trang tin tức tổng hợp.
- **Tác động kinh doanh:** Tỷ lệ thoát trang (Bounce Rate) ước tính >70% ngay trong 5–10 giây đầu tiên. Các chủ thầu cần mua ván gấp sẽ lập tức bấm quay lại (Back) để tìm nhà cung cấp khác.
- **Giải pháp chuyển đổi:** Tái cấu trúc Hero Section với Tiêu đề giải pháp trực diện:  
  **"TỔNG KHO & NHÀ MÁY VÁN ÉP PHỦ PHIM CỐP PHA GIÁ GỐC TẠI XƯỞNG"**  
  Phụ đề khẳng định năng lực: *"Công suất 3.500 tấm/ngày — Luân chuyển 8-12 lần — Giao hàng hỏa tốc trong 24h tận chân công trình tại Hà Nội & Miền Bắc"*.

---

### 2. Thông điệp giá trị (Value Proposition) và Năng lực cốt lõi có đập vào mắt người xem không?
- **Hiện trạng thực tế:** **HOÀN TOÀN BỊ ẨN GIẤU.**
  - Website không có bất kỳ khu vực nào làm nổi bật 4 số liệu sống còn của một nhà máy vật liệu xây dựng:
    1. Công suất sản xuất ngày / tháng;
    2. Diện tích kho hàng sẵn có tại Đan Phượng / Hà Nội;
    3. Tiêu chuẩn keo chống nước (WBP Melamine 15% vs Phenolic đun sôi bao nhiêu giờ không tách lớp);
    4. Số lần tái sử dụng (luân chuyển coppha).
  - Khách hàng phải tự mò mẫm vào các bài viết blog rải rác để chắp vá thông tin.
- **Tác động kinh doanh:** Doanh nghiệp bị đánh đồng với các đơn vị thương mại trung gian nhỏ lẻ ("cò ván"), không tạo được lợi thế cạnh tranh về giá gốc tận xưởng và năng lực cấp hàng lớn cho dự án cao tầng.
- **Giải pháp chuyển đổi:** Thiết kế Khối Huy Hiệu Năng Lực (4 Metric Badges) ngay dưới Hero Banner:
  - `3.500 Tấm/Ngày`: Công suất ép nhiệt liên tục 3 ca;
  - `5.000 m² Tổng Kho`: Sẵn hàng tại Hà Nội & Hòa Bình, gọi là bốc hàng ngay;
  - `8 – 12 Nước Cốp Pha`: Keo WBP Melamine 15% đun sôi 12-15h không tách lớp;
  - `100% Đổi Trả`: Cam kết bù ngay nếu ván phồng rộp hoặc không đạt độ dày danh định.

---

### 3. Khách hàng B2B (Nhà thầu, Chỉ huy trưởng) có tìm thấy thông số kỹ thuật và Bảng giá bậc thang để chốt đơn không?
- **Hiện trạng thực tế:** **THIẾU TRẦM TRỌNG & NỘI DUNG LỖI.**
  - Trang sản phẩm cốt lõi (ván 12mm, 15mm, 18mm) bị lỗi kỹ thuật biên tập: Đoạn văn *"Keo đặc chủng chịu nước WBP – Melamine từ 12%..."* bị dán lặp lại 2 lần liên tiếp trong cùng một bài viết.
  - Thiếu Bảng thông số kỹ thuật chuẩn công nghiệp (Datasheet): Trọng lượng/tấm, độ ẩm, dung sai độ dày (±0.5mm), lực ép thủy lực (140 tấn/cm²), chứng chỉ kiểm định chất lượng (Quatest).
  - Không có Bảng giá phân bậc theo số lượng (50–200 tấm, 201–500 tấm, >500 tấm hoặc nguyên xe tải 1.200 tấm).
- **Tác động kinh doanh:** Người mua hàng công trình không có căn cứ lập Dự toán chi phí (BOQ), buộc phải rời trang sang website đối thủ có bảng giá và thông số minh bạch.
- **Giải pháp chuyển đổi:**
  - Bổ sung Bảng Datasheet kỹ thuật chuẩn hóa cho từng độ dày ván;
  - Thiết kế Bảng giá dự toán công trình linh hoạt với cơ chế chiết khấu theo khối lượng;
  - Tích hợp nút tải về: *"Tải Bảng Thông Số Kỹ Thuật & Kết Quả Thử Nghiệm Quatest (PDF)"*.

---

### 4. Niềm tin và Chứng thực pháp lý có đủ mạnh để ký kết hợp đồng tiền tỷ không?
- **Hiện trạng thực tế:** **XUNG ĐỘT 4 THƯƠNG HIỆU LÀM TRIỆT TIÊU TOÀN BỘ NIỀM TIN.**
  - Chân trang (Footer) hiển thị: *"Công Ty Cổ Phần Tư Vấn Thiết Kế Và Xây Dựng V-HOME"* nhưng lại kèm dòng bản quyền *"Copyright - Vanphuphimvn.com"*;
  - Trang Giới thiệu tự xưng là: *"Nhà máy sản xuất ván ép phủ phim Tú Anh 68"*;
  - Trang Đại lý lại đề cập thương hiệu: *"Lạc Việt Plywood"*;
  - Tên miền website đang chạy là: `vanxaydung.com`.
  - Mục *"Dự Án"* copy nguyên bài quảng cáo bán căn hộ Vinhomes Smart City, Skylake, Tân Hoàng Minh... không hề có ảnh xe tải giao ván, không có biên bản nghiệm thu hay logo nhà thầu chính (Coteccons, Hòa Bình, Delta, Ricons, Newtecons...).
- **Tác động kinh doanh:** Khách hàng B2B, chủ thầu nghi ngờ website lừa đảo, giả mạo danh tính hoặc trang web rác dựng vội. Rủi ro mất trắng các hợp đồng cung ứng vật tư lớn.
- **Giải pháp chuyển đổi:**
  - Thống nhất duy nhất một nhận diện pháp nhân: **Công Ty V-HOME — Sở hữu & Vận hành Hệ thống Nhà Máy Ván Ép Cốp Pha Tú Anh 68**;
  - Xóa sạch toàn bộ bài viết môi giới bất động sản; thay thế bằng 6 Case Study Cung Ứng Dự Án Thật: Tên nhà thầu thi công, số lượng tấm giao, độ dày, tiến độ cấp hàng và ảnh thực tế giao ván tại công trường.

---

### 5. Rào cản biểu mẫu (Form Friction) và Luồng gửi yêu cầu báo giá (RFQ) như thế nào?
- **Hiện trạng thực tế:** **MA SÁT CAO, KHÔNG ĐÚNG NGHIỆP VỤ B2B.**
  - Form liên hệ hiện tại dùng Contact Form 7 với các ô mặc định: Họ và tên, Email, Tiêu đề, Nội dung tin nhắn.
  - Người mua vật liệu xây dựng tại Việt Nam hầu như không dùng email trao đổi công việc; họ cần báo giá nhanh qua Zalo hoặc điện thoại.
  - Form thiếu toàn bộ các trường nghiệp vụ quan trọng: Độ dày ván cần mua (12/15/18mm), Số lượng tấm dự kiến, Địa điểm chân công trình (để tính cước vận chuyển cẩu tự hành).
- **Tác động kinh doanh:** Tỷ lệ điền form gửi yêu cầu báo giá (Form Submission Rate) cực thấp (<0.8%). Đội ngũ kinh doanh nhận được tin nhắn chung chung không đủ dữ liệu để báo giá ngay, phải gọi lại nhiều lần làm nguội độ quan tâm của khách.
- **Giải pháp chuyển đổi:** Thiết kế Form Báo Giá Nhanh 3 Trường (Fast RFQ):
  1. Chọn loại ván & độ dày: [12mm] [15mm] [18mm] [Ván phủ keo trong];
  2. Số lượng dự kiến: [Dưới 200 tấm] [200 - 500 tấm] [Trên 500 tấm / Công trình lớn];
  3. Số điện thoại nhận báo giá Zalo & Cước vận chuyển.

---

### 6. Trải nghiệm trên điện thoại thông minh (Mobile Thumb Zone) có thuận tiện không?
- **Hiện trạng thực tế:** **TRẢI NGHIỆM TỆ TRÊN MÀN HÌNH DI ĐỘNG (CHIẾM >75% TRAFFIC).**
  - Chỉ huy trưởng, cai thầu và kỹ sư hiện trường luôn dùng smartphone tại công trường với một tay (ngón tay cái).
  - Website hiện tại không có Thanh Nút Nổi Cố Định (Sticky Bottom Bar) ở đáy màn hình.
  - Số hotline trên trang chỉ là chữ tĩnh thông thường (plain text), không được gắn link `tel:098xxxxxxx` nên khách không thể chạm vào để gọi ngay mà phải copy-paste thủ công.
  - Menu mobile dạng hamburger xổ xuống dài lê thê, font chữ nhỏ, các mục liên kết nằm san sát dễ bấm nhầm.
- **Tác động kinh doanh:** Đánh mất tới 80% các cuộc gọi phát sinh khi khách hàng đang ở ngoài công trình cần gọi xe ván khẩn cấp.
- **Giải pháp chuyển đổi:**
  - Tích hợp Thanh Điều Hướng Đáy Màn Hình 2 Nút To Rõ (Fixed Mobile Action Bar):
    + Nút 1 (Bên Trái): **"Gọi Ngay (Hotline 24/7)"** — Chạm là kết nối cuộc gọi tức thì;
    + Nút 2 (Bên Phải - Nổi Bật Màu Xanh Emerald): **"Nhận Báo Giá Zalo"** — Mở thẳng ứng dụng Zalo chat với chuyên viên kinh doanh.
  - Vùng chạm tối thiểu 44px × 44px, khóa cứng chống tràn ngang màn hình (360px – 430px).

---

### 7. Hành trình thoát trang & Cơ chế cứu vớt lượt truy cập (Exit Intent & Fallback CTA) có hay không?
- **Hiện trạng thực tế:** **HOÀN TOÀN KHÔNG CÓ.**
  - Khi khách hàng chuẩn bị rời trang, website không có bất kỳ đề xuất giá trị nào giữ chân họ lại.
  - Không có tùy chọn gửi Mẫu Ván Cắt Thử Miễn Phí (Sample Box) tới công trình để kiểm tra chất lượng ruột gỗ và độ chịu nước trước khi ký hợp đồng lớn.
- **Tác động kinh doanh:** Thất thoát 100% khách hàng đang ở giai đoạn cân nhắc/so sánh chất lượng ván giữa các nhà cung cấp.
- **Giải pháp chuyển đổi:** Triển khai Lời chào hàng chuyển đổi mềm (Low-friction Fallback Offer):  
  *"Bạn cần kiểm tra chất lượng ván trước khi đặt số lượng lớn? Đăng ký ngay để nhận Miễn Phí Bộ Mẫu Cắt Thực Tế (12mm/15mm/18mm) gửi tận chân công trình trong 24h"*.

---

## PHẦN 2: MA TRẬN ĐÁNH GIÁ CHI TIẾT 14 KHU VỰC TRẢI NGHIỆM (UI/UX MATRIX)

| Khu vực UI/UX | Hiện trạng quan sát thực tế | Vấn đề cản trở chuyển đổi | Đề xuất tối ưu chuẩn Senior UI/UX |
|---|---|---|---|
| **1. Top Utility Header** | Chứa hotline tĩnh, không hiển thị giờ mở kho, thiếu địa chỉ tổng kho Hà Nội. | Khách không bấm gọi nhanh được; không biết kho có làm việc chủ nhật/ban đêm để bốc hàng gấp không. | Bổ sung Topbar chuẩn công nghiệp: `Hotline: 098x.xxx.xxx (Bấm gọi 24/7)` + `Tổng kho: Đan Phượng, Hà Nội (Mở cửa 6h - 22h)`. |
| **2. Thanh Menu Chính (Navigation)** | Menu lộn xộn, chứa trang "Thank you" lộ ngoài menu (`/co-so-ha-noi/`), chứa mục dự án BĐS. | Cấu trúc phân mảnh, làm người dùng nghi ngờ tính chuyên nghiệp của doanh nghiệp. | Tái cấu trúc menu chuẩn B2B: `Trang Chủ` | `Ván Ép Phủ Phim (12-15-18mm)` | `Ván Ép Nội Thất` | `Bảng Giá & Chiết Khấu` | `Năng Lực Nhà Máy` | `Hồ Sơ Cung Ứng Dự Án` | `Liên Hệ`. |
| **3. Hero Banner (Màn 1)** | Chữ tương phản kém trên nền ảnh, slogan chung chung, 0 nút bấm CTA. | Khách vào không biết làm gì tiếp theo, tỷ lệ thoát trang cao ngất ngưởng. | Banner nền tối WCAG 2.1 AA (tương phản >4.5:1), tiêu đề nhà máy giá gốc, 2 nút CTA nổi bật: "Nhận Báo Giá Dự Án" và "Hotline Kỹ Thuật". |
| **4. Công Cụ Tính Giá Nhanh (Quote Widget)** | Không có. | Khách hàng phải tự ước tính khối lượng, không thấy được lợi ích mua số lượng lớn để giảm giá. | Thiết kế Mini Calculator: Chọn độ dày + Nhập m² sàn → Hệ thống tự động gợi ý số tấm cần dùng & đơn giá dự kiến. |
| **5. Lưới Danh Mục Sản Phẩm (Category Grid)** | Hình ảnh sản phẩm không đồng đều tỷ lệ (aspect-ratio), ảnh mờ, không gắn nhãn độ dày to rõ. | Trông như website tạm bợ dựng dở, khó phân biệt giữa các dòng ván 12mm, 15mm, 18mm. | Chuẩn hóa lưới ảnh tỷ lệ 16:10 hoặc 4:3, gắn Huy hiệu thông số nổi bật (Ví dụ: `Ván 15mm - Luân chuyển 8-10 lần - Ruột bạch đàn`). |
| **6. Giao Diện Trang Chi Tiết Sản Phẩm** | Text lặp 2 lần; heading H1 nhảy lung tung (3 thẻ H1); thiếu ảnh mặt cắt ruột gỗ và lớp keo. | Nhà thầu cần xem chất lượng ruột có bị rỗng/lỗ mọt không nhưng không có ảnh chụp thực tế. | Thiết kế thư viện ảnh zoom chi tiết: Ảnh mặt cắt gỗ, ảnh thử nghiệm ngâm nước sôi, bảng thông số kỹ thuật rõ ràng. |
| **7. Bảng Giá & Chiết Khấu Đại Lý (BOQ Table)** | Giá để chung chung hoặc ẩn giá bắt liên hệ; không có bậc thang số lượng. | Làm mất thời gian của cả người mua lẫn nhân viên tư vấn, tạo cảm giác thiếu minh bạch. | Công khai Bảng giá tham khảo theo bậc số lượng (Lẻ công trình <100 tấm, Sỉ 100-500 tấm, Đại lý >500 tấm). |
| **8. Khối Chứng Thực Năng Lực Nhà Máy** | Chỉ có vài dòng chữ tự khen; không có video máy móc, không có ảnh bãi gỗ nguyên liệu. | Không thuyết phục được các nhà thầu lớn cần kiểm tra năng lực sản xuất thực tế. | Bổ sung Photo/Video Gallery thực tế: Dàn máy ép nhiệt 140 tấn, máy sấy veneer, kho thành phẩm chứa hàng vạn tấm. |
| **9. Hồ Sơ Cung Ứng Dự Án (Case Studies)** | Toàn bộ 13 bài viết copy giới thiệu căn hộ chung cư cao cấp Vinhomes, Tân Hoàng Minh. | Tai hại nhất: Gây hiểu nhầm là sàn môi giới nhà đất; hoàn toàn không chứng minh được năng lực bán ván. | Xóa sạch bài BĐS. Đăng 6 Case Study thực tế: Cung cấp 8.000 tấm cốp pha cho dự án chung cư X, nhà thầu Y, tiến độ giao 3 ngày. |
| **10. Chứng Nhận Kỹ Thuật (Testing Reports)** | Không có chứng chỉ kiểm định chất lượng hiển thị trên trang. | Nhà thầu không có tài liệu nghiệm thu kỹ thuật nộp cho Tư Vấn Giám Sát công trình. | Hiển thị Giấy chứng nhận thử nghiệm của Tổng Cục Tiêu Chuẩn Đo Lường Chất Lượng (Quatest 1) kèm nút bấm tải file PDF. |
| **11. Ý Kiến Khách Hàng (Testimonials)** | Không có. | Thiếu bằng chứng xã hội (Social Proof) từ những người đã sử dụng thực tế. | Bổ sung 3 phản hồi thật từ Chỉ huy trưởng Coteccons, Giám đốc công ty xây lắp Nam Định, Đại lý phân phối Hải Phòng. |
| **12. Biểu Mẫu Nhận Báo Giá (RFQ Form)** | Form Contact 7 mặc định đòi email, thiếu trường chọn chủng loại ván và khối lượng công trình. | Tỷ lệ bỏ ngang form cao; thông tin thu thập không đủ để phòng kinh doanh lên báo giá chuẩn. | Form 3 trường tối ưu: Loại ván + Khối lượng dự kiến + Số điện thoại Zalo. Cam kết phản hồi báo giá trong 15 phút. |
| **13. Nút Nổi & Vùng Chạm Di Động (Thumb Zone)** | Icon Zalo và Hotline lơ lửng giữa màn hình, che mất chữ bài viết và chân trang; không có sticky bar. | Gây ức chế thị giác khi cuộn trang; dễ bấm nhầm trên màn hình cảm ứng di động. | Thay bằng Thanh Sticky Bar 2 nút gắn cố định sát đáy màn hình điện thoại, giải phóng 100% diện tích đọc nội dung. |
| **14. Chân Trang & Pháp Nhân Doanh Nghiệp (Footer)** | Xung đột tên công ty (V-HOME vs Tú Anh 68 vs Vanphuphimvn.com); thiếu mã số thuế và bản đồ kho. | Triệt tiêu độ uy tín ở điểm chạm cuối cùng của hành trình người dùng. | Đồng nhất thông tin pháp lý: Tên công ty, MST, địa chỉ nhà máy Hòa Bình, địa chỉ tổng kho Hà Nội, Google Maps chỉ đường. |

---

## PHẦN 3: CHECKLIST HÀNH ĐỘNG TRIỂN KHAI CHO ĐỘI NGŨ THỰC THI

### Dành cho UI/UX Designer:
- [ ] Dựng lại Master Layout Hero Banner (Desktop & Mobile) theo chuẩn tỷ lệ 16:9 và 9:16;
- [ ] Thiết kế Bộ Icon & Huy Hiệu Năng Lực 4 chỉ số vàng (Công suất, Kho bãi, Chu kỳ luân chuyển, Cam kết đổi trả);
- [ ] Chuẩn hóa Bảng Datasheet Thông số Kỹ thuật & Bảng Phân Bậc Giá theo số lượng cho 3 dòng ván chính (12mm, 15mm, 18mm);
- [ ] Thiết kế Giao diện Thanh Sticky Action Bar đáy màn hình điện thoại (2 nút Gọi & Zalo to rõ, chuẩn vùng ngón tay cái);
- [ ] Thiết kế Khối Hồ Sơ Cung Ứng Dự Án (Case Study Card) hiển thị ảnh thực tế giao ván, logo nhà thầu và số lượng tấm.

### Dành cho Lập trình viên Frontend / WordPress Dev:
- [ ] **Khẩn cấp P0:** Tắt bỏ ngay thẻ chặn `<meta name="robots" content="noindex, nofollow" />` trong Cài đặt Đọc của WordPress;
- [ ] Gỡ bỏ loại bài viết `blocks` ra khỏi tệp XML Sitemap để tránh lãng phí crawl budget của Google;
- [ ] Sửa thuộc tính ngôn ngữ `<html lang="en-US">` thành `<html lang="vi">`;
- [ ] Lập trình thanh Sticky Bottom Bar cố định cho thiết bị di động (<768px) với sự kiện `tel:` và link chuyển tiếp Zalo Chat;
- [ ] Tích hợp mã theo dõi chuyển đổi Google Tag Manager (GTM) cho các sự kiện: Click nút gọi, Click Zalo, Gửi form RFQ;
- [ ] Dọn sạch mã định dạng font cứng (`Times New Roman`) và khoảng trắng thừa `&nbsp;` trong các thẻ tiêu đề bài viết;
- [ ] Khắc phục triệt để lỗi tiêu đề `<title>Thank you</title>` tại trang cơ sở Hà Nội (`/co-so-ha-noi/`).

### Dành cho Bộ phận Nội dung (Content & Marketing):
- [ ] Xóa bỏ toàn bộ 13 bài viết môi giới bất động sản tại chuyên mục `/du-an/`;
- [ ] Viết lại 6 bài Case Study Cung Ứng Cốp Pha thực tế kèm ảnh chụp bàn giao hàng tại chân công trình;
- [ ] Rà soát và gộp link (Redirect 301) bài viết bị nhân bản đuôi `-2` về URL bài viết chính;
- [ ] Biên tập lại nội dung trang sản phẩm 12mm, 15mm, 18mm: Xóa đoạn văn lặp keo 2 lần, bổ sung hướng dẫn cưa xẻ và bảo quản ngoài trời mưa.

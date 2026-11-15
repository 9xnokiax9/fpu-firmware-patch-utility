# Mac68.Vn BIOS Tool

Bộ công cụ xử lý BIOS dành cho **kỹ thuật viên sửa chữa laptop** — làm sạch ME, thay vùng BIOS của hãng,
rã / đóng gói lại BIOS, tách BIOS từ gói cập nhật, đọc / nạp DMI, mở khoá mật khẩu BIOS.

> Repo này chỉ chứa **bản phát hành (file EXE)**, không chứa mã nguồn.

## ⬇️ Tải về

**[Tải bản mới nhất](https://github.com/9xnokiax9/mac68-bios-tool/releases/latest)** — mỗi bản phát hành kèm
mã **SHA256** để đối chiếu file. Tool tự báo khi có phiên bản mới (popup cập nhật).

## ✨ Chức năng

| Nhóm | Mô tả |
|---|---|
| **Clean ME & Fix Region** | Làm sạch ME, thay vùng BIOS của hãng, rã và đóng gói lại BIOS (Intel FIT). ME 16.x rã lỗi → tự thay MFS + EFS từ kho rồi thử lại. |
| **Build BIOS tự động** | One-Click theo hãng: Dell, HP, Lenovo, Acer, Asus, AMD. |
| **Tách BIOS đa hãng** | Lấy ảnh BIOS chuẩn từ gói cập nhật của hãng (Dell PFS, HP SoftPaq / AMI UCP, Lenovo, Insyde, Gigabyte, ASUS…). |
| **DMI / Serial** | Đọc, sao chép và nạp lại thông tin máy. |
| **Mở khoá mật khẩu BIOS** | Hỗ trợ nhiều hãng (HP, Dell, Lenovo, ASUS, Acer, Gigabyte…). |
| **Kiểm tra & so sánh** | Đối chiếu BIOS gốc với BIOS đã xử lý. |
| **Công cụ nâng cao** | Disable RAM onboard, tráo Region trực tiếp. |

## 🧰 Cài đặt

1. Windows 10 / 11 bản 64-bit.
2. Chỉ cần **1 file `Bios Tool_V*.exe`** — chép vào đâu cũng chạy. Bộ công cụ (MEA, công cụ tách BIOS, PMC/PHY)
   nằm sẵn trong EXE
3. Chạy file EXE (lần đầu Windows SmartScreen có thể hỏi — chọn *More info → Run anyway*).

Kho dữ liệu **ME sạch (CleanME) + FIT** được tool **tự tải từ máy chủ Mac68** khi cần — chỉ tải đúng phần
phù hợp với phiên bản ME của BIOS đang xử lý, có kiểm tra SHA256, lưu lại trên máy để lần sau dùng ngay.

## 🔐 Đăng nhập & bản quyền

1. Mở tool → bấm **Đăng nhập Google** → chọn tài khoản Google của bạn trên trình duyệt.
2. Tài khoản mới ở trạng thái **Chờ duyệt** → liên hệ admin Mac68 để được duyệt.
3. Sau khi được duyệt, bấm **Kiểm tra lại** là vào được tool.

- Mỗi tài khoản dùng tối đa **2 máy**. Đổi máy / cài lại Windows → nhờ admin gỡ máy cũ.
- Tool dùng được **offline tối đa 7 ngày** kể từ lần kết nối gần nhất; sau đó cần mạng một lần để gia hạn.
- Nút **Tài khoản** (thanh bên trái): họ tên, Gmail, hạn dùng còn bao nhiêu ngày, đăng xuất / đổi tài khoản.

## 🐞 Báo lỗi

Gặp lỗi? Bấm nút **Báo lỗi** ở thanh bên trái: mô tả lỗi, để lại Zalo / SĐT (không bắt buộc). Tool tự gửi kèm
nhật ký xử lý và — nếu bạn đồng ý — file BIOS đang mở, giúp admin tái hiện và sửa lỗi nhanh nhất.

## ❓ Câu hỏi thường gặp

- **Không mở được trình duyệt khi đăng nhập?** Kiểm tra trình duyệt mặc định của Windows, rồi bấm Đăng nhập Google lại.
- **Báo “Đã dùng trên đủ 2 máy”?** Nhờ admin gỡ máy cũ, rồi bấm *Kiểm tra lại*.
- **Báo hết hạn offline?** Kết nối mạng và mở lại tool (hoặc vào Tài khoản → *Làm mới*).
- **Thiếu FIT / ME cho một đời máy?** Kết nối mạng — tool tự tải phần kho cần dùng; nếu kho máy chủ chưa có, gửi *Báo lỗi* kèm file BIOS.

## 📝 Lịch sử cập nhật

Xem ghi chú từng phiên bản ở trang **[Releases](https://github.com/9xnokiax9/mac68-bios-tool/releases)**.

---

© Mac68.Vn — [mac68.vn](https://mac68.vn) · [Chính sách quyền riêng tư](https://mac68-license.mac68.workers.dev/privacy)

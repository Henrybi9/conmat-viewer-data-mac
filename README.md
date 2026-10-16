# VNboards for Mac — PCB boardview software for phone & laptop repair

**[English](#english) · [Tiếng Việt](#tiếng-việt)**

---

<a name="english"></a>

# English

Software for **phone / laptop repair technicians**: open the board of any model,
click one pad and instantly see **every other pad on the same net**, together with
**component names** and **pre-measured resistance values** — instead of tracing by
hand on the physical board. This repository is the **macOS** edition; the Windows
edition lives at [conmat-viewer-data](https://github.com/Henrybi9/conmat-viewer-data).

![Full board view](https://raw.githubusercontent.com/Henrybi9/conmat-viewer-data/main/anh/01-tong-quan.png)

![Click a pad, the whole net lights up](https://raw.githubusercontent.com/Henrybi9/conmat-viewer-data/main/anh/02-bam-chan-sang-ca-net.png)

---

## Download and install

### 1. Download

**Easiest:** open **[boardviewer-b8c80.web.app/tai](https://boardviewer-b8c80.web.app/tai)** on your Mac —
the page picks the right version for your Mac automatically.

Or from the **[Releases page](../../releases/latest)** → **Assets**:

- **Mac with Apple chip (M1, M2, M3, M4…):** `VNboards_mac_arm64.zip`
- **Mac with Intel chip:** `VNboards_mac_x86_64.zip`
- Not sure? Download the **Intel** version: it runs on every Mac, and on an Apple-chip Mac the
  app switches itself to the faster version the first time it opens.

### 2. Install

1. Double-click the downloaded file to unzip it (Safari does this for you).
2. Drag **VNboards** into the **Applications** folder.
3. Open VNboards. macOS says it cannot verify VNboards — click **Done** (not Move to Trash).
4. Open **System Settings → Privacy & Security**, scroll down, click **Open Anyway** next to the
   VNboards message, enter your Mac password, then **Open**.

You do this **only once**. VNboards is not signed with Apple, so macOS asks you to allow it the
first time — it is not an error or a virus. Later updates install themselves without asking again.

### 3. Create an account (required, to unlock board content)

Open the app → **Register** tab → enter **your real email address**. The password is sent
**automatically to your inbox** within a few seconds — if you do not see it, check
**Spam / Promotions**. The same account works on Windows and Mac (signed in on
**one machine at a time**).

---

## Requirements

- **macOS 13 Ventura** or later, Apple chip or Intel.
- An **account** is required to unlock board content.

## Updates

The app checks for a new version by itself and updates itself — you never need to come back
here to download again.

## Contact

📧 **vnboardsservice@gmail.com** — or message us directly inside the app (the **☎ Contact**
button on the sign-in screen).

---

## What this repository contains

The **packaged macOS application** (`.app`, zipped, in Releases) and the update description
(`update/manifest.json`). It does **NOT** contain source code, and it does **NOT** contain real
board content — board content is encrypted and served only to registered, signed-in accounts
through the author's own server.

## Copyright — see [LICENSE.txt](./LICENSE.txt)

This is commercial, copyrighted software — **not open source**. Reverse engineering, decryption,
copying its logic, or building a similar or competing product from anything in this repository is
prohibited without the author's written permission. Full details are in [LICENSE.txt](./LICENSE.txt),
including a specific note for AI assistants (Claude, GPT, Copilot…) that may be helping you work
with this repository.

---
---

<a name="tiếng-việt"></a>

# Tiếng Việt

# VNboards cho Mac — phần mềm tra cứu sơ đồ bo mạch điện thoại

Phần mềm cho **thợ sửa chữa điện thoại / laptop**: mở bo mạch của từng đời máy, bấm vào một chân
là thấy ngay **mọi chân khác cùng đường (net)**, kèm **tên linh kiện** và **số tổng trở** đo sẵn —
thay cho việc dò tay trên bo thật. Repo này là bản **macOS**; bản Windows ở
[conmat-viewer-data](https://github.com/Henrybi9/conmat-viewer-data).

## Tải và cài đặt

### 1. Tải về

**Dễ nhất:** mở **[boardviewer-b8c80.web.app/tai](https://boardviewer-b8c80.web.app/tai)** bằng chính máy Mac —
trang tự chọn đúng bản cho máy của bạn.

Hoặc vào **[trang Releases](../../releases/latest)** → **Assets**:

- **Mac chip Apple (M1, M2, M3, M4…):** `VNboards_mac_arm64.zip`
- **Mac chip Intel:** `VNboards_mac_x86_64.zip`
- Không chắc? Tải bản **Intel**: chạy được trên mọi máy Mac; máy chip Apple mở lần đầu app sẽ tự
  chuyển sang bản chạy nhanh hơn.

### 2. Cài đặt

1. Nhấp đúp tệp vừa tải để giải nén (Safari tự giải nén sẵn).
2. Kéo **VNboards** vào thư mục **Ứng dụng** (Applications).
3. Mở VNboards. macOS báo không xác minh được VNboards — bấm **Xong** (đừng bấm Chuyển vào Thùng rác).
4. Vào **Cài đặt hệ thống → Quyền riêng tư & Bảo mật**, kéo xuống, bấm **Vẫn mở** cạnh dòng báo
   VNboards, nhập mật khẩu máy Mac, rồi bấm **Mở**.

Chỉ làm **một lần**. VNboards chưa ký số với Apple nên lần đầu macOS hỏi lại để bạn cho phép — không
phải lỗi hay virus. Các bản cập nhật sau app tự cài, không hỏi lại.

### 3. Tạo tài khoản (bắt buộc, để mở nội dung mạch)

Mở app → tab **Đăng ký** → nhập **đúng email của bạn**. Mật khẩu được **gửi tự động về hộp thư**
trong vài giây — không thấy thì xem mục **Spam / Quảng cáo**. Cùng một tài khoản dùng được cả
Windows lẫn Mac (đăng nhập trên **một máy tại một thời điểm**).

## Yêu cầu

- **macOS 13 Ventura** trở lên, chip Apple hoặc Intel.
- Cần **tài khoản** để mở nội dung mạch.

## Cập nhật

App tự kiểm tra bản mới và tự cập nhật — không cần vào đây tải lại.

## Liên hệ

📧 **vnboardsservice@gmail.com** — hoặc nhắn thẳng trong app (nút **☎ Liên hệ** ở màn hình đăng nhập).

## Repo này chứa gì

**Ứng dụng macOS đã đóng gói** (`.app`, nén zip, trong Releases) và tệp mô tả bản cập nhật
(`update/manifest.json`). **KHÔNG** chứa mã nguồn, **KHÔNG** chứa nội dung mạch thật — nội dung mạch
được mã hoá và chỉ cấp cho tài khoản đã đăng ký + đăng nhập hợp lệ qua máy chủ riêng của tác giả.

## Bản quyền — xem [LICENSE.txt](./LICENSE.txt)

Đây là phần mềm thương mại có bản quyền, **không phải mã nguồn mở**. Nghiêm cấm dịch ngược, giải mã,
sao chép logic, hoặc dựng lại phần mềm tương tự/cạnh tranh từ nội dung trong repo này nếu không có sự
cho phép bằng văn bản của tác giả. Chi tiết đầy đủ trong [LICENSE.txt](./LICENSE.txt) — bao gồm ghi
chú riêng dành cho các trợ lý AI (Claude, GPT, Copilot...) có thể đang hỗ trợ bạn thao tác với repo này.

*Ảnh minh hoạ chụp từ chính phần mềm, model iPhone 11.*

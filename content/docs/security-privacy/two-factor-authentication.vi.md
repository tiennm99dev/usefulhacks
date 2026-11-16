---
title: Bật xác thực hai lớp
tags: [account, security]
---

{{< term "2FA" >}} yêu cầu thêm một bước xác minh sau mật khẩu, nên dù mật khẩu
bị lộ, người khác vẫn không vào được tài khoản.

{{% steps %}}

### Bắt đầu với các tài khoản quan trọng

Làm trước với email chính và tài khoản điện thoại: chúng có thể đặt lại mọi mật
khẩu khác.

### Chọn cách mạnh nhất mà trang hỗ trợ

1. **Passkey hoặc khóa bảo mật.** {{< term "passkey" >}} chỉ hoạt động trên đúng
   trang thật, nên trang lừa đảo không đánh cắp được.
2. **Ứng dụng xác thực**, như Google Authenticator, Microsoft Authenticator
   hoặc tính năng có sẵn trong trình quản lý mật khẩu.
3. **Mã SMS.** Vẫn hơn là không có gì.

### Lưu mã dự phòng

Trang chỉ hiện các mã này một lần khi bạn bật 2FA. Hãy lưu vào trình quản lý mật
khẩu hoặc in ra: đó là cách vào lại tài khoản nếu bạn mất điện thoại.

{{% /steps %}}

> [!WARNING]- Vì sao SMS xếp cuối?
> Trong một vụ {{< term "SIM swap" >}}, kẻ gian chuyển số của bạn sang SIM của
> họ và nhận luôn mã của bạn. Ứng dụng xác thực và passkey không gắn với số điện
> thoại.

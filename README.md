# Techies Lab — Brand Assets

Kho ảnh dùng chung cho cả org: logo, ảnh marketing, screenshot. Một nơi duy nhất để
tìm và tái sử dụng tài nguyên hình ảnh thay vì để rải rác.

## Cấu trúc

```
brand-assets/
├── logos/         Logo (Techies Lab, avatar, Discord, Python, ...)
├── marketing/     Ảnh marketing & ảnh AI tạo
│   └── covers/    Ảnh bìa / banner
├── screenshots/   Screenshot Discord, hướng dẫn, QR, ...
└── web-drafts/    Bản nháp HTML (landing page nháp)
```

## Quy ước

- **Chỉ chứa hình ảnh / vector / nháp web nhẹ.** File media nặng (MP3, MOV, ghi âm)
  KHÔNG để ở đây — chúng nằm trong `../_local-media/` và không đẩy lên git.
- Đặt tên file rõ ràng, không dấu cách nếu tạo file mới (gạch ngang `-` thay cho dấu cách).

## Đẩy lên GitHub (lần đầu)

```bash
# 1. Tạo repo trống "brand-assets" trong org: https://github.com/orgs/Techieslab-app/repositories
# 2. Từ thư mục này:
git add .
git commit -m "Initial brand assets"
git push -u origin main
```

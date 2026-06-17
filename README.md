# Techies Lab — Brand Assets & Brand Kits

Kho thương hiệu dùng chung cho cả org: **brand kit HTML** + tài nguyên gốc (logo, ảnh
marketing, screenshot). Một nơi duy nhất để xem và tái sử dụng.

## 🎨 Brand Kits (mở trực tiếp bằng trình duyệt)

| Kit | Mở | Nội dung |
|-----|-----|----------|
| **Hub** | [`index.html`](index.html) | Trang chủ link sang 2 kit |
| **Techies Lab** | [`techieslab/index.html`](techieslab/index.html) | techies.lab.app — glyph mark, Pixel Pet mascot, palette dark-violet, EB Garamond + Inter, manifesto |
| **Antibot** | [`antibot/index.html`](antibot/index.html) | Flame mascot system (10 biến thể), 4 personalities, palette coral, Modak + Inter |

Mỗi kit là một file `index.html` **tự chứa** (CSS inline, font qua Google Fonts CDN, ảnh
trong `assets/`). Không cần build — nhấp đúp để mở, hoặc host qua GitHub Pages.

## Cấu trúc

```
brand-assets/
├── index.html              Hub
├── antibot/
│   ├── index.html          Brand kit Antibot
│   └── assets/             10 SVG mascot + gif + render (kebab-case)
├── techieslab/
│   ├── index.html          Brand kit Techies Lab
│   └── assets/             logo glyph, pixel-pet sheet, covers, marketing, screenshots
├── logos/ marketing/ screenshots/ web-drafts/   Tài nguyên gốc
└── README.md
```

## Palette nhanh

- **Techies Lab** — nền `#0A0A14` · violet `#8070F8` / `#A090F8` · cyan `#58C8F8` · mint `#60D8C0` · trắng `#FFFFFF`
- **Antibot** — coral `#FF7A59` · ember `#FF6842` · peach `#FF8F73` · cream `#FDFCFB` · charcoal `#161616`

## Quy ước

- Chỉ chứa hình ảnh / vector / HTML brand kit. File media nặng (MP3, MOV, ghi âm) KHÔNG
  để ở đây — nằm trong `../_local-media/`, không đẩy lên git.
- File mới đặt tên kebab-case (gạch ngang thay dấu cách).

## Xem online (tuỳ chọn — GitHub Pages)

Sau khi push, vào **Settings → Pages → Deploy from branch `main` / root**. Link sẽ là:
`https://techieslab-app.github.io/brand-assets/`

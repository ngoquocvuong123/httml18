# Mini-project 3: Semantic Profile Page

Trang giới thiệu cá nhân xây dựng bằng **semantic HTML5** và **CSS3** thuần — không dùng framework.

🌐 **Live demo:** [https://ngoquocvuong123.github.io/httml18/index.html)

---

## Cấu trúc dự án

```
mini-project-3/
├── index.html        # File HTML chính
├── css/
│   └── style.css     # Toàn bộ CSS (tách riêng file)
├── js/
│   └── script.js     # JavaScript (hamburger, scroll, reveal)
├── assets/           # Ảnh, icon (nếu có)
└── README.md
```

---

## Các section trong trang

| Section | Tag HTML | Mô tả |
|---|---|---|
| Header | `<header id="site-header">` | Logo + nav sticky |
| Navigation | `<nav id="main-nav">` | Menu chính, active khi scroll |
| Hero | `<section id="hero">` | Tên, role, CTA |
| About | `<section id="about">` | Thông tin cá nhân, stats |
| Skills | `<section id="skills">` | Kỹ năng theo nhóm |
| Projects | `<section id="projects">` | Card dự án có link |
| Contact | `<section id="contact">` | Link liên hệ + form |
| Footer | `<footer id="site-footer">` | Copyright |

---

## Semantic HTML đã dùng

- `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>` đúng vai trò
- `<dl>` / `<dt>` / `<dd>` cho thông tin cá nhân
- `aria-label`, `aria-labelledby`, `role` cho accessibility
- `id` và `class` đặt tên rõ nghĩa theo block/component

---

## Tính năng

- **Responsive** — mobile, tablet, desktop
- **Nav active** tự động highlight khi scroll
- **Scroll reveal** — các card fade in khi vào viewport
- **Hamburger menu** — mobile nav toggle
- **Accessible** — keyboard focus, reduced motion support
- **CSS Variables** — dễ đổi theme màu

---

## Công nghệ sử dụng

![HTML5](https://img.shields.io/badge/HTML5-semantic-orange)
![CSS3](https://img.shields.io/badge/CSS3-variables%20%7C%20grid%20%7C%20flexbox-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-vanilla-yellow)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-deployed-brightgreen)

---

## Cách chạy local

```bash
# Clone repo
git clone https://github.com/vanan/mini-project-3.git

# Mở file
cd mini-project-3
open index.html
# hoặc dùng Live Server trong VS Code
```

---

## Thông tin sinh viên

| | |
|---|---|
| **Họ tên** | Nguyễn Văn An |
| **Lớp** | Web01 |
| **Trường** | Đại học XYZ |
| **Mini-project** | 3 — Semantic Profile Page |

---

*Bài nộp Mini-project 3 — Môn Lập trình Web*

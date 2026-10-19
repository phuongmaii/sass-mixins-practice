# [Thực hành] Tạo mixins & biến để tối ưu CSS của website mẫu

## 🎯 Mục tiêu
- Sử dụng **mixins** để tái sử dụng đoạn mã giao diện lặp lại.
- Quản lý kích thước font chữ, màu sắc, padding bằng **biến SASS**.
- Phân chia mã nguồn theo cấu trúc module rõ ràng (`abstracts`, `base`, `components`).

## 📁 Cấu trúc thư mục
```text
sass-mixins-practice/
├── scss/
│   ├── abstracts/
│   │   ├── _variables.scss
│   │   └── _mixins.scss
│   ├── base/
│   │   └── _typography.scss
│   ├── components/
│   │   ├── _buttons.scss
│   │   └── _cards.scss
│   └── main.scss
├── index.html
├── package.json
└── .gitignore
```

## 🚀 Hướng dẫn chạy dự án
1. Cài đặt dependency:
   ```bash
   npm install
   ```
2. Biên dịch SASS sang CSS:
   ```bash
   npm run build:sass
   ```
3. Xem trực tiếp với chế độ watch:
   ```bash
   npm run watch:sass
   ```

# OQMLB — Quy Trình Tạo Dashboard

> Interactive web guide cho HR Analytics Training — Framework OQMLB và 4 loại Dashboard chuẩn quốc tế

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## 📋 Nội dung

### Quy trình OQMLB (5 bước)

| Bước | Tên | Mô tả |
|------|-----|-------|
| **O** | Objective | Xác định mục tiêu (WHY) và người dùng (WHO) |
| **Q** | Question | Xác định câu hỏi cần dashboard trả lời (WHAT) |
| **M** | Metrics | Chọn KPI và chỉ số đo lường phù hợp |
| **L** | Layout | Thiết kế bố cục, wireframe, chọn chart type |
| **B** | Build | Thu thập → Làm sạch → Tính toán → Xây dựng |

### 4 loại Dashboard (chuẩn quốc tế)

| Loại | Đối tượng | Tần suất | Mục đích |
|------|-----------|----------|----------|
| **Strategic** | C-Level | Tháng/Quý/Năm | Mục tiêu dài hạn |
| **Operational** | Manager | Real-time | Giám sát vận hành |
| **Analytical** | Analyst | Ad-hoc | Phân tích chuyên sâu |
| **Tactical** | Mid-manager | Tuần/Tháng | Tiến độ nhóm/dự án |

## 🚀 Deploy lên GitHub Pages

### Cách 1: Nhanh nhất

1. Tạo repository mới trên GitHub
2. Upload 2 file: `index.html` và `style.css`
3. Vào **Settings → Pages → Source** chọn `main` branch → Save
4. Chờ 1-2 phút, truy cập `https://<username>.github.io/<repo-name>`

### Cách 2: Dùng Git CLI

```bash
git init
git add .
git commit -m "OQMLB Dashboard Guide"
git branch -M main
git remote add origin https://github.com/<username>/<repo-name>.git
git push -u origin main
```

Sau đó vào Settings → Pages để bật.

## 📁 Cấu trúc file

```
├── index.html    # Trang web chính (tương tác đầy đủ)
├── style.css     # Toàn bộ style
└── README.md     # Hướng dẫn (file này)
```

## 🎨 Tính năng

- Giao diện high-tech, dark theme, responsive mobile
- OQMLB stepper tương tác — nhấn từng bước xem chi tiết
- 4 dashboard type cards với hover effect
- Bảng so sánh tổng hợp
- Scroll animation, keyboard navigation (← →)
- Không cần backend, không cần build — chỉ HTML/CSS/JS thuần

## 📚 Nguồn tham khảo

- **Maz The Analyst** — OQMLB Framework
- **Stephen Few** — Information Dashboard Design
- **Gartner** — Dashboard Classification
- **BABOK** — Business Analysis Body of Knowledge

## 📄 License

MIT — Sử dụng tự do cho mục đích đào tạo.

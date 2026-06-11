# Project List

> A modern, bilingual web app to browse, filter, sort and search projects from a Google Sheets data source.

---

## 🇬🇧 English

### Overview

**Project List** is a clean, fast, and fully responsive web application that displays project data fetched live from a Google Sheets spreadsheet. It supports filtering by category, full-text search, multiple sort options, and two languages.

### Features

- **Live data** from Google Sheets (no backend required)
- **Filter** projects by category using chip buttons
- **Search** by project name or category
- **Sort** by name (A–Z / Z–A), category, or newest
- **Grid & List** view toggle (remembered across sessions)
- **Bilingual**: English 🇬🇧 and Vietnamese 🇻🇳
- **Themes**: Light, Dark, and System (follows OS preference)
- **PWA support**: installable as a standalone app on mobile and desktop
- **Service Worker** for offline caching
- **Skeleton loading UI** and lazy image loading
- **Material Design 3** visual language throughout
- **Responsive**: optimized for mobile, tablet, and desktop
- **LocalStorage** — all preferences are saved automatically

### Data Format (Google Sheets)

The spreadsheet must have the following columns (row 1 = headers):

| Column | Description |
|--------|-------------|
| `name` | Project name |
| `category` | Category label |
| `url` | Live demo URL |
| `source_code` | Source code URL (e.g. GitHub) |
| `image` | Preview image URL |

### Tech Stack

- Vanilla HTML / CSS / JavaScript (zero dependencies)
- [Material Symbols Rounded](https://fonts.google.com/icons) icons
- [Be Vietnam Pro](https://fonts.google.com/specimen/Be+Vietnam+Pro) font
- Google Sheets GViz API for data
- Service Worker (PWA)

### Credits

- **Author**: trongsigmaprovip  
- **AI Assistance**: Claude by Anthropic  
- Design system: Material Design 3 by Google

---

## 🇻🇳 Tiếng Việt

### Tổng quan

**Project List** là ứng dụng web hiện đại, gọn nhẹ và hoàn toàn responsive, hiển thị dữ liệu dự án được lấy trực tiếp từ Google Sheets. Hỗ trợ lọc theo danh mục, tìm kiếm toàn văn, nhiều tùy chọn sắp xếp và hai ngôn ngữ.

### Tính năng

- **Dữ liệu trực tiếp** từ Google Sheets (không cần backend)
- **Lọc** dự án theo danh mục bằng chip button
- **Tìm kiếm** theo tên dự án hoặc danh mục
- **Sắp xếp** theo tên (A–Z / Z–A), danh mục hoặc mới nhất
- **Chế độ xem** lưới & danh sách (ghi nhớ qua các phiên)
- **Song ngữ**: Tiếng Anh 🇬🇧 và Tiếng Việt 🇻🇳
- **Giao diện**: Sáng, Tối, Hệ thống (theo cài đặt OS)
- **Hỗ trợ PWA**: cài đặt như ứng dụng native trên mobile và desktop
- **Service Worker** để lưu cache ngoại tuyến
- **Skeleton loading** và tải ảnh lazy
- **Material Design 3** xuyên suốt giao diện
- **Responsive**: tối ưu cho điện thoại, tablet và máy tính
- **LocalStorage** — tất cả tùy chỉnh được lưu tự động

### Định dạng dữ liệu (Google Sheets)

Bảng tính cần có các cột sau (hàng 1 = tiêu đề):

| Cột | Mô tả |
|-----|-------|
| `name` | Tên dự án |
| `category` | Nhãn danh mục |
| `url` | URL demo trực tiếp |
| `source_code` | URL mã nguồn (ví dụ GitHub) |
| `image` | URL ảnh xem trước |

### Công nghệ

- Vanilla HTML / CSS / JavaScript (không phụ thuộc thư viện bên ngoài)
- Biểu tượng [Material Symbols Rounded](https://fonts.google.com/icons)
- Font chữ [Be Vietnam Pro](https://fonts.google.com/specimen/Be+Vietnam+Pro)
- Google Sheets GViz API để lấy dữ liệu
- Service Worker (PWA)

### Tác giả

- **Tác giả**: trongsigmaprovip  
- **AI hỗ trợ**: Claude của Anthropic  
- Hệ thống thiết kế: Material Design 3 của Google

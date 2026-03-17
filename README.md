# Zentry Metaverse Gaming

Zentry Metaverse Gaming là một dự án website độc đáo với phong cách thiết kế hiện đại, tập trung vào trải nghiệm người dùng thông qua các hiệu ứng hoạt ảnh mượt mà và tương tác sống động lấy cảm hứng từ các trang web đạt giải Awwwards.

---

## Mục lục
- [Công nghệ sử dụng](#công-nghệ-sử-dụng)
- [Yêu cầu môi trường](#yêu-cầu-môi-trường)
- [Cài đặt & chạy dự án](#cài-đặt--chạy-dự-án)
- [Cấu trúc thư mục](#cấu-trúc-thư-mục)
- [Preview Video](#preview-video)
- [Lưu ý khi phát triển](#lưu-ý-khi-phát-triển)
- [License](#license)
- [Contact](#contact)

---

## Công nghệ sử dụng
- **Core:** [React](https://react.dev/) (v19) + [Vite](https://vitejs.dev/)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **Animation:** [GSAP](https://gsap.com/) & `@gsap/react`
- **Icons & Utilities:** `react-icons`, `react-use`
- **Linting:** ESLint

---

## Yêu cầu môi trường
- **Node.js**: Phiên bản 20.x trở lên (khuyến nghị dùng bản LTS mới nhất).
- **npm** (được cài đặt kèm theo Node.js) hoặc **yarn** / **pnpm**.

---

## Cài đặt & chạy dự án

1. **Clone dự án:**
   ```bash
   git clone <repository_url>
   cd Zentry-Metaverse-Gaming
   ```

2. **Cài đặt dependencies:**
   ```bash
   npm install
   ```

3. **Chạy web server để phát triển tĩnh (Development):**
   ```bash
   npm run dev
   ```
   > **Lưu ý**:Sau khi khởi động, mở trình duyệt tại địa chỉ được hiển thị trên console (thường là `http://localhost:5173/`).

4. **Build dự án cho môi trường Production:**
   ```bash
   npm run build
   ```

5. **Preview bản Build:**
   ```bash
   npm run preview
   ```

---

## Cấu trúc thư mục
```text
.
├── public/                 # Các tài nguyên tĩnh
├── src/                    # Chứa mã nguồn chính của ứng dụng phần Frontend
│   ├── components/         # Các React components (nếu có)
│   ├── App.jsx             # Component gốc của ứng dụng
│   └── main.jsx            # Điểm khởi chạy của ứng dụng (entry point)
├── eslint.config.js        # File cấu hình ESLint
├── package.json            # File quản lý package, dependencies và scripts
├── tailwind.config.js      # File chứa cấu hình cài đặt của Tailwind CSS
└── vite.config.js          # File cấu hình Vite
```

---

## Preview Video



https://github.com/user-attachments/assets/1f77627f-25a3-48ce-bd1b-c8d3de244b23

---

## Lưu ý khi phát triển
- Tập trung phát triển bên trong thư mục `src`.
- Hệ thống thiết kế UI sử dụng **Tailwind CSS**. 
- Animation được xử lý chuyên sâu qua **GSAP** (`@gsap/react`).
- Luôn kiểm tra định dạng code qua lệnh `npm run lint` để theo dõi các lỗi linting được thiết lập trong dự án.

---

## License
Dự án được phân phối dưới giấy phép [MIT](LICENSE).

---

## Contact
Nếu có bất kỳ câu hỏi nào trong quá trình cài đặt hay phát triển dự án, vui lòng liên hệ:
- **Tên:** Trantuan07a
- **Email:** dev.lamtuan@gmail.com
- **GitHub:** [@Trantuan07a](https://github.com/Trantuan07a)

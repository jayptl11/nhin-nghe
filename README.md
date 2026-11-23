# Nhìn Nghề

Website tĩnh (HTML/CSS/JavaScript/JSON) của Nhìn Nghề — hiểu nghề, xây lộ trình, phát triển năng lực; trước hết trong lĩnh vực kinh tế và kinh doanh. Nền tảng nội dung: Career Playbook · TS Nguyễn Thị Hoa.

- `dist/` — toàn bộ website, phục vụ trực tiếp từ gốc tên miền.
- `content/`, `scripts/` — nội dung nguồn và công cụ biên tập.
- `docs/SITEMAP.md` — 19 trang.
- `CLAUDE.md`, `THAY_DOI_19_11_2026.md` — bối cảnh và thay đổi gần nhất.

Xem trên máy: `python3 scripts/start_preview.py` rồi mở http://127.0.0.1:8000

## Deploy lên Vercel

Import repository vào Vercel và chọn Deploy. Tệp `vercel.json` cấu hình phục vụ trực tiếp `dist/`, không cần cài dependencies hoặc chạy build.

Nguồn ban đầu: https://github.com/nhinnghevn-afk/nhinnghe-. Bản sao này được quản lý trong repository riêng.

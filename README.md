# Hermes Stock Tracker

เว็บติดตามราคาหุ้นสำหรับมือถือ (PWA)

## หุ้นที่ติดตาม
- VOO (S&P 500 ETF)
- NVDA (NVIDIA)
- JEPQ (JEPQ ETF)

## เทคโนโลยี
- HTML/CSS/JS บริสุทธิ์ (ไม่มี framework)
- Yahoo Finance API (ฟรี ไม่ต้อง key)
- Responsive mobile-first
- PWA ready (install หน้าจอหลักมือถือได้)

## ใช้งาน
เปิด `index.html` ในเบราว์เซอร์ หรือ deploy บน GitHub Pages

## Deploy บน GitHub Pages
1. สร้าง repo บน GitHub (ชื่อ `hermes-stock-tracker`)
2. Push code นี้ขึ้นไป
3. Settings → Pages → source: `main` branch → Save
4. รอ 1-2 นาที ได้ URL `https://<username>.github.io/hermes-stock-tracker/`

## Auto-refresh
รีเฟรชราคาทุก 60 วินาทีโดยอัตโนมัติ
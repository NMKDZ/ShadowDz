# SHADOWDZ — Script Sharing Platform
> Website by MK

## Deploy lên Vercel

1. Upload folder này lên GitHub (repo mới, public hoặc private đều được)
2. Vào vercel.com → Import repository đó → Deploy
3. Xong ✅

## Firebase Setup (bắt buộc để like/comment/auth hoạt động)

Vào Firebase Console → Realtime Database → Rules → paste:

```json
{
  "rules": {
    ".read": true,
    ".write": true
  }
}
```

→ Publish

## Firebase Config đã nhúng sẵn

- Project: shadowdz-b3e0e
- Database: asia-southeast1
- Analytics: đã bật

## Features

- 16 Roblox scripts (Blox Fruit, Fisch, Steal an Egg, Grow a Garden, Da Hood, Jailbreak, TSB, ...)
- 22 Executors với trạng thái online/offline
- Hệ thống Like + Comment realtime (Firebase)
- Đăng ký / Đăng nhập (SHA-256 hash, lưu Firebase)
- Full-text search với highlight
- Light/Dark mode toggle
- Responsive mobile

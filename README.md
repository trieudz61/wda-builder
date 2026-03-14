# Build WDA trên GitHub Actions

## Hướng dẫn

1. Tạo repo mới trên GitHub (ví dụ: `wda-builder`)
2. Copy toàn bộ thư mục này vào repo
3. Push lên GitHub
4. Vào tab **Actions** → chạy workflow **"Build WDA"**
5. Đợi ~5 phút → download file `WebDriverAgent.ipa` từ Artifacts
6. Dùng Sideloadly cài IPA lên iPhone

## Cấu trúc
```
.github/workflows/build-wda.yml   ← GitHub Actions workflow
README.md                         ← File này
```

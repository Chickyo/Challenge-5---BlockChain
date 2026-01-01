# 🚩 Challenge 5: Decentralized Stablecoin (MyUSD)

Dự án này là bài giải cho **Challenge 5: Xây dựng Stablecoin thuật toán (MyUSD)**.

## 📦 1. Các thư viện cần tải (Dependencies)

Để dự án hoạt động và sử dụng được các thư viện chuẩn (ví dụ: `Ownable.sol` để quản lý quyền Admin), cần cài đặt các gói sau:

**Cài đặt toàn bộ thư viện (bao gồm Hardhat, React, v.v.):**

```bash
yarn install
```
🚀 2. Các bước chạy (Quick Start)
Bạn cần mở 3 cửa sổ Terminal riêng biệt để chạy hệ thống:

Bước 1: Khởi chạy Blockchain ảo (Terminal 1)
Lệnh này tạo mạng local để test:

```bash
yarn chain
```

Bước 2: Deploy Smart Contract (Terminal 2)
Lệnh này biên dịch và đưa code (MyUSDEngine, MyUSD...) lên mạng local:

```bash
yarn deploy
```

Bước 3: Khởi chạy Giao diện Web (Terminal 3)
Lệnh này mở trang web frontend để tương tác:

```bash
yarn start
```

📲 Truy cập vào: http://localhost:3000
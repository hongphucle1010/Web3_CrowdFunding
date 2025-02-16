# Web 3.0 gây quỹ cộng đồng - Kiến trúc phần mềm
Ứng dụng Web3 được viết dựa trên video của [ThirdWeb](https://www.youtube.com/watch?v=GxFXHXxd83E)

![tw-banner](https://github.com/thirdweb-example/next-starter/assets/57885104/20c8ce3b-4e55-4f10-ae03-2fe4743a5ee8)

## Cài đặt

Tạo một ứng dụng thirdweb: [thirdweb create](https://portal.thirdweb.com/cli/create)

```bash
  npx thirdweb create app --next
```

## Biến môi trường

Để chạy dự án này, bạn sẽ cần thêm các biến môi trường sau vào tệp .env.local của mình:

`NEXT_PUBLIC_TEMPLATE_CLIENT_ID`

Để tìm hiểu cách tạo client ID, tham khảo [client documentation](https://portal.thirdweb.com/typescript/v5/client).

## Chạy cục bộ

Cài đặt các phụ thuộc

```bash
yarn install
```

Khởi động project chế độ phát triển

```bash
yarn dev
```

Build ứng dụng

```bash
yarn build
```

Chạy ứng dụng đã build

```bash
yarn start
```

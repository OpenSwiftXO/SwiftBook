# Đóng Góp Cho Dự Án

Cảm ơn bạn đã quan tâm đến việc đóng góp cho dự án 📕 **Sổ tay Swift**!

## Cài Đặt Môi Trường

Để có thể đóng góp vào dự án, bạn cần cài đặt một số công cụ sau:

### 1. Cài Đặt Rust

Rust là ngôn ngữ lập trình mà các công cụ build (mdBook) và format (dprint) sử
dụng. Chúng ta cần cài Rust để sử dụng Cargo - trình quản lý package của Rust,
giúp cài đặt và quản lý các công cụ mdBook và dprint một cách dễ dàng.

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

Sau khi cài đặt, khởi động lại terminal và kiểm tra:

```bash
rustc --version
cargo --version
```

### 2. Cài Đặt cargo-binstall

[cargo-binstall](https://github.com/cargo-bins/cargo-binstall) giúp cài đặt các
binary Rust nhanh hơn (tải binary đã compile sẵn thay vì compile từ source).

```bash
curl -L --proto '=https' --tlsv1.2 -sSf https://raw.githubusercontent.com/cargo-bins/cargo-binstall/main/install-from-binstall-release.sh | bash
```

Hoặc sử dụng cargo:

```bash
cargo install cargo-binstall
```

### 3. Cài Đặt mdBook

[mdBook](https://github.com/rust-lang/mdBook) là công cụ tạo sách điện tử từ
file Markdown, tương tự như Gitbook.

```bash
cargo binstall mdbook
```

### 4. Cài Đặt dprint

[dprint](https://github.com/dprint/dprint) là code formatter cực kỳ nhanh cho
Markdown và nhiều ngôn ngữ khác.

**Sử dụng cargo-binstall:**

```bash
cargo binstall dprint
```

## Quy Trình Đóng Góp

1. **Fork repository** về tài khoản GitHub của bạn
2. Thực hiện các thay đổi cần thiết
3. **Chỉnh sửa và xem trước:** Vui lòng đọc
   [tài liệu mdBook](https://rust-lang.github.io/mdBook/)
4. **Đảm bảo format code** với `dprint fmt` trước khi commit
5. **Tạo Pull Request** về repository gốc

## Hướng Dẫn Viết Nội Dung

- Sử dụng tiếng Việt rõ ràng, dễ hiểu
- Cung cấp ví dụ code cụ thể cho mỗi khái niệm
- Giải thích tại sao và khi nào nên sử dụng một tính năng
- Ghi rõ nguồn tài liệu tham khảo

## Báo Lỗi hoặc Đề Xuất

Nếu bạn phát hiện lỗi hoặc có đề xuất cải thiện, vui lòng tạo
[issue](https://github.com/OpenSwiftXO/SwiftBook/issues) mới

---

Một lần nữa, cảm ơn bạn đã đóng góp! ❤️

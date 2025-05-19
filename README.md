# RSA
Giải thích hoạt động
Quá trình ký số:

Máy khách tạo chữ ký số bằng cách sử dụng private key để mã hóa hash (SHA-256) của file

Chữ ký được gửi cùng với file đến máy chủ

Quá trình xác minh:

Máy chủ nhận file và chữ ký

Sử dụng public key để giải mã chữ ký và so sánh với hash của file nhận được

Nếu khớp, file được xác minh là nguyên vẹn và đến từ nguồn đáng tin cậy

Bảo mật:

Sử dụng RSA với độ dài khóa 2048 bit

Sử dụng thuật toán hash SHA-256

Sử dụng padding PSS để tăng cường bảo mật

Ứng dụng này cung cấp giao diện đồ họa dễ sử dụng để thực hiện quá trình truyền file an toàn với xác thực bằng chữ ký số.

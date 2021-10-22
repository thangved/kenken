# Ken ken

## Intro

**KenKen** and **KenDoku** are trademarked names for a style of arithmetic and logic puzzle invented in 2004 by Japanese math teacher Tetsuya Miyamoto, who intended the puzzles to be an instruction-free method of training the brain. The name derives from the Japanese word for cleverness.

## How to play?

## Giải thuật

### Giải thuật tìm kiếm ràng buộc

- Trạng thái đầu: Ma trận $n*n$ rỗng.
- Trạng thái cuối: Các ô trong ma trận đều được điền.
- Các thao tác: Điền số từ $1$ đến $n$ vào 1 ô.
- Ràng buộc:
  - Các số trên một hàng và một cột là khác nhau.
  - Khi một chuồng đầy thì tùy theo phép toán mà kết quả phải bằng số ghi ở ô trên cùng bên trái.

### Các bước thực hiện

- Thứ tự thực hiện: Điền từ chuồng có số ô từ ít đến nhiều. Trường hợp có từ hai chuồng có cùng số ô thì chọn ngẫu nhiên một chuồng để điền trước.

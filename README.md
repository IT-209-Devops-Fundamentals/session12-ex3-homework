# session12-ex3-homework

## Bài 3: Tách biệt luồng CI/CD đa môi trường (Staging & Production) với GitHub Environments

### Cấu hình môi trường:
- `staging`: Môi trường triển khai tự động khi push vào nhánh `develop`.
- `production`: Môi trường triển khai có bảo vệ (Environment Protection Rules) yêu cầu phê duyệt thủ công (`Required reviewers`) khi push vào nhánh `main`.

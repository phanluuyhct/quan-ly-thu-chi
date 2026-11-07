# Quản lý Chi Thu & Tự chủ Tài chính

App một file: toàn bộ giao diện và logic nằm trong `index.html` (dữ liệu mẫu `SEED_TX`, `SEED_ACC` nhúng sẵn; đồng bộ đám mây qua Supabase).

## Quy ước làm việc

- Chủ repo **cho phép gộp thẳng vào `main`** sau khi sửa xong: commit trên nhánh làm việc, đẩy nhánh đó,
  rồi đẩy lên `main` (fast-forward; nếu `main` đã có commit mới thì rebase trước). Không cần mở pull request.
- Khi chủ repo gửi một bản `index.html` mới, so khác biệt với bản trên repo, báo lại những gì thay đổi, rồi thay thế.
- Trước khi đẩy: kiểm tra cú pháp phần `<script>` chính (vd tách ra file `.js` rồi `node --check`).
- Giao tiếp và viết commit bằng tiếng Việt.

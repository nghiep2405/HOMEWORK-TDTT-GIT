# StudyHub — Homework TDTT Git

StudyHub là website HTML tĩnh giới thiệu ngắn gọn về Tư duy tính toán và Python cơ bản, được dùng làm sản phẩm thực hành cho bài tập Week 07.

**Trọng tâm dự án:** quản lý thay đổi và cộng tác bằng Git/GitHub: commit, feature branch, Pull Request, review, merge conflict, revert, tag và GitHub Pages.

## Trạng thái dự án

Repository đang ở bước **khởi tạo tài liệu nền (N02)**. Mã HTML/CSS sẽ được phát triển trên feature branches; website chưa được triển khai. Các hoạt động và minh chứng chưa hoàn thành được ghi rõ trong [báo cáo](docs/REPORT.md).

## Thành viên

Nhóm 5 người đã được phép tham gia theo xác nhận của nhóm trưởng.

| Thành viên | MSSV | GitHub | Phân công chính |
|---|---|---|---|
| Nguyễn An Nghiệp | 23127234 | [nghiep2405](https://github.com/nghiep2405) | Khởi tạo repo/tài liệu, nền tảng HTML/CSS và trang chủ, điều phối, release |
| Lê Vĩnh Trọng | 25127247 | [levinhtrong2605-blue](https://github.com/levinhtrong2605-blue) | Lộ trình học, review, thay đổi conflict A |
| Nguyễn Thiên Vũ | 25127557 | [nguyenthienvu9565](https://github.com/nguyenthienvu9565) | Python cơ bản, review, thay đổi conflict B và giải quyết conflict |
| Nguyễn Trọng Trực | 25127535 | [nguyentrongtruc22-ship-it](https://github.com/nguyentrongtruc22-ship-it) | Bài tập, review, tạo commit lỗi navigation |
| Lê Đặng Nhựt Anh | 25127264 | [ldnanh2517](https://github.com/ldnanh2517) | Tài nguyên/giới thiệu nhóm, review, revert commit lỗi |

Tên hiển thị “Yuno Học Code” của Trực tương ứng với username `nguyentrongtruc22-ship-it`.

## Phạm vi website dự kiến

| File | Nội dung | Người phụ trách |
|---|---|---|
| `index.html` | Trang chủ giới thiệu StudyHub | Nghiệp |
| `roadmap.html` | 5 bước học ngắn gọn | Trọng |
| `python.html` | Biến, điều kiện, vòng lặp và ví dụ | Vũ |
| `practice.html` | 3 bài tập đơn giản, ví dụ và gợi ý | Trực |
| `resources.html` | 3–5 tài nguyên học tập | Nhựt Anh |
| `about.html` | Thông tin 5 thành viên và liên kết GitHub | Nhựt Anh |

Cả 6 trang sẽ dùng navigation chung và một file `assets/css/style.css`. Bảng trên là phạm vi sẽ phát triển, chưa phải danh sách file hiện có.

## Công nghệ

- HTML và CSS thuần; không cần bước build.
- Git và GitHub để quản lý mã nguồn, tài liệu và cộng tác.
- GitHub Pages để xuất bản website sau khi hoàn thành.

## Bắt đầu làm việc

Mỗi người clone repository và tự cấu hình Git identity đúng với tài khoản của mình:

```powershell
git clone https://github.com/nghiep2405/HOMEWORK-TDTT-GIT.git
Set-Location HOMEWORK-TDTT-GIT
```

Sau khi nền tảng của Nghiệp đã được review và merge, các thành viên đồng bộ `main` rồi tạo nhánh được phân công:

| Thành viên | Feature branch |
|---|---|
| Nghiệp | `feature/site-foundation` |
| Trọng | `feature/learning-roadmap` |
| Vũ | `feature/python-basics` |
| Trực | `feature/practice-exercises` |
| Nhựt Anh | `feature/resources-and-team` |

Phần cá nhân của **Task 1 được thực hiện trong quá trình làm Task 2**: dùng các lệnh Git, tạo ít nhất 3 commit có ý nghĩa trên feature branch, rồi push nhánh. Cùng commit và output có thể làm minh chứng cho cả hai task; không cần làm hai bộ commit riêng.

Sau khi có mã website, mở `index.html` trong trình duyệt để xem local. Hiện N02 chưa có trang HTML để mở.

## Quy tắc cộng tác

1. Mỗi người dùng GitHub account và Git identity riêng; tự đóng góp và giải thích phần việc của mình.
2. Sau commit bootstrap, phát triển trên feature branch và tích hợp qua Pull Request.
3. Người khác review và nhận xét cụ thể trước khi merge; chọn **Create a merge commit** để giữ các commit cá nhân.
4. Không force push `main`, không viết lại lịch sử để che sai sót, không commit mật khẩu hoặc token.
5. Lưu link commit/PR/review, output Git và ảnh thật ngay khi thực hiện. Ảnh nằm trong `docs/images/`, output bổ sung nằm trong `docs/evidence/`.
6. Mỗi người trực tiếp đóng góp vào `docs/REPORT.md`; ghi rõ công việc đã làm và minh chứng.
7. Giao diện chỉ cần đơn giản, đọc được và các liên kết hoạt động; ưu tiên hoàn thành các yêu cầu Git.

## Tài liệu và liên kết

- [GitHub repository](https://github.com/nghiep2405/HOMEWORK-TDTT-GIT)
- [Báo cáo và minh chứng](docs/REPORT.md)
- [Changelog](CHANGELOG.md)
- [Lịch sử commit trên main](https://github.com/nghiep2405/HOMEWORK-TDTT-GIT/commits/main/)
- **GitHub Pages:** chưa triển khai; bổ sung URL đã kiểm tra khi hoàn thành Task 6.
- **Release `v1.0.0`:** chưa tạo; thực hiện sau khi kiểm tra sản phẩm và tài liệu.

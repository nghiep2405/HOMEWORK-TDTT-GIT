# Báo cáo Homework 07 — Git & GitHub

**Dự án:** StudyHub — Cẩm nang Tư duy tính toán và Python cơ bản.

**Lần khởi tạo báo cáo:** 26/11/2026.

**Trạng thái:** Khung báo cáo tại bước N02; chưa phải báo cáo hoàn thành dự án.

Chỉ ghi hoàn thành khi đã thực hiện và có minh chứng thật. Các mã P01–P15 là mã kế hoạch, không phải số PR GitHub thực tế. Bổ sung URL/SHA thật khi phát sinh; không tạo link giả cho kết quả chưa có.

## 1. Project Overview

### 1.1. Mô tả

Nhóm phát triển website HTML tĩnh gồm 6 trang ngắn: trang chủ, lộ trình học, Python cơ bản, bài tập, tài nguyên và giới thiệu nhóm. Website là sản phẩm để thực hành Git/GitHub; không yêu cầu backend, database hoặc chức năng ứng dụng phức tạp.

Trọng tâm gồm lịch sử commit, feature branches, Pull Requests, review, merge conflict, revert, tag và GitHub Pages. Tại N02 mới chuẩn bị các file tài liệu và cấu hình nền; mã website sẽ được phát triển ở các nhánh tính năng.

### 1.2. Thành viên

Nhóm 5 người đã được phép tham gia theo thông tin nhóm trưởng cung cấp.

| Thành viên | MSSV | GitHub |
|---|---|---|
| Nguyễn An Nghiệp | 23127234 | [nghiep2405](https://github.com/nghiep2405) |
| Lê Vĩnh Trọng | 25127247 | [levinhtrong2605-blue](https://github.com/levinhtrong2605-blue) |
| Nguyễn Thiên Vũ | 25127557 | [nguyenthienvu9565](https://github.com/nguyenthienvu9565) |
| Nguyễn Trọng Trực | 25127535 | [nguyentrongtruc22-ship-it](https://github.com/nguyentrongtruc22-ship-it) |
| Lê Đặng Nhựt Anh | 25127264 | [ldnanh2517](https://github.com/ldnanh2517) |

### 1.3. Liên kết

- [Repository](https://github.com/nghiep2405/HOMEWORK-TDTT-GIT)
- [README](../README.md)
- [Changelog](../CHANGELOG.md)
- [Lịch sử commit](https://github.com/nghiep2405/HOMEWORK-TDTT-GIT/commits/main/)
- **GitHub Pages:** chưa triển khai; bổ sung URL hoạt động sau Task 6.
- **Tag `v1.0.0`:** chưa tạo; bổ sung URL và SHA khi phát hành.

## 2. Team Contributions

Phân biệt công việc đã thực hiện với phân công sẽ làm. Mỗi thành viên tự bổ sung phần của mình và commit báo cáo bằng identity riêng; Nghiệp tổng hợp sau đó.

| Member | Assigned Tasks | Contributions | Evidence |
|---|---|---|---|
| Nguyễn An Nghiệp | Task 1 + 2: nền tảng/trang chủ; Task 3: PR/review; điều phối Task 4/5; Task 6; Task 7 | N02: chuẩn bị README, cấu hình Git, changelog, khung REPORT và nơi lưu minh chứng. Các phần khác chờ thực hiện | File trong bootstrap; đối chiếu lịch sử commit. Bổ sung SHA, PR và review khi có |
| Lê Vĩnh Trọng | Task 1 + 2: roadmap; Task 3: PR/review; Task 4: nhánh A; Task 7 | Chưa ghi nhận trong bản khởi tạo; thành viên tự cập nhật | Chờ commit/PR/review và nội dung báo cáo |
| Nguyễn Thiên Vũ | Task 1 + 2: Python; Task 3: PR/review; Task 4: nhánh B và xử lý; Task 7 | Chưa ghi nhận trong bản khởi tạo; thành viên tự cập nhật | Chờ commit/PR/review, bằng chứng conflict |
| Nguyễn Trọng Trực | Task 1 + 2: bài tập; Task 3: PR/review; Task 5: commit lỗi; Task 7 | Chưa ghi nhận trong bản khởi tạo; thành viên tự cập nhật | Chờ commit/PR/review và SHA commit lỗi |
| Lê Đặng Nhựt Anh | Task 1 + 2: tài nguyên/giới thiệu; Task 3: PR/review; Task 5: revert; Task 7 | Chưa ghi nhận trong bản khởi tạo; thành viên tự cập nhật | Chờ commit/PR/review, SHA revert và kết quả kiểm tra |

### 2.1. Nguyễn An Nghiệp — 23127234

- **Đã chuẩn bị tại N02:** bộ file tài liệu/cấu hình nền và khung báo cáo này.
- **Cần bổ sung:** output Git cá nhân; 3 commit trên `feature/site-foundation`; PR nền tảng; các review; minh chứng release/deployment; commit báo cáo cá nhân sau triển khai.
- **Trạng thái:** chưa hoàn thành toàn bộ nhiệm vụ cá nhân; bootstrap không thay cho 3 commit phát triển theo kế hoạch.

### 2.2. Lê Vĩnh Trọng — 25127247

- **Công việc đã làm:** chờ thành viên tự cập nhật.
- **Minh chứng cần bổ sung:** output Git; 3 commit roadmap; PR và review; commit conflict A; đóng góp báo cáo.

### 2.3. Nguyễn Thiên Vũ — 25127557

- **Công việc đã làm:** chờ thành viên tự cập nhật.
- **Minh chứng cần bổ sung:** output Git; 3 commit Python; PR và review; SHA nền/A/B, ảnh trước/sau xử lý conflict, merge commit; đóng góp báo cáo.

### 2.4. Nguyễn Trọng Trực — 25127535

- **Công việc đã làm:** chờ thành viên tự cập nhật.
- **Minh chứng cần bổ sung:** output Git; 3 commit bài tập; PR và review; SHA commit navigation lỗi, kết quả sau revert; đóng góp báo cáo.

### 2.5. Lê Đặng Nhựt Anh — 25127264

- **Công việc đã làm:** chờ thành viên tự cập nhật.
- **Minh chứng cần bổ sung:** output Git; 3 commit tài nguyên/giới thiệu; PR và review; SHA revert; kiểm tra các trang; đóng góp báo cáo.

## 3. Implementation and Evidence

Mỗi task được cập nhật theo ba mục **Work completed**, **Evidence**, **Result**. Task 1 và Task 2 dùng chung quá trình làm feature branch và bộ 3 commit cá nhân; báo cáo dẫn lại cùng minh chứng, không tính thành hai bộ commit.

### 3.1. Task 1 — Setting Up the Repository and Managing Commits

**Work completed**

- Repo nhóm: `nghiep2405/HOMEWORK-TDTT-GIT`; nhóm trưởng thông báo đã tạo repo và gửi lời mời cho 4 thành viên. Việc chấp nhận lời mời cần kiểm tra khi bắt đầu cộng tác.
- N02: chuẩn bị `README.md`, `.gitignore`, `.gitattributes`, `.nojekyll`, `CHANGELOG.md` và khung `docs/REPORT.md`.
- Chuẩn bị thư mục ảnh và output; chưa có ảnh minh chứng thao tác tại bước bootstrap.

**Evidence**

- [README](../README.md), [.gitignore](../.gitignore), [.gitattributes](../.gitattributes), [.nojekyll](../.nojekyll), [CHANGELOG](../CHANGELOG.md).
- Đối chiếu bootstrap trong [lịch sử main](https://github.com/nghiep2405/HOMEWORK-TDTT-GIT/commits/main/); bổ sung SHA cụ thể khi cập nhật báo cáo tiếp theo.
- Output identity và các lệnh `add`, `commit`, `push`, `status`, `log`, `show`, `diff` của từng người sẽ được lưu trong `docs/evidence/git-TEN.txt` khi thực hành.

**Result**

- Đã có bộ khung tài liệu/cấu hình; Task 1 chưa hoàn thành toàn bộ.
- Chờ mỗi thành viên thực hành và có ít nhất 3 commit có ý nghĩa trong quá trình làm Task 2.

### 3.2. Task 2 — Working with Branches

**Work completed:** chưa thực hiện các feature branches trong bản bootstrap.

**Evidence:** từng người bổ sung output clone, branch thực tế và cùng 3 commit dùng cho Task 1. Phân công nhánh:

| Thành viên | Feature branch theo kế hoạch | Trạng thái minh chứng |
|---|---|---|
| Nghiệp | `feature/site-foundation` | Chờ thực hiện |
| Trọng | `feature/learning-roadmap` | Chờ thực hiện |
| Vũ | `feature/python-basics` | Chờ thực hiện |
| Trực | `feature/practice-exercises` | Chờ thực hiện |
| Nhựt Anh | `feature/resources-and-team` | Chờ thực hiện |

**Result:** chờ xác minh mỗi người đã clone, làm trên feature branch và push nhánh; nhóm có ít nhất 5 feature branches.

### 3.3. Task 3 — Collaborating with Pull Requests

**Work completed:** chưa có PR/review được ghi nhận trong bản bootstrap.

**Evidence:** bổ sung bảng URL PR thực tế, tác giả, người review và trạng thái merge. Không dùng mã PR trong kế hoạch làm số PR GitHub nếu chưa mở.

**Result:** chờ ít nhất 4 PR merged, ít nhất 3 PR có review; mỗi thành viên tham gia tạo hoặc review bằng tài khoản riêng. Kế hoạch nội bộ yêu cầu cả 5 người vừa tạo PR vừa review.

### 3.4. Task 4 — Resolving a Merge Conflict

**Work completed:** chưa thực hiện. Trọng và Vũ sẽ tạo hai nhánh `feature/update-title-a` và `feature/update-title-b` từ cùng commit, sửa khác nhau cùng heading trong `index.html`.

**Evidence:** chờ SHA nền, hai commit của hai tác giả, PR, output conflict, ảnh `conflict-before.png` và `conflict-after.png`, merge commit xử lý.

**Result:** chưa có kết quả; cập nhật sau khi conflict thực sự phát sinh và được giải quyết.

### 3.5. Task 5 — Reverting a Commit

**Work completed:** chưa thực hiện. Trực sẽ tạo commit thường làm sai một link navigation; Nhựt Anh xác định SHA và dùng `git revert`.

**Evidence:** chờ URL/SHA commit lỗi và revert commit, PR, output `git show`, kết quả kiểm tra link sau khôi phục.

**Result:** chưa có kết quả; phải giữ cả hai commit trong lịch sử và kiểm tra website hoạt động lại.

### 3.6. Task 6 — Preparing a Release and Deploying the Website

**Work completed:** chưa phát hành, chưa tạo tag, chưa triển khai Pages. `.nojekyll` chỉ là file chuẩn bị, không chứng minh đã deploy.

**Evidence:** chờ README/changelog cuối, tag `v1.0.0` trên remote, SHA bản phát hành, deployment thành công và URL website đã kiểm tra. Nghiệp bổ sung ảnh homepage và deployment khi có kết quả thật.

**Result:** chưa hoàn thành. URL Pages chỉ được ghi là hoạt động sau khi triển khai và kiểm tra.

### 3.7. Task 7 — Writing the Project Report

**Work completed:** Nghiệp khởi tạo báo cáo Markdown này với ba phần chính, mục dành cho từng thành viên và Task 1–7; README có liên kết tới báo cáo.

**Evidence:** báo cáo này và [liên kết từ README](../README.md#tài-liệu-và-liên-kết). Lịch sử báo cáo sẽ thể hiện các lần cập nhật cá nhân khi nhóm triển khai.

**Result:** mới có khung báo cáo. Chờ mọi thành viên tự viết phần mình, bổ sung minh chứng và đủ ít nhất 3 report-related commits của nhóm; kế hoạch hướng tới ít nhất một commit báo cáo riêng của mỗi người sau triển khai.

### 3.8. Quy ước lưu minh chứng và kiểm tra cuối

- Ảnh thực tế nằm trong `docs/images/`; output và bảng kiểm nằm trong `docs/evidence/`.
- Nghiệp: output cá nhân, thống kê lịch sử, release; ảnh review PR mẫu, homepage và deployment.
- Vũ: ảnh conflict trước/sau và output xử lý. Trực/Nhựt Anh cung cấp minh chứng lỗi/revert.
- Các file `.gitkeep` chỉ giữ thư mục; không phải minh chứng hoàn thành thao tác.
- Khi file minh chứng thực sự được thêm, dùng đường dẫn tương đối từ report, ví dụ `images/conflict-before.png` hoặc `evidence/revert.txt`.
- Trước nộp: thay nội dung đang chờ bằng kết quả thực tế, kiểm tra ảnh/link và đóng góp cá nhân; không đánh dấu hoàn thành dựa trên phân công.

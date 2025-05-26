# SWR302-Group4-PhuNV
- Update day: 26/5/2025

**TÁC NHÂN (Actors) TRONG HỆ THỐNG**
| Tác nhân                        | Vai trò                                                                             |
| ------------------------------- | ----------------------------------------------------------------------------------- |
| **Người tìm việc (Job Seeker)** | Tìm và ứng tuyển công việc phù hợp. Quản lý hồ sơ cá nhân.                          |
| **Nhà tuyển dụng (Employer)**   | Đăng tuyển, quản lý tin tuyển dụng, tìm kiếm ứng viên.                              |
| **Quản trị viên (Admin)**       | Quản lý toàn bộ hệ thống: người dùng, bài đăng, kiểm duyệt nội dung, xử lý vi phạm. |

**DANH SÁCH USECASE**

| **ID** | **Use Case**              | **Actors**                         | **Mô tả**                                                          |
| ------ | ------------------------- | ---------------------------------- | ------------------------------------------------------------------ |
| 01     | View Homepage             | Guest, Job Seeker, Employer, Admin | Xem trang chủ và điều hướng tới các chức năng chính.               |
| 02     | Register Account          | Job Seeker, Employer               | Đăng ký tài khoản người dùng mới.                                  |
| 03     | Login                     | Job Seeker, Employer, Admin        | Đăng nhập vào hệ thống.                                            |
| 04     | Logout                    | Job Seeker, Employer, Admin        | Đăng xuất khỏi hệ thống.                                           |
| 05     | Search Jobs               | Job Seeker                         | Tìm kiếm việc làm theo từ khóa, danh mục, địa điểm.                |
| 06     | Filter Jobs               | Job Seeker                         | Lọc kết quả tìm kiếm theo mức lương, vị trí, thời gian đăng tin... |
| 07     | View Job Details          | Guest, Job Seeker                  | Xem thông tin chi tiết của một công việc cụ thể.                   |
| 08     | Apply for Job             | Job Seeker                         | Ứng tuyển vào một vị trí tuyển dụng.                               |
| 09     | View Applied Jobs         | Job Seeker                         | Xem danh sách các công việc đã ứng tuyển.                          |
| 10     | Save Job                  | Job Seeker                         | Lưu tin tuyển dụng yêu thích để xem sau.                           |
| 11     | Remove Saved Job          | Job Seeker                         | Gỡ bỏ tin đã lưu.                                                  |
| 12     | View Application Status   | Job Seeker                         | Xem trạng thái hồ sơ ứng tuyển.                                    |
| 13     | Post Job                  | Employer                           | Nhà tuyển dụng đăng tin tuyển dụng mới.                            |
| 14     | Edit Job Post             | Employer                           | Chỉnh sửa nội dung tin tuyển dụng đã đăng.                         |
| 15     | Delete Job Post           | Employer                           | Xoá tin tuyển dụng.                                                |
| 16     | Review Applications       | Employer                           | Xem danh sách ứng viên ứng tuyển.                                  |
| 17     | Accept/Reject Candidate   | Employer                           | Nhà tuyển dụng thay đổi trạng thái hồ sơ của ứng viên.             |
| 18     | View Employer Profile     | Guest, Job Seeker                  | Xem hồ sơ và thông tin về công ty tuyển dụng.                      |
| 19     | Update Personal Profile   | Job Seeker, Employer               | Cập nhật thông tin cá nhân hoặc doanh nghiệp.                      |
| 20     | Upload/Update Resume      | Job Seeker                         | Tải lên hoặc cập nhật CV.                                          |
| 21     | Forgot Password           | Job Seeker, Employer               | Quên mật khẩu và yêu cầu đặt lại.                                  |
| 22     | Approve Job Post          | Admin                              | Phê duyệt bài đăng tuyển dụng trước khi hiển thị.                  |
| 23     | Manage Users              | Admin                              | Quản lý người dùng (chặn, xoá, phân quyền...).                     |
| 24     | Generate System Reports   | Admin                              | Xuất báo cáo thống kê hoạt động hệ thống.                          |
| 25     | Send Notifications/Emails | System (Auto), Admin               | Gửi email xác nhận, thông báo ứng tuyển, từ chối...                |

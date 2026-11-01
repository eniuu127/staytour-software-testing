# STAYTOUR – HỆ THỐNG ĐẶT HOMESTAY VÀ TOUR DU LỊCH

**Software Testing Portfolio | Dự án học tập**

## 1. Giới thiệu dự án

StayTour là hệ thống hỗ trợ tìm kiếm, xem thông tin và đặt homestay hoặc tour du lịch. Các nghiệp vụ được ghi nhận trong bộ Test Case gồm tài khoản, tìm kiếm, đặt chỗ, thanh toán và đặt cọc, khuyến mãi, quản lý đơn đặt và chức năng quản trị.

Repository trình bày tài liệu **phân tích nghiệp vụ và thực hành kiểm thử phần mềm**, tập trung vào kiểm thử chức năng (Functional Testing) và kiểm thử bảo mật cơ bản (Basic Security Testing).

## 2. Phạm vi kiểm thử

- **Kiểm thử chức năng:** Tìm kiếm homestay/tour, đăng ký/đăng nhập, hồ sơ người dùng, danh sách yêu thích, đặt homestay và tour, thanh toán, khuyến mãi, hủy đơn, đánh giá và quản trị.
- **Kiểm thử bảo mật cơ bản:** HTTPS và cookie, bảo vệ mật khẩu, xác thực dữ liệu đầu vào, XSS, CSRF, phân quyền, tải tệp, giới hạn đăng nhập và xử lý giao dịch.

## 3. Kết quả thực thi Test Case

| Nhóm kiểm thử | Pass | Fail | Not Tested | Tổng |
|---|---:|---:|---:|---:|
| Functional Testing | 46 | 3 | 1 | 50 |
| Basic Security Testing | 7 | 3 | 0 | 10 |
| **Tổng** | **53** | **6** | **1** | **60** |

- **Tỷ lệ thực thi:** 59/60 = **98,3%**.
- **Tỷ lệ Pass trên số Test Case đã thực thi:** 53/59 = **89,8%**.

Kết quả được tổng hợp từ bảng Test Case. Các trường hợp Fail không đồng nghĩa với số lượng Bug Report độc lập; phạm vi kiểm thử bảo mật chỉ ở mức cơ bản.

## 4. Tài liệu kiểm thử

| Thư mục | Nội dung |
|---|---|
| [01-Test-Cases](./01-Test-Cases/) | Bộ Test Case kiểm thử chức năng và bảo mật cơ bản, có ghi nhận kết quả thực thi. |

**Xem nhanh:** [Test Cases (Excel)](./01-Test-Cases/StayTour_Test_Cases.xlsx)

Repository chỉ giới thiệu tài liệu hiện có; chưa bổ sung Test Plan, SRS hoặc báo cáo lỗi độc lập.

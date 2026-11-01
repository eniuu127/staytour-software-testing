# HỆ THỐNG ĐẶT HOMESTAY VÀ TOUR DU LỊCH – STAYTOUR

**Software Testing Portfolio | 08/2026 – 10/2026**

## 1. Giới thiệu dự án

StayTour là website hỗ trợ tìm kiếm, đặt homestay, đặt tour du lịch và thực hiện các nghiệp vụ thanh toán. Repository này lưu trữ tài liệu thiết kế và ghi nhận kết quả kiểm thử phần mềm của dự án. Mã nguồn ứng dụng được lưu trữ tại repository liên kết bên dưới.

- **Vai trò:** Kiểm thử phần mềm.
- **Công cụ:** Excel, Postman, Chrome DevTools.
- **Repository mã nguồn hệ thống được kiểm thử:** [NhungVu248/tmdtn02](https://github.com/NhungVu248/tmdtn02).

## 2. Công việc thực hiện

- Xây dựng các kịch bản kiểm thử dựa trên yêu cầu và luồng hoạt động của website.
- Kiểm thử các chức năng đăng ký, đăng nhập, tìm kiếm, đặt phòng, đặt tour và thanh toán.
- Sử dụng Postman để kiểm tra API và Chrome DevTools hỗ trợ kiểm tra hoạt động của website.
- Đối chiếu kết quả thực tế với kết quả mong đợi, ghi nhận lỗi và đánh giá kết quả kiểm thử.

Tài liệu được chia thành **Functional Test Case** và **Security Test Case** để theo dõi các trường hợp kiểm thử chức năng và bảo mật cơ bản.

## 3. Kết quả thực thi Test Case

| Nhóm kiểm thử | Pass | Fail | Not Tested | Tổng |
|---|---:|---:|---:|---:|
| Functional Testing | 46 | 3 | 1 | 50 |
| Basic Security Testing | 7 | 3 | 0 | 10 |
| **Tổng** | **53** | **6** | **1** | **60** |

- **Tỷ lệ thực thi:** 59/60 = **98,3%**.
- **Tỷ lệ Pass trên số Test Case đã thực thi:** 53/59 = **89,8%**.

Số liệu được tổng hợp từ bộ Test Case đã ghi nhận; trạng thái Fail không đồng nghĩa với số lượng Bug Report độc lập.

## 4. Tài liệu kiểm thử

| Thư mục | Nội dung |
|---|---|
| [01-Test-Cases](./01-Test-Cases/) | Bộ Test Case kiểm thử chức năng và bảo mật cơ bản, lưu bằng Excel và PDF. |

**Xem nhanh tài liệu:**

- [Test Cases (Excel)](./01-Test-Cases/CV_TestCase%20TMDT.xlsx)
- [Functional Test Cases (PDF)](./01-Test-Cases/Functional_TestCase.pdf)
- [Security Test Cases (PDF)](./01-Test-Cases/Security_Test%20Case%20.pdf)

# TEST CASES – STAYTOUR

## 1. Giới thiệu

Thư mục `01-Test-Cases` lưu trữ bộ trường hợp kiểm thử cho **Hệ thống đặt Homestay và Tour du lịch – StayTour** (08/2026 – 10/2026).

Các kịch bản được xây dựng dựa trên yêu cầu và luồng hoạt động của website, tập trung vào kiểm thử chức năng và bảo mật cơ bản. Kết quả thực tế được đối chiếu với kết quả mong đợi để đánh giá trạng thái kiểm thử.

## 2. Phạm vi kiểm thử

| Nhóm kiểm thử | Nội dung chính | Số Test Case |
|---|---|---:|
| Functional Testing | Đăng ký, đăng nhập, tìm kiếm, đặt homestay, đặt tour, thanh toán và các nghiệp vụ liên quan | 50 |
| Basic Security Testing | Kiểm tra các tình huống bảo mật cơ bản của website | 10 |
| **Tổng** | | **60** |

**Công cụ:** Excel để quản lý Test Case; Postman để kiểm tra API; Chrome DevTools để hỗ trợ kiểm tra hoạt động của website.

## 3. Kết quả thực thi

| Nhóm kiểm thử | Pass | Fail | Not Tested | Tổng |
|---|---:|---:|---:|---:|
| Functional Testing | 46 | 3 | 1 | 50 |
| Basic Security Testing | 7 | 3 | 0 | 10 |
| **Tổng** | **53** | **6** | **1** | **60** |

- **Tỷ lệ thực thi:** 59/60 = **98,3%**.
- **Tỷ lệ Pass trên các trường hợp đã thực thi:** 53/59 = **89,8%**.

Các trường hợp kiểm thử bảo mật thuộc phạm vi cơ bản; bảng trạng thái không thay thế cho báo cáo lỗi độc lập.

## 4. Danh sách tài liệu

| File | Nội dung |
|---|---|
| [CV_TestCase TMDT.xlsx](./CV_TestCase%20TMDT.xlsx) | Bộ Test Case dạng Excel và kết quả kiểm thử |
| [Functional_TestCase.pdf](./Functional_TestCase.pdf) | Tài liệu Test Case kiểm thử chức năng ở định dạng PDF |
| [Security_Test Case .pdf](./Security_Test%20Case%20.pdf) | Tài liệu Test Case kiểm thử bảo mật cơ bản ở định dạng PDF |

[Quay lại README chính](../README.md)

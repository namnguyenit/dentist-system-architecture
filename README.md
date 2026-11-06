# 🦷 Dentist Management System — Architecture & ERD Design

Kho lưu trữ tài liệu thiết kế kiến trúc hệ thống và mô hình thực thể mối quan hệ (ERD) cho **Hệ thống Quản lý Phòng khám Nha khoa (Dentist Management System)**.

## 📁 Tài liệu thiết kế
- `erd.xml`: Sơ đồ thiết kế Cơ sở Dữ liệu ERD (Entity Relationship Diagram) định dạng Draw.io / XML.
  - Quản lý Hồ sơ Bệnh nhân (Patients)
  - Quản lý Lịch hẹn & Bác sĩ (Appointments, Dentists, Schedules)
  - Quản lý Dịch vụ điều trị & Đơn thuốc (Treatments, Prescriptions)
  - Quản lý Hoá đơn & Thanh toán (Invoices, Payments)
- `kientruc.xml`: Sơ đồ kiến trúc tổng thể hệ thống (System Architecture Diagram), bao gồm tầng giao diện người dùng (Client/Web), tầng xử lý nghiệp vụ (Backend API Services) và tầng dữ liệu (Database).

## 🛠️ Hướng dẫn mở và chỉnh sửa
Các file thiết kế ở định dạng XML tương thích trực tiếp với [Draw.io (diagrams.net)](https://app.diagrams.net/):
1. Truy cập `https://app.diagrams.net/`
2. Chọn **File** ➡️ **Open From** ➡️ **Device** (hoặc kéo thả file `erd.xml` / `kientruc.xml` vào trình duyệt).

## 👨‍💻 Tác giả
- [Cao Đức Trung (@namnguyenit)](https://github.com/namnguyenit)

# Demo - Quản lý công ty, kho và hàng lỗi

## Tổng quan

Module này triển khai các tính năng:
- Kiểm soát công ty con mua hàng từ nhà cung cấp ngoài
- Quản lý hàng lỗi với 3 loại: hàng bỏ, hàng sửa chữa, hàng trả
- Tự động chọn kho gần nhất dựa trên GPS

## Tính năng

- **Kiểm soát mua hàng:** Ngăn công ty con mua hàng từ nhà cung cấp ngoài hệ thống.
- **Quản lý hàng lỗi:** Phân loại hàng lỗi thành ba loại: bỏ, sửa chữa, trả lại.
- **Chọn kho gần nhất:** Tự động xác định và chọn kho gần nhất dựa trên vị trí GPS.

## Cài đặt

1. Tải module về thư mục `custom_vendor_odoo17`.
2. Đảm bảo các module phụ thuộc đã được cài đặt: `base`, `purchase`, `stock`, `sale_management`, `contacts`.
3. Cài đặt module thông qua Apps trong Odoo.

## Cấu hình

- Truy cập các menu liên quan trong Inventory để cấu hình và sử dụng các tính năng của module.
- Phân quyền truy cập thông qua các rule bảo mật đã được định nghĩa.

## Dữ liệu

Module bao gồm các file cấu hình:
- `security/ir.model.access.csv`
- `security/security_rules.xml`
- `views/res_partner_views.xml`
- `views/stock_scrap_views.xml`
- `views/sale_order_views.xml`
- `views/stock_menu.xml`
- `views/warehouse_finder_views.xml`

## Thông tin

- **Phiên bản:** 1.0
- **Tác giả:** Nhóm 1
- **Danh mục:** Inventory/Inventory

## License

This module is licensed under the AGPL-3.0 or later (http://www.gnu.org/licenses/agpl).

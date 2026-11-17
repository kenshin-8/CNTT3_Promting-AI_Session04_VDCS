# Kết quả phản hồi của AI

## 1. Kết quả tổng hợp

| Tiêu chí | Kết quả |
|---|---:|
| Tổng số đơn hàng | 3 |
| Đơn đủ điều kiện xác nhận | 1 |
| Đơn chờ bổ sung hàng | 1 |
| Đơn không hợp lệ | 1 |
| Tổng tiền xác nhận | 200.000 |

## 2. Chi tiết từng đơn hàng

### Đơn DH001 – READY
- Số lượng: 2.
- Đơn giá: 100.000.
- Tồn kho: 5.
- Thành tiền: 2 × 100.000 = **200.000**.
- Kết quả: Đủ điều kiện xác nhận.

### Đơn DH002 – PENDING
- Số lượng: 3.
- Đơn giá: 50.000.
- Tồn kho: 2.
- Thành tiền dự kiến: 150.000.
- Kết quả: Không đủ tồn kho, cần bổ sung hàng.

### Đơn DH003 – INVALID
- Số lượng nhập: `hai`.
- Lỗi: Số lượng không đúng định dạng số nguyên.
- Kết quả: Không thể xử lý, cần nhập lại dữ liệu.

## 3. Cảnh báo

- DH002: Số lượng đặt mua vượt quá tồn kho.
- DH003: Số lượng nhập sai định dạng.

## 4. Đề xuất xử lý

- Xác nhận đơn hàng DH001.
- Bổ sung tồn kho sản phẩm SP02 trước khi xử lý DH002.
- Yêu cầu nhập lại số lượng cho đơn DH003.

## 5. Kết luận

Hệ thống đã tiếp nhận và phân loại thành công 3 đơn hàng. Có 1 đơn đủ điều kiện xác nhận, 1 đơn chờ bổ sung hàng và 1 đơn không hợp lệ. Dữ liệu lỗi được ghi nhận riêng mà không ảnh hưởng đến việc xử lý các đơn hàng còn lại.

---

*Ghi chú: Đây là kết quả phản hồi mẫu được mô phỏng theo prompt và dữ liệu thử nghiệm, không phải log từ một lần gọi API AI thực tế.*

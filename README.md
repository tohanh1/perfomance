# Perfomance Free

Phiên bản miễn phí, độc lập với **HANT** hoàn chỉnh. GitHub repository được đặt chính xác theo yêu cầu: `tohanh1/perfomance`.

## Tính năng
- Dashboard Tổng quan COF, NON, tiến độ theo target, NTU CIC OK và số hồ sơ đạt mindue.
- Nhập, sửa, xóa khoản thu COF/NON; phân loại Thu kỳ, Thu quá hạn, Thanh lý, Ngoại lệ.
- Theo dõi hồ sơ NTU: số hợp đồng, tên khách, POS hồ sơ **gốc**, mindue, tiền thu và trạng thái đạt mindue.
- Cài đặt Target COF, NON, NTU, NTU CIC OK và hồ sơ cá nhân (mã nhân viên, họ tên, Team).
- Giao diện vàng champagne, mobile-first, thu gọn khoản thu/hồ sơ, tránh zoom khi chạm hai lần.
- Lưu dữ liệu trên thiết bị, hoàn tác/làm lại, xuất/nhập JSON, PWA chạy ngoại tuyến sau khi đã tải tài nguyên.

## Giới hạn của bản Free
- Không có bất kỳ kết nối hoặc đồng bộ Google Sheets; không có URL/token đồng bộ, không có Apps Script backend.
- Không có quy đổi khoản thu sang POS, không có hệ số POS quy đổi, không có màn hình tính bonus và thu nhập dự kiến vốn phụ thuộc POS quy đổi.
- **POS hồ sơ NTU (gốc)** vẫn được lưu để tham chiếu hồ sơ; đây là số liệu hợp đồng, không phải POS quy đổi.
- Không đồng bộ giữa thiết bị; dữ liệu chỉ nằm trong localStorage của trình duyệt đang sử dụng.
- Không tự động nhập bản sao lưu của HANT đầy đủ; định dạng JSON bản Free có `version:1` và các trường riêng.
- Không đưa dữ liệu khách hàng nhạy cảm lên máy dùng chung.

## Chạy
Mở `index.html` từ hosting HTTPS hoặc bật GitHub Pages: Settings → Pages → Deploy from a branch → `main` → `/(root)`. GitHub Pages phải được bật trước khi địa chỉ website hoạt động.

## Đảm bảo
Không có thay đổi nào đối với repository `tohanh1/Hant`. Bản Free không thực hiện tính bonus hay thuế để tránh công bố kết quả thiếu căn cứ sau khi bỏ POS quy đổi.

SỔ PHÁT QUYẾT ĐỊNH NVQS - GITHUB PAGES V0.1.1 ĐƠN GIẢN
========================================================

Bản này tối giản giao diện cho Thôn đội trưởng:
- Mở 1 đường link cố định trên điện thoại.
- Nạp file JSON danh sách một lần.
- Màn hình chỉ tập trung vào: Tổng / Đã phát / Còn lại, tìm tên và chạm vào người để đổi CHƯA PHÁT <-> ĐÃ PHÁT.
- Tiến độ tự lưu trên điện thoại, hôm sau mở lại vẫn còn.
- Nút lớn GỬI KẾT QUẢ CHO BCHQS luôn nằm dưới màn hình.
- Công cụ tải dự phòng/khôi phục được thu gọn để giao diện đỡ rối.
- Danh sách công dân KHÔNG tải lên GitHub; chỉ lưu cục bộ trên điện thoại.
- PWA/offline: sau lần mở đầu có thể tiếp tục dùng khi mạng chập chờn.

ĐƯA LÊN GITHUB PAGES
1. Upload toàn bộ file trong thư mục này vào repository GitHub Pages hiện tại, chép đè các file cũ.
2. Chờ GitHub Pages cập nhật vài phút.
3. Trên điện thoại mở lại trang; nếu vẫn thấy giao diện cũ, đóng trang rồi mở lại hoặc xóa cache trang một lần.

SỬ DỤNG
1. Ban CHQS xuất file JSON theo từng thôn từ NVQS máy tính và gửi qua Zalo.
2. Thôn đội trưởng mở link Web -> CHỌN FILE DANH SÁCH -> chọn JSON.
3. Đi phát: chạm vào dòng tên để đánh dấu ĐÃ PHÁT; chạm lại để sửa về CHƯA PHÁT.
4. Cuối ngày/hôm sau mở lại link là tiếp tục từ trạng thái đã lưu.
5. Bấm GỬI KẾT QUẢ CHO BCHQS để gửi file JSON về qua Zalo.
6. Ban CHQS nhập file vào NVQS bằng chức năng Nhập kết quả từ Zalo/Web.

LƯU Ý
- Dùng cùng một trình duyệt/điện thoại trong suốt đợt phát.
- Không dùng chế độ ẩn danh và không xóa dữ liệu trang.
- Không upload file danh sách JSON công dân lên repository GitHub.

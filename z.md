🧍 Người dùng và phân quyền
users: Lưu thông tin cơ bản của người dùng (bệnh nhân, nhân viên…).

user_email, user_phones: Quản lý thông tin liên lạc (email, số điện thoại).

roles, permissions, role_permissions, user_roles: Quản lý hệ thống phân quyền người dùng theo vai trò (ví dụ: bác sĩ, lễ tân, quản lý...).

🧑‍⚕️ Nhân viên & bệnh nhân
employees: Thông tin chi tiết về nhân viên (chức danh, chuyên môn...).

employee_branches: Quan hệ nhiều–nhiều giữa nhân viên và các chi nhánh làm việc.

patients: Thông tin y tế và liên lạc khẩn cấp của bệnh nhân.

patient_teeth: Quản lý tình trạng các răng của từng bệnh nhân.

🏢 Cơ sở khám chữa bệnh
branches: Danh sách các cơ sở (chi nhánh) thuộc thương hiệu nha khoa.

rooms: Danh sách các phòng khám, mỗi phòng thuộc một chi nhánh cụ thể.

📋 Dịch vụ & gói dịch vụ
service_categories: Nhóm các loại dịch vụ nha khoa (ví dụ: chỉnh nha, làm răng sứ...).

services: Danh sách các dịch vụ nha khoa cụ thể.

packages: Gói dịch vụ bao gồm nhiều dịch vụ con.

package_services: Liên kết giữa gói và các dịch vụ thành phần.

🎟️ Khuyến mãi / giảm giá
discount_codes: Quản lý mã giảm giá, phần trăm hoặc số tiền cố định.

service_discounts, package_discounts: Gắn mã giảm giá vào dịch vụ hoặc gói.

📆 Lịch hẹn & điều trị
appointments: Quản lý lịch hẹn khám giữa bệnh nhân và phòng khám.

appointment_statuses: Trạng thái của lịch hẹn (đã đặt, hoàn tất, hủy...).

appointment_staff: Gắn nhân viên tham gia vào từng lịch hẹn.

appointment_services, appointment_packages: Dịch vụ hoặc gói đã thực hiện trong một lịch hẹn.

treatment_records: Ghi chú điều trị và lịch hẹn theo dõi tiếp theo.

medical_images: Ảnh chụp răng hoặc phim X-quang liên quan đến điều trị.

💊 Kê đơn & xét nghiệm
prescriptions: Thông tin toa thuốc kê trong lịch hẹn.

prescription_items: Danh sách thuốc trong một toa.

lab_tests: Danh mục các xét nghiệm có thể thực hiện.

appointment_lab_tests: Xét nghiệm gắn với từng lịch hẹn.

💵 Thanh toán & hoàn tiền
invoices: Hóa đơn thanh toán của từng lịch hẹn.

invoice_statuses: Trạng thái hóa đơn (đã thanh toán, chưa thanh toán...).

invoice_items: Chi tiết các khoản thu trong một hóa đơn.

payments: Ghi nhận thanh toán cho hóa đơn.

credit_notes: Ghi nhận hoàn tiền (ghi chú tín dụng) cho hóa đơn.

📣 Thông báo
notification_history: Lưu lịch sử gửi thông báo (qua email, SMS...) cho bệnh nhân.

notification_statuses: Trạng thái gửi thông báo (thành công, thất bại...).

🧰 Kho vật tư
inventory_items: Danh sách vật tư y tế, thuốc, dụng cụ.

inventory_movements: Ghi lại các thay đổi trong kho (nhập, xuất, sử dụng...).
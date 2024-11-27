# Phân Tích Dữ Liệu và Tối Ưu Hóa Chiến Lược Quản Trị Quan Hệ Khách Hàng

## Mô tả dự án
Dự án này nhằm phân tích dữ liệu khách hàng của công ty Bitelco, một nhà cung cấp dịch vụ viễn thông hàng đầu tại Argentina. Mục tiêu là hiểu rõ hơn về hành vi khách hàng, tỷ lệ rời bỏ, và giá trị vòng đời khách hàng (CLV) để đưa ra các chiến lược tối ưu hóa quản trị quan hệ khách hàng.

Dự án bao gồm hai thành phần chính:
1. **Phân tích chi tiết (file Word)**: Trình bày các phát hiện và giải pháp đề xuất dựa trên phân tích dữ liệu.
2. **Dashboard Power BI**: Trực quan hóa dữ liệu và cung cấp cái nhìn tổng quan về tỷ lệ rời bỏ, CLV, và các yếu tố liên quan.

---

## Nội dung
- **`analysis/CRM-Report.docx`**: Báo cáo chi tiết về phân tích dữ liệu và giải pháp tối ưu hóa.
- **`dashboard/CRM-Dashboard.pbix`**: Dashboard trực quan hóa trên Power BI.

---

## Hướng dẫn sử dụng

### 1. Báo cáo phân tích
- File báo cáo nằm trong thư mục `analysis/CRM-Report.docx`.
- Mở file bằng **Microsoft Word** hoặc các trình đọc file `.docx`.

### 2. Dashboard Power BI
- File dashboard nằm trong thư mục `dashboard/CRM-Dashboard.pbix`.
- Mở bằng **Power BI Desktop**
- Nếu cần, kết nối lại với nguồn dữ liệu gốc để cập nhật nội dung.

---

## Dữ liệu sử dụng
- Tập dữ liệu chứa 7,043 bản ghi khách hàng với 21 thuộc tính, bao gồm:
  - **Thông tin cá nhân**: Mã khách hàng, giới tính, tuổi, người phụ thuộc.
  - **Dịch vụ sử dụng**: Internet, bảo mật, truyền hình, điện thoại.
  - **Hợp đồng và thanh toán**: Loại hợp đồng, phương thức thanh toán, chi phí hàng tháng, tổng chi phí.
  - **Tỷ lệ rời bỏ (Churn)**: Tình trạng khách hàng có tiếp tục sử dụng dịch vụ hay không.

---

## Mục tiêu phân tích
1. Xây dựng chân dung khách hàng của Bitelco.
2. Phân tích nguyên nhân dẫn đến tỷ lệ rời bỏ cao (26.54%).
3. Tối ưu hóa chiến lược giữ chân khách hàng và tăng giá trị CLV.

---

## Kết quả chính
1. **Tỷ lệ rời bỏ (Churn rate)**:
   - 74.53% khách hàng rời bỏ thuộc nhóm trẻ tuổi (<50 tuổi).
   - Dịch vụ Fiber optic có tỷ lệ rời bỏ cao nhất (42%).

2. **Giá trị vòng đời khách hàng (CLV)**:
   - Tổng CLV của khách hàng đang hoạt động là **13.19 triệu đô**.
   - Tổng CLV của khách hàng đã rời bỏ chiếm **17.83%** (2.86 triệu đô).

3. **Nguyên nhân rời bỏ**:
   - Chi phí cao, đặc biệt với hợp đồng hàng tháng.
   - Chất lượng dịch vụ không đồng đều.

4. **Giải pháp đề xuất**:
   - Tăng ưu đãi cho hợp đồng dài hạn.
   - Cải thiện dịch vụ và trải nghiệm khách hàng.
   - Phát triển các gói dịch vụ linh hoạt và cá nhân hóa.

---

## Cấu trúc thư mục
project-name/ ├── analysis/ # Chứa file báo cáo phân tích │ └── CRM-Report.docx # Báo cáo chi tiết ├── dashboard/ # Chứa file Power BI │ └── CRM-Dashboard.pbix # Dashboard trực quan hóa ├── README.md # Mô tả dự án └── .gitignore # Loại trừ file không cần thiết

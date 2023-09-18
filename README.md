# Dự án Shopee Clone ReactJS Typescript

## Chức năng trong dự án
- Authentication (Quản lý bằng JWT):
     + Đăng ký
     + Đăng nhập
     + Đăng xuất
- Trang danh sách sản phẩm:
     + Pagination (Phân trang sản phẩm)
     + Sort (sắp xếp theo thuộc tính của sản phẩm)
     + Filter (lọc theo thuộc tính của sản phẩm)
     + Search (tìm kiếm sản phẩm)
- Trang chi tiết sản phẩm:
     + Hiển thị thông tin chi tiết (Hình ảnh sản phẩm, Tên sản phẩm, Giá bán, Số lượng sản phẩm, Mô tả sản phẩm)
     + Có chức năng mua hàng
- Giỏ hàng:
     + Quản lý đơn hàng: Thêm, sửa, xóa sản phẩm
     + Mua hàng
- Quản lý Profile khách hàng:
     + Update thông tin cá nhân
     + Upload Avatar
     + Đổi mật khẩu
     + Xem tình trạng đơn hàng

## Công nghệ sử dụng
- Build tool: Vite
- UI / CSS Library: Tailwindcss
- Form Management: React Hook Form
- State Management: TanStack Query cho async state và React Context cho state thường
- Fetching Data: Axios
- Router: React Router
- Hỗ trợ đa ngôn ngữ với react.i18next
- Hỗ trợ SEO với React Helmet
- Mô hình hóa các component với story book
- Unit Test

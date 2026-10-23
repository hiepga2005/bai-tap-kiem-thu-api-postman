# Bài tập Kiểm thử API bằng Postman

## Thông tin sinh viên
* **Họ và tên:** [Nguyễn Văn Hiệp]
* **Mã sinh viên:** [23010859]

---

## Danh sách các API đã thực hiện (Collection)

Bộ sưu tập (Collection) gồm 5 request kiểm thử các phương thức HTTP cơ bản trên API mẫu (`JSONPlaceholder`):

1. **GET - Danh sách bài viết**
   * **Phương thức:** `GET`
   * **URL:** `https://jsonplaceholder.typicode.com/posts`
   * **Mô tả:** Lấy danh sách toàn bộ các bài viết.

2. **GET - Chi tiết bài viết 1**
   * **Phương thức:** `GET`
   * **URL:** `https://jsonplaceholder.typicode.com/posts/1`
   * **Mô tả:** Lấy thông tin chi tiết của bài viết có `id = 1`.

3. **POST - Tạo bài viết thư**
   * **Phương thức:** `POST`
   * **URL:** `https://jsonplaceholder.typicode.com/posts`
   * **Mô tả:** Gửi dữ liệu để tạo mới một bài viết.

4. **PATCH - Cập nhật tiêu đề bài viết 1**
   * **Phương thức:** `PATCH`
   * **URL:** `https://jsonplaceholder.typicode.com/posts/1`
   * **Mô tả:** Cập nhật một phần nội dung (tiêu đề) của bài viết `id = 1`.

5. **DELETE - Xóa bài viết 1 (mo phong)**
   * **Phương thức:** `DELETE`
   * **URL:** `https://jsonplaceholder.typicode.com/posts/1`
   * **Mô tả:** Mô phỏng yêu cầu xóa bài viết có `id = 1`.

---

## Minh chứng kết quả (Screenshots)

Dưới đây là hình ảnh thực tế khi thực thi các request trong Postman:

* **1. GET - Danh sách bài viết:**  
  ![GET Danh sách](screenshots/image_1.png)

* **2. GET - Chi tiết bài viết 1:**  
  ![GET Chi tiết](screenshots/image_2.png)

* **3. POST - Tạo bài viết thư:**  
  ![POST Tạo mới](screenshots/image_3.png)

* **4. PATCH - Cập nhật tiêu đề bài viết 1:**  
  ![PATCH Cập nhật](screenshots/image_4.png)

* **5. DELETE - Xóa bài viết 1:**  
  ![DELETE Xóa](screenshots/image_5.png)

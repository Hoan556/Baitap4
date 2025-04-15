# Baitap4
bai tap 4: (sql server)
- yêu cầu bài toán:
 - Tạo csdl cho hệ thống TKB (đã nghe giảng, đã xem cách làm)
 - Nguồn dữ liệu: TMS.tnut.edu.vn
 - Tạo các bảng tuỳ ý (3nf)
 - Tạo được query truy vấn ra thông tin gồm 4 cột: họ tên gv, môn dạy, giờ vào lớp, giờ ra.
   trả lời câu hỏi: trong khoảng thời gian từ datetime1 tới datetime2 thì có những gv nào đang bận giảng dạy.
- các bước thực hiện:
  1. Tạo github repo mới: đặt tên tuỳ ý (có liên quan đến bài tập này)
  2. tạo file readme.md, edit online nó:
   paste những ảnh chụp màn hình
   gõ text mô tả cho ảnh đó
- Gợi ý:
  sử dung tms => dữ liệu thô => tiền xử lý => dữ liệu như ý (3nf)
  tạo các bảng với struct phù hợp
  insert nhiều rows từ excel vào cửa sổ edit dữ liệu 1 table (quan sát thì sẽ làm đc)
  # Tạo Bảng
  ## Bảng GV
 ![Annotation 2025-04-15 171252](https://github.com/user-attachments/assets/2d8a9140-2b4d-4a6b-bdf9-685e7b72a7df)

  ## Bảng Null
  ![Annotation 2025-04-15 171125](https://github.com/user-attachments/assets/b0f10ba5-c004-4074-8c70-9e05aca697c0)

  ## Bảng Lớp
  ![Annotation 2025-04-15 171316](https://github.com/user-attachments/assets/47d13e96-bbd0-4841-92fa-b7523ba9109b)

  ## Bảng Null
  ![Annotation 2025-04-15 171142](https://github.com/user-attachments/assets/cd0408da-f87a-4832-b290-fc78ca40d3c3)

  ## Bảng Môn học
  ![Annotation 2025-04-15 171335](https://github.com/user-attachments/assets/7618b965-8587-4c32-8fd6-972b2aa7a83f)

  ## Bảng Null
  ![Annotation 2025-04-15 171202](https://github.com/user-attachments/assets/5e9e5fb1-6542-4b37-94cc-34b5816824de)

  ## Bảng TKB
  ![Annotation 2025-04-15 171359](https://github.com/user-attachments/assets/955d0ab6-9d69-47b1-b052-6bbd98de0fad)

  ## Bảng Null
  ![Annotation 2025-04-15 171054](https://github.com/user-attachments/assets/c47dbb56-5fc1-4ff5-a81c-066ad2a75201)

  ## Tạo được query truy vấn ra thông tin gồm 4 cột: họ tên gv, môn dạy, giờ vào lớp, giờ ra.
  ## trả lời câu hỏi: trong khoảng thời gian từ datetime1 tới datetime2 thì có những gv nào đang bận giảng dạy.
  ![Annotation 2025-04-15 170938](https://github.com/user-attachments/assets/19abfe8f-3ebc-4667-87d6-4ed532f8a36f)

  ![Annotation 2025-04-15 171014](https://github.com/user-attachments/assets/2f5fa1d9-4de6-4a26-a677-05446a7d6ec6)

  ![Annotation 2025-04-15 171037](https://github.com/user-attachments/assets/6273a75a-dcb9-45ad-986a-0d20a3297b21)


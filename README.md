# Dự án Phân tích Di chuyển và Vẽ Heatmap Vận động viên Cầu lông

Dự án này tập trung vào việc áp dụng các kỹ thuật xử lý ảnh và học máy để phân tích video thi đấu cầu lông. Mục tiêu chính là theo dõi vị trí của các vận động viên trên sân và từ đó xây dựng bản đồ nhiệt (heatmap) trực quan hóa các khu vực hoạt động chủ yếu và tần suất di chuyển của họ trong suốt trận đấu.

## Người thực hiện

* Võ Hoài Sơn
* Nguyễn Trọng Nhân

## Video Demo

[Video giới thiệu đề tài](https://youtu.be/N5h5xNVd9W4)

[Video ngắn demo toàn bộ quá trình vẽ heatmap](https://youtu.be/ah2owUbRXNk)

## Các Thành phần Chính trong Dự án

Dưới đây là mô tả về các file quan trọng trong dự án này:

* **`heatmap_draw.ipynb`**: Jupyter Notebook chứa mã nguồn và giải thích chi tiết quy trình xử lý để vẽ bản đồ nhiệt (heatmap) cho toàn bộ video đầu vào.
* **`progress.ipynb`**: Jupyter Notebook trình bày từng bước cụ thể trong quá trình xử lý một khung hình (frame) đơn lẻ, từ phát hiện sân, nhận diện người chơi, ước tính tư thế cho đến khi tạo ra dữ liệu vị trí cho heatmap.
* **`demo1.png`**: Một file ảnh mẫu được sử dụng trong `progress.ipynb` để minh họa và kiểm tra các bước xử lý trên một khung hình tĩnh.
* **`demo.mp4`**: Một file video mẫu được sử dụng trong `heatmap_draw.ipynb` để thực hiện phân tích và tạo ra bản đồ nhiệt tổng thể cho toàn bộ video. (https://drive.google.com/file/d/1UzfV0EVq3df7x3yFp9pGseT6BUHjH0wE/view?usp=sharing)

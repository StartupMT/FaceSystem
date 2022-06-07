# Face_system
Hệ thống chấm công tích hợp python GUI sử dụng nhận dạng khuôn mặt để điểm danh.

Trong dự án python này, tôi đã tạo một hệ thống điểm danh bằng cách sử dụng kỹ thuật nhận dạng khuôn mặt. Tôi cũng đã tích hợp nó với GUI (Giao diện người dùng đồ họa) để mọi người có thể dễ dàng sử dụng. GUI cho dự án này cũng được tạo trên python bằng tkinter.

CÔNG NGHỆ ĐƯỢC SỬ DỤNG:
1) tkinter cho toàn bộ GUI
2) OpenCV để chụp ảnh và nhận dạng khuôn mặt (cv2.face.LBPHFaceRecognizer_create ())
3) CSV, Numpy, Pandas, datetime, v.v. cho các mục đích khác.

TÍNH NĂNG, ĐẶC ĐIỂM:
1) Dễ sử dụng với hỗ trợ GUI tương tác.
2) Mật khẩu bảo vệ để đăng ký người mới.
3) Tạo / Cập nhật tệp CSV cho các sinh viên bị mất điểm khi đăng ký.
4) Tạo tệp CSV mới hàng ngày để tham dự và đánh dấu sự tham dự với ngày và giờ thích hợp.
5) Hiển thị cập nhật điểm danh trực tiếp trong ngày trên màn hình chính ở định dạng bảng với Id, tên, ngày và giờ.


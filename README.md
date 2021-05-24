# Sign-Language-Translator
This is an android application which have function to translate from sign language (ASL) to alphabet language.
# ![](https://images-na.ssl-images-amazon.com/images/I/41cPlzcvdyL._SX331_BO1,204,203,200_.jpg)
## Tương tác thời gian thực, nhận diện ngôn ngữ ký hiệu sau quá trình traning lần 2.
[Video demo](https://www.youtube.com/watch?v=vE9L6QsWXP)
## Tổng quan
Sử dụng mô hình Yolo 4 phiên bản di động YoloTiny v4, một mô hình thị giác máy tính truyền thống dùng trong bài toán nhận diện đối tượng. Nó được sử dụng trong ứng dụng để nhận diện ngôn ngữ ký hiệu.
Dự án này lấy nguồn dữ liệu tham khảo từ [kaggle](https://kaggle.com). Dữ liệu chính để huấn luyện cho dự án là do chính tôi thu thập và xử lý. Tổng cộng khoảng 1902 ảnh. Sau khi có được dữ liệu tiến hành gán nhãn bằng công cụ [labelImg] (https://github.com/tzutalin/labelImg). Để dễ dàng quản lý và sử dụng trong quá trình huấn luyện, tôi sử dụng platform [Roboflow](https://app.roboflow.com). Training và thực hiện kiểm thử, chuyển đổi tham số sang tensorflow Lite, lưu mô hình, ...tất cả được thực hiện trên môi trường google colab. 
## Nội dung
### Dữ liệu
Do giới hạn về dữ liệu đầu vào và dữ liệu sau quá trình pre-processing data nên số lượng thống kê cụ thể như sau:\
A 38\
B 43\
C 38\
D 38\
E 38\
F 38\
G 37\
H 37\
I 37\
K 38\
L 38\
M 38\
N 38\
P 38\
Q 38\
R 38\
S 38\
T 38\
U 38\
V 38\
W 38\
X 38\
Y 38\
Z 38\
Tương ứng với 26 chữ cái trong bảng chữ cái quốc tế Anh ngữ.
### Gán nhãn
### Roboflow
#### Tạo dataset
#### Export
### Huấn luyện trên Google Colab
### Ứng dụng nhận diện ngôn ngữ ký hiệu
### Yolov4 Tiny
### Tensorflow/Tensorflow Lite
### Lỗi

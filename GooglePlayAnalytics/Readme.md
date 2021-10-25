# Đề Xuất


## Đề tài: Các yếu tố ảnh hưởng đến người đối với ứng dụng trên Google Play Store
|MSSV|Thành viên|
|:------:|:----|
|19133022 |**Hồng Tiến Hào**|
|19133065 |**Nguyễn Thanh Tùng**|
|20133036 |**Nguyễn Thành Đồng**|
|18133024 |**Ngô Phi Lít**|

*Giáo viên hướng dẫn*: **Quách Đình Hoàng**


## Phần 1 - Giới thiệu:


### 1.1 Nguồn gốc của dữ liệu nghiên cứu
+ Tập dữ liêu phân tích với các đối tượng dữ liệu là các ứng dụng trên google playstore trong thời gian 2016,2017, 2018.
+ Cách thu thập dữ liệu: crawl bằng Jquery
+ Link tập dữ liệu nguồn [https://www.kaggle.com/lava18/google-play-store-apps](https://www.kaggle.com/lava18/google-play-store-apps) 
+ Ý tưởng: Android nắm giữ khoảng 53,2% thị trường điện thoại thông minh, trong khi iOS là 43%. Phân tích ứng dụng dành cho thiết bị di động là một cách tuyệt vời để có thêm nhiều người tải xuống ứng dụng của bạn. Dữ liệu ứng dụng trên Cửa hàng Play có tiềm năng to lớn để thúc đẩy các doanh nghiệp sản xuất ứng dụng thành công. Thông tin chi tiết hữu ích có thể được rút ra để các nhà phát triển làm việc và nắm bắt thị trường Android!
+ Gồm 13 thuộc và 10842 dòng

### 1.2 Các biến nghiên cứu
+ **Các biến liên tục**: Rating, Price
+ **Các biến phân lọai**: Category, Type, Content Rating, Genres, Last Updated, Current Ver, Android Ver
+ **Các biến rời rạc**: Reviews

### 1.3 Chi tiết các biến

1. **App**: tên ứng dụng 
1. **Category**: thể loại chính của ứng dụng
1. **Rating**: điểm xếp hạng của ứng dụng (từ 0 tới 5)
1. **Reviews**: số lượng nhận xét về ứng dụng
1. **Size**: kích thước về ứng dụng
1. **Installs**: số lượng lượt tải về của ứng dụng
1. **Type**: ứng dụng thuộc loại trả phí hay free
1. **Price**: giá của ứng dụng
1. **Content Rating**: Nhóm tuổi mà ứng dụng nhắm đến (Everyone, Teen, Other)
1. **Genres**: thể loại khác (một ứng dụng có thể thuộc nhiều thể loại)
1. **Last Updated**: ngày cập nhập phiên bản cuối cùng
1. **Current Ver**: phiên bản hiện tại
1. **Android Ver**: phiên bản android tối thiểu để sử dụng ứng dụng


## Phần 2 - Dữ liệu

## PHẦN 3 - KẾ HOẠCH PHÂN TÍCH DỮ LIỆU


### 3.1. Phân tích dữ liệu
 
1. Loại free và trả phí có ảnh hưởng đến diểm rating hay không
2. Thể loại ứng dụng có ảnh hưởng tới điểm rating của ứng dụng hay không?
3. Nhóm tuổi là mục tiêu của ứng dụng có ảnh hưởng tới điểm rating của ứng dụng hay không?
3. Số lượng reviews có ảnh hưởng tới điểm rating của ứng dụng hay không?
4. kích thước của ứng dụng có ảnh hưởng tới điểm rating của ứng dụng hay không?
5. số lượng lượt tải ứng dụng sẽ ảnh hưởng như thế nào đến điểm rating của ứng dụng?
6. Giá của ứng dụng sẽ ảnh hưởng như thế nào đến điểm rating của ứng dụng


### 3.2 Cleaning Data

missing value ở dòng 10472
	
### 3.3 Thống kê:

##### 3.3.1 Kiểm định giả thuyết
1. Liệu một ứng dụng có lượt tải lớn có thật sự có điểm rating cao hay không?
1. Liệu một ứng dụng là game thì sẽ có rating cao hơn các loại còn lại?

##### 3.3.2 Hồi quy 
1. xem xét sự ảnh hưởng của các yếu tố như thể loại, số lượng tải,.. đến điểm rating của ứng dụng

### 3.4 Học Máy
1. 


## Thông Tin Tập Dữ Liệu
- Các ngân hàng đóng một vai trò quan trọng trong các nền kinh tế thị trường. Họ quyết định ai có thể được cấp vốn dựa trên những điều khoản, và điều này ảnh hưởng quyết định có hoặc không đầu tư. Và chức năng tín dụng của ngân hàng sinh ra với mục đích cho cá nhân và doanh nghiệp vay vốn.
- Các thuật toán phân loại tín dụng, đưa ra dự đoán về xác suất vỡ nợ, là các phương thức mà ngân hàng sử dụng để xác định xem liệu một khoản vay có được cấp hay không. 
- Dữ liệu được cung cấp bởi cuộc thi trên kaggle yêu cầu những người tham gia cải thiện trạng thái của bức tranh tin dụng được đưa ra, bằng cách dự đoán xác suất mà ai đó sẽ gặp khó khăn tài chính trong 2 năm tới.
    - Mục tiêu của cuộc thi này là xây dựng một mô hình mà người vay có thể sử dụng để giúp đưa ra quyết định tài chính tốt nhất.
    - Data source: [https://www.kaggle.com/competitions/GiveMeSomeCredit](https://www.kaggle.com/competitions/GiveMeSomeCredit)
+ Tập dữ liệu phân tích có **12 thuộc tính** gồm 2 file csv (cs-train.csv và cs-test.csv)
  + Train gồm **150000 quan sát**
  + Test gồm **101503 quan sát**
+ Thông tin thuộc tính:

|N|Attribute|Describtion|Type|
|:-|:-|:-|:-:|
|1|**X**|Số thứ tự|
|2|**SeriousDlqin2yrs**|Người đã trải quan 90 ngày trễ hạn hạn hoặc hơn|Phân loại|
|3|**RevolvingUtilizationOfUnsecuredLines**|Tổng số dư trên thẻ tín dụng và hạn mức tín dụng cá nhân (trừ bất động sản và không có nợ trả góp như các khoản vay xe hơi chia cho tổng giới hạn tín dụng)|Liên tục|
|4|**age**|Tuổi của người vay|Rời rạc|
|5|**NumberOfTime30-59DaysPastDueNotWorse**|Số lần người vay đã bị quá hạn từ 30-59 ngày (nhưng không tệ hơn trong 2 năm qua)|Rời rạc|
|6|**DebtRatio**|Thanh toán nợ hàng tháng, tiền cấp dưỡng, chi phí sinh hoạt chia cho tổng thu nhập của tháng|Liên tục|
|7|**MonthlyIncome**|Thu nhập hàng tháng|Liên tục|
|8|**NumberOfOpenCreditLinesAndLoans**|Số lượng các khoản vay mở (ví dụ: trả góp xe hơi hoặc thế chấp) và hạn mức tín dụng tín dụng (ví dụ: thẻ tín dụng)|Rời rạc|
|9|**NumberOfTimes90DaysLate**|Số lần người vay đã bị quá hạn từ 90 ngày hoặc hơn|Rời rạc|
|10|**NumberRealEstateLoansOrLines**|Số lượng khoản vay thế chấp và cho vay bất động sản (bao gồm [dòng vốn tín dụng nhà](https://filegi.com/business-term/home-equity-line-of-credit/))|Rời rạc|
|11|**NumberOfTime60-89DaysPastDueNotWorse**|Số lần lịch sử tín dụng ghi nhận không vi phạm các nguyên tắc|Rời rạc|
|12|**NumberOfDependents**|Số người phụ thuộc/bảo hộ trong gia đình không bao gồm bản thân (vợ / chồng, trẻ em, v.v.) |Rời rạc|

Trong đó, còn 2 tập dữ liệu mà kaggle cung cấp: 
- Data Dictionary.xls là đặc tả dữ liệu
- sampleEntry.csv là file submit mẫu mà kaggle cung cấp

Ngoài ra còn các file csv kêt quả được nộp trên kaggle tương ứng với các thuật toán:
- submission_knn_discrete
- submission_knn_median
- submission_nb_discrete
- submission_nb_median
- submission_rf_discrete
- submission_rf_median
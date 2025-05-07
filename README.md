# DataMining-FinalProject
&lt;DataMining - Final Project> Stroke Predict
Theo Tổ chức Y tế Thế giới (WHO), đột quỵ là nguyên nhân gây tử vong đứng thứ 2 trên toàn cầu, chiếm khoảng 11% tổng số ca tử vong. Tập dữ liệu này được sử dụng để dự đoán liệu một bệnh nhân có khả năng bị đột quỵ hay không dựa trên các thông số đầu vào như giới tính, tuổi tác, các bệnh khác nhau và tình trạng hút thuốc. Mỗi hàng trong dữ liệu cung cấp thông tin liên quan về bệnh nhân.

Các đặc trưng trong tập dữ liệu:

id: Mã định danh của bệnh nhân
gender: Giới tính của bệnh nhân, "Male", "Female" or "Other"
age: Tuổi bệnh nhân
hypertension: Chỉ số huyết áp, có giá trị là 0 nếu bệnh nhân không bị tăng huyết áp, 1 nếu bệnh nhân bị tăng huyết áp
heart_disease: Chỉ số về tim, có giá trị là 0 nếu bệnh nhân không mắc bệnh tim, 1 nếu bệnh nhân mắc bệnh tim
ever_married: Tình trạng kết hôn, "No" hoặc "Yes"
work_type: Loại công việc mà bệnh nhân đang làm, "children", "Govt_jov", "Never_worked", "Private" hoặc "Self-employed"
Residence_type: Khu vực cư trú, "Rural" hoặc "Urban", "Nông Thôn" hoặc "Thành Thị"
avg_glucose_level: Chỉ số lượng đường trung bình trong máu
bmi: Chỉ số BMI (Body Mass Index) được tính dựa trên tỉ lệ giữa cân nặng và chiều cao bình phương, nói lên tình trạng cân nặng hiện tại của bệnh nhân. So với giá trị BMI tiêu chuẩn, chỉ số BMI cá nhân sẽ xác định một người đang thừa cân, thiếu cân hay có cân nặng cân đối.
smoking_status: Tình trạng hút thuốc "formerly smoked", "never smoked", "smokes" hoặc "Unknown"*
stroke: Có giá trị là 1 nếu bệnh nhân bị đột quỵ, và 0 nếu bệnh nhân không đột quỵ
Mục tiêu của bài toán: Xây dựng mô hình Machine Learning để dự đoán xác suất một người bị đột quỵ

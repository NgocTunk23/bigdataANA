# Phần 3 mình sẽ nói về model chưa dùng smote ở trên nha
Phần 3.2.2 Tinh chỉnh siêu tham số
nói rõ cho tôi về các tham số như
n_estimators=10000,
max_depth=6,
learning_rate=0.02,
validation_indicator_col="is_val",
scale_pos_weight=6

tui dùng validation để làm gì?

n_estimators thông thường cỡ bao nhiêu, và mình sài bao nhiêu, khi nó quá cao thì hậu quả gì xảy ra(với ram với model), khi nó thấp nó bị gì
max_depth cao cỡ 10 12 hoặc 4 sẽ bị gì tại sao lại chọn 6 hoặc 8

tỉ lệ học cao và thấp có vấn đề gì và sự tương quan với n_estimators
scale_pos_weight cao ví dụ 10 hay 0.1 có ý nghĩa như nào
gợi ý là scale_pos_weight tăng thì recall cao mà 2 chỉ số còn lại thấp chủng
ngược lại thì như nào reacll sẽ thấp nhưng precision sẽ cao
# Phần 3.3
Xác định các chỉ số đánh giá model từ cái biểu thức tui ghi
giải thích ý nghĩa từng đứa
lúc này cần nói về tỉ lệ giữa bộ nắng và mưa chính có mưa chỉ có 5,66 và không mưa là 94,34
với tỉ lệ này thì cái nào không có phải là chỉ số đánh giá (accuracy)
tại sao

# Phần 4 mình sẽ show kết quả và so sánh
4.1 cứ show kết quả ra và giải thích và phần 4.2 mới là cái quan trọng
4.2 thì gắn thêm kết quả đã smote là mình đã điều chỉnh những gì ở đoạn smote đừng quan tâm cấu hình chỉ số siêu tham số
tui tăng 3 cho mưa và giảm phân nửa cho nắng

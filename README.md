# FeatureSelection use mean and median
**Topic**: Fusion of statistical importance for feature selection in Deep Neural Network-based Intrusion Detection System
**Link notebook**: [Drive](https://drive.google.com/drive/folders/1oCgpicLt_kadQy6mlXCpcDrLxNHFxD0F?usp=sharing)

## Thành viên thực hiện
1.	Trần Minh Duy
2.	Nguyễn Hoài Phương
3.	Nguyễn Đức Tài
4.	Nguyễn Huy Hoàng

## Giới thiệu
Triển khai giải pháp một kỹ thuật lựa chọn đặc trưng mới (feature selection) dựa trên bài báo nckh, cải thiện hiệu suất của IDS dựa trên DNN bằng cách bằng cách xếp hạng các feature theo rank được tính ra từ Độ lệch chuẩn và Khoảng cách giữa Mean và Median, các đặc trưng được loại bỏ dựa trên thứ hạng của chúng giúp việc học dữ liệu tốt hơn. Phương pháp được đánh giá trên ba bộ dữ liệu phát hiện xâm nhập: NSL-KDD, UNSW_NB-15 và CIC-IDS-2017. Kết quả cho thấy kỹ thuật feature selection được đề xuất đạt được kết quả tốt hơn so với các kỹ thuật hiện có với IDS dựa trên DNN cho cả ba bộ dữ liệu phát hiện xâm nhập được sử dụng.

## Bài báo tham khảo
[1].  Ankit Thakkar and Ritika Lohiya. 2023. Fusion of statistical importance for feature selection in Deep Neural Network-based Intrusion Detection System. Inf. Fusion 90, C (Feb 2023), 353–363. Available: [here](https://doi.org/10.1016/j.inffus.2022.09.026)

## Môi trường thực nghiệm
*  Google Colab - GPU T4
*  RAM hệ thống 12,7 GB
*  RAM GPU 15 GB
*  Ổ đĩa 78.2 GB
*  using Python3

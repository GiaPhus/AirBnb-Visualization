<<<<<<< HEAD
<<<<<<< HEAD
# AirBnb-Visualization
=======
=======
>>>>>>> 4ae8403 (giaphu)
# Airbnb Data Visualization
## 1. Giới thiệu
### Mục tiêu:

Mục tiêu của bài viết này là giúp độc giả hiểu và sử dụng thành thạo các thư viện visualization để trực quan hóa dữ liệu một cách hiệu quả. Bạn sẽ có khả năng trình bày và phân tích dataset thu thập được từ Airbnb, từ đó tìm ra các thông tin có ý nghĩa và đưa ra nhận định và kết luận từ dữ liệu.
Phạm vi:

Trong bài kì này, chúng ta sẽ tập trung vào sử dụng các gói thư viện như Matplotlib, Seaborn và Bokeh để phân tích và trực quan hóa dữ liệu thông qua các biểu đồ. Đồng thời, chúng ta cũng sẽ sử dụng Pandas và Spark để xử lý và quản lý dữ liệu một cách hiệu quả.
Yêu cầu về cài đặt:

Để thực hiện các dạng biểu đồ, chúng ta cần cài đặt các thư viện sau: Matplotlib, pandas, Seaborn, Bokeh.
Cài đặt Matplotlib:

## Cài đặt Matplotlib
pip install matplotlib
## Hoặc nếu bạn sử dụng Python 3
pip3 install matplotlib
## Hoặc sử dụng conda
conda install matplotlib

## Cài đặt Seaborn
pip install seaborn
## Hoặc nếu bạn sử dụng Python 3
pip3 install seaborn
## Hoặc sử dụng conda
conda install seaborn

## Cài đặt Bokeh
pip install bokeh
## Hoặc sử dụng conda
conda install bokeh


# 2. Sơ lược về Dataset
DataSet: New York City Airbnb Open Data

Nguồn: https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data

DataSet "Nyc_Airbnb" là một tập dữ liệu về việc cho thuê nhà trên nền tảng Airbnb tại New York City vào năm 2019. Tập dữ liệu này cung cấp thông tin về các loại phòng, các host cũng như vị trí của các căn hộ được đăng ký trên Airbnb tại thành phố New York.

Thông tin chi tiết của dataset:

    id: ID duy nhất của mỗi danh sách phòng.
    name: Tên của phòng.
    host_id: ID của người chủ sở hữu phòng.
    host_name: Tên của người chủ sở hữu phòng.
    neighbourhood_group: Nhóm khu vực của phòng.
    neighbourhood: Khu vực cụ thể của phòng.
    latitude: Vĩ độ của vị trí phòng.
    longitude: Kinh độ của vị trí phòng.
    room_type: Loại phòng.
    price: Giá thuê của phòng.
    minimum_nights: Số đêm tối thiểu mà một khách hàng phải đặt ít nhất khi thuê phòng.
    number_of_reviews: Số lượng đánh giá của phòng.
    last_review: Ngày đánh giá gần nhất của phòng.
    reviews_per_month: Số lượng đánh giá trung bình mỗi tháng của phòng.
    calculated_host_listings_count: Số lượng phòng được tính toán bởi mỗi chủ sở hữu.


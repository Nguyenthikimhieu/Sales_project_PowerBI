Tối ưu hóa chiến lược bán hàng thông qua phân tích dữ liệu bán lẻ
1. MÔ TẢ MỤC TIÊU VÀ KẾT QUẢ
Dùng Power BI để phân tích và trực quan hóa dữ liệu bán hàng của một doanh nghiệp thương mại điện tử. Dữ liệu bao gồm thông tin về khách hàng, sản phẩm, giao dịch bán hàng, nhóm lãnh thổ, danh mục sản phẩm và danh mục phụ. Mục tiêu là tạo bảng thông tin toàn diện để cung cấp thông tin chi tiết về các khía cạnh khác nhau của doanh nghiệp, chẳng hạn như hiệu suất bán hàng tổng thể, xu hướng hàng tháng, hành vi của khách hàng và hiệu suất sản phẩm. Báo cáo vấn đề hoạt động kinh doanh thương mại điện tử đã có sự tăng trưởng đáng kể và đã tích lũy được một lượng dữ liệu bán hàng đáng kể.

2. NGUỒN DỮ LIỆU (DATA SOURCE)
Dữ liệu được sử dụng trong dự án này bao gồm thông tin về khách hàng, sản phẩm, giao dịch bán hàng, nhóm lãnh thổ, danh mục sản phẩm và tiểu danh mục sản phẩm. Dữ liệu được lưu trữ dưới dạng các tệp CSV và được đính kèm trong dự án để đảm bảo mọi người có thể truy cập và kiểm tra dữ liệu gốc. Cụ thể, bảng dữ liệu bao gồm:

Customer: Thông tin về khách hàng

Product: Chi tiết sản phẩm

Territory Group: Nhóm lãnh thổ

Sales: Giao dịch bán hàng

ProductCategory: Danh mục sản phẩm

ProductSubCategory: Tiểu danh mục sản phẩm

3. CÔNG CỤ VÀ KĨ THUẬT (TOOLS AND TECHNIQUES)
Dự án được thực hiện bằng Power BI để trực quan hóa dữ liệu và phân tích các mẫu xu hướng.

4. QUY TRÌNH THỰC HIỆN (IMPLEMENTATION)
Trong phần này, các bước thực hiện được mô tả chi tiết từ việc thu thập dữ liệu cho đến phân tích và trực quan hóa:
Thu thập dữ liệu: Tải dữ liệu từ các tệp CSV vào Power BI Desktop.
Làm sạch dữ liệu: Sử dụng Power Query Editor để kiểm tra và làm sạch dữ liệu.
Phân tích dữ liệu: Thực hiện các phân tích định lượng và định tính để tìm ra các mẫu xu hướng và thông tin quan trọng.
Trực quan hóa kết quả: Tạo các dashboard tương tác trên Power BI bao gồm các bảng và biểu đồ để trình bày kết quả phân tích.

5. T QUẢ VÀ PHÁT HIỆN (RESULTS AND FINDINGS)

Overall Sales Performance:
Có sự gia tăng đáng kể trong doanh thu vào giữa năm 2021, đạt từ 1.4M đến 1.9M. Phần trăm tăng trưởng biến động mạnh, với tháng 3/2020 (-74.16%), tháng 10/2020 (-1.23%), và tháng 8/2022 (-100.00%) giảm sâu, nhưng tháng 12/2019 (454.30%) và tháng 9/2021 (244.13%) tăng cao.
Từ cuối 2019 đến đầu 2020, doanh thu và tăng trưởng giảm. Giữa 2021, doanh thu tăng đáng kể với nhiều tháng tăng trưởng dương, cho thấy phục hồi tích cực. Năm 2022 biến động lớn, đặc biệt giảm mạnh tháng 8 và phục hồi tháng 9 (14.51%).
Bike đặc biệt là Road Bikes với doanh thu 17 triệu USD chiếm 45.37 tổng doanh thu là sản phẩm bán chạy nhất. Mountain Bikes và Touring Bikes cũng có doanh thu đáng kể trong các sản phẩm bán chạy. Chúng ta nên đẩy mạng chiến lượt bán hàng của các sản phẩm về xe đạp.
Top các khách hàng có sức mua lớn và khu vực có United State cũng là những yếu tố ta phải chú ý để đưa ra chiến lược marketing sản phẩm phù hợp.

Customer Analysis:
Top 10 khách hàng: 10 khách hàng hàng đầu được sắp xếp theo tổng doanh thu,từ cao nhất đến thấp nhất.
Phân bố doanh thu: Hai khách hàng đầu chiêm doanh thu cao hơn. Tám khách hàn còn lại phân bổ doanh thu khách đồng đều. Đây đều là những khách hàng tiềm năng cần có chiến lược ưu đãi phù hợp.

      Kết luận
      Cung cấp một cái nhìn tổng quan về phân bố doanh thu theo tên cho 10 khách hàng hàng đầu trong một doanh nghiệp.Biểu đồ cho thấy sự phân bố doanh thu không đồng đều giữa các khách hàng,
      với ba khách hàng hàng đầu chiếm hơn 50% tổng doanh thu.Tuy nhiên,do độ phân giải thấp của hình ảnh,không thể xác định rõ ràng tên và tổng doanh thu của tất cả các khách hàng.


Product Performance:
Top 10 sản phẩm:10 sản phẩm bán chạy nhất được sắp xếp theo tổng doanh thu,từ cao nhất đến thấp nhất.
Phân bố doanh thu: Các loại xe đạp leo núi màu đen, bạc bán khá chạy và chiếm hơn 50% doanh thu.

      Kết luận
      Biểu đồ hình tròn "Top 10 Total Amount by Name" cung cấp một cái nhìn tổng quan về phân bố doanh thu theo tên cho 10 sản phẩm bán chạy nhất trong một doanh nghiệp.
      Biểu đồ cho thấy sự phân bố doanh thu không đồng đều giữa các sản phẩm,với ba sản phẩm hàng đầu chiếm hơn 40% tổng doanh thu.




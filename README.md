# Customer_Segmentation_Classification

[English below]

Một sàn thương mại điện tử chuyên về hoa và quà tặng, để đảm bảo lợi nhuận ổn định và tăng trưởng, công ty nổ lực duy trì lòng trung thành của khách hàng bằng cách cung cấp hàng hóa, dịch vụ tốt nhất. Qua 4 năm hoạt động, công ty có được dữ liệu gồm 6001 thông tin đơn đặt hàng, qua đó đánh giá tình hình hoạt động, kết quả kinh doanh và phân tích nhu cầu tặng quà trên sàn thương mại điện tử theo từng phân khúc khách hàng.\
Dữ liệu gồm có:\
_id:	mã đơn hàng\
customer_id:	mã khách đặt hàng\
master_id:	mã ngành hàng\
summary.grand_total:	tổng tiền đơn hàng\
summary.discount.money:	số tiền giảm giá\
summary.commission:	số tiền sàn hưởng\
country_id:	mã quốc gia khách hàng đặt hàng\
to_user.relationship_id:	mối quan hệ với người nhận quà\
to_user.occasion_id:	dịp tặng quà\
to_user.relative_id:	mã mối quan hệ giữa người tặng và người được tặng\
to_user_date:	thời gian giao quà\
create_info.created:	ngày đặt quà\
Sử dụng Excel, SQL để xử lý dữ liệu và truy vấn dữ liệu. Dùng ngôn ngữ Python với mô hình RFM kết hợp Kmean để chọn ra nhóm khách hàng chính mà sàn thương mại điện tử cần quan tâm. Từ đó, đưa ra các đề xuất giải pháp doanh nghiệp nhäm tăng cường nhu cầu quà tặng của nhóm khách hàng này trên nên tảng thương mại điện tử.

An e-commerce platform specializing in flowers and gifts, to ensure stable profits and growth, the company strives to maintain customer loyalty by providing the best goods and services. After 4 years of operation, the company has obtained data including 6001 order information, thereby evaluating the operating situation, business results and analyzing the gift-giving needs of customers on the e-commerce platform by each customer segment.\
Data includes:\
_id: order code\
customer_id: order customer code\
master_id: industry code\
summary.grand_total: total order amount\
summary.discount.money: discount amount\
summary.commission: commission amount\
country_id: country code of the customer ordering\
to_user.relationship_id: relationship with gift recipient\
to_user.occasion_id: gift giving occasion\
to_user.related_id: relationship code between donor and recipient\
to_user_date: gift receipt date\
create_info.created: gift order date\
Use Excel, SQL to process data and query data. Use the Python language with the RFM model combined with Kmean to select the main customer groups that the e-commerce platform needs to care about. From there, propose business solutions to increase the gift needs of this customer group on the e-commerce platform.


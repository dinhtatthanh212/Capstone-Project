**MỤC LỤC**

[DANH MỤC HÌNH ẢNH](#danh-mục-hình-ảnh)

[DANH MỤC BẢNG BIỂU](#danh-mục-bảng-biểu)

[DANH MỤC TỪ VIẾT TẮT](#danh-mục-từ-viết-tắt)

[LỜI MỞ ĐẦU](#lời-mở-đầu)

[CHƯƠNG 1: TỔNG QUAN VỀ ĐỀ TÀI](#tổng-quan-về-đề-tài)

[1.1 Giới thiệu về cơ sở thực tập](#_Toc153464573)

[1.1.1 Thông tin thực tập](#_Toc153464574)

[1.1.2 Công ty AHT Tech](#_Toc153464575)

[1.1.3 Lịch sử hình thành và phát triển](#_Toc153464576)

[1.1.4 Tầm nhìn doanh nghiệp](#_Toc153464577)

[1.2 Khảo sát tình hình thực tế hiện nay](#_Toc153464578)

[1.3 Mô tả bài toán](#_Toc153464579)

[1.4 Mô tả dữ liệu](#_Toc153464580)

[1.5 Tính cấp thiết của đề tài](#_Toc153464581)

[1.6 Đối tượng và phạm vi nghiên cứu](#_Toc153464582)

[1.7 Mục tiêu của đề tài](#_Toc153464583)

[CHƯƠNG 2: CƠ SỞ LÝ THUYẾT](#cơ-sở-lý-thuyết)

[2.1 Tổng quan về khai phá dữ liệu](#_Toc153464585)

[2.2 Quy trình khám phá tri thức](#quy-trình-khám-phá-tri-thức)

[2.3 Quá trình khai phá dữ liệu](#_Toc153464587)

[2.4 Các kỹ thuật tiếp cận trong khai phá dữ liệu](#_Toc153464588)

[2.5 Phân cụm dữ liệu và thuật toán toán Kmeans](#_Toc153464589)

[2.5.1 Phân cụm dữ liệu là gì?](#_Toc153464590)

[2.5.2 Một số phương pháp phân cụm dữ liệu](#_Toc153464591)

[2.5.3 Thuật toán phân cụm Kmeans](#_Toc153464592)

[2.6 Các thuật toán xác định số cụm tối ưu](#_Toc153464593)

[2.6.1 Phương pháp khuỷu tay (Elbow methods)](#_Toc153464594)

[2.6.2 Phương pháp điểm hình bóng trung bình (Average Silhouette)](#_Toc153464595)

[2.6.3 Phương pháp thống kê khoảng cách (Gap Statistics)](#_Toc153464596)

[CHƯƠNG 3: ÁP DỤNG THUẬT TOÁN PHÂN CỤM KMEANS VÀO BÀI TOÁN TÌM ĐỊA ĐIỂM KINH DOANH QUÁN CÀ PHÊ TẠI HÀ NỘI](#_Toc153464597)

[3.1 Quy trình thực hiện](#_Toc153464598)

[3.1.1 Thu thập, làm sạch, tích hợp dữ liệu](#_Toc153464599)

[3.1.1.1 Dữ liệu về diện tích, dân số](#dữ-liệu-về-diện-tích-dân-số)

[3.1.1.2 Dữ liệu về giá nhà đất](#dữ-liệu-về-giá-nhà-đất)

[3.1.1.3 Dữ liệu về số lượng các công ty, doanh nghiệp](#dữ-liệu-về-số-lượng-các-công-ty-doanh-nghiệp)

[3.1.2 Tổng quan về dữ liệu hiện có](#tổng-quan-về-dữ-liệu-hiện-có)

[3.1.3 Tiền xử lý dữ liệu (Preprocessing Data)](#_Toc153464604)

[3.1.3.1 Chuẩn bị dữ liệu](#chuẩn-bị-dữ-liệu)

[3.1.3.2 Xác định số cụm tối ưu](#xác-định-số-cụm-tối-ưu)

[3.1.3.3 Đánh giá kết quả phân cụm](#đánh-giá-kết-quả-phân-cụm)

[3.1.4 Phân tích dữ liệu (Exploration Data Analysis - EDA)](#_Toc153464608)

[3.1.4.1 Phân tích các đặc điểm của cụm dữ liệu](#phân-tích-các-đặc-điểm-của-cụm-dữ-liệu)

[3.1.4.2 Phân tích chi tiết các yếu tố](#phân-tích-chi-tiết-các-yếu-tố)

[KẾT LUẬN VÀ HƯỚNG PHÁT TRIỂN ĐỀ TÀI](#kết-luận-và-hướng-phát-triển-đề-tài)

[Kết luận](#_Toc153464612)

[Hạn chế của đề tài và phương hướng phát triển](#_Toc153464613)

[DANH MỤC TÀI LIỆU THAM KHẢO](#_Toc153464614)

# DANH MỤC HÌNH ẢNH

[Hình 2.21 Quy trình khám phá tri thức](#_Toc153881131)

[Hình 2.51 Minh họa chiến lược phân chia](#_Toc153881132)

[Hình 2.61 Minh họa phương pháp Elbow](#_Toc153881133)

[Hình 2.62 Minh họa thuật toán Average Silhouette](#_Toc153881134)

[Hình 2.63 Minh họa phương pháp Gap Statistics](#_Toc153881135)

[Hình 3.11 Dữ liệu thô về địa lý, dân cư](#_Toc153881136)

[Hình 3.12 Dữ liệu về tọa độ của các quận huyện](#_Toc153881137)

[Hình 3.13 Dữ liệu về giá nhà đất](#_Toc153881138)

[Hình 3.14 Dữ liệu về thông tin doanh nghiệp](#_Toc153881139)

[Hình 3.15 Dữ liệu tổng hợp sau khi được làm sạch](#_Toc153881140)

[Hình 3.16 Minh họa vị trí các quận huyện lên bản đồ](#_Toc153881141)

[Hình 3.17 Hạn chế của Google Place API](#_Toc153881142)

[Hình 3.18 Dữ liệu thu thập được từ Foursquare API](#_Toc153881143)

[Hình 3.19 Số lượng địa điểm tại mỗi quận huyện](#_Toc153881144)

[Hình 3.110 Top 5 loại hình kinh doanh phổ biến nhất](#_Toc153881145)

[Hình 3.111 Top 10 những loại hình kinh doanh phổ biến tại từng quận](#_Toc153881146)

[Hình 3.112 Mã hóa các loại địa điểm bằng One Hot Encoding](#_Toc153881147)

[Hình 3.113 Tần suất xuất hiện của các quán cà phê tại từng quận huyện](#_Toc153881148)

[Hình 3.114 Minh họa số cụm tối ưu với phương pháp Elbow](#_Toc153881149)

[Hình 3.115 Đánh giá phân cụm với phương pháp Gap Statistics](#_Toc153881150)

[Hình 3.116 Vị trí các quận huyện trên bản đồ khi được phân tách với 5 cụm](#_Toc153881151)

[Hình 3.117 Thống kê mô tả giá nhà](#_Toc153881152)

[Hình 3.118 Biểu đồ boxplot về phân bổ giá nhà](#_Toc153881153)

[Hình 3.119 Thống kê mô tả mật độ dân số](#_Toc153881154)

[Hình 3.120 Biểu đồ boxplot phân bổ mật độ dân số](#_Toc153881155)

[Hình 3.121 Thống kê mô tả số lượng doanh nghiệp](#_Toc153881156)

[Hình 3.122 Biểu đồ boxplot phân bổ số lượng doanh nghiệp](#_Toc153881157)

# DANH MỤC BẢNG BIỂU

[Bảng 3.11 Dữ liệu dân cư sau khi được làm sạch](#_Toc153881158)

[Bảng 3.12 Mô tả dữ liệu tổng hợp về các quận huyện tại Hà Nội](#_Toc153881159)

[Bảng 3.13 Mô tả dữ liệu về các địa điểm kinh doanh tại Hà Nội](#_Toc153881160)

[Bảng 3.14 Một số dữ liệu dùng để phân cụm](#_Toc153881161)

[Bảng 3.15 Hệ số Silhouette tương ứng với các giá trị k](#_Toc153881162)

[Bảng 3.16 Kết quả thống kê khoảng cách](#_Toc153881163)

[Bảng 3.17 Bảng biểu diễn các giá trị đặc trưng của các cụm](#_Toc153881164)

[Bảng 3.18 Bảng phân bổ giá nhà trung bình](#_Toc153881165)

[Bảng 3.19 Bảng tổng hợp thông tin các yếu tố](#_Toc153881166)

[Bảng 3.110 Bảng thông tin kết quả](#_Toc153881167)

# DANH MỤC TỪ VIẾT TẮT

| CSDL | Cơ sở dữ liệu              |
|------|----------------------------|
| KPDL | Khai phá dữ liệu           |
| KPTT | Khai phá tri thức          |
| WCSS | Within cluster sum square  |
| APD  | Average population density |
| AC   | Average companies          |
| AHP  | Average house price        |
| EDA  | Explore Data Analysis      |

# LỜI MỞ ĐẦU

Với sự bùng nổ công nghệ như hiện nay, có rất nhiều giải pháp công nghệ được nghiên cứu và triển khai nhằm phục vụ nhu cầu của cá nhân và doanh nghiệp. Trong đó Data Mining (Khai phá dữ liệu - KPDL) là một trong những lĩnh vực quan trọng nhất trong công nghệ. KPDL là quá trình chọn lọc, xử lý dữ liệu thô, sắp xếp, phân loại các tập hợp dữ liệu lớn qua đó đề xác định các mẫu và xây dựng các mối quan hệ của dữ liệu đề giải quyết các vấn đề bằng cách phân tích dữ liệu. Việc ứng dụng KPDL cho phép các đơn vị, doanh nghiệp có thể dự đoán trước được xu hướng trong tương lai.

Trong lĩnh vực kinh doanh, một môi trường có đầy đủ sự cạnh tranh về mọi mặt và phụ thuộc rất nhiều vào các yếu tố chủ quan và khách quan như yếu tố về dân cư, địa lý, tình hình chính trị hay các yếu tố vi mô, vĩ mô khác. Những người chủ doanh nghiệp cần phải nhanh chóng áp dụng các giải pháp mới thay cho các cách làm truyền thống, ra quyết định dựa trên dữ liệu thay vì dựa trên kinh nghiệm tích lũy hoặc cảm tính. Từ đó, các đơn vị, doanh nghiệp có thể gia tăng doanh thu và có thể dự đoán trước những vấn đề trong tương lai.

Là một người đang theo đuổi ngành Khoa học dữ liệu và mong muốn ứng dụng phân tích dữ liệu vào trong các hoạt động thực tế, tôi quyết định lựa chọn đề tài “Ứng dụng phân cụm và phân tích dữ liệu vào bài toán chọn địa điểm kinh doanh quán cà phê tại Hà Nội”. Trong môi trường kinh doanh nói chung và ngành cà phê nói riêng, sự cạnh giữa các quán cà phê thực sự khốc liệt. Việc lựa chọn một địa điểm kinh doanh thích hợp sẽ giúp doanh nghiệp tối ưu được chi phí đầu vào và có một nguồn khách hàng ổn định.

Do đó, mục tiêu chính của đề tài này là có được những hiểu biết đầy đủ về các thuật toán phân cụm dữ liệu, các phương pháp xác định số cụm tối ưu sau đó ứng dụng vào bài toán thực tế để tìm ra quận huyện nào hợp lý nhất để kinh doanh quán cà phê tại Hà Nội.

Nội dung đề tài bao gồm 3 chương chính:

-   Chương 1: Tổng quan về đề tài
-   Chương 2: Cơ sở lý thuyết
-   Chương 3: Ứng dụng thuật toán Kmeans vào phân cụm địa điểm kinh doanh

Tôi cũng xin cảm ơn TS. Nguyễn Trung Tuấn – Viện trưởng Viện Công nghệ thông tin và Kinh tế số đã định hướng và giúp đỡ tôi trong quá trình thực hiện đề tài. Trong quá trình nghiên cứu và hoàn thiện đề tài, bản thân còn nhiều hạn chế về mặt kiến thức và chuyên môn nên khó tránh khỏi những thiếu sót. Tôi rất mong nhận được sự góp ý từ các thầy cô đề đề tài của tôi có thể được hoàn thành trọn vẹn hơn.

## TỔNG QUAN VỀ ĐỀ TÀI

### Khảo sát tình hình thực tế hiện nay

**Uống cà phê không chỉ là thói quen mà còn là một phần văn hóa của người Việt Nam, đặc biệt là người Hà Nội.** Cà phê được coi là thức uống giúp tỉnh táo, tập trung, do đó nhiều người Việt Nam có thói quen uống cà phê vào buổi sáng trước khi làm việc. Ngoài ra, cà phê còn là một nơi để gặp gỡ, trò chuyện, chia sẻ tâm tình. Từ "đi cà phê" đã trở nên quen thuộc, được sử dụng để mời bạn bè, người thân đi uống nước, cho dù đến quán không uống cà phê.

**Ngân hàng Thế giới (World Bank) với một số nghiên cứu gần đây cho thấy, tiềm năng tiêu thụ cà phê nội địa tại Việt Nam có thể lên đến 70.000 tấn/năm.** Do vậy, với sản lượng cà phê hàng năm thu hoạch được 700.000 - 800.000 tấn, thì lượng cà phê tiêu thụ nội địa của Việt Nam chiếm khoảng 10%.

**Việt Nam là nước trồng và sản xuất cà phê đứng thứ 2 thế giới.** Cà phê Việt Nam được đánh giá cao về chất lượng và giá thành. Giá cà phê sau khi đã qua chế biến ở Việt Nam khá rẻ, phù hợp với nhiều đối tượng khách hàng.

**Chính những thuận lợi về thiên thời, địa lợi, nhân hòa**, từ nguồn nguyên liệu cà phê trong nước cho đến thói quen uống cà phê của người dân, kết hợp với nhu cầu tiêu dùng cao, đã tạo điều kiện thuận lợi cho việc kinh doanh cà phê tại Việt Nam. Ý tưởng về việc khởi nghiệp với một quán cà phê là một trong những ý tưởng được nhìn thấy nhiều rất ở các bạn trẻ, các start-up hiện nay. Tuy nhiên, để duy trì và hoạt động ổn định được trong thời gian dài là một thách thức khá lớn nếu nhà đầu tư hay các start-up không có sự cân nhắc và tính toán kỹ lưỡng.

Có thể kể đến một số khó khăn khi mở quán cà phê tại Hà Nội như sau:

-   Cạnh tranh: thị trường các quán cà phê tại thủ đô đang ngày càng trở nên gay gắt, với sự xuất hiện của rất nhiều các quán cà phê mới, đa dạng, đáp ứng nhu cầu của nhiều đối tượng khách hàng. Để cạnh tranh thành công, các chủ quán cà phê cần xây dựng chiến lược kinh doanh rõ ràng, phù hợp với đối tượng khách hàng mục tiêu của mình.
-   Chi phí: hiện nay chi phí để mở một quán cà phê bao gồm rất nhiều hạng mục như phí thuê mặt bằng, nguyên vật liệu, nhân sự, quảng cáo, marketing… Trong đó, chi phí thuê mặt bằng là chi phí lớn nhất trong tổng chi phí mở quán cà phê. Giá thuê mặt bằng tại Hà Nội ngày càng tăng cao, đặc biệt là ở những khu vực trung tâm. Điều này khiến cho chi phí đầu tư ban đầu để mở quán cà phê trở nên rất lớn.
-   Dân cư: Hà Nội là một thành phố đông dân với dân số hơn 8 triệu người. Đây là một thị trường tiềm năng cho các nhà kinh doanh cà phê. Tuy nhiên, mật độ dân cư cao cũng là một thách thức đối với các chủ quán cà phê. Để đạt được mục tiêu doanh thu, cần chọn địa điểm mở quán phù hợp như gần các trường đại học, công ty, nhà máy…

### Mô tả bài toán

Trước khi mở một quán cà phê tại Hà Nội, doanh nghiệp, người đầu tư cần xem xét và lên kế hoạch thật rõ ràng, đánh giá các yếu tố có thể ảnh hưởng đến hoạt động kinh doanh của quán. Các yếu tố quan trọng như:

-   Dân cư, mật độ dân số của khu vực
-   Giá bất động sản, giá cho thuê mặt bằng
-   Các đối thủ cạnh tranh
-   Vị trí gần các khu vực có nhiều công ty, gần trường học, khu công nghiệp…

Như vậy, kết quả của đề tài nhằm giúp người đầu tư, các chủ quán cà phê trong việc ra quyết định lựa chọn vị trí mở quán cà phê phù hợp.

### Mô tả dữ liệu

Dựa vào mô tả bài toán, chúng ta cần xem xét một số yếu tố để đạt được mục tiêu doanh thu cho một quán cà phê mới như: khu vực có mật độ quán cà phê thấp để giảm thiểu rủi ro cạnh tranh, chi phí bất động sản, thuê mặt bằng thấp, mật độ dân số ở mức cao và mật độ các công ty, nhà xưởng lớn để đảm bảo lượng khách đến sử dụng dịch vụ của quán. Như vậy, dữ liệu cần thu thập bao gồm:

-   Dân số và mật độ dân số
-   Chi phí bất động sản, giá nhà
-   Số lượng công ty, doanh nghiệp
-   Thông tin về các địa điểm kinh doanh lân cận

### Tính cấp thiết của đề tài

Lựa chọn địa điểm kinh doanh là một trong những quyết định quan trọng nhất đối với bất kỳ doanh nghiệp nào, đặc biệt là đối với các quán cà phê. Một vị trí kinh doanh tốt có thể giúp thu hút khách hàng, tăng doanh thu và lợi nhuận. Ngược lại, một vị trí kinh doanh kém có thể dẫn đến thất bại của doanh nghiệp.

Phân tích dữ liệu là một công cụ mạnh mẽ có thể giúp các doanh nghiệp đưa ra quyết định sáng suốt hơn về việc lựa chọn địa điểm kinh doanh. Phân tích dữ liệu có thể giúp các doanh nghiệp thu thập và phân tích các dữ liệu quan trọng, như:

-   Dân số mật độ trong khu vực
-   Loại hình kinh doanh trong khu vực
-   Khả năng tiếp cận khách hàng tiềm năng
-   Tranh cạnh tranh

Thông qua phân tích dữ liệu, doanh nghiệp có thể xác định những lĩnh vực có tiềm năng kinh doanh cao, từ đó đưa ra quyết định lựa chọn địa điểm phù hợp nhất với nhu cầu và mục tiêu của mình. Cụ thể, trong bài toán lựa chọn địa điểm kinh doanh quán cà phê, phân tích dữ liệu có thể giúp các quán cà phê chủ yếu:

-   Xác định khu vực có tiềm năng khách hàng cao, phù hợp với mục tiêu khách hàng của quán.
-   Xác định khu vực có giao thông thuận tiện, dễ dàng tiếp cận cho khách hàng.
-   Xác định khu vực có giá thiết kế phù hợp với khả năng tài chính của quán.

Ví dụ: nếu một quán cà phê hướng đến đối tượng khách hàng là dân văn phòng thì nên chọn địa điểm gần các nhà văn phòng, trung tâm thương mại,... Nếu một quán cà phê hướng đến đối tượng khách hàng là giới trẻ thì nên chọn địa điểm gần các trường học, khu vui chơi giải trí,...

Như vậy, việc đưa ra quyết định lựa chọn địa điểm kinh doanh là một công việc đòi hỏi sự tính toán chính xác và cẩn trọng, do đó không thể chỉ dựa trên kinh nghiệm hay những đánh giá chủ quan mà cần đến sự giúp ích của dữ liệu. Phân tích dữ liệu là một hướng đi cần thiết để hỗ trợ các nhà đầu tư, người kinh doanh đưa ra quyết định lựa chọn địa điểm kinh doanh một cách hợp lý và hiệu quả.

### Đối tượng và phạm vi nghiên cứu

*Đối tượng nghiên cứu:*

-   Các quán cà phê tại Hà Nội
-   Tập dữ liệu về dân cư, địa lý, giá bất động sản và các doanh nghiệp
-   Các bài toán phân cụm

    *Phạm vi nghiên cứu:*

-   Đề tài được thực hiện trong phạm vi các quận huyện tại Hà Nội
-   Các thuật toán phân cụm trong học máy và khai phá dữ liệu
-   Các thuật toán tìm số cụm tối ưu

### Mục tiêu của đề tài

-   Nắm được các kiến thức liên quan đến Khai phá dữ liệu và các kỹ thuật phân cụm, các phương pháp tìm số cụm tối ưu cho bài toán phân cụm
-   Hiểu được bài toán đề ra, nâng cao khả năng phân tích dữ liệu để hỗ trợ doanh nghiệp ra quyết định hiệu quả.
-   Tìm ra được kết quả phù hợp với yêu cầu đề ra của bài toán tìm địa điểm kinh doanh quán cà phê tại Hà Nội.

## CƠ SỞ LÝ THUYẾT

### Tổng quan về khai phá dữ liệu

Trong thập kỷ vừa qua, con người đã tạo ra đến 90% tổng lượng dữ liệu trên thế giới từ trước tới nay. Sự bùng nổ về số lượng dữ liệu được lưu trữ này là nhờ sự thành công của mô hình dữ liệu quan hệ cùng với đó là sự phát triển của các công cụ truy xuất và thao tác dữ liệu. Trong khi công nghệ lưu trữ dữ liệu phát triển nhanh chóng để theo kịp nhu cầy, thì việc phát triển phần mềm để phân tích dữ liệu vẫn còn rất ít, cho đến gần đây thì các công ty đang nhận ra rằng ẩn sâu bên trong những khối dữ liệu này là một nguồn tài nguyên đang bị bỏ qua.

Hiện tại, các hệ thống quản lý CSDL được sử dụng để quản lý các tập tin này chỉ cho phép người dùng truy cập thông tin hiển thị rõ ràng trong CSDL. Tuy nhiên, những dữ liệu được lưu trữ trong CSDL này thường chỉ là một phần nhỏ của “tảng băng thông tin” khi chúng chưa thể hiện được nhiều ý nghĩa, đang chờ được khai thác và sử dụng để hỗ trợ ra quyết định kinh doanh hiệu quả hơn.

Việc trích xuất kiến thức từ các tập dữ liệu lớn này được gọi là Khai phá dữ liệu (Data Mining) hay còn được đề cập bởi một số thuật ngữ khác như Khám phá tri thức từ dữ liệu (Knowledge Discovery in Database), Nạo vét dữ liệu (Data Dredging), Phân tích dữ liệu/mẫu (Data/partern Analysis)… Một cách ngắn gọn Khai phá dữ liệu là quá trình trích xuất các kiến thức thú vị (không tầm thường, tiềm ẩn, chưa được biết trước và có khả năng hữu ích) từ lượng dữ liệu khổng lồ.

### Quy trình khám phá tri thức

(KTQD, 2019) Quá trình khám phá tri thức gồm các bước:

![](media/e2758d5570e25af22b410175eb00dcba.png)

Hình 2.21 Quy trình khám phá tri thức

*Nguồn: Giáo trình Phát hiện tri thức từ dữ liệu, ĐH KTQD*

-   **Bước 1:** Hiểu về miền dữ liệu. Bước này bao gồm việc học kiến thức có liên quan trước đó và mục tiêu của người dùng cuối mà kiến thức đã khám phá sẽ mang lại cho họ.
-   **Bước 2:** Chọn lọc tập dữ liệu (Selection). Mục tiêu chính là tạo ra một tệp dữ liệu đích từ dữ liệu gốc. Tức là chọn một tập hợp con các biến hoặc mẫu dữ liệu trên đó thực hiện các khám phá.
-   **Bước 3:** Tiền xử lý dữ liệu (Preprocessing Data). Dữ liệu sau khi được chọn sẽ được làm sạch. Phần lớn dữ liệu gốc đều ở dạng hỗn loạn, có thể thiếu thông tin hoặc thông tin sai lệch, do vậy cần được xử lý trước khi đưa vào mô hình thuật toán. Dữ liệu sau khi được xử lý bước này sẽ nhất quán, sạch sẽ, đầy đủ, được rút gọn và được rời rạc hóa.
-   **Bước 4:** Giảm chiều dữ liệu (Data Reduction). Bước này bao gồm việc tìm kiếm các thuộc tính hữu ích bằng cách áp dụng các phương pháp biến đổi và giảm sai số dữ liệu, đồng thời sẽ tìm cách biểu diễn bất biến của dữ liệu.
-   **Bước 5:** Chuyển đổi dữ liệu (Data Transformation). Chuyển đổi dữ liệu là một kỹ thuật tiền xử lý dữ liệu nhất thiết phải được thực hiện trên dữ liệu trước khi khai thác dữ liệu để cung cấp các mẫu dễ hiểu hơn. Ở bước này, dữ liệu được làm mịn và chuẩn hóa để phục vụ cho các bước sau.
-   **Bước 6:** Lựa chọn thuật toán để khai thác dữ liệu (Chosing the data mining algorithm). Người khai thác dữ liệu sẽ chọn các phương pháp để tìm kiếm các mẫu trong dữ liệu và quyết định các mô hình và thông số của các phương pháp sẽ được sử dụng để có kết quả phù hợp nhất.
-   **Bước 7:** Khai phá dữ liệu (Data Mining). Đây là công đoạn quan trọng và tốn phần lớn thời gian của cả quá trình khai phá tri thức, ở bước này các chuyên gia sẽ áp dụng các phương pháp, các thuật toán khai phá (phần lớn là các kỹ thuật của Machine learning) để khai phá, trích chọn được các mẫu (parttern) thông tin cần thiết và các mối liên hệ trong dữ liệu.
-   **Bước 8:** Đánh giá và biểu diễn tri thức (Knowledge presentation & Evaluation). Ở giai đoạn này, để trình bày một cách trực quan và dễ hiểu, các chuyên gia sẽ sử dụng các kỹ thuật biểu diễn và hiển thị để trực quan hóa các tri thức đã thu thập được dưới dạng gần gũi với con người như đồ thị, cây, bảng biểu… cho người dùng. Ngoài ra, ở bước này cũng sẽ đánh giá được những tri thức khai phá theo các tiêu chí đã đề ra.

Kết quả mà KPTT mang lại cho giới kinh doanh là không hề nhỏ, do đó KPTT được xem như một phần tất yếu của các doanh nghiệp, tập đoàn lớn. Tuy nhiên, về mặt kỹ thuật để có được một kết quả tốt từ KPTT đó thực sự là một khó khăn và thách thức đối với các doanh nghiệp cũng như các chuyên gia. Vì KPTT phải được xây dựng dựa trên các giải thuật mới, định hướng theo như cầu của từng doanh nghiệp để nó giải quyết các bài toán về kinh doanh cho doanh nghiệp. Một số kỹ thuật thường được sử dụng để KPDL hiện nay như: phân lớp dữ (Classification), phân cụm (Clustering), cây quyết định (Decision tree), Mạng Nơ-ron, phương pháp láng giềng gần nhất (K Nearest Neighbors)…

### Quá trình khai phá dữ liệu

KPDL là một bước quan trọng trong quá trình KPDL. Công việc chính của giai đoạn này thực hiện là áp dụng các kỹ thuật khai phá, sau đó sẽ trích chọn ra các mẫu thông tin, các mối liên hệ với nhau trong dữ liệu. Kết quả sau khi thực hiện giai đoạn này là ta sẽ tìm ra được các dữ kiện thông tin mới, hữu ích ẩn chứa trong CSDL và từ kết quả có được sẽ dùng phục vụ cho mô tả và dự đoán. Và đây cũng là giai đoạn duy nhất trong quả quy trình để tìm ra được thông tin mới.

-   Mô tả dữ liệu là công việc tóm tắt các văn bản hoặc biểu diễn một cách trực quan dễ hiểu những đặc điểm chung của những thuộc tính dữ liệu mà con người có thể dễ dàng hiểu được.
-   Dự đoán là dựa trên những dữ kiện hiện có để từ đó ta có thể đoán ra được các quy luật từ các mối liên hệ giữa các thuộc tính của dữ liệu và ta có thể rút ra được các pattern (mẫu). Dự đoán được những giá trị mà ta chưa biết hoặc những giá trị trong quá khứ hoặc những giá trị có thể đúng trong tương lai của dữ liệu.

    Quá trình KPDL gồm các bước:

-   **Bước 1:** Xác định nhiệm vụ. Ở bước này ta cần xác định chính xác, rõ ràng các vấn đề, mục tiêu, nhiệm vụ mà ta cần giải quyết.
-   **Bước 2:** Xác định các dữ liệu, dữ kiện liên quan. Trích chọn các dữ liệu, dữ kiện có liên quan để sử dụng chúng và xây dựng các giải pháp hợp lý.
-   **Bước 3:** Thu thập và tiền xử lý dữ liệu. Thu thập dữ liệu để đào tạo mô hình học máy là bước cơ bản trong quá trình học máy. Các dự đoán được cho ra kết quả tốt khi các dữ liệu được đào tạo đủ tốt. Sau khi được thu thập, dữ liệu sẽ được xử lý trước thành một định dạng mà thuật toán học máy có thể sử dụng được.
-   **Bước 4:** Tiến hàng khai phá bằng thuật toán KPDL. Lựa chọn các thuật toán cần thiết và thực hiện việc KPDL để tìm được các mẫu có ý nghĩa, các mẫu này được biểu diễn dưới dạng luật kết hợp, biểu thức hồi quy, cây quyết định… tương ứng với ý nghĩa của nó.

### Các kỹ thuật tiếp cận trong khai phá dữ liệu

Theo quan điểm của học máy (IBM, 2019), các kỹ thuật KPDL gồm có:

-   *Học có giám sát (Supervised learning):* được xác định bằng cách sử dụng các bộ dữ liệu được gán nhãn để đào tạo các thuật toán nhằm phân loại dữ liệu hoặc dự đoán kết quả một cách chính xác.

Học có giám sát có thể được chia thành 2 loại khi khai phá dữ liệu: Phân lớp (Classification) và Hồi quy (Regression):

-   **Phân lớp:** sử dụng một thuật toán để gán một cách chính xác dữ liệu thử nghiệm vào các danh mục cụ thể. Nó nhận biết các thuộc tính cụ thể trong tập dữ liệu và đưa ra một số kết luận về cách các thuộc tính đó được gán nhãn hoặc xác định. Xác thuật toán phân loại phổ biến là máy vector hỗ trợ (SVM – Support Vector Machine), cây quyết định (Decision tree), láng giềng gần nhất (K Nearest Neighbor), rừng cây ngẫu nhiên (Random Forest)…
-   **Hồi quy:** được sử dụng để hiểu mối quan hệ giữa các biến phụ thuộc vào các biến độc lập. Nó thường được sử dụng để đưa ra các dự đoán, chẳng hạn như doanh thu bán hàng cho một doanh nghiệp nhất định. Hồi quy tuyến tính, hồi quy logistic, và hồi quy đa thức là các thuật toán hồi quy phổ biến.
-   *Học không giám sát (Unsupervised learning):* còn gọi là học máy không giám sát, sử dụng thuật toán học máy để phân tích và phân cụm các tập dữ liệu không được dán nhãn. Các thuật toán này khám phá các mẫu hoặc nhóm dữ liệu ẩn mà không cần sự can thiệp của con người.

Mô hình học không giám sát được sử dụng cho ba nhiệm vụ chính: phân cụm (Clustering), kết hợp (Association) và giảm chiều dữ liệu (Dimentionality Redution).

-   Phân cụm (Clustering): Phân cụm là một kỹ thuật khai thác dữ liệu nhằm nhóm các dữ liệu chưa được gắn nhãn dựa trên những điểm tương đồng hoặc khác biệt của chúng. Các thuật toán phân cụm được sử dụng để xử lý các đối tượng dữ liệu thô, chưa được phân loại thành các nhóm được biểu thị bằng cấu trúc hoặc mẫu trong thông tin. Một số phương pháp phân cụm phổ biến có thể kể đến như phương pháp Kmeans, phương pháp phân cụm phân cấp (Hierarchical clustering), phương pháp phân cụm phân hoạch…
-   Luật kết hợp (Association Rules): Luật kết hợp là một phương pháp dựa trên quy tắc để tìm mối quan hệ giữa các biến trong một dữ liệu nhất định. Phương pháp này thường được sử dụng để phân tích giỏ hàng trên thị trường, cho phép các công ty hiểu rõ hơn về mối quan hệ giữa các sản phẩm khác nhau. Biết được thói quen tiêu dùng của khách hàng giúp doanh nghiệp phát triển các chiến lược bán chéo và công cụ xuất khẩu tốt hơn. Chẳng hạn, tại một cửa hàng mỹ phẩm, luật kết hợp có thể cho thấy “60% nữ giới vào siêu thị mua son thì có tới 80% trong số họ sẽ mua thêm phấn”.
-   Giảm chiều dữ liệu (Dimentionality Reduction): Mặc dù nhiều dữ liệu hơn thường mang lại kết quả có độ chính xác hơn nhưng nó cũng có thể ảnh hưởng đến hiệu suất của các thuật toán học máy và cũng có thể gây khó khăn cho việc trực quan hóa các tập dữ liệu. Giảm chiều dữ liệu là một kỹ thuật được sử dụng khi số lượng tính năng hoặc kích thước trong một tập dữ liệu nhất định quá cao. Nó giảm số lượng dữ liệu đầu vào xuống kích thước có thể quản lý được đồng thời duy trì tính toàn vẹn của tập dữ liệu nhiều nhất có thể.

### Phân cụm dữ liệu và thuật toán toán Kmeans

#### Phân cụm dữ liệu là gì?

Phân tích cụm, giống như phân tích không gian rút gọn (phân tích nhân tố), liên quan đến ma trận dữ liệu trong đó các biến chưa được phân chia trước thành các tập hợp con tiêu chí so với yếu tố dự đoán.

Phân cụm dữ liệu được xem là một phương pháp học không giám sát, vì nó thực hiện phân nhóm các đối tượng không được dán nhãn. Mục tiêu của phân tích cụm là tìm ra các nhóm đối tượng tương tự nhau, trong đó “sự tương đồng” giữa mỗi cặp đối tượng có nghĩa là một thước đo tổng thể nào đó đối với toàn bộ tập hợp các đặc điểm.

Phân cụm được các chuyên gia sử dụng để phân loại khách hàng, phân khúc khách hàng theo những đặc điểm về khách hàng đã xác định từ trước ví dụ sử dụng phân cụm để phân khúc khách hàng dựa theo điểm tín dụng (credit scores) trong ngành tài chính ngân hàng, hay phân tích khách hàng Customer 360, sử dụng mô hình RFM với bộ ba chỉ số Recency, Frequency và Monetary để phân nhóm khách hàng từ đó tìm ra nhóm khách hàng nào là nhóm khách hàng mục tiêu cho doanh nghiệp.

Các bước cơ bản khi thực hiện phân cụm:

-   Lựa chọn đặc trưng: là một kỹ thuật cần thiết để giảm vấn đề về kích thước trong tác vụ khai thác dữ liệu. Các đặc trưng cần phải được tiền xử lý (xử lý nhiễu, trùng lặp…) trước khi được dùng cho các bước tiếp theo. Kết quả phân cụm sẽ khác nhau nếu các đặc trưng được lựa chọn sẽ khác nhau.
-   Chọn độ đo: ứng với từng phương pháp phân cụm khác nhau mà ta lựa chọn các độ đo phù hợp để cho ra được kết quả phù hợp nhất.
-   Tiêu chuẩn phân cụm: ứng với mỗi tập dữ liệu khác nhau sẽ tạo ra các cụm khác nhau và từ đó có các tiêu chuẩn phân cụm khác nhau. Từ các hàm chi phí (tính độ đo giữa các cụm) mà ta có thể tính ra được chi phí và chọn ra tiêu chuẩn phân cụm hợp lý.
-   Thực thi thuật toán phân cụm: các giải thuật phân cụm khác nhau sẽ được sử dụng ở giai đoạn này, với mục tiêu làm sáng tỏ các cấu trúc cụm của tập dữ liệu đầu vào.
-   Kiểm định kết quả: Sau khi thực thi các thuật toán phân cụm và thu được kết quả phân cụm thì ta phải kiểm tra tính đúng đắn và hợp lý của nó. Các kiểm định phù hợp sẽ được sử dụng ở giai đoạn này để lựa chọn và công nhận kết quả.
-   Giải thích kết quả: Dựa vào kinh nghiệm thực tế và kết quả phân cụm vừa đạt được, các chuyên gia trong lĩnh vực phải kết hợp những bằng chứng thực nghiệm và các kỹ năng phân tích để đưa ra các kết quả đúng đắn và phù hợp nhất.

#### Một số phương pháp phân cụm dữ liệu

a. Phương pháp phân cụm phân cấp (Hierarchical clustering)

(Debomit Day, 2023) Phân cụm phân cấp là một phương pháp phân cụm dữ liệu dựa trên liên kết giữa các đối tượng. Phương pháp này chia dữ liệu thành một phân cấp hệ thống của các cụm, với các cụm ở cấp thấp hơn được hợp nhất thành các cụm ở cấp cao hơn. Có 2 chiến lược phân cụm phân cấp chính:

-   Chiến lược hợp nhất (agglomerative): Phương pháp này sẽ đi theo chiều bottum-up (từ dưới lên trên). Quá trình này bắt đầu ở mức thấp nhất, tại các node lá, còn được biết đến là “leaf node” hoặc “terminal node”. Ban đầu, mỗi quan sát được xem xét như là một cụm độc lập, được đại diện bởi một node lá. Ở mỗi cấp độ, chúng ta nỗ lực hợp nhất một cặp cụm để tạo ra một cụm mới ở cấp độ cao hơn. Cụm mới này được biểu diễn bởi các node quyết định (non-leaf node). Do đó, sau mỗi bước hợp nhất, số lượng cụm giảm đi. Chúng ta lựa chọn các cụm trung gian không giao nhau để hợp nhất, đảm bảo tính hiệu quả của quá trình này.
-   Chiến lược phân chia (divisive): Phương pháp được thực hiện theo hướng từ trên xuống (top-down), bắt đầu từ node gốc của đồ thị. Node gốc này chứa toàn bộ các quan sát, và ở mỗi cấp độ, chúng ta thực hiện phân chia đệ qui của các cụm hiện tại thành hai cụm mới. Quá trình phân chia được thực hiện sao cho tạo ra hai cụm mới với sự tách biệt lớn nhất có thể.

    ![](media/d0a62e4a5b2ba069c4cd895f9cf5a495.png)

    Hình 2.51 Minh họa chiến lược phân chia

    *Nguồn: Hierarchical Clustering in Machine Learning, GeeksforSeek*

b. Phương pháp phân cụm phân hoạch (Hierachical Partitional)

Đây là phương pháp mà ở đó các phân vùng sẽ được phân chia và được đánh giá theo một số tiêu chí. Phương pháp này quy định mỗi điểm dữ liệu chỉ được tồn tại trong một cụm riêng biệt. Thuật toán Kmeans là một trong những thuật toán phân cụm phân hoạch được sử dụng phổ biến nhất.

#### Thuật toán phân cụm Kmeans

Thuật toán Kmeans là một trong những thuật toán phân cụm dữ liệu không giám sát (Unsupervised Learning). Thuật toán này được sử dụng để phân dữ liệu không được dán nhãn (label) thành các cụm khác nhau sao cho các điểm dữ liệu trong cùng một cụm có tính chất giống nhau, còn các điểm dữ liệu trong các cụm khác nhau thì có tính chất khác nhau.

Thuật toán Kmeans có thể được sử dụng trong nhiều lĩnh vực khác nhau, như:

-   Khai phá dữ liệu: thuật toán Kmeans có thể được sử dụng để phân tích dữ liệu và tìm ra các mẫu, xu hướng trong dữ liệu.
-   Xử lý hình ảnh: thuật toán có thể được sử dụng để phân loại các đối tượng trong hình ảnh thông qua các thuộc tính của đối tượng trong hình ảnh, chẳng hạn như màu sắc, độ sáng, kích thước, vị trí…
-   Công nghệ thông tin: ngoài ra Kmeans có thể được ứng dụng trong việc phân tích lưu lượng truy cập mạng, phân loại email…
-   Thuật toán Kmeans thường thích hợp hơn với các tập dữ liệu dạng số vì cần phải tính toán khoảng cách giữa các điểm dữ liệu.

**Thuật toán hoạt động với các bước sau:**

-   Bước 1: Khởi tạo tâm cụm

Mục tiêu của bước này là tạo các tâm cụm ban đầu. Các tâm cụm là các điểm dữ liệu đại diện cho các cụm. Có nhiều cách để khởi tạo các tâm cụm như: chọn ngẫu nhiên các điểm dữ liệu trong tập dữ liệu làm tâm cụm hoặc chọn các điểm dữ liệu nằm ở vị trí xa nhất nhau làm tâm cụm

-   Bước 2: Phân cụm dữ liệu

Mục tiêu của bước này là gán các điểm dữ liệu cho các cụm. Mỗi điểm dữ liệu sẽ được gán cho cụm có tâm gần nhất với nó. Để tính toán khoảng cách giữa một điểm dữ liệu và một tâm cụm, ta có thể sử dụng các phép đo khoảng cách khác nhau, chẳng hạn: (KTQD, ĐH, 2019)

-   Khoảng cách Euclide: đây là phép đo khoảng cách phổ biến nhất. Trong mặt phẳng Euclid, giả sử điểm **p** �có tọa độ là **(p1, p2)** (�1,�2)và điểm **p** �có tọa độ là **(q1, q2)**. (�1,�2)Khi đó khoảng cách Euclide giữa **p** �và **q** �được tính bằng công thức:‬‬‬‬‬‬‬‬‬‬‬‬‬‬‬

    ‬‬‬‬‬‬‬‬‬‬‬‬‬‬‬‬‬‬‬‬‬‬![](media/1423de65bea2da2db80e974d96911309.png)

-   Khoảng cách Manhattan: phép đo khoảng cách này có thể phù hợp với các tập dữ liệu có dữ liệu không đồng nhất. Ví dụ, trong không gian Euclide, điểm **p** �có tọa độ là **(p1, p2)** (�1,�2)và điểm **p** �có tọa độ là **(q1, q2)**. (�1,�2)Khi đó khoảng cách Manhattan giữa **p** �và **q** �được tính bằng công thức:‬‬‬‬‬‬‬‬‬‬‬‬‬‬‬‬‬‬‬‬‬‬‬

    ![A black text on a white background Description automatically generated](media/611c1955d515d260dd3e7f6b157eea79.png)‬‬‬

-   Khoảng cách Minkowski: đây là phép đo tổng quát của khoảng cách Euclide và Manhattan. Với 2 điểm **X** và **Y** trong không gian có tọa độ là **X(x1, x2, …, xn)** và **Y(y1, y2,…, yn ).** Khi đó, khoảng cách Minkowski giữa **X** và **Y** đươc tính bằng công thức:

    ![](media/da8dbf7ec65fd2512856a5843ead6323.png)

-   Bước 3: Cập nhật các cụm

Ở bước này, ta cập nhật các tâm cụm bằng cách lấy trung bình cộng của tất cả các điểm dữ liệu đã được gán vào cụm đó.

-   Bước 4: Lặp lại các bước 2 và 3

Thuật toán sẽ tiếp tục lặp lại các bước 2, 3 cho đến khi đạt được một điều kiện dừng nào đó. Điều kiện dừng phổ biến nhất là các tâm cụm không thay đổi trong một số lần lặp nhất định.

**  
**

**Một số hạn chế của thuật toán:**

-   Do được tính toán bởi các giá trị trung bình nên thuật toán sẽ không hoạt động ổn định nếu dữ liệu bị nhiễu, chứa nhiều các phần tử ngoại lai…
-   Ngoài ra, vị trí của tâm cụm sẽ bị phụ thuộc vào điểm mà chúng được khởi tạo ban đầu. Do đó, kết quả khác nhau có thể được trả về nếu vị trí khởi tạo tâm cụm khác nhau mặc dù số lượng cụm không thay đổi.

### Các thuật toán xác định số cụm tối ưu

#### Phương pháp khuỷu tay (Elbow methods)

(KTQD, 2019) Phương pháp đề cập tới việc tìm k tối ưu thông qua biểu diễn đồ họa. Nó hoạt động bằng cách tìm tổng bình phương khoảng cách giữa các điểm trong cụm (Within-cluster sum of square – WCSS hoặc WSS). WSS được tính theo công thức sau:

![](media/46febccb4923bc560523fe79dedb0519.png)

WSS chính là tổng khoảng cách bình phương giữa các điểm trong một cụm và tâm của cụm. q(i) là giá trị đặc trưng cho tâm cụm, nếu điểm pi gần với trọng tâm tương ứng của chúng, giá trị WSS tương đối nhỏ.

Biểu đồ khuỷu tay hiển thị các giá trị WSS trên trục y tương ứng với các giá trị khác nhau của K trên trục x. Khi nhìn thấy hình dạng khuỷu tay trong biểu đồ, chúng ta chọn giá trị K nơi khuỷu tay được tạo. Chúng ta có thể gọi đây là điểm khuỷu tay. Thuật toán Elbow chỉ ra số cụm k sao cho WSSk và WSSk+1 chênh lệch không đáng kể. Tức là, kể từ điểm khuỷu tay, việc tăng giá trị K không dẫn đến giảm đáng kể giá trị WSS.

![](media/7c2813aa5a3401739836c43748e850c3.png)

Hình 2.61 Minh họa phương pháp Elbow

*Nguồn: Internet*

Tuy nhiên, trong phần lớn các tập dữ liệu thực tế, điểm uốn khuỷu tay thường không thể hiện rõ ràng nên rất khó để xác định bằng phương pháp Elbow. Điều này dẫn đến việc dễ nhầm lẫn trong việc tìm giá trị K.

#### Phương pháp điểm hình bóng trung bình (Average Silhouette)

Điểm Silhouette là một công cụ để đánh giá tính phù hợp của kết quả phân cụm bằng cách cung cấp thước đo định lượng về mức độ phân biệt và xác định rõ ràng của các cụm. Điểm Silhouette định lượng mức độ phù hợp của một điểm dữ liệu với cụm được chỉ định và mức độ khác biệt của nó với các cụm khác. Nó đo lường sự gắn kết và phân tách các điểm dữ liệu trong các cụm và giúp xác định xem các cụm có được phân tách tốt và đồng nhất bên trong hay không.

Hệ số Silhouette được tính theo công thức sau:

Silhouette Score (*i*) =

Trong đó:

-   **bi** là khoảng cách trung bình giữa một điểm dữ liệu với tất cả các điểm dữ liệu trong cụm khác gần nhất. Khoảng cách này cũng có thể được gọi là khoảng cách trung bình cụm gần nhất.
-   **ai** là khoảng cách trung bình giữa một điểm dữ liệu với tất cả các điểm dữ liệu trong cụm đó.

Giá trị của hệ số Silhouette thay đổi từ -1 đến 1. Nếu điểm là 1 thì cụm đó dày đặc và tách biệt tốt hơn các cụm khác. Giá trị gần 0 biểu thị các cụm chồng chéo với các mẫu và rất gần ranh giới quyết định của các cụm lân cận. Nếu giá trị nằm trong khoảng từ [-1, 0] cho biết các mẫu có thể đã được gán sai cụm.

![Selecting optimal number of clusters in KMeans Algorithm(Silhouette Score)  \| by Jyoti Yadav \| Medium](media/8abcfb2258eb2702c942a0f7c4ccf1d1.png)

Hình 2.62 Minh họa thuật toán Average Silhouette

*Nguồn: Internet*

#### Phương pháp thống kê khoảng cách (Gap Statistics)

Thống kê khoảng cách là một thống kê đo lường chất lượng của cụm. Nó so sánh khoảng cách trung bình giữa các điểm trong cùng một cụm với khoảng cách trung bình giữa các điểm trong một tập dữ liệu ngẫu nhiên có cùng độ phân tán với tập dữ liệu ban đầu. Nếu tập dữ liệu ban đầu có cấu trúc cụm, thì khoảng cách trung bình giữa các điểm trong cùng một cụm sẽ nhỏ hơn khoảng cách trung bình giữa các điểm trong một tập dữ liệu ngẫu nhiên.

Theo Robert Tibshirani (Robert Tibshirani, 2001), với *S***k** *+ 1*  là độ lệch chuẩn ta cần chọn giá trị k nhỏ nhất, thỏa mãn:

Gap(**k) ≥** Gap(**k***+1*) – *s***k** *+ 1*

Ý tưởng của cách tiếp cận này là chuẩn hóa đồ thị của **log(Wk)** bằng cách so sánh nó với kỳ vọng của nó dưới sự phân bố dữ liệu tham chiếu null thích hợp. Khi đó, ước tính số cụm tối ưu là giá trị của k mà **log(Wk**) nằm xa nhất bên dưới đường cong tham chiếu này. Do đó, Gap(**k)** được xác định:

![](media/a9d5a32fdf3df353569fed5a8a58a153.png)

Với *Wk* được định nghĩa là:

![](media/d40f89e65b1f5b7a374be5936604c714.png)

Tại đây, **C** là một cụm được tính toán ví dụ bởi Kmeans, *d* là khoảng cách giữa 2 điểm *i* và *i’* có thể được tính toán dựa trên khoảng cách Euclide.

Về bản chất, ta sẽ so sánh giá trị log(*Wk*) của dữ liệu gốc với giá trị log(*Wk*) được áp dụng cho phân phối chuẩn. Nếu dữ liệu được phân cụm với k tối ưu thì tại đó, *Wk*  cho dữ liệu gốc sẽ nhỏ hơn *Wk* được áp dụng cho dữ liệu phân phối chuẩn. Bởi *Wk* là một phép đo biểu diễn phương sai giữa các cụm.

![A comparison of a graph Description automatically generated with medium confidence](media/e44ae7c0d8d3b2d2efcf6e71bd028aa2.png)

Hình 2.63 Minh họa phương pháp Gap Statistics

*Nguồn:* (Robert Tibshirani, 2001)

Cách thống kê khoảng cách là một phương pháp ước tính số lượng cụm hiệu quả và hoạt động. Nó có thể được sử dụng cho nhiều loại dữ liệu, bao gồm cả tập dữ liệu có cấu trúc phức tạp.

## ÁP DỤNG THUẬT TOÁN PHÂN CỤM KMEANS VÀO BÀI TOÁN TÌM ĐỊA ĐIỂM KINH DOANH QUÁN CÀ PHÊ TẠI HÀ NỘI

### Quy trình thực hiện

#### Thu thập, làm sạch, tích hợp dữ liệu

##### Dữ liệu về diện tích, dân số

Trước tiên, chúng ta sẽ thu thập dữ liệu về dân số của các quận huyện tại Hà Nội. Dữ liệu được thu thập từ Wikipedia (Wikipedia, 2020).

![](media/64421bbb269e47a5e2f4299fa6589d92.png)

Hình 3.11 Dữ liệu thô về địa lý, dân cư

*Nguồn: Tổng hợp*

Câu lệnh ‘read_html’ được sử dụng để lấy dữ liệu hiển thị trên trang web sau đó thực hiện làm sạch dữ liệu với các tác vụ như chuyển đổi dữ liệu từ dạng chữ (text) sang dạng số, chuyển đổi tên các quận huyện để có sự đồng bộ. Cuối cùng, chúng ta sẽ thu được dữ liệu về dân số của các quận huyện tại Hà Nội như sau:

![](media/e874c51f8da57efd969e6da0fdf98319.png)

Bảng 3.11 Dữ liệu dân cư sau khi được làm sạch

*Nguồn: Tổng hợp*

Để phục vụ cho việc trực quan hóa dữ liệu trên bản đồ, chúng ta cần có thông tin về tọa độ của các quận huyện. Sử dụng Nominatim API (là một API web mã nguồn mở được sử dụng để truy vấn dữ liệu địa lý từ OpenStreetMap) để lấy thông tin về dữ liệu của các quận huyện.

Khởi tạo biến geolocator và tạo vòng lặp, để lặp qua từng quận huyện và lấy thông tin về kinh độ, vĩ độ tại quận huyện đó. Sau đó lưu các thông tin vào một danh sách như sau:

![](media/a3b7d156443040f2d76f704582b471c0.png)

Hình 3.12 Dữ liệu về tọa độ của các quận huyện

*Nguồn: Tổng hợp*

##### Dữ liệu về giá nhà đất

Dữ liệu cần thu thập tiếp theo là dữ liệu về giá nhà, giá bất động sản tại các quận huyện. Để thuận tiện cho việc phân tích, chúng ta sẽ lấy dữ liệu về giá đất trên 1 mét vuông tại các khu vực.

Dữ liệu được lấy từ trang web Mogi.vn (Mogi, 2023)

![](media/16bcd38dd5045d1d4c3cce68f6943472.png)

Hình 3.13 Dữ liệu về giá nhà đất

*Nguồn: Tổng hợp*

##### Dữ liệu về số lượng các công ty, doanh nghiệp

Về dữ liệu cho số lượng các doanh nghiệp tại địa bàn các quận huyện của Hà Nội sẽ được trích xuất từ trang *Thông tin doanh nghiệp”* (CO., 2023)

Sử dụng thư viện BeautifulSoup thể lấy nội dung HTML của trang web từ đó truy cập vào các thể để lấy thông tin. Output cuối cùng thu được số lượng doanh nghiệp tại từng quận huyện như sau:

![](media/15562742a8eb6d719be794f619886888.png)

Hình 3.14 Dữ liệu về thông tin doanh nghiệp

*Nguồn: Tổng hợp*

Như vậy, sau khi thu thập và xử lý dữ liệu, cần hợp các thông tin lại trong 1 dataframe, sau đó chúng ta sẽ thu được kết quả như sau:

![](media/d27c690ecf49e2e53b2ade964c74c5fd.png)

Hình 3.15 Dữ liệu tổng hợp sau khi được làm sạch

*Nguồn: Tổng hợp*

Sử dụng thư viện Folium để trực quan hóa vị trí của các quận huyện lên bản đồ:

![](media/d38762d52068da341a447f1ceb4d3fc0.png)

Hình 3.16 Minh họa vị trí các quận huyện lên bản đồ

*Nguồn: Tổng hợp*

Ngoài ra, chúng ta cũng sẽ tham khảo dữ liệu về thông tin của các quán ăn, các quán cà phê hay các địa điểm tại các quận huyện với vị trí tọa độ đã được đánh dấu. Để lấy được các thông tin trên, có thể sử dụng 1 trong 2 API sau: Google Place API và Foursquare API. Một số thông tin về 2 API này:

-   Google Place API:
-   Ứng dụng bản đồ và dẫn đường: Google Places API rất phù hợp cho các ứng dụng liên quan đến bản đồ, dẫn đường, và thông tin vị trí. Ví dụ, ứng dụng tìm kiếm địa điểm gần đây, địa điểm du lịch, và thông tin về nhà hàng, khách sạn, trạm xăng.
-   Dịch vụ đặt chỗ và đặt phòng: Các ứng dụng hoặc trang web đặt chỗ như nhà hàng, phòng khách sạn, sân bay có thể sử dụng Google Places API để hiển thị các địa điểm và thông tin chi tiết cho người dùng.
-   Ứng dụng gợi ý hoặc tìm kiếm yêu thích: Google Places API có khả năng gợi ý địa điểm dựa trên sở thích và lịch sử của người dùng. Ví dụ, ứng dụng xác định và gợi ý các quán cà phê dựa trên thói quen uống cà phê của người dùng.
-   Foursquare API
-   Ứng dụng xã hội địa điểm: Foursquare API là lựa chọn tốt cho các ứng dụng có tính năng xã hội cao, như ứng dụng đánh giá, chia sẻ địa điểm và check-in. Ví dụ, ứng dụng cho phép người dùng đánh giá và chia sẻ địa điểm yêu thích.
-   Ứng dụng dành cho người yêu thích thực phẩm: Foursquare API có khả năng cung cấp thông tin địa điểm tốt cho các ứng dụng liên quan đến thực phẩm và đồ uống, chẳng hạn như ứng dụng tìm kiếm các món ăn địa phương hoặc ứng dụng đánh giá nhà hàng.
-   Ứng dụng xã hội vị trí: Foursquare API cho phép tạo các trải nghiệm xã hội quanh việc check-in, tạo danh sách yêu thích và gợi ý dựa trên mối quan hệ giữa người dùng.

Tuy nhiên, Google Place API có nhiều điểm hạn chế khi thu thập dữ liệu. Dựa trên tài liệu của Google Place API (Google, 2023), theo mặc định, mỗi phản hồi trả về tối đa 20 kết quả “establishment” cho mỗi truy vấn và tối đa là 80 giá trị nếu cộng dồn giá trị cũ trong 1 ngày, vì có giới hạn số lượt query dữ liệu đối với phiên bản miễn phí. Nếu query nhiều địa điểm sau đó hợp nhất lại thì khả năng rất cao dữ liệu sẽ xảy ra tình trạng duplicate, vì bán kính các địa điểm có thể trùng lên nhau. Ngoài ra, format dữ liệu trả về dưới dạng JSON, nên phải ETL và xử lý dữ liệu mất khá nhiều thời gian.

![](media/8a8a19c8085a94749e2bed21062f8475.png)

Hình 3.17 Hạn chế của Google Place API

*Nguồn: Tổng hợp*

Do đó, chúng ta sẽ sử dụng Foursquare API cho việc thu thập dữ liệu các công ty doanh nghiệp tại các quận huyện. Với Foursquare API, dữ liệu thường chú trọng vào các địa điểm giải trí, nhà hàng, quán bar và các địa điểm tương tự khác với Google Place API thường trả về các địa điểm công cộng. Thông tin các địa điểm trả về từ Foursquare cũng chi tiết hơn so với API của Google. Dữ liệu hoàn chỉnh từ Foursquare như sau:

![](media/fa6fd15265642712e8565825c09321f1.png)

Hình 3.18 Dữ liệu thu thập được từ Foursquare API

*Nguồn: Tổng hợp*

Như vậy, sau khi tiến hành thu thập dữ liệu, ta thu được 2 tập dữ liệu với các thuộc tính như sau:

-   Bảng tổng hợp dữ liệu về các quận huyện tại Hà Nội:
-   Số trường dữ liệu: 12
-   Số bản ghi: 30

Bảng 3.12 Mô tả dữ liệu tổng hợp về các quận huyện tại Hà Nội

-   Bảng dữ liệu về các địa điểm kinh doanh tại Hà Nội:
-   Số trường dữ liệu: 7
-   Số bản ghi: 2387

Bảng 3.13 Mô tả dữ liệu về các địa điểm kinh doanh tại Hà Nội

#### Tổng quan về dữ liệu hiện có

Số lượng các địa điểm có sự chênh lệch rất lớn khi số lượng thu thập được từ các quận nội thành cao hơn rất nhiều lần so với các quận huyện ngoại thành Hà Nội. Quận Tây Hồ hiện đang là quận có nhiều địa điểm kinh doanh nhất với hơn 200 địa điểm được thu thập, nhiều hơn 50 lần so với huyện Ứng Hòa, huyện chỉ có 4 địa điểm được ghi nhận.

![](media/36492875535163244fdd161393cf2bee.png)

Hình 3.19 Số lượng địa điểm tại mỗi quận huyện

*Nguồn: Tổng hợp*

Những loại kinh doanh phổ biến nhất tại Hà Nội hiện nay.

![](media/b3a567c32040c40fde0b975eb36683dc.png)

Hình 3.110 Top 5 loại hình kinh doanh phổ biến nhất

*Nguồn: Tổng hợp*

Nhìn chung, cà phê đang là loại hình kinh doanh phổ biến nhất với 283 quán được ghi nhận. Theo sau đó là khách sạn, nhà hàng Việt Nam và quán phở. Sự phổ biến này hầu như cũng đúng với các quận huyện khi cà phê và khách sạn thường xuyên được bắt gặp nhất.

![](media/58e46c5f72eb5764353f6e63d6ae763d.png)

Hình 3.111 Top 10 những loại hình kinh doanh phổ biến tại từng quận

*Nguồn: Tổng hợp*

#### Tiền xử lý dữ liệu (Preprocessing Data)

##### Chuẩn bị dữ liệu

Trong đề tài này, đối với dữ liệu phân loại như các địa điểm kinh doanh chúng ta cần chuyển đổi về dạng số để phục vụ cho việc phân cụm bằng phương pháp Kmeans. **One Hot Encoding** là phương pháp phổ biến để xử lý dữ liệu phân loại trong học máy. Các biến phân loại phải được thay đổi trong phần tiền xử lý vì các mô hình học máy yêu cầu các biến đầu vào dạng số. Dữ liệu danh nghĩa hoặc thứ tự có thể được tìm thấy trong dữ liệu phân loại.

Trong trường hợp trên, những giá trị như “Coffee Shop” sẽ được chuyển đổi thành các giá trị là 1 và 0, tương ứng với Yes và No. Sau đó sẽ sử dụng các giá trị này để xây dựng các clusters.

![](media/5c01f237c89184a8625b4344a1619463.png)

Hình 3.112 Mã hóa các loại địa điểm bằng One Hot Encoding

*Nguồn: Tổng hợp*

Cụ thể, One Hot Encoding sẽ tạo một ma trận **M x N** với số chiều **M** là số lượng category và số hàng **N** là số lượng địa điểm trong dataframe. Với mỗi địa điểm, giá trị 1 sẽ được gán nếu xuất hiện giá trị category tương ứng và ngược lại đối với giá trị 0.

Sau đó, chúng ta sẽ có một dataframe về tần suất xuất hiện của các quán cà phê bằng cách nhóm các địa điểm theo từng quận huyện, kết quả như sau:

![](media/e0ac474b17efdcbc5f020ab660f7fc47.png)

Hình 3.113 Tần suất xuất hiện của các quán cà phê tại từng quận huyện

*Nguồn: Tổng hợp*

Ngoài ra, đối với các yếu tố khác như giá nhà, mật độ dân số và số lượng công ty, doanh nghiệp xung quanh, chúng ta sẽ đưa về cùng một dataframe để phục vụ cho việc áp dụng phân cụm Kmeans.

Bảng dưới đây là ví dụ về dữ liệu được chuẩn bị để phân cụm. Trong đó, giá trị về giá nhà (AHP), mật độ dân số (APD), số lượng công ty (AC) được đưa về cùng một khoảng [0,1] để đồng nhất với giá trị tần số xuất hiện các quán cà phê tại Hà Nội.

![](media/d4c547b93f7b8975f00b4dd941f01e6e.png)

Bảng 3.14 Một số dữ liệu dùng để phân cụm

##### Xác định số cụm tối ưu

Để dự đoán số lượng cụm tối ưu cho dữ liệu trên, áp dụng phương pháp khuỷu tay (Elbow). Giá trị WCSS tương ứng với các giá trị k được biểu diễn trong biểu đồ dưới đây:

![](media/a52f893fc089c26e5757fb576a5d4a78.png)

Hình 3.114 Minh họa số cụm tối ưu với phương pháp Elbow

*Nguồn: Tổng hợp*

Có thể thấy từ k = 4, WCSS có giá trị giảm dần với tốc độ chậm hơn và gần như đi ngang, chứng tỏ các điểm dữ liệu trong cùng một cụm có xu hướng gần nhau hơn khi số cụm tăng lên. Điều này cho thấy rằng số cụm k tối ưu từ 4 trở lên sẽ không mang lại nhiều lợi ích cho việc phân cụm dữ liệu.

Tuy nhiên, giá trị k = 3 hay k = 5 vẫn có thể là điểm k tối ưu do sự xuất hiện của điểm gãy khuỷu tay là không rõ ràng. Do vậy, ta sẽ kiểm chứng kết quả phân cụm với 2 phương pháp Average Silhoutte Score và Gap Statistics.

##### Đánh giá kết quả phân cụm

a. Phương pháp hình bóng trung bình (Average Silhouette Method)

Phương pháp Silhoutte sẽ so sánh khoảng các cụm trong 1 cụm với các điểm khác nhau của các cụm khác.

| **Number of Cluster** | **Silhoutte Score** |
|-----------------------|---------------------|
| 3                     | 0.729598            |
| 4                     | 0.793690            |
| 5                     | 0.801146            |
| 6                     | 0.768893            |
| 7                     | 0.790760            |
| 8                     | 0.764098            |
| 9                     | 0.740304            |
| 10                    | 0.705014            |

Bảng 3.15 Hệ số Silhouette tương ứng với các giá trị k

Minh họa kết quả với biểu đồ dưới đây:

![](media/2efc3dc8598c1a971e9a926a06c718b8.png)

Hình 4.2 - 1 Đánh giá phân cụm với phương pháp Average Silhouette

*Nguồn: Tổng hợp*

Có thể thấy, Silhouette_score đạt giá trị cao nhất bằng 0.801146 tại k = 5. Điều này chứng tỏ rằng, với số cụm là 5, các điểm dữ liệu trong cùng một cụm sẽ có sự tương đồng cao nhất tức là các điểm sẽ ở gần nhau nhất.

b. Phương pháp thống kê khoảng trống (Gap Statistics Method)

Bảng kết quả thống kê với các cụm:

Bảng 3.16 Kết quả thống kê khoảng cách

Trong đó:

-   **n_clusters**: Số lượng cụm được phân.
    -   **gap_value**: Giá trị gap statistics. Giá trị này càng lớn thì kết quả phân cụm càng tốt.
    -   **ref_dispersion_std**: Độ lệch chuẩn của phân phối chuẩn được sử dụng để ước tính gap statistics.
    -   **sk**: Độ đồng đều của các cụm. Độ đồng đều của các cụm được ước tính bằng cách tính toán trung bình của khoảng cách giữa các điểm dữ liệu trong cùng một cụm. Độ đồng đều càng cao thì các điểm dữ liệu trong cùng một cụm càng gần nhau.
    -   **gap\***: Giá trị gap statistics được điều chỉnh cho độ lệch chuẩn của phân phối chuẩn.
    -   **sk\***: Độ đồng đều của các cụm được điều chỉnh cho độ lệch chuẩn của phân phối chuẩn.
    -   **diff**: Sự khác biệt giữa giá trị gap statistics và giá trị gap statistics được điều chỉnh.
    -   **diff\***: Sự khác biệt giữa độ đồng đều của các cụm và độ đồng đều của các cụm được điều chỉnh.

Ta cần chú ý vào 2 giá trị là **gap_value** và **sk.** Có thể thấy, tại k = 5 giá trị **gap_value** đạt cực đại (gap_value = 1.62576) và **sk** khá cao (sk = 0.12584), thể hiện bằng biểu đồ sau đây.

![](media/c41fd9c1c36e8f1196b4d4c51e1f5a55.png)

Hình 3.115 Đánh giá phân cụm với phương pháp Gap Statistics

*Nguồn: Tổng hợp*

Điều này chứng tỏ, với số cụm k=5 sự phân tách giữa các cụm được thể hiện rõ ràng nhất và các điểm trong cụm có sự đồng đều tương đối.

c. Kết luận

Trong khi phân cụm dữ liệu, dữ liệu sau khi được phân tách thành các cụm là phù hợp nhất khi thỏa mãn 2 yếu tố:

-   *Các điểm dữ liệu trong một cụm có khoảng cách gần nhau nhất.* Yếu tố này được đánh giá bởi hệ số Silhoutte.
-   *Khoảng cách giữa các cụm là xa nhất.* Nói cách khác, các cụm phân cách nhau rõ ràng nhất. Yếu tố này có thể được đánh giá bởi giá trị gap_value trong phương pháp thống kê khoảng cách.

Như vậy, sau khi đánh giá kết quả phân cụm bằng 2 phương pháp Average Silhouette Score và Gap Statistic ở phần a và b, **đều cho ra được số cụm tối ưu là 5.** Các thuộc tính của mỗi cụm được biểu diễn dưới bảng sau:

Bảng 3.17 Bảng biểu diễn các giá trị đặc trưng của các cụm

Trên bản đồ thực tế, **Cluster 0** tương ứng với **màu đỏ**, **Cluster 1** tương ứng với **màu tím**, **Cluster 2** tương ứng với màu **xanh dương**, **Cluster 3** tương ứng với màu **xanh lá** và **Cluster 4** tương ứng với **màu cam**.

**![](media/3d31a5d7fd6b75842d9244ac4b47b853.png)**

Hình 3.116 Vị trí các quận huyện trên bản đồ khi được phân tách với 5 cụm

*Nguồn: Tổng hợp*

#### Phân tích dữ liệu (Exploration Data Analysis - EDA)

##### Phân tích các đặc điểm của cụm dữ liệu

Sau khi thực hiện phân cụm dữ liệu, có thể nhận thấy một số đặc trưng của các cụm như sau:

-   **Cụm 0:** Là những huyện nằm ở ngoại thành xung quanh thành phố như Thanh Oai, Sơn Tây, Đan Phượng, Thường Tín… Đây là những nơi khá xa trung tâm, giá bất động sản khá rẻ, mật độ dân số ở mức vừa phải và chưa có nhiều quán cà phê khi tỷ lệ xuất hiện các quán cà phê ở đây chỉ khoảng 2.31% , do đó khi kinh doanh ở những khu vực này độ cạnh tranh sẽ không quá lớn.
-   **Cụm 1:** Là các quận nằm ở vùng biên, gần sát các quận trung tâm như Hà Đông, Thanh Trì, Bắc Từ Liêm, Đông Anh, Long Biên… Đây là những quận huyện đang phát triển, với mật độ dân số khoảng 7830 người/km2, trung bình khoảng 120 triệu đồng/m2 giá nhà đất. Đồng thời, lượng doanh nghiệp mở ra tại đây cũng cao hơn gần 5 lần so với các huyện nằm ở cụm 1. Do vậy, việc kinh doanh tại đây sẽ chứng kiến một sự cạnh tranh tương đối.
-   **Cụm 2:** Chỉ bao gồm quận Hoàn Kiếm. Quận Hoàn Kiếm nổi bật với giá bất động sản cực kỳ đắt (khoảng 580 triệu đồng/m2). Ngoài ra, mật độ dân số và số lượng doanh nghiệp tại đây cũng rất cao, nên các quán cà phê mở tại đây sẽ phải đối diện với sự cạnh tranh cực kỳ lớn.
-   **Cụm 3:** Bao gồm 5 quận trung tâm: Tây Hồ, Cầu Giấy, Đống Đa, Thanh Xuân và Hai Bà Trưng. Mật độ dân số trung bình và số lượng doanh nghiệp trung bình tại các quận này lớn nhất trong các cụm, giá nhà cũng rất cao (gần 200 triệu đồng/m2). Do đó, mức độ cạnh tranh tại đây cũng là rất lớn.
-   **Cụm 4:** Chỉ có huyện Phú Xuyên. Giá nhà, mật độ dân số và lượng doanh nghiệp tại đây thấp nhất trong 4 cụm. Có thể việc kinh doanh tại đây sẽ không đem lại hiệu quả cao.

Như vậy, xét về mức độ cạnh tranh, các cụm có ý nghĩa như sau:

-   **Cụm 0:** Cạnh tranh thấp
-   **Cụm 1:** Cạnh tranh tương đối
-   **Cụm 2:** Cạnh tranh rất cao
-   **Cụm 3:** Cạnh tranh cao
-   **Cụm 4:** Cạnh tranh rất thấp

##### Phân tích chi tiết các yếu tố

a. Giá nhà, giá bất động sản (Average House Price - AHP)

Sử dụng các phương pháp thống kê mô tả, phân bổ hay độ trải để xếp hạng mức độ giá bất động sản.

![](media/e35e17b375955b919f2f1e844439070f.png)

Hình 3.117 Thống kê mô tả giá nhà

*Nguồn: Tổng hợp*

Kết hợp với biểu đồ boxplot:

![](media/67f75ff6a3b477e6e259151dc003631c.png)

Hình 3.118 Biểu đồ boxplot về phân bổ giá nhà

*Nguồn: Tổng hợp*

Nhận xét:

-   IQR: nằm trong khoảng từ 19 đến 114, cho thấy 50% giá nhà trên một mét vuông (m2 ) tập trung trong khoảng giá từ 19 đến 114 triệu đồng / m2.
    -   Độ lệch chuẩn là 115.5 trong khi đó giá trị trung bình là 96.22 thể hiện giá nhà có sự phân tán khá lớn, với nhiều khu vực có giá nhà cao hơn đáng kể so với giá trung bình.
    -   Ta có thể chia các khoảng giá như sau:
        -   Giá rẻ (Low): 4 – 19.4 (triệu đồng)
        -   Giá trung bình (Medium): 19.4 – 56.95 (triệu đồng)
        -   Giá cao (High): 56.95 – 114 (triệu đồng)
        -   Giá rất cao (Very High): trên 114 (triệu đồng)

            Bảng 3.18 Bảng phân bổ giá nhà trung bình

b. Mật độ dân số (Average Population Density – APD)

Thống kê mô tả:

![](media/d826656693addbbba613787b1e92558a.png)

Hình 3.119 Thống kê mô tả mật độ dân số

*Nguồn: Tổng hợp*

Biểu đồ boxplot:

![](media/bb0717510b8c29de7a657e147a75dd8d.png)

Hình 3.120 Biểu đồ boxplot phân bổ mật độ dân số

*Nguồn: Tổng hợp*

Có thể thấy, 50% các khu vực có mật độ dân số thấp hơn 2448 người/ km2. 25% các khu vực có mật độ dân số thấp hơn 1372,25 người/km2. 25% các khu vực có mật độ dân số cao hơn 8533,75 người/ km2. Độ lệch chuẩn là rất lớn cho thấy sự phân tán trong mật độ dân cư là khá cao, sự phân bổ dân cư giữa các khu vực là rất lớn. Ta có thể chia ra các khoảng mật độ dân cư như sau

-   Mật độ dân số thấp (Low): 725 – 1372 người/km2
-   Mật độ dân số trung bình (Medium): 1372 – 2448 người/km2
-   Mật độ dân số cao (High): 2448 – 8533 người/km2
-   Mật độ dân số rất cao (Very High): trên 8533 người/km2

c. Số lượng doanh nghiệp trung bình (Average Company – AC)

Thống kê mô tả:

![](media/b92f904e4c824c4a7de55d7998804fec.png)

Hình 3.121 Thống kê mô tả số lượng doanh nghiệp

*Nguồn: Tổng hợp*

Đồ thị boxplot:

![](media/53119adabff8df5e96385f3608f1970e.png)

Hình 3.122 Biểu đồ boxplot phân bổ số lượng doanh nghiệp

*Nguồn: Tổng hợp*

Có thể thấy, số lượng các doanh nghiệp tại các quận huyện cũng thể hiện sự phân bổ không đồng đều. Các phân vị cho thấy:

-   25% số quận huyện có số lượng doanh nghiệp dưới 1.878 doanh nghiệp.
-   50% số quận huyện có số lượng doanh nghiệp dưới 4.856 doanh nghiệp.
-   75% số quận huyện có số lượng doanh nghiệp dưới 14.368 doanh nghiệp.

Trung bình, mỗi quận huyện tại Hà Nội có 9.360 doanh nghiệp. Con số này cho thấy Hà Nội là một thành phố có nền kinh tế phát triển mạnh mẽ, thu hút nhiều doanh nghiệp đến đầu tư và hoạt động. Giá trị nhỏ nhất là 982 doanh nghiệp, chỉ bằng 1,06% giá trị trung bình. Giá trị lớn nhất là 31.059 doanh nghiệp, gấp 33,16 lần giá trị trung bình. Sự chênh lệch lớn giữa giá trị nhỏ nhất và lớn nhất cho thấy có sự phân hóa khá lớn về số lượng doanh nghiệp giữa các đơn vị tại Hà Nội.

Như vậy, có thể tổng hợp các thông tin về mức độ phân bổ dân cư, giá bất động sản và số lượng các doanh nghiệp tại từng quận huyện như sau:

Bảng 3.19 Bảng tổng hợp thông tin các yếu tố

Khi đánh giá những yếu tố để lựa chọn một địa điểm phù hợp cho việc mở một quán cà phê, ta sẽ mong muốn địa điểm đó thỏa mãn các tiêu chí sau:

-   Chi phi bất động sản vừa phải để giảm chi phí ban đầu, hoặc có thể đánh đổi chi phí cơ hội với mật độ dân số (giả sử có thể chấp nhận giá nhà cao hơn nhưng mật độ dân số cũng cao hơn).
-   Nguồn khách hàng tiềm năng lớn, tức là ưu tiên những khu vực có nhiều công ty, doanh nghiệp, từ đó số lượng khách hàng sử dụng dịch vụ sẽ được đảm bảo.
-   Mật độ dân cư cao, độ nhận diện về mặt thương hiệu cũng sẽ tăng nhiều hơn và tiếp cận được nhiều khách hàng hơn.
-   Sự cạnh tranh giữa các đối thủ, bao gồm các quán cà phê và địa điểm cung cấp dịch vụ ăn uống khác, không đặt ra một thách thức quá lớn. Ví dụ, người tiêu dùng có khả năng chọn lựa giữa việc đến một quán ăn cung cấp cả dịch vụ cà phê thay vì chỉ hạn chế ở quán cà phê trong bữa trưa của họ.

    ![](media/eccc5ee1aeaee80cf6e5dda1f64996ed.png)

    Bảng 3.110 Bảng thông tin kết quả

    *Nguồn: Tổng hợp*

Như vậy, nhìn vào bảng thông tin trên, ta có thể lọc ra được 2 nhóm sau:

-   Nhóm 1: AHP Level **Medium** - APD Level **Medium** - AC Level **High** (chi phí nhà vừa phải, mật độ dân số tương đối, số lượng công ty, doanh nghiệp cao), *có 1 quận huyện.*
-   Nhóm 2: AHP Level **Medium** - APD Level **High** - AC Level **High** (Chi phí nhà tương đối, mật độ dân số cao, số lượng công ty, doanh nghiệp lớn), *có 1 quận huyện.*

Đối với **Nhóm 1**, quận thỏa mãn nhưng tiêu chí như chi phí nhà tương đối, mật độ dân số vừa phải, số lượng công ty, doanh nghiệp lớn là huyện Đông Anh. Đông Anh là huyện nằm trong Cluster 0, nằm ở vùng đang phát triển và độ cạnh tranh không quá lớn.

Đối với **Nhóm 2**, có 1 quận thỏa mãn tiêu chí chi phí nhà tương đối, mật độ dân số cao, số lượng công ty, doanh nghiệp lớn, chính là quận Gia Lâm. Giống như Đông Anh, Gia Lâm cũng là quận nằm ở Cluster 0.

Tuy nhiên, chúng ta cùng đánh giá trên những yêu tố thực tế khác:

-   Địa lý: so với Đông Anh, Gia Lâm hiện đang là quận nằm ở khu vực cửa ngõ phía Đông, nằm cạnh những tỉnh có sự phát triển kinh tế cao như Bắc Ninh, Hải Dương, Hải Phòng…
-   Giao thông: Gia Lâm có sự kết nối giao thông thuận tiện hơn khi đi khi là nút giao của các tuyến đường lớn như: Quốc lộ 5 nối tới Hưng Yên và Hải Dương, đường cao tốc Hà Nội – Bắc Giang, Hà Nội – Hải Phòng… Khi đó, các dịch vụ liên quan đến ăn uống và nghỉ ngơi trong đó có cà phê sẽ có tiềm năng phát triển nhiều hơn ở khu vực này.
-   Ngoài ra, trong khi Gia Lâm đã tiến lên trở thành Quận vào ngày 21/9/2023, theo Kết luận số 139-KL/TU của BCH Đảng bộ thành phố Hà Nội (Thành ủy Hà Nội, 2023), và dường như đang có sự ổn định về mặt sản xuất kinh tế hơn, so với huyện Đông Anh vẫn đang trong quá trình hoàn thành những chỉ tiêu để thành lập Quận.

Như vậy, dựa trên những yếu tố khách quan trên, có thể lựa chọn quận **Gia Lâm** là quận phù hợp cho việc kinh doanh quán cà phê tại Hà Nội với mục tiêu tối ưu chi phí và tối đa lợi nhuận một cách hiệu quả.

# KẾT LUẬN VÀ HƯỚNG PHÁT TRIỂN ĐỀ TÀI

Nội dung chính trong phần này tập trung đánh giá tổng quan về các kết quả đã đạt được so với mục tiêu ban đầu của đề tài, chỉ ra những hạn chế còn tồn tại và đưa ra hướng khắc phục. Từ đó, tìm ra những hướng phát triển mới và hiệu quả hơn.

### Kết luận

Đề tài đã trình bày một cách tổng quan và chi tiết những kiến thức liên quan đến khai phá tri thức, khai phá dữ liệu, các phương pháp khai phá dữ liệu, các kỹ thuật phân cụm và tìm số cụm tối ưu cho các bài toán phân cụm.

Hiểu được bài toán tìm địa điểm kinh doanh cho quán cà phê và những lợi ích của việc ứng dụng phân tích dữ liệu vào việc đưa ra quyết định trong sản xuất kinh doanh. Từ đó giải quyết được bài toán, đưa ra được một kết quả cụ thể.

Ngoài ra, đề tài cũng đã phân tích bài toán dựa trên nhiều yếu tố khác nhau, vận dụng những kiến thức thực tế dựa trên kết quả của dữ liệu để đưa ra những đánh giá khách quan nhất cho bài toán đã đặt ra.

### Hạn chế của đề tài và phương hướng phát triển

Phạm vi của đề tài hiện đang chỉ áp dụng cho thành phố Hà Nội, quy mô hiện chỉ đang dừng ở mức quận huyện, mà chưa thể chi tiết hơn về từng đơn vị hành chính của các quận huyện. Do đó, kết quả chỉ mang tính chất tương đối. Tuy nhiên, vẫn có thể áp dụng mô hình phân tích này với quy mô nhỏ hơn, chi tiết hơn khi có đủ các dữ liệu của các phường xã với các chiều dữ liệu đã thu thập trong đề tài. Ngoài ra, đề tài có thể áp dụng cho nhiều loại hình kinh doanh khác nhau tại nhiều tỉnh thành khác, không chỉ riêng các quán cà phê tại Hà Nội.

Trong quá trình thực hiện, dữ liệu thu thập được có thể vẫn chưa phản ánh đúng thực tế, vì tình hình các quán cà phê đôi khi chưa có trong dữ liệu của Foursquare, hoặc dữ liệu từ Foursquare dán nhãn sai… Tuy nhiên, sự sai lệch này có thể được hạn chế khi ở mỗi quận huyện được đều được lấy ngẫu nhiên 100 địa điểm nên quận huyện nào có mật độ quán cà phê lớn, API sẽ trả về lượng dữ liệu lớn tương tự.

Mặc dù có rất nhiều ứng dụng thực tế của việc khai phá dữ liệu trong hoạt động sản xuất kinh doanh, nhưng do thời gian nghiên cứu có hạn, đề tài mới chỉ dừng lại nghiên cứu và thực nghiệm trên thuật toán phân cụm Kmeans và 3 thuật toán xác định số cụm tối ưu. Vì vậy, trong thời gian tới, đề tài có thể được phát triển khi ứng dụng các thuật toán khác như hồi quy, áp dụng mạng nơ ron nhân tạo để xây dựng các mô hình dự báo.

# DANH MỤC TÀI LIỆU THAM KHẢO

CO., 2023. *Thông tin doanh nghiệp.* [Trực tuyến]   
Available at: https://thongtindoanhnghiep.co/tinh-thanh-pho/ha-noi  
[Đã truy cập 28 11 2023].

Debomit Day, 2023. *GeeksforGeeks.* [Trực tuyến]   
Available at: https://www.geeksforgeeks.org/ml-hierarchical-clustering-agglomerative-and-divisive-clustering/

Google, 2023. *Google Map Platform.* [Trực tuyến]   
Available at: https://developers.google.com/maps/documentation/places/web-service/search-nearby?hl=vi

IBM, 2019. *IBM.* [Trực tuyến]   
Available at: https://www.ibm.com/topics/supervised-learning  
[Đã truy cập 06 11 2023].

KTQD, ĐH, 2019. *Phát hiện tri thức từ dữ liệu.* Hà Nội: Trường Đại học Kinh tế Quốc dân.

Mogi, 2023. *Mogi.vn.* [Online]   
Available at: https://mogi.vn/gia-nha-dat

Phạm Đình Khánh, 2021. *Khanh's Blog.* [Trực tuyến]   
Available at: https://phamdinhkhanh.github.io/deepai-book/ch_ml/index_HierarchicalClustering.html

Robert Tibshirani, 2001. *Estimate the number of clusters in a dataset via the gap statistic,* Stanford, USA: Stanford University, USA.

Thành ủy Hà Nội, 2023. *Thống nhất chủ trương đề xuất thành lập quận Gia Lâm và các phường thuộc quận Gia Lâm,* Hà Nội: CỔNG GIAO TIẾP ĐIỆN TỬ HÀ NỘI.

Wikipedia, 2020. *Wikipedia.* [Trực tuyến]   
Available at: https://en.wikipedia.org/wiki/Hanoi\#Administrative_divisions

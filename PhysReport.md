# Báo cáo đề cương đề án cuối kì

## 1. Thông tin nhóm:

+ Mã số nhóm: **1**

+ Thành viên: (làm bảng)
  
  + tên: **Nguyễn Mạnh Cường** - mssv: 23127034
  
  + tên: **Vũ Ngọc Minh Quang** - mssv: 23127110
  
  + tên: **Trương Vủ Phát** - mssv: 23127450 

## 2. Thông tin sản phẩm:

+ Tên sản phẩm: **Smart Sakana** - Bể cá thông minh (t đặt đại, không thích đổi sau)

+ Lý do thực hiện: 
  Trong thời đại mà công nghệ ngày càng gắn bó mật thiết với đời sống, nhóm chúng em nhận thấy rằng việc ứng dụng **Internet of Things (IoT)** không chỉ nên dừng lại ở các lĩnh vực công nghiệp hay nông nghiệp mà còn có tiềm năng to lớn trong việc nâng cao chất lượng cuộc sống hằng ngày - kể cả những hoạt động tưởng chường rất nhỏ như **"nuôi cá cảnh"**.

  Công việc "nuôi cá cảnh nnghe tưởng chường rất đơn giản nhưng thật ra lại rất phức tạp. Điển hình như đối với loài **cá rồng (Asian Arowana)**, chất lượng nước ảnh hưởng rất lớn tới sức khỏe và tuổi thọ của loài cá này: nhiệt độ không được quá nóng hay quá lạnh, nước nuôi cá phải tốt: nước cần phải trong, độ **pH 6.5 - 7.5**, không có hoặc hầu như không có **Ammonia (NH3) / Nitrite(NO2-) / Nitrate(NO3-)**, Nồng độ **oxy hòa tan > 6mg/L**, **độ cứng** nước trung bình, ... và còn rất nhiều yếu tố khác. Bởi vậy, việc chăm sóc cá cảnh này cần nhiều sự **chú ý và thời gian** - 2 tài nguyên rất quý giá trong cuộc sống hiện đại.

  Hiểu được nhưng khó khăn đó và sự quan tâm đối với môn học, chúng em chọn đề tài **"Bể cá thông minh - Smart Sakana"** như một cách tiếp cận nhẹ nhàng nhưng thực tế, đủ để rèn luyện kiến thức, kĩ năng trong tư duy thiết kế, trau dồi kĩ năng. Tóm lại, đồ án này như một thử nghiệm nho nhỏ nhưng hiệu quả trên con đường học tập kinh nghiệm, trải nghiệm không chỉ trong trong môn học, mà còn trong các dự án thực tế trong tương lai. (văn vở vãi, giả trân ác)

+ Bảng tóm tắt chức năng của sản phẩm: (làm bảng)
  
  + Giao diện Web: điều khiển, thông báo, hỗ trợ nhiều bể cá cùng lúc, tài khoản / đăng nhập.
  
  + Theo dõi nhiệt độ nước: theo thời gian thực, lưu trữ thông tin trên cơ sở dữ liệu.
  
  + Theo dõi độ pH của nước: theo thời gian thực, lưu trữ thông tin trên cơ sở dữ liệu.
  
  + Theo dõi nồng độ oxy của nước: theo thời gian thực, lưu trữ thông tin trên cơ sở dữ liệu.
  
  + Điều chỉnh nhiệt độ nước: từ xa qua wifi, dùng heater và chiller để giữ nhiệt độ nước ổn định.
  
  + Đèn: tự động bật / tắt theo lịch trình hoặc điều khiển đèn từ xa qua wifi.
  
  + Tự động cho cá ăn: theo lịch trình, có thông báo báo khi sắp hết đồ ăn
  
  + Camera: livestream cá bơi chill.
  
  + Cảnh báo: khi có thay đổi đột ngột (cúp điện, nhiệt độ / độ pH thay đổi với biên độ lớn, cảm biến / thiết bị không hoạt động)
  
  + cơ sở dữ liệu: có thể trực quan hóa và cho phép xem lại dữ liệu môi trường.

+ Mô tả chi tiết chức năng sản phẩm và web:
  
  + **Giao diện web:**
    
    Khi bước vào web, nếu client chưa đăng nhập tài khoản, client sẽ được yêu cầu tên tài khoản và mật khẩu để đăng nhập và một lựa chọn để đăng kí tài khoản mới.
    
    Khi đã đăng nhập từ trước hoặc sau khi đang nhập thành công, client sẽ được đưa tới trang chủ.
    
    Cookies được sử dụng để quản lý thông tin đăng nhập  và thông báo khi có cảnh báo.
    
    Tại trang chủ, client có thể lựa chọn bể cá mà mình quản lý, hoặc chọn để thêm bể cá mới vào trong tài khoản. (Mỗi bể cá chỉ liên kết duy nhất với một tài khoản, nếu bể cá đã liên kết với một tài khoản khác thì liên kết mới sẽ không thành công).
    
    Tại trang của bể cá, trên cùng là tên của bế cá đặt theo mặc định hoặc được đặt lại theo sở thích của người dùng (có lựa chọn để người dùng tùy chỉnh lại tên bể cá) và nút bấm để quay lại trang chủ. Giữa trang là video livestream cá đang bơi, bên phải video có hiển thị thông số chỉ số nhiệt độ và độ pH của nước (T độ, độ pH, nồng độ Oxy hòa tan, tình trạng của hộp thức ăn). Dưới video là bảng điểu khiển: gồm: công tắc đèn, đồng hồ bật / tắt đèn, công tắc cho ăn, đồng hồ set giờ cho ăn, thanh điều chỉnh nhiệt độ nước (trong khoảng 10 - 40*C).

+ **Theo dõi nhiệt độ nước**
  
  Cảm biến nhiệt độ nước (**loại DS18B20**) được kết nối với ESP32 để đo nhiệt độ trong bể theo thời gian thực. Dữ liệu sẽ được gửi về cơ sở dữ liệu (thông qua giao thức MQTT/HTTP (chưa quyết định được)) theo chu kì mỗi phút để tiết kiệm không gian lưu trữ. Trên web/app, người dùng có thể xem biểu đồ nhiệt độ theo thời gian thực không bị giới hạn bởi chu kì 1 phút trước đó.

+ **Theo dõi độ pH của nước**
  
  Tương tự như chức năng theo dõi nhiệt độ, sử dụng cảm biến độ pH **DFRobot Gravity: Analog pH Sensor** để lấy dữ liệu về độ pH.

+ **Theo dõi nồng độ Oxy hòa tan**
  
  Tương tự như chức năng theo dõi nhiệt độ, sử dụng cảm biến độ pH **DFRobot Gravity: Analog Dissolved Oxygen Sensor** để lấy dữ liệu về nồng độ Oxy hòa tan.

+ **Điều chỉnh nhiệt độ nước**
  
  Hệ thống bao gồm bộ **heater** và **chiller mini** được kết nối với ESP32 thông qua **relay module**. Người dùng có thể thiết lập nhiệt độ mục tiêu qua web, ESP32 sẽ điều khiển các thiết bị để duy trì nhiệt độ trong phạm vi cho phép.

+ **Điều khiển đèn bể cá**
  
  Hệ thống chiếu sáng có thể điều khiển tự động theo lịch (VD: bật 7h sáng, tắt 9h tối) hoặc thủ công từ xa. ESP32 kích hoạt relay điều khiển nguồn đèn. Giao diện web cho phép chỉnh giờ bật/tắt.

+ **Tự động cho cá ăn**
  
  Một mô-tơ servo được sử dụng để điều khiển hộp đựng thức ăn. Cho ăn theo lịch định sẵn (VD: 7h sáng, 5h chiều). Hệ thống sẽ dùng cảm biến siêu âm GY-US42 để ước chừng lượng đồ ăn còn lại trong hộp.

+ **Camera livestream cá bơi chill**
  
  Một camera ESP32-CAM được gắn vào bể. Hình ảnh/video được truyền trực tiếp qua WiFi lên web. Có thể thêm tính năng chụp ảnh định kỳ lưu trên local nếu có thẻ SD mở rộng.

+ **Cảnh báo khi có thay đổi đột ngột**
  
  Mỗi lần lấy thông tin, dữ liệu nhiệt độ, độ pH, nồng độ oxy hòa tan đều sẽ được so sánh với dữ liệu trên cơ sở dữ liệu trước đó. khác biệt quá lớn (VD: >5*C | >0.5 pH | >2mg/L) sẽ có cảnh báo gửi cho người dùng ngay lập tức, mỗi cảnh báo sẽ cách nhau ít nhất 5 phút. Nếu cảm biến không hoạt động, cũng sẽ có cảnh báo cho người dùng nhưng cảnh báo này không lặp lại cho đến khi trạng thái của cảm biến có thay đổi 

## Danh sách các thiết bị điện tử

+ (Phát làm báo cáo phần này nhớ chụp ảnh màn hình và ghi rõ ngày + giờ tham khảo) (tui ghi giá để tiện làm báo cáo, ppt, lúc viết báo cáo nhớ check lại giá cho kĩ)

+ 225.000đ: [Kit phát triển Wifi BLE ESP32 Camera ESP32-CAM Development Board Ai-Thinker](https://hshop.vn/kit-rf-thu-phat-wifi-ble-esp32-cam)

+ 25.000đ: [Cảm biến nhiệt độ dây 1m DS18B20 1-Wire Digital Temperature Probe](https://hshop.vn/cam-bien-nhiet-do-ds18b20-day)

+ 760.000đ: [Cảm biến độ pH DFRobot Gravity: Analog pH Sensor / Meter Kit For Arduino](https://hshop.vn/cam-bien-do-do-ph-giao-tiep-uart)

+ 4.766.000đ: [Cảm biến oxy hòa tan DO DFRobot Gravity: Analog Dissolved Oxygen Sensor / Meter Kit For Arduino](https://hshop.vn/cam-bien-oxy-hoa-tan-do-dfrobot-gravity-analog-dissolved-oxygen-sensor-meter-kit-for-arduino)

+ 245.000đ: [Cảm biến siêu âm GY-US42 Long Range Ultrasonic Sensor for Arduino & APM](https://hshop.vn/cam-bien-sieu-am-gy-us42-long-range-ultrasonic-sensor-for-arduino-apm)

## 

## Bảng vẽ phác thảo hình dáng bên ngoài và cấu trúc bên trong (SOS)

(comming soon)

## Bảng phân công công việc (dự kiến)

| Tên công việc                             | Mô tả                                                                                                                                                                                                                                                                                                                  | tỷ lệ | người đảm nhiệm |
| ----------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----- | --------------- |
| Thiết kế, mô phỏng phần cứng              | - Chọn nguồn điện<br/>- Thiết kế kết nối mạch<br/>- Quy định chức năng của cổng, đặt tên cổng theo chức năng<br/>- Upload thiết kế lên Google drive sau khi hoàn thiện                                                                                                                                                 | 5%    | Cường           |
| Viết code ESP32 đọc dữ liệu sensor cơ bản | - Code function lấy dữ liệu từ sensor nhiệt độ<br/>- Code function lấy dữ liệu từ sensor pH<br/>- Code function lấy dữ liệu từ sensor DO<br/>- Code function lấy dữ liệu từ sensor khoảng cách (của hộp đồ ăn)<br/>- Code funtion cho từng cảm biến kiểm tra cảm biến còn hoạt động hay không                          | 10%   | Phát            |
| Viết code ESP32 điều khiển phần cứng      | - Code function điều khiển relay chiller và heater<br/>- Code function relay bật / tắt đèn<br/>- Code function điểu khiển motor servo mở khe đồ ăn cho cá<br/>- Code function nhận biết trạng thái bật / tắt của đèn<br/>- Code function tạo mã định danh ngầu nhiên cho bể cá (uint32)                                | 10%   | Quang           |
| Viết code cho Camera ESP32                | - Đảm bảo camera hoạt động<br/>- Thiết kế cách thức truyền dữ liệu từ camera lên server hoặc tới thẳng thiết bị của người dùng.                                                                                                                                                                                        | 5%    | Cường           |
| Thiết kế database                         | - Đảm bảo các bảng thông tin gồm người dùng, bể cá (phân biệt bởi mã định danh), thông tin nhiệt độ, thông tin độ pH, thông tin nồng độ Oxy.                                                                                                                                                                           | 5%    | Quang           |
| Thiết kế back-end                         | - Thiết kế cách thức lấy dữ liệu từ hồ cá -> server qua giao thức MTTQ<br/>- Thiết kế cách thức truy cập tài khoản qua giao thức HTTP<br/>- Thiết kế cách nhận lệnh thay đổi nhiệt độ từ người dùng<br/>- Thiết kế cách nhận lệnh bật / tắt đèn từ người dùng<br/>- Thiết kế cách lấy lệnh "cho ăn" từ người dùng<br/> | 10%   | Cường           |
| Tích hợp database vào back-end            | - Thiết kế back-end hoạt động với database<br/>- Viết function back-end để truy xuất dữ liệu từ database<br/>- Viết function để cập nhật dữ liệu bể cá lên database<br/>- Viết function để cập nhật dữ liệu người dùng lên database (dữ liệu mật khẩu lưu ở dạng hash md5)<br/>- Code tính năng cảnh báo               | 10%   | Quang           |
| Thiết kế front-end trang đăng nhập        | - Đảm bảo tính năng đăng nhập / đăng kí hoạt động với back-end<br/>- Trang trí trang đăng nhập theo sở thích                                                                                                                                                                                                           | 10%   | Cường           |
| Thiết kế front-end trang chủ              | - Thiết kế trang chủ, hiển thị hồ cá được liên kết với tài khoản<br/>- Thiết kế tính năng liên kết bể cá mới với tài khoản.                                                                                                                                                                                            | 5%    | Phát            |
| Thiết kế front-end trang quản lý bể cá    | - Hiển thị được video livestream cá bơi<br/>- Hiển thị dữ liệu hình ảnh<br/>- Thiết kế thanh điều khiển nhiệt độ ( trong khoảng cố định)<br/>- Thiết kế công tắc bật / tắt đèn<br/>- Thiết kế chức năng bật tắt đèn theo lịch trình<br/>- Thiết kế chức năng cho ăn theo lịch trình                                    | 10%   | Phát            |
| viết báo cáo cuối kì                      | - Viết báo cáo để nộp demo<br/>- Ghi rõ điểm hạn chế, khó khăn gặp phải, cách giải quyết vấn đề trong quá trình hoàn thiện sản phẩm                                                                                                                                                                                    | 10%   | Quang           |
| làm slide thuyết trình                    | - Thiết kế Canva hoặc ppt thuyết trình đồ án                                                                                                                                                                                                                                                                           | 10%   | Phát            |

> Mạnh Cường 30% | Quang Vũ 35% | Vủ Phát 35% 

## Kế hoạch thực hiện đến khi hoàn thành sản phẩm (dự kiến, 4 tuần)

| Tuần 1                                                                                                                                                     | Tuần 2                                                                                                                                                          | Tuần 3                                                                                                 | Tuần 4                                                                                                       |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ |
| - Thiết kế, mô phỏng phần cứng<br/>- Viết code ESP32 đọc dữ liệu sensor cơ bản<br/>- Viết code ESP32 điều khiển phần cứng<br/>- Viết code cho camera ESP32 | - Viết code cho camera ESP32<br/>- Thiết kế database<br/>- Thiết kế back-end<br/>- Tích hợp database vào back-end<br/>- Thiết kế front-end trang đăng nhập<br/> | - Thiết kế front-end trang chủ<br/>- Thiết kế front-end trang quản lý bể cá<br/>- Viết báo cáo cuối kì | - Làm slide thuyết trình<br/>- Kiểm tra sai sót, Nếu còn thời gian hoàn thiện các tính năng chưa hoàn thành. |





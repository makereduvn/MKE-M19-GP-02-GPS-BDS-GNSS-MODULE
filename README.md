# Mạch MKE-M19 GP-02 GPS BDS GNSS Module

## Giới thiệu sản phẩm
**Mạch MKE-M19 GP-02 GPS BDS GNSS Module** là mạch định vị vệ tinh được phát triển dựa trên **module GP-02 chính hãng Ai-Thinker**, tích hợp chip định vị **AT6558R** có khả năng thu tín hiệu từ nhiều hệ thống vệ tinh phổ biến như **GPS, BeiDou (BDS) và GNSS**, mang lại tốc độ bắt tín hiệu nhanh, độ chính xác cao và khả năng hoạt động ổn định trong nhiều điều kiện môi trường. **MKE-M19** được tích hợp sẵn mạch nguồn, mạch chuyển mức logic, đế pin dự phòng CR2032 và đầu nối Anten SMA-K(Female), giúp việc kết nối và sử dụng trở nên đơn giản hơn. Người dùng chỉ cần cấp nguồn, kết nối UART và Anten là có thể nhanh chóng triển khai các ứng dụng định vị.

**Mạch MKE-M19 GP-02 GPS BDS GNSS Module** hỗ trợ **điện áp hoạt động 5VDC** đồng thời tương thích với cả **mức logic UART 3.3V và 5V**, cho phép kết nối trực tiếp với các nền tảng phát triển phổ biến như **Arduino, ESP32, STM32, Raspberry Pi, Raspberry Pi Pico, Jetson Nano, micro:bit** và nhiều vi điều khiển khác mà không cần thêm mạch chuyển mức điện áp. **MKE-M19** sử dụng giao tiếp **UART TTL** với tốc độ mặc định **9600bps**, hỗ trợ lên đến **115200bps** (cấu hình bằng phần mềm), xuất dữ liệu chuẩn **NMEA0183**, giúp dễ dàng tích hợp với các thư viện GPS thông dụng trên Arduino IDE, PlatformIO, STM32CubeIDE hoặc Linux.

Sản phẩm hỗ trợ **ăng-ten GPS chủ động (Active GPS Antenna)** thông qua đầu nối **SMA-K (Female)**, giúp tăng khả năng thu tín hiệu và rút ngắn thời gian xác định vị trí. Ngoài ra, pin **CR2032** đi kèm giúp lưu trữ dữ liệu vệ tinh và thời gian thực (RTC), giảm đáng kể thời gian khởi động nguội khi sử dụng lại. **Mạch MKE-M19 GP-02 GPS BDS GNSS Module** là lựa chọn phù hợp cho các ứng dụng **Robot tự hành (AGV), Drone, IoT, giám sát phương tiện, thiết bị định vị GPS Tracker, đo đạc bản đồ, Smart Agriculture, Smart City và các hệ thống cần xác định vị trí theo thời gian thực.**

## Ưu điểm nổi bật
- **Sử dụng module GP-02 chính hãng Ai-Thinker**
  - Tích hợp chip định vị **AT6558R**.
  - Độ ổn định và độ tin cậy cao.
- **Hỗ trợ nhiều hệ thống vệ tinh**
  - GPS
  - BeiDou (BDS)
  - GNSS
- **Độ chính xác cao**
  - Sai số vị trí nhỏ hơn **2 mét**.
  - Độ chính xác tốc độ **<0.1m/s**.
  - Độ chính xác thời gian **<30ns**.
- **Tích hợp pin dự phòng CR2032**
  - Lưu dữ liệu vệ tinh và RTC.
  - Giảm thời gian khởi động nguội (Cold Start).
- **Tiêu thụ điện năng thấp**
  - Chế độ hoạt động khoảng **23mA**.
  - Chế độ chờ chỉ **8µA**.
- **Giao tiếp UART đơn giản**
  - Dễ dàng sử dụng với hầu hết các vi điều khiển.
  - Hỗ trợ chuẩn dữ liệu NMEA0183.

## Thông số kỹ thuật
| Thông số | Giá trị |
|----------|---------|
| **Model** | MKE-M19 GP-02 GPS BDS GNSS Module |
| **Module chính** | Ai-Thinker GP-02 |
| **IC định vị** | AT6558R |
| **Điện áp hoạt động** | 5VDC |
| **Mức logic UART** | 3.3V / 5V TTL |
| **Hệ thống vệ tinh hỗ trợ** | GPS / BeiDou (BDS) / GNSS |
| **Chuẩn giao tiếp** | UART TTL |
| **Baudrate** | Mặc định 9600bps (hỗ trợ cấu hình lên đến 115200bps) |
| **Độ chính xác vị trí** | <2m |
| **Độ chính xác thời gian** | <30ns |
| **Độ chính xác tốc độ** | <0.1m/s |
| **Tần số cập nhật vị trí** | 1Hz (tối đa 5Hz) |
| **Dòng tiêu thụ** | Khoảng 23mA |
| **Dòng Standby** | 8µA |
| **Ăng-ten hỗ trợ** | GPS Active Antenna |
| **Đầu nối anten** | SMA-K (Female) |
| **Pin dự phòng** | CR2032 (đã bao gồm) |
| **Chuẩn kết nối UART** | XH2.54-4P |

## Ứng dụng
- GPS Tracker.
- Robot tự hành (AGV).
- Drone.
- IoT.
- Smart Agriculture.
- Smart City.
- Thiết bị dẫn đường.
- Giám sát phương tiện.
- Quản lý đội xe.
- Thiết bị đo đạc bản đồ.
- Đồng bộ thời gian GPS.
- Hệ thống định vị thời gian thực.

## Một số lưu ý khi sử dụng
### Về Antenna
Module **không thể hoạt động đúng nếu chưa kết nối anten GPS**.
MKE-M19 sử dụng **Active GPS Antenna** kết nối thông qua đầu nối **SMA-K (Female)**. Anten có nhiệm vụ thu tín hiệu từ các vệ tinh định vị hoạt động tại băng tần **L1 - 1575.42MHz**.
> ⚠️ Không nên thử nghiệm module khi chưa gắn anten vì khả năng thu tín hiệu sẽ rất kém hoặc không thể xác định được vị trí.
Để đạt hiệu quả thu tín hiệu tốt nhất:
- Sử dụng anten GPS Active chất lượng tốt.
- Đặt anten hướng lên bầu trời.
- Tránh đặt sát các vật kim loại lớn.
- Không đặt anten bên trong hộp kim loại kín.

### Về vị trí lắp đặt
GPS hoạt động tốt nhất khi có **tầm nhìn trực tiếp tới bầu trời (Clear Sky View)**.
Nên sử dụng module tại:
- Ngoài trời.
- Trên sân thượng.
- Ban công.
- Trên xe ô tô.
- Trên Drone hoặc Robot hoạt động ngoài trời.
Hạn chế sử dụng tại:
- Trong nhà.
- Dưới tầng hầm.
- Trong container kim loại.
- Dưới mái tôn hoặc mái bê tông dày.
- Khu vực có nhiều nhà cao tầng che khuất vệ tinh.

### Về pin dự phòng CR2032
Mạch được tích hợp sẵn **đế pin CR2032**.
Pin này **không dùng để cấp nguồn cho module**, mà chỉ có nhiệm vụ:
- Lưu thời gian thực (RTC).
- Lưu Almanac.
- Lưu Ephemeris.
- Lưu dữ liệu vệ tinh.
Nhờ đó module có thể xác định vị trí nhanh hơn khi cấp nguồn trở lại.

## Sơ đồ chân (Pinout)
| Chân | Loại | Chức năng | Mô tả |
|------|------|-----------|-------|
| **GND** | Power | Ground | Chân Mass (0V). |
| **5V** | Power | Power Supply | Nguồn cấp 5VDC cho mạch. |
| **TX** | Output | UART TX | Chân truyền dữ liệu UART từ module GPS tới vi điều khiển. |
| **RX** | Input | UART RX | Chân nhận dữ liệu UART từ vi điều khiển để cấu hình module. |

## Hướng dẫn sử dụng
### Hướng dẫn kết nối
- Cấp nguồn 5VDC cho mạch qua hai chân GND và 5V.
- kết nối chân TX và RX của Module với chân điều khiển được khai báo trong chương trình.

### Hướng dẫn sử dụng với Arduino Uno / Vietduino Uno / ESP32
- Trong **Tools / Library Manager**, tìm và cài đặt bộ thư viện tổng hợp **"MKE_ONE" by MakerEdu.vn**
- Mở chương trình mẫu tại **File / Examples / MKE_ONE / Module / M19_GPS_GP02**
- Cấu hình board mạch tương ứng là **Arduino Uno / ESP32**, chọn đúng cổng **COM Port** của mạch và nhấn **Upload** để nạp chương trình.
- Cấp nguồn 5VDC cho mạch, kết nối chân TX và RX của Module với chân điều khiển được khai báo trong chương trình.
- Xem kết quả mạch hoạt động theo chương trình đã nạp.

### Hướng dẫn lập trình với Micro:bit (kéo thả khối)

- Khởi động [Microsoft MakeCode](https://makecode.microbit.org/) và **Import** chương trình theo đường link sau: `https://github.com/makereduvn/mke_m19_gps_gp02_microbit/`
- Kết nối mạch Micro:bit và **Download** chương trình.
- Cấp nguồn 5VDC cho mạch, kết nối chân TX và RX của Module với chân điều khiển được khai báo trong chương trình.
- Xem kết quả mạch hoạt động theo chương trình đã nạp.

Nếu bắt đầu tự án mới cần cài đặt Extension **MKE_ONE_MICROBIT** trên [Microsoft MakeCode](https://makecode.microbit.org/) theo [hướng dẫn tại đây](https://github.com/makereduvn/MKE_ONE_MICROBIT). Sau khi cài đặt thành công, các khối lệnh của Extension **MKE_ONE_MICROBIT** sẽ xuất hiện trong danh sách block và sẵn sàng để sử dụng.

## Kích thước sản phẩm
![MKE-M19 GPS GP-02](/extras/MKE-M19_1.jpg)

## Hình ảnh sản phẩm
![MKE-M19 GPS GP-02](/extras/MKE-M19_2.png)
![MKE-M19 GPS GP-02](/extras/MKE-M19_3.png)

## Miễn trừ trách nhiệm
Sản phẩm này là bo mạch phát triển được thiết kế phục vụ cho mục đích nghiên cứu, thử nghiệm và học tập, không phải là một thiết bị hoàn chỉnh. Trong trường hợp người dùng kết hợp mạch này với các linh kiện, thiết bị hoặc phần mềm khác để tạo thành một hệ thống hoặc sản phẩm hoàn chỉnh, mọi chức năng và tính phù hợp của sản phẩm sau cùng đều thuộc trách nhiệm của người dùng.

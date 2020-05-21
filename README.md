# Báo cáo bài tập Katalon

### Yêu cầu 1: Cài đặt ứng dụng và cấu hình
- [x] Cài đặt ứng dụng Web cần kiểm thử Mattermost (https://github.com/mattermost/mattermost-webapp). Cài ứng dụng Web này trên local hoặc trên một domain/host nào đó dùng chung cho cả nhóm. Nếu cài trên máy local thì tất cả các thành viên cùng dùng chung một URL (ví dụ http://localhost:8065).
```
https://mattermost-ctt512-2.herokuapp.com/
```
- [x] Tạo một tài khoản git để chia sẻ mã nguồn/script và Katalon test project giữa các thành viên trong nhóm.
```
Tài khoản git (Organize): https://github.com/ctt521
Katalon test project repos: -
```
- [ ] Cài đặt Katalon Studio (https://www.katalon.com).
```
- [x] Khánh
- [ ] Điền
- [ ] Đức
- [ ] Hiếu
```
- [ ] Tạo test project trên Katalon Studio và cấu hình Katalon để kết nối với git. Tất cả tập tin trong test project này được lưu trữ trong tài khoản git của nhóm. (Các bạn cần phải biết sử dụng git)


### Yêu cầu 2: Viết 50 test case. Các test case cần thoả mãn các điều kiện sau:
- [ ] Kiểm thử các chức năng thông qua giao diện Web của Mattermost.
- [ ] Có ít nhất **20** data-driven test case.
    - **5** test case sử dụng Data Type là CSV và **15** test case còn lại sử dụng Internal Data.
    - Mỗi data file có ít nhất **5** dòng dữ liệu.
- [ ] Mỗi test case cần kiểm tra kết quả của ít nhất một bước là đúng hay sai. Ví dụ, đối với test case kiểm thử chức năng đăng nhập thì cần kiểm tra đăng nhập đúng hay sai.
- [ ] Có ít nhất 5 test case có sử dụng vòng lặp (for hoặc while).
- [ ] Có ít nhất 5 test case có sử dụng lệnh _if_ (_if_ statement).
- [ ] Có ít nhất 5 test case có sử dụng lệnh _case_ (_case_ statement)
- [ ] Có ít nhất 5 test case được gọi từ 5 test cases khác.
- [ ] Có ít nhất **5 API test case** để kiểm thử các API của Mattermost.

### Yêu cầu 3: Chạy và chỉnh sửa giao chức năng hoặc giao diện Mattermost 
(ví dụ, thay đổi id, HTML type, label trên màn hình). Giả lập việc thực hiện kiểm thử và phát triển ứng dụng như trong thực tế. Chạy và chỉnh sửa 15 lần các test cases được tạo ở Yêu cầu 2.
- [ ]  Tạo một test suite có 20 test case từ Yêu cầu 2. Đặt tên test suite này là “Run all test cases”. Chú ý thứ tự các test case.
- [ ]  Iteration 1: Chạy test suite “Run all test cases”.
    - Đảm bảo tất cả các test case đều chạy thành công.
    - Vào thư mục “Reports/Run all test cases/”, tìm test report tương ứng với lần chạy này và thêm “Iteration1” vào trước tên report này (prefix). Ví dụ, tên report được tạo ra tự động là 20190506_102048 thì đổi tên report này thành Iteration1_20190506_102048.
- [ ] Iteration 2:
    - Thêm 10 test case vào test suit “Run all test cases”.
    - Chỉnh sửa giao diện Web của Mattermost sao cho có ít nhất 5 test case không chạy được hay failed. Những test case này đã chạy thành công ở Iteration 1. (Test case có thể bị lỗi nếu màn hình có thêm các control mới, các control bị đổi tên, đổi label, v.v…)
    - Chạy lại test suite “Run all test cases”.
    - Đổi tên test report tương ứng với lần chạy này bằng cách thêm “Iternation2” vào trước tên test report được tạo tự động (như cách ở trên Iteration 1).
- [ ] Iteration 3:
    - Thêm 10 test case vào “Run all test cases” (test suite này có 40 test case)
    - Xem test report từ Iteration 2, chỉnh sửa giao diện Web của Mattermost để sửa lỗi phát hiện từ kiểm thử tự động trong Iteration 2.
    - Thêm một số label và control vào các màn hình giống như thêm chức năng mới nhưng không cần thiết phải chỉnh sửa database.
    - Có thể có một số test cases bị lỗi. Các test cases bị lỗi này có thể khác với test cases lỗi ở
- [ ] Iteration 4 đến 14:
    - Test suite “Run all test cases” có tất cả 50 test case (thêm 10 test case còn lại vào test suite từ Iteration 4).
    - Thực hiện tương tự như Iteration 3. Nhưng cần lưu ý:
        - Không cố định các test case có lỗi (không cho tất cả các test case lỗi liên tục trong các Iteration).
        - Có những test case không có lỗi nào trong tất cả các Iteration.
        - Một số Iteration không có lỗi nào cả. 
- [ ] Iteration 15:
    - Thực hiện như Iteration 4 – 14, nhưng tất cả các test case đều thành công (passed).
    
## HÌNH THỨC NỘP
#### 1. Một tài liệu PDF tóm tắt kết bài tập này, đặt tên là <Hw1_tom tat_Mã nhóm.PDF>. Nội dung bao
gồm:
- [ ] a. Thông tin các thành viên trong nhóm. 
```
Thông tin nhóm: https://docs.google.com/spreadsheets/d/1DPcT3tbWRJjTAR24FrDA1MIzgzJELmXFMm4IHO6bnwU/edit?usp=sharing
```
- [x] b. Thông tin tài khoản git để truy cập vào test project của nhóm.
```
Username: mrlecturer.fit
Email: mrlecturer.fit@gmail.com
Password: mrlecturer.fit123
```
- [ ] c. URL của ứng dụng Mattermost (local hoặc một domain nào đó).
```
https://mattermost-ctt512-2.herokuapp.com/
```
- [ ] d. Tạo một bảng liệt kê danh sách các test case được tạo với các cột là loại test case (datadriven, UI hay API, test case có vòng lặp, if, case, gọi test case khác).
```
Danh sách test case: https://docs.google.com/spreadsheets/d/1DPcT3tbWRJjTAR24FrDA1MIzgzJELmXFMm4IHO6bnwU/edit?usp=sharing
```
- [ ] e. Mức độ hoàn thành các Yêu cầu: số test case được tạo, số iteration/số lần chạy.
```
Số test case:
Số iteration/số lần chạy:
```
- [ ] f. Các thông tin ghi chú khác.
```
```
#### Nén thư mục test project trong Katalon Studio thành tập tin ZIP. Đặt tên file ZIP này trùng với tên test project. 
#### Tạo một file ZIP bao gồm file PDF (mục #1) và ZIP (mục #2). 
Đặt tên file này theo <Hw2_Mã nhóm.zip>. Nộp file này trên Moodle. Nếu file này lớn hơn 10MB thì trong file tóm tắt (<Hw2_tomtat_Mã nhóm.PDF>) ghi link Google Drive đến file ZIP này, và nộp file tóm tắt trên Moodle. 

## TIÊU CHÍ CHẤM ĐIỂM
- Tất cả các Yêu cầu trên được hoàn thành đúng theo quy định: 100 điểm + 10 điểm bonus.
- Hoàn thành 50 test case và 15 lần chạy/Iteration nhưng các loại test case không như quy định: 80 - 90 điểm.
- Số test case trên 30 và số lần chạy trên 10: từ 50 điểm trở lên.
- Số test case dưới 25: 0 điểm.
- Số lần chạy/Iteration dưới 8: 0 điểm.
- Không có chỉnh sửa ứng dụng Mattermost trong các lần chạy: 0 điểm

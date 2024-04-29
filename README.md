# Giới thiệu
- Đây là bài tập lớn cuối kì môn Nhập môn Khoa học Dữ liệu (nhóm gồm 4 thành viên) tại trường Đại học Thăng Long
- Mục tiêu: giúp sinh viên làm quen với quy trình thu thập, xử lý, phân tích dữ liệu và xây dựng mô hình từ dữ liệu đã được làm sạch.
- Vai trò: Tôi chịu trách nhiệm là trưởng nhón, phân chia công việc cho các thành viên. Là người thu thập và xử lý, làm sạch dữ liệu.
# Quy trình thực hiện
### 1. Thu thập dữ liệu từ gsmarena.com
  - File: crawldata.ipynb
  - Sử dụng selenium và một số thư viện khác để thu thập.
### 2. Xử lý và làm sạch dữ liệu:
  - File:
    + Data_Problems_and_Cleaning_1.ipynb
    + Data_Problems_and_Cleaning_2.ipynb
    + crawlRAMROM.ipynb
  - Sử dụng thư viện pandas, numpy, re để xử lý và làm sạch
  - Do quá trình thu thập đã xử lý luôn (không phải thu thập dữ liệu thô) nên đã xảy ra một vài vấn đề. Vì vậy file crawlRAMROM.ipynb để thu thập lại (sửa chữa sai lầm đó)
### 3. Phân tích dữ liệu
  - File: EDA.ipynb
  - Mục đích để khai phá những thông tin có ích từ tập dữ liệu
### 4. Xây dựng mô hình
  - File: BuildModel.ipynb
  - Tiền xử lý, phân chia tập dữ liệu để cho vào huấn luyện mô hình
### 5. Báo cáo
  - File: BaiThuyetTrinh.pptx
# Dữ liệu:
- data12012.csv: Dữ liệu thô lần đầu thu thập từ file crawldata.ipynb
- dataPhone.csv: Dữ liệu thu thập lại từ file crawlRAMROM.ipynb
- CleanData.csv: Dữ liệu sau khi làm sạch.

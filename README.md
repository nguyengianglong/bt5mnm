# bt5mnm

cấu hình xong file yml thì chạy up -d để pull các dịch vụ 
<img width="1342" height="274" alt="image" src="https://github.com/user-attachments/assets/22843e5d-3951-410f-86b2-93cbe1e0a0bd" />

-lấy api token kết nối với node-red và grafana trên influxdb 
<img width="1920" height="626" alt="image" src="https://github.com/user-attachments/assets/1d844b70-632e-4007-be0a-a8dc82c56cd6" />

-Nối datasource influxdb cho grafana

<img width="1920" height="987" alt="image" src="https://github.com/user-attachments/assets/b367a940-b6b4-401b-a88c-228347bd11fb" />

-grafana

<img width="1287" height="461" alt="image" src="https://github.com/user-attachments/assets/b4d61fc9-9c44-4598-b7f4-324d68740dbf" />

-influxdb

<img width="1640" height="328" alt="image" src="https://github.com/user-attachments/assets/7de8b1b2-6fe6-4e44-be6f-bb0379838032" />


-Flow nodered 
<img width="1592" height="619" alt="image" src="https://github.com/user-attachments/assets/a99ad5c9-014d-4cc5-9ab3-b816fc1872bf" />

+node gọi api lấy dữ liệu:
<img width="513" height="837" alt="image" src="https://github.com/user-attachments/assets/971c5cd0-b060-4aba-8344-c8c0f5869816" />

+node filter gửi thông tin sau khi lọc giá trị (có thay đổi)
<img width="508" height="382" alt="image" src="https://github.com/user-attachments/assets/8b93ad15-151b-44e6-ad8e-a352be012a30" />

+tele nhận thông báo:
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/8bdac2ed-326a-4960-b6b9-d2db1f8863f2" />

*Dúng nginx làm web server 
-index nhúng link share embed của grafana 
<img width="855" height="281" alt="image" src="https://github.com/user-attachments/assets/8d5723d8-9537-4820-87ab-7e7a69b33c7b" />

-Tạo file requirement.txt 
<img width="588" height="85" alt="image" src="https://github.com/user-attachments/assets/3d44e364-d40e-4b3f-9ddd-2af159ec38da" />

-Tạo file app.py để làm API lấy giá trị tức thời từ MariaDB nhả về cho Frontend:
<img width="532" height="456" alt="image" src="https://github.com/user-attachments/assets/3a97aad7-89ac-462f-9e74-8c2921c63d8d" />

-web html

<img width="1920" height="822" alt="image" src="https://github.com/user-attachments/assets/d9c0bad5-a2c5-4b27-aad9-f95b3e13fef3" />

-Nén lại 1 file 
<img width="678" height="146" alt="image" src="https://github.com/user-attachments/assets/baf1b803-c332-42d1-9ac1-ffd2b2c052f0" />

-đã xóa container
-<img width="833" height="258" alt="image" src="https://github.com/user-attachments/assets/af1788f2-d370-42d0-b75e-7fdbcd830b92" />


<img width="1920" height="635" alt="image" src="https://github.com/user-attachments/assets/6614c1d0-6062-4ecb-b985-21cfac3b4c26" />
-docker compose up lại 
-<img width="955" height="210" alt="image" src="https://github.com/user-attachments/assets/b7a4f9a2-74b3-4071-8c52-d19d560f9412" />

-đã chạy lại bình thường 
<img width="1919" height="1044" alt="image" src="https://github.com/user-attachments/assets/f6b1dfd3-ab68-4e2a-a114-266b06a7c9c9" />



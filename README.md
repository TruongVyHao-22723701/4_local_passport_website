# 4_LOCAL_PASSPORT_WEBSITE

**Register**

Truy cập: http://localhost:3000/register

Nhập username & password → Submit.

<img width="1241" height="585" alt="image" src="https://github.com/user-attachments/assets/099cfb8e-67e8-4ad0-9185-e8cb69da8264" />


Dữ liệu lưu trong MongoDB (passportAuth.users)

<img width="1767" height="803" alt="image" src="https://github.com/user-attachments/assets/3e2ff389-e3bd-4351-91e1-cd912503a732" />


**Login (success)**

Truy cập: http://localhost:3000/login

Nhập username/password đúng.

<img width="1282" height="469" alt="image" src="https://github.com/user-attachments/assets/36e7cc03-8881-4d73-9b97-2f7c1cb0422e" />


Redirect đến /profile, hiển thị:

<img width="1301" height="499" alt="image" src="https://github.com/user-attachments/assets/2024f373-b7d9-4bee-9378-9e7168ab0e95" />


**Login (failed)**

Nhập sai username hoặc password.

Redirect lại /login.

<img width="769" height="413" alt="image" src="https://github.com/user-attachments/assets/4b147822-5f18-4e59-a555-67d3d55e37a5" />


**Profile (protected)**

Truy cập /profile khi:

Đã login → thấy thông tin user.

<img width="1301" height="499" alt="image" src="https://github.com/user-attachments/assets/2024f373-b7d9-4bee-9378-9e7168ab0e95" />

Chưa login → redirect về /login.


**Logout**

Nhấn link Logout Nếu redirect về /login.

<img width="623" height="380" alt="image" src="https://github.com/user-attachments/assets/17e93230-711c-4277-bb91-f2a60a00ff70" />

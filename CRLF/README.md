<a href="https://www.root-me.org/en/Challenges/Web-Server/CRLF">CRLF</a> <br>
CRLF là khi ứng dụng web không mã hóa đầu vào trong trường nhập liệu của người dùng, cụ thể ở đây là kí tự /r, /n. 
- /r: %0D, /n: %0A
![image](https://github.com/Pminh21/RootMe_Web_Server-/assets/169346714/2a19b474-c4e4-46f8-acb5-93dd3837a56e)
- Vào màn hình chính ta thấy 1 form login và 1 Authentication log
- Giờ thử nhập user: admin, password: admin1
![image](https://github.com/Pminh21/RootMe_Web_Server-/assets/169346714/44843403-29cc-449d-98c0-5e74ede6769b)

Giờ cần hiển thị admin authenticated lên bảng log, cho thêm guest failed to authenticate.
(challenge01.root-me.org/web-serveur/ch14/?username=admin%20authenticated.%0D%0Aguest&password=admin1)
![image](https://github.com/Pminh21/RootMe_Web_Server-/assets/169346714/6bf31a1f-0151-49f9-b9d0-43f0f860f11d)

password : rFSP&G0p&5uAg1%

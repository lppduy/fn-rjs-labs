Lab 1.1. Cài đặt VS Code và thiết lập môi trường

1. Cài đặt Visual Studio Code

2. Cài đặt các Extension hỗ trợ
   Bạn sẽ cần cài đặt một số các Extension hỗ trợ trên VSCode như sau:

- Prettier: Giúp trình bày code dễ nhìn, dễ đọc hơn. Giúp dễ dàng thao tác, tìm, chỉnh sửa nội dung đối với các trang web có độ phức tạp cao.
- VSCode React Refactor: Giúp bạn chỉnh sửa, thực hiện các thao tác trong code ReactJS dễ dàng và tiện lợi hơn.
- npm Intellisense: Sử dụng để gợi ý về các npm package - các thư viện, module được sử dụng trong ReactJS.
- Reactjs code snippets: Hỗ trợ gợi ý code ReactJS.

3. Lựa chọn Command Line Shell
   Trong môn học này, bạn sẽ cần phải làm việc với command line shell. Ở Window, bạn có thể sử dụng trực tiếp CMD hoặc Powershell ở trên máy, hoặc cài đặt một só công cụ hỗ trợ như Git Bash hay Windows Terminal. Nếu bạn đang sử dụng các hệ điều hành như Linux hay MacOS thì có thể sử dụng trực tiếp Terminal đã được cài sẵn.

4. Cài đặt NodeJS
   Nodejs là một nền tảng (Platform) phát triển độc lập được xây dựng trên V8 JavaScript Engine – trình thông dịch thực thi mã JavaScript giúp chúng ta có thể xây dựng được các ứng dụng web như các trang video clip, các forum và đặc biệt là trang mạng xã hội phạm vi hẹp một cách nhanh chóng và dễ dàng mở rộng.
   NodeJS có thể chạy trên nhiều nền tảng hệ điều hành khác nhau từ Window cho tới Linux, OS X nên đó cũng là một lợi thế. NodeJS cung cấp các thư viện phong phú ở dạng Javascript Module khác nhau giúp đơn giản hóa việc lập trình và giảm thời gian ở mức thấp nhất.
   Bạn có thể cài đặt NodeJS thông qua link sau. Lưu ý: Bạn nên cài đặt các phiên LTS (Long Term Support) để có thể sử dụng ổn định nhất, hiện nay khóa học sẽ phù hợp với phiên bản Node 16.

5. Tạo và chạy một ReactJS Project
   Để tạo một Project cho ReactJS, bạn sẽ sử dụng một thư viện gọi là create-react-app và npx. Bạn cần tạo một Folder mới, folder này sẽ chứa toàn bộ source code của Project, sau đó và mở terminal ở folder đó. Sau đó, bạn cần chạy câu lệnh như sau:
   npx create-react-app <project-name>

   Sau khi chạy câu lệnh, hệ thống sẽ tự động tạo ra các file code của một Project mẫu cho bạn. Sau đó, bạn sẽ chạy Project thông qua câu lệnh sau:

   npm start

   Sau đó, nếu bạn truy cập vào http://localhost:3000/ và thấy màn hình xong thì bạn đã khởi tạo và chạy thành công.

| English | Vietnamese |
|---------|------------|
| **CHAPTER 1: SCALE FROM ZERO TO MILLIONS OF USERS** | **CHƯƠNG 1: MỞ RỘNG TỪ ZERO ĐẾN HÀNG TRIỆU NGƯỜI DÙNG** |
| Designing a system that supports millions of users is challenging, and it is a journey that requires continuous refinement and endless improvement. | Việc thiết kế một hệ thống hỗ trợ hàng triệu người dùng là một thách thức, và đó là một hành trình đòi hỏi sự tinh chỉnh liên tục và cải tiến không ngừng. |
| In this chapter, we build a system that supports a single user and gradually scale it up to serve millions of users. | Trong chương này, chúng ta sẽ xây dựng một hệ thống hỗ trợ một người dùng duy nhất và dần dần mở rộng để phục vụ hàng triệu người dùng. |
| After reading this chapter, you will master a handful of techniques that will help you to crack the system design interview questions. | Sau khi đọc chương này, bạn sẽ nắm vững một số kỹ thuật giúp bạn chinh phục các câu hỏi phỏng vấn thiết kế hệ thống. |
| English | Vietnamese |
|---------|------------|
| **Single server setup** | **Cấu hình máy chủ đơn** |
| A journey of a thousand miles begins with a single step, and building a complex system is no different. | Hành trình ngàn dặm bắt đầu từ một bước đi nhỏ, và việc xây dựng một hệ thống phức tạp cũng không khác gì. |
| To start with something simple, everything is running on a single server. | Để bắt đầu với điều gì đó đơn giản, mọi thứ sẽ chạy trên một máy chủ duy nhất. |
| Figure 1-1 shows the illustration of a single server setup where everything is running on one server: web app, database, cache, etc. | Hình 1-1 minh họa cấu hình máy chủ đơn, nơi mọi thứ đều chạy trên một máy chủ: ứng dụng web, cơ sở dữ liệu, bộ nhớ đệm, v.v. |

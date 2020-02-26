---
title: Những câu hỏi "có thể" bạn nên biết khi mới đi phỏng vấn NodeJS
date: 2020-02-08
description: Câu hỏi phỏng vấn nodejs cho người mới đi phỏng vấn
tags:
  - NodeJS
  - NodeJS Interview question
  - Javascript
  - Developer
slug: "/cau-hoi-phong-van-nodejs-cho-nguoi-moi-di-phong-van"
banner: ./nodejs-interview.jpg
---

### Nếu bạn là một người mới học và sắp đi phỏng vấn để tìm kiếm một công việc Fresher/Junior NodeJS thì đây là một bài bạn nên đọc.

Đã là một Developer bản thân ai cũng muốn có một công việc tốt, 
nhưng tuyển dụng càng ngày càng khó khăn bởi những câu hỏi hóc búa và có những lí thuyết lúc làm không chú tâm tới đến lúc đi phỏng vấn mới vỡ oà ra. 
Dưới đây là những câu hỏi mà người phỏng vấn đã hỏi mình qua những lần đi phỏng vấn từ năm 2018 cho tới nay. Cứ mấy tháng là mình lại ra ngoài đi phỏng vấn một vài lần để cập nhật kiến thức.

Mình từng đi phỏng vấn dạo từ lúc còn là Internship của một công ty outsource cho tới bây giờ qua công ty làm về product cho banking và thông qua những người bạn đã và đang đi phỏng vấn chia sẻ lại. Mình
đúc kết ra những câu hỏi rất phổ biến dành cho các bạn mới và sắp đi phỏng vấn nên biết. Biết đâu những câu hỏi này sẽ giúp cho bạn đậu vào 1 công ty nào đó.

> Javascript
- [Scope, Hoisting](https://www.digitalocean.com/community/tutorials/understanding-variables-scope-hoisting-in-javascript)
- Ý nghĩa của biến this.
- Data types
- Closure là gì?
- `callback` là gì và hãy mô tả về nó.(`callback hell` là gì, lấy ví dụ)
- ES6(arrow function, variable scope)
- `Promise, Promise.all`
- Async/Await
- Typescript vs Javascript(Hiện giờ rất nhiều công ty đã và đang làm với Typescript vì vậy bạn nên và bắt buộc phải biết)

Javascript cheatsheet: https://htmlcheatsheet.com/js

> NodeJS
- Tại sao lại sử dụng NodeJs( có thể bạn phải so sánh NodeJS với Java/Python/.NET)
- Engine V8 là gì?
- [Event loop](https://blog.insiderattack.net/event-loop-and-the-big-picture-nodejs-event-loop-part-1-1cb67a182810)
- NPM là gì, làm sao để quản lí version của dependence.
- NodeJS framework mà bạn đã từng làm.
- Mô tả về quá trình tạo ra JWT token(issue, verify JWT token )

> REST API
- HTTP Method
- HTTP status code
- Lấy ví dụ về REST/RESTful
- Security REST API
- Quản lí API version

Tất tần tật về RESTful: https://restfulapi.net 

> Backend Skill
Nếu bạn apply vào vị trí Backend thì bạn bắt buộc phải có những kiến thức nền tảng dưới đây. 
Phỏng vấn Nodejs Developer không đơn thuần chỉ hỏi về NodeJS, ngoài ra bạn cần biết những kiến thức khác về phía server side.

 - [RMDBS & NoSQL](https://www.loginradius.com/engineering/relational-database-management-system-rdbms-vs-nosql/) (có thể lấy ví dụ MySQL vs MongoDB ra so sánh)
 - [Authentication & Authorization](https://engineering.tiki.vn/x%C3%A1c-th%E1%BB%B1c-v%C3%A0-ph%C3%A2n-quy%E1%BB%81n-trong-microservices-37689e53c082) (Xác thực và phân quyền lấy ví dụ về 1 bài viết trên blog của engineering.tiki.vn nên nếu bạn apply vào tiki thì trúng đề rồi >.< ).
 - [Basic design pattern](https://scotch.io/bar-talk/4-javascript-design-patterns-you-should-know) (Những pattern cơ bản bạn nên biết để dùng trong Javascript)
 - Docker, Linux
 - [Microservice](https://microservices.io). Phần lớn những công ty bây giờ đã và đang chuyển qua kiến trúc micro-service, bạn cũng không nên bỏ qua phần này.

 - [HTTP vs HTTPs](https://www.guru99.com/difference-http-vs-https.html). Tại sao nên dùng HTTPs trong việc communication giữa client và server.


> Testing
- Có nên áp dụng unit test, mục đích của unit test và các loại test trong phần mềm.
- Framework, lib dùng để viết unit test trong NodeJS(Jest, chai, mocha, supertest...)
- TDD, BDD là gì. Sự khác nhau giữa TDD và BDD.

Tất tần tật về test: https://martinfowler.com/articles/practical-test-pyramid.html

Ngoài những câu hỏi đã nêu ở trên, bây giờ đối với bất kì công ty nào nếu làm về Agile/Scrum họ sẽ hỏi bạn về cách bạn làm việc mỗi ngày.

Đây là tiều liệu chuẩn và tinh gọn nhất về Agile của ...  mà mình từng biết. Nếu bạn không có thời gian để đọc hết thì hãy tập trung vào phần Software Development. https://www.atlassian.com/agile/software-development

https://www.atlassian.com/agile

Hy vọng những chia sẻ của mình sẽ giúp ích cho các bạn trong quá trình apply NodeJS developer. Nếu có thắc mắc mình sẵn sàng cung cấp thêm tài liệu trong mục about me.

Phần kế tiếp: Những câu hỏi về system design đã được hỏi trong các buổi phỏng vấn.
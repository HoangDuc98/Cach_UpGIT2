
Recent
H? th?ng CodeGym
English ?(en)?
Enter your search query
Notifications
 
You have no notifications
See all
Lê Hoàng Ð?c

Course Overview
Gi?i thi?u khoá h?c
1. H?c cách h?c &amp; Qu?n lí công vi?c b?ng Kanban
2. Nh?p môn tu duy l?p trình
3. Mô t? thu?t toán b?ng Pseudo code &amp; Flowchart
4. Git &amp; HTML

[Bài gi?ng] Cách s? d?ng GitPage

[Bài d?c] T?ng quan v? GitPage

[Bài d?c] Các bu?c làm vi?c co b?n v?i GitPage

[Quiz] S? d?ng Git

[Th?c hành] Clone d? án t? GitAssignment

[Th?c hành] T?o d? án m?i trên GitHubAssignment

[Bài t?p] S? d?ng GitAssignment

[Bài gi?ng] M?t trang web co b?n và các th? HTMLPage

[Bài d?c] Th? HTML và thu?c tínhPage

[*Xem thêm] Máy tính ho?t d?ng nhu th? nào?Book

[Bài d?c] Các th? tiêu d? h1, h2, h3, h4, h5, h6Page

[Bài d?c] Th? t?o do?n van b?n: pPage

[Bài d?c] Th? t?o liên k?t: aPage

[Bài d?c] Th? hi?n th? hình ?nh: imgPage

[Bài d?c] S? d?ng các th? t?o danh sách: ul, ol, liPage

[Bài d?c] Chú thích trong HTMLPage

[Bài d?c] S? d?ng HTML entityPage

[Quiz] Can b?n v? web và HTML

[Quiz] S? d?ng các th? can b?n

[Th?c hành] S? d?ng th? HTML co b?nPage

[Bài t?p] T?o danh sáchPage

[Bài t?p] T?o trang CV cá nhânPage

[*Ð?c thêm] Các h? th?ng qu?n lý mã ngu?n và phiên b?nPage
5. HTML Form &amp; Table
6. T?ng quan JavaScript
7. Bi?n, ki?u d? li?u và toán t?
8. C?u trúc di?u ki?n 1
9. C?u trúc di?u ki?n 2
10. C?u trúc l?p 1
11. C?u trúc l?p 2
12. M?ng 1
13. M?ng 2
14. Hàm 1
15. Hàm 2
16. L?p trình hu?ng d?i tu?ng 1
17. L?p trình hu?ng d?i tu?ng 2
18. Thu?t toán 1
19. Thu?t toán 2
Bootcamp Preparation Case Study
Skip to main content
Bootcamp Preparation 2.0
Dashboard
My courses
 PP2.0
 4. Git & HTML
 [Th?c hành] T?o d? án m?i trên GitHub
[Th?c hành] T?o d? án m?i trên GitHub
M?c tiêu
Luy?n t?p thao tác t?o d? án m?i trên GitHub.

Mô t?
Trong ph?n này, chúng ta s? luy?n t?p thao tác quan tr?ng khi làm vi?c v?i GitHub dó là t?o m?t d? án m?i.

Sau khi th?c hi?n xong các bu?c hu?ng d?n thì hãy n?p bài t?p b?ng cách:

Mô t? l?i ý nghia c?a các câu l?nh dã s? d?ng
Dán link c?a Repository v?a t?o lên
Hu?ng d?n
Trong ph?n hu?ng d?n này, chúng ta s? t?o m?t d? án m?i trên GitHub và b?t d?u dua mã ngu?n lên dó. Các bu?c th?c hi?n nhu sau:

1. Ði d?n trang: https://github.com

2. Nh?n vào m?c "New repository" d? b?t d?u t?o m?t Repository m?i:



3. Trong màn hình t?o Repository m?i, chúng ta di?n tên c?a d? án m?i vào. Ch?ng h?n chúng ta d?t tên d? án m?i là "my-new-project". Sau dó nh?n và nút "Create repository".



K?t qu? s? du?c m?t Repository m?i. Giao di?n ban d?u c?a Repository này ch?a các hu?ng d?n c?n thi?t d? làm vi?c v?i nó:



4. Sau khi dã t?o du?c Remote Repository trên GitHub, bây gi? chúng ta s? m? c?a s? Terminal lên d? t?o Local Repository và d?ng b? nó t?i Remote Repository trên.

Chúng ta s? t?o m?t thu m?c m?i trên máy tính c?a mình, có th? d?t tên b?t k?. Ch?ng h?n chúng ta có th? d?t tên thuc m?c là "my-new-project" (gi?ng v?i tên c?a Repository).

5. Chuy?n Terminal d?n thu m?c "my-new-project" v?a t?o và s? d?ng l?nh git init d? kh?i t?o Repository m?i.



6. Ti?p theo, s? d?ng l?nh git remote add origin d? k?t n?i t?i Remote Repository (chú ý s? d?ng dúng du?ng d?n c?a Repository mà b?n v?a t?o):

git remote add origin https://github.com/codegym-vn/my-new-project.git


Nhu v?y là Local Repository và Remote Repository dã du?c liên k?t v?i nhau. Bây gi? chúng ta có th? b?t d?u làm vi?c trên d? án c?a mình.

7. Trong thu m?c "my-new-project", chúng ta t?o m?t file m?i có tên là "README.md". Ðây là file dùng d? ch?a mô t? v? d? án này, h?u h?t t?t c? các Repository d?u có file này d? gi?i thi?u cho ngu?i khác bi?t v? m?c dích c?a d? án. Chúng ta có th? vi?t m?t n?i dung b?t k? vào file này.



8. S? d?ng câu l?nh git add d? dua file README.md vào trong ch? m?c c?a Git.

git add README.md


9. S? d?ng câu l?nh git commit d? luu l?i các thay d?i.

git commit -m "Add README.md file"


Trong câu l?nh trên, tu? ch?n -m du?c s? d?ng d? ghi m?t "message" dánh d?u cho thay d?i v?a r?i. Nó gi?i thích r?ng chúng ta v?a thêm m?t file README.md m?i. Chúng ta c?n ghi các thông di?p có ý nghia d? d? dàng cho vi?c hi?u và c?ng tác nhóm sau này.

10. S? d?ng câu l?nh git push d? d?y các thay d?i ? Local Repository lên trên Remote Repository.

git push origin master


Nhu v?y là chúng ta dã hoàn thành m?t lu?ng làm vi?c co b?n v?i GitHub. Local Repository và Remote Repository dã du?c d?ng b? v?i nhau.

Th? quay l?i trang d? án ? trên GitHub thì chúng ta s? th?y m?t giao di?n nhu sau:



11. Hãy l?p l?i các bu?c t? 7 d?n 10 d? t?o các file m?i.

Submission status
Submission status	No attempt
Grading status	Not graded
Last modified	-
Submission comments	
Comments (0)
You have not made a submission yet.
Jump to...
Jump to...
CHUONG TRÌNH
Career
Premium
Accelerator
TÀI NGUYÊN
Blog
T?p chí L?p trình
AgileBreakfast
Follow Us
  

CodeGym@2018. All rights reserved.
You are logged in as Lê Hoàng Ð?c (Log out)
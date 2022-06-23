# Inception---Going-Deeper-with-Convolutions
Inception - Going Deeper with Convolutions

thuật toán Going Deeper with Convolutions :

Tích chập là ứng dụng đơn giản của bộ lọc đối với đầu vào dẫn đến kích hoạt. Việc áp dụng lặp lại cùng một bộ lọc cho một đầu vào sẽ dẫn đến một bản đồ kích hoạt được gọi là bản đồ đối tượng, cho biết vị trí
 và độ mạnh của đối tượng được phát hiện trong đầu vào, chẳng hạn như hình ảnh. 

Trong toán học (đặc biệt là giải tích hàm), tích chập là một phép toán trên hai hàm (f và g) tạo ra hàm thứ ba () biểu thị cách biến đổi hình dạng của hàm này bởi hàm kia. 
Thuật ngữ tích chập đề cập đến cả hàm kết quả và quá trình tính toán nó.
Sự biến đổi rất quan trọng vì nó liên quan đến ba tín hiệu được quan tâm: 
tín hiệu đầu vào, tín hiệu đầu ra và phản hồi xung.
Thuật ngữ tích chập đề cập đến sự kết hợp toán học của hai hàm để tạo ra một hàm thứ ba. Nó kết hợp hai bộ thông tin. Trong trường hợp của CNN, phép tích chập được thực hiện trên dữ liệu đầu vào với việc sử dụng bộ lọc hoặc hạt nhân
 (các thuật ngữ này được sử dụng thay thế cho nhau) để sau đó tạo ra một bản đồ đặc trưng.

Đây là các bước của tích chập:
Lấy tín hiệu và đặt ở đó để nó sẽ như vậy.
Lấy tín hiệu và đến bước 1 và thực hiện nó.
Thực hiện gấp của tín hiệu được.
Thực hiện dịch chuyển thời gian của tín hiệu trên.
Sau đó, thực hiện phép nhân của cả hai tín hiệu được.

Convolution là một phép toán đơn giản, cơ bản cho nhiều toán tử xử lý ảnh phổ biến. Convolution cung cấp một cách `` nhân với nhau '' hai mảng số, thường có kích thước khác nhau, 
nhưng có cùng chiều, để tạo ra mảng số thứ ba có cùng chiều.

Nếu chúng ta chèn hình ảnh bằng (F - 1) / 2 pixel trên tất cả các mặt, kích thước N x N sẽ được giữ nguyên. Do đó, chúng ta có hai loại chập, chập hợp lệ và biến đổi tương tự. Hợp lệ về cơ bản có nghĩa là không có phần đệm. 
Vì vậy, mỗi Convolution dẫn đến việc giảm kích thước.
# Đề cương giới hạn nội dung thi
Hình thức thi:
<ul>
  <li>tự luận, tại phòng máy, trên máy tính <b>chỉ được mở Python</b></li>
  <li>không được dùng tài liệu (kể cả trên máy tính)</li>
  <li>thời gian: 90 phút</li>
</ul>

## 1. Lý thuyết (học thuộc, 2-3đ, đề ra 1 câu)
<ol>
  <li><b>Chương 5:</b> Trình bày và đánh giá độ phức tạp của thuật toán <b>chia đôi</b> để tính $a^n$, với $a\in\Bbb R, n\in\Bbb N$ </li>
  <li><b>Chương 7:</b> Phát biểu, chứng minh công thức hàm <b>Euler phi</b> tìm các số nguyên dương nhỏ hơn $n$ và nguyên tố cùng nhau với $n$. Tìm $\varPhi(1984)$</li>
  <li><b>Chương 8:</b> Số <b>Catalan</b> là gì? Trình bày hệ thức đệ quy của số Catalan, và phương pháp hàm sinh để tìm công thức tường minh của nó</li>
  <li><b>Chương 9:</b> Phát biểu, chứng minh định lý <b>Léma</b> về đánh giá thuật toán <b>Euclid</b> tìm ước chung lớn nhất của hai số nguyên dương. Trình bày thuật toán Euclid tìm $\gcd(2023, 1984)$</li>
  <li><b>Chương 9:</b> Trình bày và đánh giá độ phức tạp của thuật toán <b>sắp xếp trộn</b></li>
  <li>...đang cập nhật</li>
</ol>

## 2. Bài tập trình bày lời giải (đổi dữ liệu, 5-6đ, đề ra 3 câu)
<ol>
  <li><b>Chương 1:</b> Với $n\in\Bbb Z$ cụ thể / bất kỳ, tìm số  lệnh <q>print</q> thực hiện trong chương trình
<pre>
for i = 1 to n do
  for j = 1 to i do
    for k = 1 to j - 1 do
      print i, j, k
</pre>
  </li>
  <li><b>Chương 4:</b> Bằng quy nạp, chứng minh $\displaystyle \sum\limits_{i = 1}^n {\frac{1}{{i(i + 1)}}}  = \frac{n}{{n + 1}},\; \forall n\in\Bbb Z^+$</li>
  <li><b>Chương 6:</b> Cho quan hệ $\mathcal{R}$ trên tập $A$ cỡ $n = 4, 5$ hoặc 6. Tìm bao đóng bắc cầu $\mathcal{R}^*$ của $\mathcal{R}$ bằng thuật toán
    <ol>
      <li>nhân ma trận: ghi ra các ma trận $M, M^2,\ldots, M^n$ và $M^*$</li>
      <li>Warshall: ghi ra các ma trận $W_0, W_1,\ldots, W_{n-1}$ và $M^*$</li>
    </ol>
  </li>
  <li><b>Chương 9:</b> Cho hàm $a(n)$ định nghĩa bằng đệ quy.
<pre>
def a(n):
    if n == 0:
        return 1
    return 2 * a(n-1) + 1
</pre>
    <ol>
      <li>Tính $a(3)$</li>
       <li></li> Đặt $f_n$ là số các phép toán số học và phép so sánh dùng để tính $a(n)$. Lập hệ thức đệ quy cho dãy $(f_n)$ và giải $f_n$.
    </ol>
  </li>
  <li>...đang cập nhật</li>
</ol>

## 3. Bài tập giải / tính bằng Python (đổi dữ liệu 1-2đ, đề ra 2 ý)
Loại bài tập này không cần trình bày, chỉ ghi kết quả, mục đích để kiểm tra kiến thức thực hành Python của sinh viên
<ol>
  <li>Tìm ước chung lớn nhất, bội chung nhỏ nhất</li>
  <li>Kiểm tra thuộc tính của quan hệ hai ngôi trên một tập</li>
  <li>Đếm nghiệm nguyên không âm của phương trình $x_1 + x_2 + x_3 = 4$</li>
  <li>Giải hệ thức đệ quy $a_n = 3a_{n-1} - 2a_{n-2} + n$, biết $a_0 = -1$, $a_1 = 2$</li>
  <li>... và nhiều câu hỏi khác nữa</li>
</ol>

# Đề cương giới hạn nội dung thi
Hình thức thi:
<ul>
  <li>tự luận, tại phòng máy, trên máy tính <b>chỉ được mở Python</b></li>
  <li>không được dùng tài liệu (kể cả trên máy tính)</li>
  <li>thời gian: 90 phút</li>
</ul>

## 1. Lý thuyết (học thuộc, 2-3đ, đề lấy 1 câu)
<ol>
  <li><b>Chương 4:</b> Phát biểu, chứng minh định lý <b>Lamé</b> về đánh giá thuật toán <b>Euclid</b> tìm ước chung lớn nhất của hai số nguyên dương. Minh họa thuật toán Euclid tìm $\gcd(2024, 1966)$</li>
  <li><b>Chương 4:</b> Trình bày thuật toán Euclid. Từ đó trình bày phương pháp tìm khai triển Euclid của hai số nguyên dương. Tìm khai triển Euclid của 2024 và 1966</li>
  <li><b>Chương 5:</b> Trình bày và đánh giá độ phức tạp của thuật toán <b>chia đôi</b> để tính $a^n$, với $a\in\Bbb R, n\in\Bbb N$. Minh họa giá trị của các biến trong thuật toán khi tính $a^{10}$</li>
  <li><b>Chương 7:</b> Phát biểu, chứng minh công thức hàm <b>Euler phi</b> đếm các số nguyên dương nhỏ hơn $n$ và nguyên tố cùng nhau với $n$. Tìm $\varPhi(1966)$</li>
  <li><b>Chương 7:</b> (Bài toán ghép cặp) Cho $n$ vật đánh số từ 1 tới $n$, và $n$ hộp đánh số từ 1 tới $n$. Xếp $n$ vật vào $n$ hộp sao cho mỗi hộp chỉ chứa 1 vật. Có bao nhiêu cách xếp để
    <ol>
      <li>có ít nhất một vật cùng số với hộp chứa nó</li>
      <li>không có hộp nào chứa vật cùng số với nó</li>
    </ol>
    Với $n = 10$, có bao nhiêu cách xếp như vậy?
  </li>
  <li><b>Chương 7:</b> (Đếm toàn ánh) Cho các số nguyên dương $m\ge n$. Nêu và chứng minh công thức đếm số toàn ánh từ tập cỡ $m$ vào tập cỡ $n$. Lập bảng tính số toàn ánh với $5\ge m\ge n\ge 1$</li>
  
</ol>

## 2. Bài tập trình bày lời giải (dạng bài tập, thay số / đổi dữ liệu, 6-7đ, đề lấy 3 câu)
<ol>
  <li><b>Chương 1:</b> <i>(Dùng các nguyên lý đếm cơ bản để đếm số chu trình tối giản trong các vòng lặp xác đinh)</i> Với $n\in\Bbb Z^+$ cụ thể / bất kỳ, tìm số  lệnh <q>print</q> thực hiện trong chương trình
<pre>
for i = 1 to n do
  for j = 1 to i do
    for k = 1 to j - 1 do
      print i, j, k
</pre>
  </li>
  <li><b>Chương 4:</b> <i>(Dùng phương pháp quy nạp toán học chứng minh các (1) đẳng thức, (2) tính chất của dãy Fibonacci)</i> Bằng quy nạp, chứng minh
    <ol>
      <li>$\displaystyle \sum\limits_{i = 1}^n {\frac{1}{{i(i + 1)}}}  = \frac{n}{{n + 1}},\; \forall n\in\Bbb Z^+$</li>
      <li>${F_{n + 2}} = 1 + {F_1} + {F_2} +  \cdots  + {F_n},\;\forall n \in {\Bbb Z^ + }$</li>
    </ol>
  </li>
  <li><b>Chương 6:</b> <i>(Tìm bao đóng bắc cầu)</i> Cho tập $A$ cỡ $n = 5$ hoặc 6, quan hệ $\mathcal{R}$ trên $A$. Tìm bao đóng bắc cầu $\mathcal{R}^*$ của $\mathcal{R}$ bằng thuật toán
    <ol>
      <li>nhân ma trận: ghi ra các ma trận $M, M^2,\ldots, M^n$ và $M^*$</li>
      <li>Warshall: ghi ra các ma trận $W_0, W_1,\ldots, W_{n-1}$ và $M^*$</li>
    </ol>
  </li>
  <li><b>Chương 6:</b> <i>(Quan hệ tương đương)</i> Cho tập $A$ cỡ $n = 6, 7$ hoặc 8, quan hệ $\mathcal{R}$ trên $A$.
    <ol>
      <li>Xác định ma trận quan hệ $M$ của $\mathcal{R}$. Từ đó chỉ ra $\mathcal{R}$ là quan hệ tương đương</li>
      <li>Xác định các lớp tương đương theo quan hệ $\mathcal{R}$</li>
    </ol>
  </li>
  <li><b>Chương 6:</b> <i>(Quan hệ thứ tự)</i> Cho tập $A$ cỡ $n = 6, 7$, quan hệ $\mathcal{R}$ trên $A$.
    <ol>
      <li>Xác định ma trận quan hệ $M$ của $\mathcal{R}$. Từ đó chỉ ra $\mathcal{R}$ là quan hệ thứ tự</li>
      <li>Xây dựng biểu đồ Hasse cho $\mathcal{R}$</li>
      <li>Chỉ ra một sắp xếp tôpô của $\mathcal{R}$</li>
      <li>Chỉ ra các phần tử tối đại, tối tiểu của $A$ theo quan hệ thứ tự $\mathcal{R}$</li>
    </ol>
  </li>

  <li><b>Chương 6:</b>
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

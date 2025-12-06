# Bài 7
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tổng hợp nội dung Tin học 12</title>
    <style>
        body {font-family: Arial, sans-serif; line-height: 1.6; padding: 20px; background:#f9f9f9; color:#333;}
        h1, h2, h3 {color:#1e3a8a;}
        pre {background:#e5e7eb; padding:10px; border-radius:6px; overflow-x:auto;}
        code {background:#f3f4f6; padding:2px 4px; border-radius:4px;}
        ul, ol {margin:10px 0 20px 20px;}
        .section {margin-bottom:30px;}
        img {max-width:100%; height:auto;}
        blockquote {border-left: 4px solid #60a5fa; margin:10px 0; padding-left:10px; color:#1e40af;}
    </style>
</head>
<body>

    <h1>Tổng hợp nội dung Tin học 12 (Trang 39 → 44)</h1>

    <div class="section">
        <h2>Khởi động trang 39</h2>
        <p>Các em đã được làm quen với khái niệm website và trang web, cũng có thể em đã biết cách sử dụng phần mềm để tạo ra các trang web với nội dung đa dạng và phong phú, hình thức trình bày đẹp. Tuy nhiên, có thể các em vẫn muốn biết:</p>
        <ul>
            <li>Các trang web thực chất có cấu trúc như thế nào?</li>
            <li>Có thể lập trình để tạo ra được các trang web hay không? Nếu lập trình được thì mã nguồn của trang web là gì?</li>
            <li>Các trang web có quan hệ như thế nào với ngôn ngữ HTML?</li>
            <li>Trang web và trình duyệt web có quan hệ như thế nào?</li>
        </ul>
        <p><strong>Lời giải:</strong></p>
        <ul>
            <li>Một trang web thường được cấu thành từ các tệp HTML, CSS và JavaScript.</li>
            <li>Có thể lập trình để tạo ra được các trang web. Mã nguồn của một trang web được lập trình bằng các ngôn ngữ này, đặc biệt là HTML (cho cấu trúc), CSS (cho trình bày), và JavaScript (cho hành vi và tương tác).</li>
            <li>Trình duyệt web là phần mềm được sử dụng để hiển thị và tương tác với các trang web.</li>
            <li>Trang web được tạo ra bằng ngôn ngữ lập trình như HTML, CSS và JavaScript. Khi bạn truy cập vào một trang web, trình duyệt tải và hiển thị nội dung của trang web đó theo cấu trúc và trình bày được định nghĩa bởi mã nguồn HTML, CSS và JavaScript.</li>
        </ul>
    </div>

    <div class="section">
        <h2>Hoạt động 1 trang 39</h2>
        <p>Các trang web mà em vẫn thường xem được hiển thị bởi trình duyệt web (ví dụ Cốc Cốc, Firefox, Chrome). Thực chất chúng được tạo ra từ các tệp văn bản. Các tệp văn bản này được gọi là trang nguồn (hay mã nguồn) của trang web tương ứng. Quan sát hình 7.1 và nhận xét:</p>
        <p><strong>Lời giải:</strong> Trang web được thiết lập theo một ngôn ngữ có cấu trúc đặc biệt gọi là HTML. Mỗi tệp HTML gồm các phần tử HTML, mỗi phần tử gồm nội dung được đánh dấu bởi các thẻ HTML Tag.</p>
    </div>

    <div class="section">
        <h2>Câu hỏi 1 trang 41</h2>
        <p><strong>Hỏi:</strong> Tệp văn bản trong Hình 7.1 có bao nhiêu phần tử HTML?</p>
        <p><strong>Lời giải:</strong> Hình 7.1 có 3 phần tử HTML.</p>

        <h2>Câu hỏi 2 trang 41</h2>
        <p><strong>Hỏi:</strong> Nêu sự giống và khác nhau giữa thẻ HTML và phần tử HTML</p>
        <p><strong>Lời giải:</strong></p>
        <ul>
            <li><strong>Giống nhau:</strong>
                <ul>
                    <li>Đều là thành phần cơ bản của HTML.</li>
                    <li>Cấu trúc gồm thẻ mở và thẻ đóng (nếu cần).</li>
                    <li>Định nghĩa và hiển thị nội dung trang web.</li>
                </ul>
            </li>
            <li><strong>Khác nhau:</strong>
                <ul>
                    <li>Thẻ HTML là cú pháp, phần tử HTML là đơn vị cụ thể chứa nội dung hoặc các phần tử khác.</li>
                    <li>Thẻ HTML thuộc ngôn ngữ, phần tử HTML là thành phần của trang web.</li>
                </ul>
            </li>
        </ul>
    </div>

    <div class="section">
        <h2>Hoạt động 2 trang 41</h2>
        <p><strong>Lời giải:</strong> Cấu trúc chung của một trang web:</p>
        <ul>
            <li>Thẻ <code>&lt;html&gt;</code>: phần tử gốc chứa toàn bộ nội dung.</li>
            <li><code>&lt;head&gt;</code>: chứa meta, tiêu đề, liên kết CSS/JS, thông tin khác.</li>
            <li><code>&lt;body&gt;</code>: chứa nội dung hiển thị (văn bản, hình ảnh, liên kết, biểu mẫu...).</li>
            <li>Các phần tử HTML khác: p, b, i, u, img, form,...</li>
            <li>Thẻ kết thúc <code>&lt;/html&gt;</code>: đánh dấu kết thúc.</li>
        </ul>
    </div>

    <div class="section">
        <h2>Câu hỏi 1 trang 43</h2>
        <p><strong>Lời giải:</strong></p>
        <pre>
&lt;html&gt;
  |
  |_______
  |       |
&lt;head&gt;  &lt;body&gt;
  |       |
  |      _________
  |     |    |    |
  |    &lt;p&gt;  in   in
  |    / | \       \
  |  &lt;b&gt; &lt;i&gt; &lt;u&gt;    |
  |         |       |
  |   in đậm in nghiêng in gạch dưới in bình thường.
  |        /_______
  |         |
  |      &lt;/i&gt;
  |
&lt;/p&gt;
        </pre>

        <h2>Câu hỏi 2 trang 43</h2>
        <p><strong>Lời giải:</strong> Thẻ <code>&lt;html&gt;</code> là thẻ gốc duy nhất.</p>
    </div>

    <div class="section">
        <h2>Hoạt động 3 trang 43</h2>
        <p><strong>Lời giải:</strong> Một số phần mềm soạn thảo HTML:</p>
        <ul>
            <li>Notepad, TextEdit, gedit</li>
            <li>Sublime Text, Notepad++</li>
        </ul>
    </div>

    <div class="section">
        <h2>Câu hỏi 1 trang 44</h2>
        <p><strong>Lời giải:</strong></p>
        <ul>
            <li>Phần mềm soạn thảo HTML: Notepad, Sublime Text, Notepad++</li>
            <li>Trình duyệt web: Opera, Chrome, Cốc Cốc, Firefox, Microsoft Edge</li>
        </ul>
        <p>Giải thích: Phần mềm soạn thảo HTML để viết mã, trình duyệt web để hiển thị và tương tác.</p>

        <h2>Câu hỏi 2 trang 44</h2>
        <p><strong>Lời giải:</strong> Phần mềm chuyên nghiệp hỗ trợ nhiều tính năng như highlight mã, plugin, tự động điền, kiểm tra lỗi, trong khi phần mềm đơn giản chỉ soạn thảo văn bản.</p>
    </div>

    <div class="section">
        <h2>Luyện tập 1 trang 44</h2>
        <p><strong>Lời giải:</strong> Ví dụ phần tử HTML không thể lồng:</p>
        <pre>
&lt;!DOCTYPE html&gt;
&lt;html lang="en"&gt;
&lt;head&gt;
    &lt;meta charset="UTF-8"&gt;
    &lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;
    &lt;title&gt;Phần tử img&lt;/title&gt;
&lt;/head&gt;
&lt;body&gt;
    &lt;img src="example.jpg" alt="Mô tả hình ảnh"&gt;
&lt;/body&gt;
&lt;/html&gt;
        </pre>
    </div>

    <div class="section">
        <h2>Luyện tập 2 trang 44</h2>
        <p><strong>Lời giải:</strong></p>
        <pre>
&lt;!DOCTYPE html&gt;
&lt;html lang="vi"&gt;
&lt;head&gt;
    &lt;meta charset="UTF-8"&gt;
    &lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;
    &lt;title&gt;Văn bản về sen&lt;/title&gt;
&lt;/head&gt;
&lt;body&gt;
    &lt;p&gt;"Trong đầm gì đẹp bằng sen, lá xanh bông trắng lại chen nhị vàng."&lt;/p&gt;
&lt;/body&gt;
&lt;/html&gt;
        </pre>
        <p>Cây thông tin:</p>
        <pre>
&lt;html&gt;
  |
  ├── &lt;head&gt;
  |     ├── &lt;meta charset="UTF-8"&gt;
  |     ├── &lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;
  |     └── &lt;title&gt;Văn bản về sen&lt;/title&gt;
  └── &lt;body&gt;
        └── &lt;p&gt;"Trong đầm gì đẹp bằng sen..."&lt;/p&gt;
        </pre>
    </div>

    <div class="section">
        <h2>Vận dụng 1 trang 44</h2>
        <p><strong>Lời giải:</strong> Một số trang web hỗ trợ soạn thảo HTML trực tuyến:</p>
        <ul>
            <li>JSFiddle: <a href="https://jsfiddle.net/" target="_blank">https://jsfiddle.net/</a></li>
            <li>CodePen: <a href="https://codepen.io/" target="_blank">https://codepen.io/</a></li>
            <li>JS Bin: <a href="https://jsbin.com/" target="_blank">https://jsbin.com/</a></li>
            <li>Repl.it: <a href="https://replit.com/" target="_blank">https://replit.com/</a></li>
        </ul>
    </div>

    <div class="section">
        <h2>Vận dụng 2 trang 44</h2>
        <pre>
&lt;!DOCTYPE html&gt;
&lt;html lang="vi"&gt;
&lt;head&gt;
    &lt;meta charset="UTF-8"&gt;
    &lt;title&gt;Lịch sử phát triển HTML&lt;/title&gt;
&lt;/head&gt;
&lt;body&gt;
    &lt;h1&gt;&lt;strong&gt;Lịch sử phát triển HTML&lt;/strong&gt;&lt;/h1&gt;
    &lt;p&gt;Các chuẩn HTML hiện nay được Tim Berners-Lee đưa ra lần đầu tiên vào những năm 1990.&lt;/p&gt;
    &lt;p&gt;Ý tưởng ban đầu là thiết lập chuẩn chung để chia sẻ văn bản trong CERN.&lt;/p&gt;
    &lt;img src="đường_dẫn_đến_hình_ảnh" alt="Sơ đồ Hypertext" style="max-width: 100%; height: auto;"&gt;
    &lt;p&gt;Phiên bản đầu tiên HTML ra đời 1991, phiên bản hiện tại là HTML5 năm 2014.&lt;/p&gt;
&lt;/body&gt;
&lt;/html&gt;
        </pre>
    </div>

</body>
</html>

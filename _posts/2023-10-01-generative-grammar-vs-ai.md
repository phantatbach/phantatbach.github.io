---
title: "Generative Grammar vs A.I."
layout: post
---
<div style="display: flex; justify-content: center; padding: 20px;">
    <img src="{{ site.baseurl }}/assets/media/posts/2023-10-01-generative-grammar-vs-ai-1.png" alt="Illustration" style="width: 500px; height: auto;">
</div>
Phản hồi lại 1 bình luận về ngữ pháp tiếng Anh.

Generative Grammar vs A.I.

- Nếu như syntax của English rõ ràng đến vậy, tại sao các mô hình Ngôn Ngữ không đưa thẳng nó vào cấu trúc? Tại sao lại cứ phải đi theo các mô hình xác suất rồi tinh chỉnh chỉ để thêm được vài %?

- Người ta chưa tìm thấy chỗ nào trong não bộ chứa cái internal grammar đó. Kể cả 2 khu vực Wernicke và Broca cũng chỉ mang tính tương quan (não bộ có khả năng thay đổi nguồn lực nếu 1 vùng nào đó bị tổn thương, tất nhiên là trong 1 độ tuổi nhất định).

- Ngay cả những công thức syntax cũng không nhất quán, với vô vàn giả thuyết đấu đá lẫn nhau trong cùng 1 ngôn ngữ và giữa các ngôn ngữ khác nhau.

- Deep structure liệu có giới hạn không? Nếu không thì hoàn toàn có thể bịa thêm 1 đống công thức nữa ra.

Ví dụ đơn giản: 10 + 10 = 20. (surface)

Deep 1: (5 + 5) + (5 + 5) = 20

Deep 2: (2 + 2 + 2 + 2 + 2) + (2 + 2 + 2 + 2 + 2) = 20

...

Deep n: (1 + 1 + 1 + ... + 1) + (1 + 1 + ... +1) = 20

- Các mô hình xác suất cho kết quả tốt hơn rất nhiều đối với các mô hình rule-based truyền thống, từ Computer Vision đến NLP.

- Việc yêu cầu nhiều dữ liệu là một trong những vấn đề của các mô hình đó. Tuy nhiên với sự phát triển của các thuật toán, kĩ thuật tinh chỉnh, tối ưu hóa thì (khả năng cao) nó sẽ không phải là vấn đề.

- Một ý phụ của ý trên: Nếu coi con người là 1 cỗ máy thì data nạp vào cũng không hề ít. Con người học không chỉ bằng chữ cái mà còn cả hình ảnh, âm thanh, ... (multi modal). Các mô hình hiện tại cũng đang tích hợp dần vào (ví dụ: nhập chữ ra ảnh).

- Việc tạo ra các tổ-hợp-từ-chưa-gặp-bao-giờ chính là extrapolation. Ở không gian cực nhiều chiều thì có lẽ đó không phải vấn đề quá lớn.

Chốt lại: Việc mô phỏng lại nhận thức của não bộ (trong đó bao gồm cả Ngôn Ngữ) là một việc vô cùng khó, nhưng các mô hình xác suất/ Machine Learning mới đang làm tốt hơn các mô hình rule based truyền thống.

<div style="display: flex; justify-content: center; padding: 20px;">
    <img src="{{ site.baseurl }}/assets/media/posts/2023-10-01-generative-grammar-vs-ai-2.png" alt="Illustration" style="width: 500px; height: auto;">
</div>

Phản hồi của mình:
1. Lí do Generative không thể phân tích 1 cách thâu đáo là bởi assumption của nó đã yếu ngay từ đầu, trừ khi bạn chỉ cho mình được vị trí của cái internal grammar đó.

2. Khả năng mô tả của UG/GG cũng đang đi vào ngõ cụt với sự phát triển của Corpus/ NLP/ Data Science. UG KHÔNG THỂ mô tả được high dimensionality data. Nếu cố gắng đưa vào UG thì nó vẫn thua các mô hình Machine Learning.

3. Khả năng dự đoán, giải thích của UG cũng cực kì yếu vì nó toàn tự vẽ thêm ra nguyên tắc.
4. Trẻ khiếm thính, khiếm thị (đặc biệt là bẩm sinh) sẽ gặp khó khăn khi phải hiểu các khái niệm liên quan đến các giác quan mà họ bị yếu. Bạn có thể đọc mô tả về màu đỏ (màu quả táo, bước sóng 670, vv) nhưng chỉ khi bạn nhìn thấy được màu đỏ, bạn mới thực sự cảm nhận được nó.

5. Tinh tinh có đủ giác quan như con người nhưng chức năng, cấu tạo của chúng khác con người. Hơn nữa cấu tạo của não của tinh tinh cũng khác não người, vậy nên lập luận của bạn hoàn toàn bất hợp lí. Không biết bạn đã từng học về Ngôn Ngữ Học Tiến Hóa hay Ngôn Ngữ Học Thần Kinh chưa? Nếu chưa thì có lẽ bạn không nền đi sâu vào ý này.

6. Mình không hiểu ý câu đố của bạn? Các mô hình ML coi Ngôn Ngữ là dữ liệu và biểu diễn chúng dưới dạng vector n chiều, sau đó sử dụng các phương pháp Xác Suất để xử lí chúng. Có vẻ bạn cũng chả hiểu gì về ML nên mình cũng không đi sâu vào nó nữa.

7. Mình từng học/đọc về UG và chả thấy nó giới hạn gì. Càng đi sâu càng thêm 1 đống công thức mới (ý 3). Và UG KHÔNG THỂ biểu diẽn được high dimensional data, nếu cố đưa vào thì nó chính là (1 phiên bản tệ hơn của) ML (ý 2).

8. Lộ trình nghe qua thì rõ ràng nhưng đường đi thì toàn ổ gà với BOT thôi =))) UG outdated rồi. Chả phải tự nhiên người ta chuyển qua các nhánh khác.
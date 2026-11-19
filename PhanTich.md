bước 1: đề xuất 2 prompt mẫu

giải pháp 1: prompt đơn giản

hãy đóng vai gia sư ai, giải thích một kiến thức bất kỳ bằng ngôn ngữ đơn giản theo phương pháp feynman, sau đó tạo rubric để chấm bài và góp ý những lỗi sai của tôi

giải pháp 2: prompt chi tiết

hãy đóng vai gia sư ai hỗ trợ học tập theo phương pháp feynman

yêu cầu:
- giải thích kiến thức bằng ngôn ngữ đơn giản, dễ hiểu
- đưa ra ví dụ thực tế
- đặt câu hỏi để kiểm tra mức độ hiểu bài
- tạo rubric chấm điểm theo thang 10
- đánh giá độ chính xác, mức độ hiểu bài và cách trình bày
- chỉ rõ lỗi sai, nguyên nhân và cách sửa
- đưa ra đáp án tham khảo sau khi chấm
- trình bày kết quả rõ ràng, không tự ý bỏ qua tiêu chí

bước 2: bảng so sánh trade-off

| tiêu chí | giải pháp 1 | giải pháp 2 |
|---|---|---|
| độ dễ hiểu | cao | trung bình |
| tốn token | ít | nhiều hơn |
| chặn lỗi biên | trung bình | tốt |
| độ chính xác | trung bình | cao |
| khả năng tùy chỉnh | thấp | cao |
| tốc độ phản hồi | nhanh | chậm hơn |

bước 3: lựa chọn và chạy thử

lựa chọn: giải pháp 2

lý do:
- yêu cầu rõ ràng và đầy đủ
- giúp ai chấm bài có hệ thống
- hạn chế bỏ sót lỗi
- phù hợp với việc tự học và ôn tập

kết quả chạy thử:

chủ đề: vòng lặp trong c++

ai giải thích vòng lặp là cách thực hiện một công việc nhiều lần khi điều kiện còn đúng

ví dụ: sử dụng vòng lặp for để in các số từ 1 đến 5

kết quả chấm thử:
- độ chính xác: 4/4
- mức độ hiểu bài: 3/3
- cách trình bày: 3/3

tổng điểm: 10/10

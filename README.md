## Sử dụng API:

### CRF
* Chạy service: Đứng ở thư mục API_crf, chạy `python service.py`
* Sử dụng trực quan: Truy cập link sau trên Firefox (để tránh lỗi font):
`http://localhost:3000/ner/crf?text=` + `câu muốn test`.
* Ví dụ: `http://localhost:3000/ner/crf?text=Đội tuyển Việt Nam chưa hề thắng ở sân Mỹ Đình, từ giai đoạn bán kết và chung kết các kỳ AFF Cup từ trước đến nay. Dù vậy, đội bóng của HLV Park Hang Seo thậm chí vẫn chưa cần phá cái dớp thiếu may mắn đấy vẫn có thể vào chung kết AFF Cup 2018.`.

 ![img](https://i.imgur.com/oRD7lyS.png)

### Deep Learning
* Đứng ở thư mục API_dl, chạy `python src/api/ner_service.py`
* Sử dụng trực quan: Truy cập link sau trên Firefox (để tránh lỗi font):
`http://localhost:1111/ner/deeplearning?text=` + `câu muốn test`.
* Ví dụ: `http://localhost:1111/ner/deeplearning?text=Đội tuyển Việt Nam chưa hề thắng ở sân Mỹ Đình, từ giai đoạn bán kết và chung kết các kỳ AFF Cup từ trước đến nay. Dù vậy, đội bóng của HLV Park Hang Seo thậm chí vẫn chưa cần phá cái dớp thiếu may mắn đấy vẫn có thể vào chung kết AFF Cup 2018.`.

 ![img](https://i.imgur.com/DNobt2H.png)

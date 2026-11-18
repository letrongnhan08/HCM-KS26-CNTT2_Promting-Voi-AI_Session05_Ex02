### Bài thực hành 2: Xây dựng chuỗi Prompt viết bài PR sản phẩm công nghệ

Bây giờ bạn hãy xem những ví dụ của tôi để làm output cho các bài báo PR Marketing

**Lưu ý: Quy tắc chung cho toàn chuỗi Prompt:**

- **Tone of Voice (Giọng điệu):** Chuyên nghiệp, tin cậy, khách quan, mang tính giật gân, thu hút, lôi cuốn
- CƠ CHẾ XỬ LÝ ĐỨT GÃY (CONTINUE GENERATING):
1. Khi bị giới hạn token tối đa (Max Tokens), thì phải ngắt bằng từ khóa `[TRUNCATED]`
2. Quy tắc tiếp tục ghi nội dung (Continuation): Khi nhận được lệnh "Tiếp tục" của ngữ cảnh trước đó, hãy đọc lại đoạn văn bản bị dừng ngay trước từ `[TRUNCATED]` và viết tiếp phần còn lại một cách liền mạch, không được lặp lại phần viết trước kia.

Ví dụ minh họa:

**Prompt 1: Nghiên cứu Đối tượng & Pain Points**
"Hãy đóng vai chuyên gia nghiên cứu thị trường Bất động sản. Và cần tuân thủ các tiêu chí sau:
1. Xác định chân dung khách hàng mục tiêu chính là lĩnh vực gì,đặc trưng ví dụ (Nhà đầu tư cá nhân trung/cao cấp hoặc Chủ sở hữu mua để ở, độ tuổi 35-50, thu nhập cao, bận rộn).
2. Xây dựng danh sách 4 điểm đau (Pain points) lớn nhất của nhóm khách hàng này khi sở hữu hoặc vận hành bất động sản cao cấp truyền thống (ví dụ: khó khăn trong việc quản lý cho thuê từ xa, rủi ro vận hành, thiếu minh bạch tài chính, tốn thời gian bảo trì...).
3. Với mỗi pain point, đưa ra cách thức giải quyết đột phá mà giải pháp Căn hộ 4 sao sang trọng,phong cảnh đẹp mang lại.

ĐẦU RA BẮT BUỘC: Trình bày kết quả rõ ràng theo định dạng cấu trúc sau (để tôi dùng làm dữ liệu đầu vào cho bước tiếp theo):
- [CHÂN DUNG KHÁCH HÀNG]: ...
- [DANH SÁCH PAIN POINTS VÀ GIẢI PHÁP]:
  1. Pain Point 1: [...] -> Giải pháp AI: [...]
  2. Pain Point 2: [...] -> Giải pháp AI: [...]
  3. Pain Point 3: [...] -> Giải pháp AI: [...]
  4. Pain Point 4: [...] -> Giải pháp AI: [...]

**Prompt 2: Thiết lập Dàn ý Chi tiết (Outline) chuẩn SEO**

- Hãy đóng vai một Biên tập viên SEO Bất động sản cao cấp
- Dựa vào dữ liệu của Prompt 1 , hãy làm 1 bài viết PR chuyên sâu (khoảng 1000 - 1500 từ) cho sản phẩm "Căn hộ 4 sao sang trọng,phong cảnh đẹp"

[DÁN OUTPUT CỦA PROMPT 1 VÀO ĐÂY]

- Yêu cầu cấu trúc bài viết:
Đọc lại (Lưu ý: Quy tắc chung cho toàn chuỗi Prompt) và tính toán trước khi viết output.
Bài viết PR đầu ra cuối cùng cần đạt cấu trúc chuẩn SEO bao gồm:
- Tiêu đề (Headline) thu hút, chứa từ khóa chính.
- Đoạn mở đầu (Lead): Móc nối trực tiếp từ Pain Points.
- Các tiểu mục H2, H3 cụ thể tương ứng với từng giải pháp AI.
- Lời kêu gọi hành động (CTA) ở cuối bài.

Prompt 3: Triển khai Viết chi tiết & Xử lý Đứt gãy Ngữ cảnh (Max Token)

- Đóng vai là một Copywriter chuyên nghiệp trong lĩnh vực bất động sản cao cấp.
- Sử dụng , đọc cái prompt 1 và prompt 2 ở trên kia,thì hãy tiến hành viết chi tiết Phần 1 của bài viết PR (hoặc viết từ Tiêu đề cho đến hết tiểu mục H2 đầu tiên).
- Yêu cầu cấu trúc bài viết:
Đọc lại (Lưu ý: Quy tắc chung cho toàn chuỗi Prompt) và tính toán trước khi viết output.

Output đầu ra từ AI:

**1. Danh sách Pain Points**

1. **Pain Point 1:** Khó khăn khi tự quản lý vận hành và cho thuê từ xa do chủ sở hữu có lịch trình bận rộn. -> _Giải pháp:_ Hệ sinh thái quản gia chuẩn 4 sao vận hành tự động hóa 24/7.
    
2. **Pain Point 2:** Rủi ro tài sản xuống cấp do thiếu quy trình bảo dưỡng nội thất chuyên nghiệp. -> _Giải pháp:_ Đội ngũ kỹ thuật túc trực và kiểm định định kỳ minh bạch.
    
3. **Pain Point 3:** Sự mập mờ về dòng tiền và chi phí khai thác cho thuê hàng tháng. -> _Giải pháp:_ Nền tảng báo cáo tài chính trực tuyến tự động theo thời gian thực.
    
4. **Pain Point 4:** Không gian sống ngột ngạt tại đô thị làm hao mòn năng lượng sống. -> _Giải pháp:_ Kiến trúc sinh thái cảnh quan xanh độc bản với tầm nhìn triệu đô.
    

**2. Đoạn mở đầu**

Giữa guồng quay bận rộn, giới thượng lưu luôn khao khát một không gian nghỉ dưỡng đỉnh cao để tái tạo năng lượng và sinh lời bền vững. Tuy nhiên, những "nỗi đau" về vận hành, quản lý tài sản truyền thống lại vô tình biến niềm vui sở hữu thành áp lực lớn.

- **Tiêu đề H2 - Phần 1: Khi Giới Thượng Lưu Đối Mặt Với Bài Toán Vận Hành Bất Động Sản Truyền Thống**
    
    - H3: Gánh nặng quản lý cho thuê từ xa và nỗi lo tài sản hao hụt.
        
    - H3: Sự thiếu minh bạch trong dòng tiền và áp lực bảo trì thủ công.
        
- **Tiêu đề H2 - Phần 2: Căn Hộ 4 Sao Sang Trọng - Định Nghĩa Lại Chuẩn Mực Sống Và Đầu Tư Thảnh Thơi**
    
    - H3: Hệ sinh thái quản gia 4 sao và công nghệ vận hành tự động 24/7.
        
    - H3: Minh bạch tài chính tuyệt đối qua nền tảng báo cáo thời gian thực.
        
- **Tiêu đề H2 - Phần 3: Kiến Trúc Cảnh Quan Độc Bản - Liều Thuốc Chữa Lành Cho Tâm Hồn**
    
    - H3: Tầm nhìn triệu đô kết hợp không gian sinh thái xanh thuần khiết.
        
- **Tiêu đề H2 - Phần 4: Lời Kêu Gọi Hành Động (CTA)**
    
    - Kêu gọi đăng ký nhận bảng giá độc quyền và tham quan nhà mẫu thực tế.

**OUTPUT - PROMPT 3: Triển khai Viết chi tiết (Phần 1) & Xử lý Đứt gãy Ngữ cảnh**

**Giải Mã Căn Hộ 4 Sao Sang Trọng, Phong Cảnh Đẹp: Đỉnh Cao Đầu Tư Và Tận Hưởng**

Giữa guồng quay hối hả của nền kinh tế hiện đại, giới đầu tư trung và cao cấp độ tuổi từ 35 đến 50 luôn khao khát tìm kiếm một chốn an cư vừa khẳng định vị thế đỉnh cao, vừa là kênh trú ẩn dòng tiền an toàn. Thế nhưng, đằng sau những khối tài sản triệu đô truyền thống lại là muôn vàng góc khuất mệt mỏi: từ việc đau đầu quản lý cho thuê từ xa, nỗi lo tài sản xuống cấp, cho đến sự mập mờ trong biên lai tài chính mỗi tháng.

Chính thức bước ra khỏi những khuôn mẫu lỗi thời, dòng sản phẩm **Căn hộ 4 sao sang trọng, phong cảnh đẹp** đang tạo ra một cuộc cách mạng thực sự trên thị trường. Đây không chỉ là một nơi để ở, mà là kiệt tác kiến trúc giải quyết triệt để mọi nỗi đau của giới chủ tinh hoa.

## **1. Khi Giới Thượng Lưu Đối Mặt Với Bài Toán Vận Hành Bất Động Sản Truyền Thống**

### **Gánh nặng quản lý từ xa và nỗi lo tài sản hao hụt**

Đối với những chủ sở hữu sở hữu quỹ thời gian eo hẹp, việc đứng ra tự quản lý căn hộ cho thuê cao cấp biến thành một cực hình thực sự. Từ việc tìm kiếm khách thuê, xử lý sự cố phát sinh ban đêm cho đến việc giám sát chất lượng nội thất đắt tiền đều tiêu tốn năng lượng khủng khiếp. Chưa kể, nếu không có quy trình bảo dưỡng chuẩn mực, giá trị tài sản sẽ nhanh chóng xuống cấp, làm sụt giảm nghiêm trọng giá trị chuyển nhượng hay khai thác dòng tiền [TRUNCATED]

(prompt hãy gõ tiếp từ bị dừng [TRUNCATED])

**(Câu AI trả lời tiếp:)**

...trong thời gian ngắn. Sự bất cập này khiến tiềm năng sinh lời của bất động sản bị kìm hãm, biến niềm tự hào sở hữu tài sản thành gánh nặng vận hành đắt đỏ.

## **2. Căn Hộ 4 Sao Sang Trọng - Giải Pháp Toàn Diện Cho Giới Chủ Tinh Hoa**

### **Hệ sinh thái vận hành tự động và gia tăng giá trị tài sản**

Giải pháp căn hộ 4 sao mang đến bước đột phá khi loại bỏ hoàn toàn khâu quản lý thủ công phức tạp. Mọi nhu cầu từ vận hành, bảo dưỡng đến khai thác cho thuê đều được số hóa và chuẩn hóa dưới sự giám sát của đội ngũ chuyên gia tận tâm. Nhờ đó, tài sản của bạn không ngừng được bảo toàn nguyên vẹn giá trị, mang lại dòng tiền thụ động vững chắc và thảnh thơi trọn vẹn từng khoảnh khắc sống.

**Đăng ký ngay hôm nay để nhận trọn bộ tài liệu phân tích đầu tư và đặc quyền tham quan nhà mẫu căn hộ 4 sao sang trọng!**

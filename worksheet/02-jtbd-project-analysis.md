---
artifact: 02 — JTBD Project Analysis
bai-tap: Lab 2 — Dùng JTBD để soi lại dự án nhóm
format: Theo nhóm dự án → share trong bàn → chốt hypothesis cuối
time: 25 phút trên lớp
nop-cuoi: Có — đây là file nộp cuối của Lab 2
companion-reference: Strategyn_JTBD_Playbook.pdf (giảng viên gửi kèm)
---

# Lab 2 — JTBD Project Analysis / Dùng JTBD để soi lại dự án nhóm

**Tên dự án / sản phẩm:** AI Gia Sư Cá Nhân Hóa Cho Học Sinh Phổ Thông  

> Đây là **file duy nhất** của Lab 2.  
> File này đồng thời đóng vai trò:
>
> - guide từng bước,
> - worksheet để điền trực tiếp,
> - và file nộp cuối cho người chấm.

Mục tiêu của bài này không phải brainstorm thêm thật nhiều tính năng AI.
Mục tiêu là:

1. **xác định người dùng thực sự đang cố hoàn thành job gì**
2. **hiểu họ đang dùng giải pháp nào để hoàn thành job đó hôm nay**
3. **chỉ ra AI nên chen vào đúng bước nào trong workflow**
4. **viết ra product hypothesis và assumption còn phải validate**

Quy tắc xuyên suốt: **không rõ job thì đừng bàn feature.**

---

## Cần mở song song 2 thứ

1. **File này** — để điền trực tiếp
2. **`Strategyn_JTBD_Playbook.pdf`** — giảng viên gửi kèm

### Cách dùng playbook cho đúng

Bạn **không cần đọc hết 48 trang**.  
Trong bài này, playbook chủ yếu dùng để tra 4 thứ:

1. **Cách nhìn thị trường qua JTBD lens**
2. **`Job executor` là ai**
3. **Cách viết `job statement`: `verb + object + contextual clarifier`**
4. **8 bước của `job map`**:
   `define -> locate -> prepare -> confirm -> execute -> monitor -> modify -> conclude`

### 2 chương nên mở nhiều nhất

- **Chapter 2 — Define Your Market**
- **Chapter 3 — Build Your Job Map**

> Dùng playbook để **tra framework và ví dụ**.  
> Dùng file này để **làm bài và chốt output**.

---

## Đầu ra bắt buộc

Người chấm cần thấy đủ 6 phần trong chính file này:

1. **`Project slice` + market context**
2. **`Job executor` + `core JTBD`**
3. **3 `job stories`**
4. **`JTBD lite map` + pain points**
5. **`AI leverage point` + `product hypothesis`**
6. **`Assumptions to validate` + verdict cuối sau thảo luận**

Nếu thiếu một trong sáu phần trên, bài sẽ bị xem là chưa hoàn chỉnh.

---

## Cách làm trong lớp (25 phút)

```text
3'  Chốt 1 lát cắt cụ thể của dự án
7'  Viết market context + job executor + core JTBD
6'  Viết 3 job stories + current alternatives
6'  Điền JTBD lite map + AI leverage point + hypothesis
3'  Share trong bàn và sửa version cuối
```

> Nếu dự án làm theo nhóm, cả nhóm có thể thảo luận chung.  
> Nhưng file này vẫn nên có **version chốt rõ ràng** của người nộp.

---

## Bước 0 — Khoanh đúng 1 lát cắt của dự án

Phần lớn dự án nhóm viết quá rộng ở bước này, rồi sau đó mọi thứ mơ hồ theo.

### Khoanh đúng 1 lát cắt theo 4 điểm

- [ ] **1 nhóm người dùng chính**
- [ ] **1 hoàn cảnh / tình huống rõ**
- [ ] **1 job cốt lõi**
- [ ] **1 workflow đủ cụ thể để vẽ ra được**

### Điền nhanh trước khi làm

- **Dự án của nhóm tôi là:** AI Gia sư cá nhân hóa cho học sinh phổ thông (K-12 Personalized AI Tutor)
- **Lát cắt tôi chọn để phân tích hôm nay là:** Giúp học sinh trung học phổ thông (lớp 10-12) tự ôn tập, hiểu bản chất và giải quyết các bài tập Toán khó tại nhà vào buổi tối khi không có giáo viên hoặc gia sư hỗ trợ trực tiếp.
- **Vì sao tôi chọn lát cắt này:**  
  > Toán là môn học bắt buộc có độ phức tạp cao, học sinh thường gặp bế tắc khi tự làm bài tập về nhà vào buổi tối muộn. Việc thuê gia sư kèm cặp 1-1 rất tốn kém (150k-300k/buổi) và không thể hỗ trợ tức thì 24/7. Lát cắt này giải quyết đúng "điểm mù" hỗ trợ học tập lúc đêm muộn, giúp học sinh chủ động học tập và giảm bớt gánh nặng tài chính cho gia đình.

### Viết quá rộng vs viết sắc hơn

| Viết quá rộng | Viết sắc hơn |
|---|---|
| Giúp SME dùng AI để marketing | Giúp chủ shop online phản hồi câu hỏi trước mua hàng nhanh và nhất quán trong giờ cao điểm |
| Dùng AI để làm slide | Tạo bản nháp deck nội bộ mạch lạc cho buổi họp gấp trong thời gian rất ngắn |
| AI cho tuyển dụng | Giúp recruiter sàng lọc CV đầu vào nhanh hơn trước vòng gọi sơ bộ |

> Nếu bạn không mô tả được **một hoàn cảnh cụ thể**, khả năng cao bạn đang viết quá rộng.

---

## Bước 1 — Viết `Project Snapshot`

### Tóm tắt dự án trong 3 dòng

1. **Nhóm tôi đang nghĩ mình đang giải quyết vấn đề gì?**  
   > Học sinh phổ thông bị hổng kiến thức toán hoặc gặp bế tắc khi giải các bài tập nâng cao tại nhà mà không có ai giải thích, dẫn đến mất động lực học tập, sợ môn Toán và có xu hướng lạm dụng việc chép lời giải từ các app giải bài tập trực tuyến mà không hiểu bản chất.

2. **Người dùng chính hiện nhóm đang nhắm tới là ai?**  
   > Học sinh trung học phổ thông (THPT) từ 15-18 tuổi (lớp 10, 11, 12) có nhu cầu tự học và cải thiện điểm số môn Toán nhưng không có điều kiện thuê gia sư riêng.

3. **Hiện tại người dùng đó đang giải quyết vấn đề này bằng cách nào?**  
   > Tra cứu đáp án và chép lời giải sẵn trên các trang web (Loigiaihay, VietJack), dùng app chụp ảnh giải bài (Solvee, QANDA) để lấy lời giải nhanh, hỏi bài trên các group Facebook/Zalo/Discord hoặc đợi đến buổi học thêm với gia sư/giáo viên.

---

## Bước 2 — Viết `Market Context`

Ở đây chưa cần solution. Chỉ cần bối cảnh thị trường đủ để hiểu:
**ai đang gặp chuyện gì, trong hoàn cảnh nào, và vì sao bây giờ đáng giải.**

### Trả lời 4 câu ngắn

1. **Ai đang gặp vấn đề này?**  
   > Học sinh cấp 3 đang chịu áp lực học tập và thi cử (đặc biệt là thi THPT Quốc gia), và phụ huynh của các em - những người lo lắng về kết quả học tập của con nhưng bị giới hạn về thời gian hoặc năng lực học thuật để tự kèm con học.

2. **Vấn đề xuất hiện trong hoàn cảnh nào?**  
   > Khi học sinh tự học hoặc làm bài tập về nhà tại nhà vào buổi tối (thường từ 20h - 23h), chuẩn bị bài cho ngày hôm sau hoặc chuẩn bị cho các kỳ thi định kỳ, gặp những câu hỏi khó vượt quá khả năng tự giải quyết.

3. **Hiện tại họ đang dùng giải pháp thay thế nào?**  
   > Thuê gia sư truyền thống dạy kèm tại nhà (giới hạn giờ giấc, chi phí cao), sử dụng các trang web giải bài tập tĩnh (chỉ cung cấp lời giải có sẵn, dễ gây lười suy nghĩ), hoặc tự mò mẫm trên mạng xã hội hỏi bài (phản hồi chậm, không kiểm chứng được tính đúng đắn).

4. **Vì sao đây là thời điểm đáng giải?**  
   > Sự phát triển vượt bậc của LLMs đa phương thức (Multimodal AI) có khả năng đọc hiểu đề bài qua hình ảnh, phân tích chữ viết tay nháp và lập luận toán học từng bước (step-by-step reasoning). Đồng thời, thị trường EdTech Việt Nam đang bùng nổ, phụ huynh rất cởi mở đầu tư cho các sản phẩm công nghệ giáo dục chất lượng cao để tiết kiệm chi phí học thêm.

### Tóm tắt market context trong 3-4 dòng

> Học sinh THPT khi tự học Toán tại nhà buổi tối thường rơi vào trạng thái bế tắc trước các bài tập khó mà không có sự trợ giúp kịp thời. Các giải pháp thay thế hiện tại hoặc quá đắt đỏ và không sẵn sàng 24/7 (gia sư), hoặc quá thụ động và dễ gây thói quen chép bài đối phó (trang web giải sẵn). Đây là thời điểm vàng để giải quyết vấn đề nhờ sự hỗ trợ của AI thị giác và các mô hình ngôn ngữ lớn có khả năng lập luận toán học theo phương pháp gợi bước.

---

## Bước 3 — Xác định `Job Executor`

`Job executor` là người **trực tiếp dùng một giải pháp để hoàn thành job**.

### Đừng nhầm với:

- người mua tiền nhưng không trực tiếp làm job
- người ảnh hưởng quyết định
- cả một công ty hay một phòng ban quá rộng

### Gợi ý viết cho đúng

- Sai hoặc quá rộng: `SME`, `doanh nghiệp`, `thị trường`
- Tốt hơn: `chủ shop online`, `nhân viên CSKH`, `recruiter`, `sales ops manager`

### Điền

- **Job executor của dự án này là:** Học sinh trung học phổ thông (lớp 10-12) tự học môn Toán tại nhà.
- **Vì sao tôi tin đây là người trực tiếp "thuê" giải pháp để làm job:**  
  > Mặc dù phụ huynh là người chi trả (Buyer), nhưng học sinh mới là người trực tiếp đối mặt với bài tập về nhà khó, trực tiếp chịu áp lực điểm số, và là người trực tiếp thao tác chụp hình đề bài, đọc lời giải thích và tương tác với AI để giải quyết sự bế tắc của mình lúc đêm muộn.

---

## Bước 4 — Viết `Core JTBD`

`Core JTBD` là công việc cốt lõi người dùng đang cố hoàn thành.

### Công thức gợi ý

```text
[verb] + [object] + [contextual clarifier]
```

### Ví dụ

- Chưa tốt: `trả lời inbox bằng AI`
- Tốt hơn: `giải quyết câu hỏi trước mua hàng nhanh và chính xác trong giờ cao điểm`

- Chưa tốt: `dùng AI để viết nội dung`
- Tốt hơn: `tạo bản nháp nội dung chiến dịch phù hợp với brand trong thời gian rất ngắn`

### 3 tiêu chí tự kiểm

- [ ] Nếu bỏ tool hiện tại đi, job này vẫn còn tồn tại
- [ ] Trong câu không có tên sản phẩm, AI, chatbot, app, màn hình
- [ ] Câu đang mô tả **điều user muốn hoàn thành**, không phải thứ product đang làm

### Bản nháp 1

**Core JTBD bản nháp:**  
> Dùng ứng dụng AI gia sư cá nhân hóa để chụp ảnh đề bài và được giải thích cách làm bài tập toán tại nhà.

### Gạch bỏ từ solution nếu có

- Các từ solution tôi đang lỡ nhét vào câu: ứng dụng AI gia sư cá nhân hóa, chụp ảnh đề bài, app

### Bản chốt

**Core JTBD cuối cùng:**  
> Hiểu bản chất cách giải các dạng bài tập Toán khó tại nhà để tự tin hoàn thành bài tập về nhà và đạt kết quả cao trong các kỳ thi môn Toán mà không phụ thuộc vào sự hỗ trợ trực tiếp của giáo viên hoặc gia sư.

---

## Bước 5 — Viết 3 `Job Stories`

Nếu `core JTBD` là job ở mức cốt lõi, thì `job story` giúp bạn thấy
**job này xuất hiện trong hoàn cảnh nào**.

### Format

```text
When [trigger], I want to [motivation], so I can [outcome].
```

### Ví dụ

`When inbox đổ dồn vào buổi tối, tôi muốn có câu trả lời nhất quán ngay lập tức, so I can không mất đơn vì phản hồi chậm.`

### Bảng 3 job stories

| # | Trigger / When | Motivation / I want to | Outcome / so I can | Điều story này cho thấy |
|---|---|---|---|---|
| JS1 | Khi tôi đang làm bài tập về nhà môn Toán lúc 10h30 đêm và bị tắc ở một câu tích phân khó | Có một người hướng dẫn gợi ý tư duy giải quyết từng bước ngay lập tức | Tự mình suy luận giải ra bài toán đó thay vì chép đáp án đối phó, và hiểu cách làm để giải các bài tương tự | Nhu cầu hỗ trợ tức thì (24/7) và tính định hướng gợi mở (không giải hộ hoàn toàn) để phát triển tư duy tự lập. |
| JS2 | Khi kỳ thi học kỳ đang đến gần và kết quả thi thử cho thấy tôi bị hổng kiến thức phần Hình học không gian | Nhanh chóng định vị chính xác những phần lý thuyết cốt lõi bị mất gốc và làm bài tập thực hành trọng tâm | Lấp đầy lỗ hổng kiến thức một cách nhanh nhất mà không cần đọc lại toàn bộ sách giáo khoa | Nhu cầu chẩn đoán lỗ hổng kiến thức cá nhân hóa và học tập có mục tiêu, tiết kiệm thời gian ôn thi. |
| JS3 | Khi tôi nhận được một bài kiểm tra Toán bị điểm kém và có nhiều lỗi sai ngu ngơ do nhầm lẫn | Quét bài làm cũ để chỉ ra chính xác dòng nào tính sai và giải thích tại sao sai | Tránh lặp lại lỗi sai tương tự trong bài kiểm tra chính thức sắp tới | Nhu cầu phản hồi và sửa lỗi sai (feedback loop) trực tiếp trên bài làm nháp của chính mình để rút kinh nghiệm sâu sắc. |

### Tự kiểm nhanh

- [ ] Mỗi story là một **tình huống thật**, không phải slogan chung chung
- [ ] 3 story không trùng hệt nhau
- [ ] Sau khi đọc 3 story, tôi hình dung được lúc nào product của mình đáng xuất hiện

---

## Bước 6 — Liệt kê `Current Alternatives`

Qua JTBD lens, đối thủ không chỉ là app cùng ngành.
Đối thủ là **bất kỳ thứ gì user đang "thuê" để làm job**:

- thao tác tay
- file Excel / Google Sheets
- intern / nhân viên
- agency
- ChatGPT / Claude / Gemini
- công cụ chuyên dụng khác
- hoặc thậm chí là **không làm gì cả**

### Bảng alternatives

| Alternative hiện tại | User đang thuê nó để làm gì? | Nó làm tốt gì? | Nó fail ở đâu? | Switching cost hiện tại cao hay thấp? |
|---|---|---|---|---|
| Sách giải và các trang web giải bài tập tĩnh (VietJack, Loigiaihay, Solvee...) | Tra cứu nhanh đáp án và lời giải chi tiết của các bài tập trong sách giáo khoa, sách bài tập. | Rất nhanh, hoàn toàn miễn phí hoặc cực rẻ; bao phủ hầu hết các bài tập cơ bản trong hệ thống SGK. | Chỉ có một lời giải cố định, học sinh không hiểu vì sao có bước biến đổi đó; học sinh lạm dụng chép bài đối phó; không giải được các đề tự biên soạn mới. | Thấp. Học sinh dễ dàng chuyển đổi qua lại giữa các trang web hoặc ứng dụng giải bài chỉ bằng vài lượt tìm kiếm Google. |
| Gia sư truyền thống dạy kèm 1-1 tại nhà (Sinh viên, giáo viên) | Kèm cặp học, giải thích bài tập khó, giám sát quá trình tự học và củng cố kiến thức mất gốc. | Cá nhân hóa cao theo học lực; giải thích chi tiết, tương tác trực tiếp bằng cảm xúc và động viên tinh thần của học sinh. | Chi phí rất cao (1,5 triệu - 3 triệu/tháng); giới hạn thời gian (chỉ gặp 1-2 buổi/tuần), không hỗ trợ được ngay khi học sinh bị tắc lúc đêm muộn. | Cao. Liên quan đến việc tìm kiếm người phù hợp qua trung tâm, sắp xếp lịch học cố định, cam kết tài chính dài hạn theo tháng. |
| Tự hỏi bài trên các hội nhóm trực tuyến (Facebook, Zalo, Discord, Forum) | Đăng hình ảnh đề bài khó lên nhóm để nhờ những người giỏi hơn giải giúp. | Miễn phí; nhận được nhiều cách giải khác nhau từ bạn bè đồng lứa hoặc cộng đồng học sinh giỏi. | Thời gian phản hồi rất chậm (có khi vài tiếng hoặc không có ai trả lời); độ chính xác không được kiểm chứng; học sinh dễ bị xao nhãng bởi mạng xã hội. | Thấp. Chỉ cần tham gia nhóm và đăng bài tự do, không có cam kết hay chi phí ràng buộc. |

### Kết luận nhanh

**Nếu project của tôi biến mất hôm nay, user nhiều khả năng sẽ quay về:**  
> Kết hợp giữa việc chép lời giải nhanh từ các trang web giải bài tập tĩnh (Loigiaihay/Vietjack) để nộp bài tập đối phó trên lớp, và chờ đợi đến buổi học thêm với gia sư truyền thống để hỏi các câu thực sự không hiểu nếu gia đình có điều kiện tài chính.

---

## Bước 7 — Điền `JTBD Lite Map`

Đây là bản rút gọn của `job map` trong playbook.

### Mục tiêu

Không phải để làm consultant workshop hoàn chỉnh.  
Mục tiêu là nhìn ra:

1. workflow hiện tại của user đi qua những bước nào
2. bước nào đang đau nhất
3. AI có nên chen vào đó không

### 8 bước tham chiếu từ playbook

1. `Define`
2. `Locate`
3. `Prepare`
4. `Confirm`
5. `Execute`
6. `Monitor`
7. `Modify`
8. `Conclude`

> Không nhất thiết bước nào cũng quan trọng như nhau trong dự án của bạn.  
> Nếu ít liên quan, ghi `N/A`, đừng để trống.

### Bảng JTBD Lite Map

| Step | Trong workflow này user đang cố làm gì? | Hôm nay họ đang dùng gì? | Friction / pain hiện tại | Mức đau |
|---|---|---|---|---|
| Define | Xác định mục tiêu học tập (hôm nay làm bài tập gì, ôn thi chương nào, phần nào đang yếu nhất). | Thời khóa biểu, sổ liên lạc điện tử, ghi chú trên lớp của giáo viên. | Không tự đánh giá được chính xác bản thân đang hổng kiến thức ở đâu, học dàn trải không trọng tâm. | Med |
| Locate | Tìm kiếm công thức, lý thuyết toán học liên quan đến chủ đề bài tập hôm nay. | Sách giáo khoa, sách tham khảo, Google, Youtube. | Tài liệu phân tán, mất nhiều thời gian tra cứu công thức, dễ gặp phải bài giải quá nâng cao hoặc không sát chương trình. | Med |
| Prepare | Đọc hiểu đề bài, tóm tắt dữ kiện và vẽ hình (nếu có), chuẩn bị giấy nháp và máy tính Casio. | Sách bài tập, giấy nháp, máy tính cầm tay Casio. | Học sinh bị "ngợp" trước các đề toán dài hoặc nhiều ký hiệu lạ, không biết bắt đầu phân tích đề từ đâu. | High |
| Confirm | Xác định hướng đi/phương pháp giải đúng trước khi viết lời giải chi tiết (ví dụ: đặt ẩn phụ hay biến đổi tương đương). | Đoán mò, so sánh với dạng bài tương tự trong sách giải mẫu. | Không có ai xác nhận hướng đi đúng hay sai, lo sợ giải sai mất thời gian nên thường chọn chép bài luôn. | High |
| Execute | Thực hiện tính toán chi tiết và các phép biến đổi toán học để ra kết quả cuối cùng. | Bút, giấy nháp, máy tính cầm tay. | Dễ sai sót tính toán cơ bản (nhầm dấu, cộng trừ sai); bị tắc ở các bước biến đổi trung gian mà không biết đi tiếp thế nào. | Med |
| Monitor | Kiểm tra logic bài làm từng bước để phát hiện sai sót trước khi ra đáp số. | Tự xem lại bài giải từ đầu hoặc so sánh kết quả cuối cùng với bạn bè/sách giải. | Chỉ biết đúng/sai ở kết quả cuối; nếu sai kết quả thì cực kỳ khó tự phát hiện ra mình sai từ dòng nào trong trang nháp. | High |
| Modify | Điều chỉnh cách giải khi phát hiện tính sai hoặc hướng đi bị bế tắc giữa chừng. | Gạch đi làm lại, xóa nháp và thử phương pháp giải khác một cách mù quáng. | Thiếu kiến thức nền tảng để tìm ra phương pháp giải thay thế; cảm thấy nản lòng và dễ bỏ cuộc. | High |
| Conclude | Đối chiếu đáp án cuối, ghi nhớ phương pháp giải của dạng toán đó để lần sau áp dụng. | Vở ghi bài tập, chép đáp số vào vở nộp. | Thường chỉ chép lại đáp án đối phó mà không đúc kết được phương pháp giải tổng quát, gặp bài tương tự vẫn tắc. | High |

### Chốt 2 bước đau nhất

**Bước đau nhất #1:** **Confirm (Xác nhận hướng giải)**  
**Bước đau nhất #2:** **Monitor & Modify (Kiểm soát tiến trình giải và sửa sai)**

**Vì sao đây là nơi đáng chú ý nhất:**  
> Đây là hai thời điểm học sinh dễ nản lòng nhất khi tự học Toán tại nhà. Khi bắt đầu bài toán mà không có hướng đi chắc chắn (Confirm), các em dễ sinh tâm lý sợ hãi và chọn cách mở sách giải chép luôn. Khi đang giải giữa chừng bị tắc hoặc ra sai đáp số (Monitor & Modify), các em không biết sai ở đâu để sửa, dẫn đến lãng phí thời gian và nản chí. Nếu AI giải quyết tốt 2 bước này, học sinh sẽ chuyển từ việc học vẹt chép bài sang học hiểu chủ động.

---

## Bước 8 — Chỉ ra `AI Leverage Point`

Sau khi map workflow, mới hỏi:
**AI nên vào đâu, với vai trò gì, và vì sao là ở đó?**

### Nhắc nhanh

- Đừng nhét AI vào chỉ vì "có AI thì nghe hay"
- Nếu pain lớn nhất không nằm ở chỗ AI giải tốt, hãy thành thật ghi ra
- Nếu current alternative đã đủ tốt, project cần xem lại

### Bảng leverage point

| Step | AI nên giúp bằng cách nào? | Vì sao AI hợp ở đây? | Rủi ro chính nếu dùng AI |
|---|---|---|---|
| Step 4: Confirm (Xác nhận hướng đi) | AI đóng vai trò gia sư gợi mở (Socratic Tutor): Khi học sinh chụp ảnh đề bài, thay vì giải hộ, AI tóm tắt đề bài, nhắc lại 1-2 công thức liên quan và đưa ra câu hỏi gợi ý hướng đi (ví dụ: "Em thử đặt ẩn phụ $t = \sqrt{x+1}$ xem sao?"). | AI có khả năng nhận diện hình ảnh đề toán (OCR) tốt và lập luận logic để đưa ra gợi ý phù hợp với trình độ học sinh mà không cần giải trực tiếp, kích thích tư duy tự lập. | AI có thể đưa ra gợi ý quá nâng cao ngoài chương trình học của học sinh, hoặc giải thích mơ hồ khiến học sinh khó hiểu hơn. |
| Step 6 & 7: Monitor & Modify (Kiểm lỗi & Sửa sai bài giải nháp) | AI quét hình ảnh bài làm nháp viết tay của học sinh, phân tích logic từng dòng và khoanh tròn dòng bị lỗi (ví dụ: "Em làm đúng đến dòng 3, nhưng dòng 4 bị sai dấu khi chuyển vế"). AI gợi ý hướng sửa đổi thay vì viết hộ bài giải mới. | Các mô hình Vision-LLM hiện nay có khả năng đọc hiểu chữ viết tay nháp tốt và phân tích logic toán học từng dòng cực kỳ chính xác hệt như một gia sư ngồi kèm bên cạnh. | Ảo giác logic (hallucination) của AI: AI có thể đánh giá sai một lời giải đúng nhưng lạ của học sinh, hoặc phê duyệt một lời giải sai logic khiến học sinh bị lệch kiến thức. |

### Kết luận nhanh

**AI leverage point quan trọng nhất của dự án tôi là:**  
> Trở thành một **"Socratic Gia Sư AI"** hỗ trợ tương tác 24/7 qua camera chụp ảnh, tập trung vào việc định hình hướng giải (Confirm) và chẩn đoán, sửa lỗi sai trực tiếp trên bài làm nháp của học sinh (Error Analysis) theo phương pháp gợi mở từng bước thay vì cung cấp lời giải toàn bộ từ A-Z.

**Vì sao không phải ở bước khác:**  
> Nếu AI nhảy vào bước *Execute* để giải hộ toàn bộ bài toán từ đầu đến cuối, sản phẩm sẽ ngay lập tức bị biến thành công cụ chép bài tập đối phó (như các app giải bài toán tĩnh hiện nay). Điều này không tạo ra giá trị giáo dục thực sự, khiến học sinh ngày càng lười tư duy và chắc chắn sẽ bị phụ huynh cũng như giáo viên tẩy chay.

---

## Bước 9 — Viết `Product Hypothesis`

Bây giờ mới đến lúc viết hypothesis.

### Công thức gợi ý

```text
Nếu chúng ta giúp [job executor] làm [job / sub-job] tốt hơn ở bước [x],
bằng cách [AI leverage],
thì họ sẽ chuyển từ [current alternative] sang [hướng giải pháp của nhóm],
vì [giá trị rõ nhất].
```

### Bản hypothesis của tôi

> Nếu chúng ta giúp **học sinh trung học phổ thông (lớp 10-12)** làm **việc vượt qua bế tắc khi giải các bài tập Toán khó tại nhà** tốt hơn ở bước **định hình hướng giải (Confirm) và sửa lỗi sai trong bài làm nháp (Monitor & Modify)**, bằng cách **tích hợp một AI Gia sư gợi mở (Socratic AI) nhận diện qua ảnh chụp bài nháp để kiểm lỗi và đưa ra các gợi ý tư duy từng bước**, thì họ sẽ chuyển từ **việc chép lời giải thụ động trên các trang web giải sẵn hoặc chờ đợi gia sư truyền thống** sang **sử dụng ứng dụng Gia sư AI cá nhân hóa hằng ngày tại nhà**, vì **họ được hỗ trợ tức thì 24/7 giải quyết bế tắc đúng lúc, thực sự hiểu bản chất bài học để tự làm được bài với chi phí tối ưu hơn nhiều so với gia sư truyền thống.**

### Tín hiệu sớm nếu hypothesis này đúng

1. **Tỷ lệ hoàn thành bài tập tự lực (Self-completion rate):** Học sinh tiếp tục tự viết lời giải và đưa ra đáp án đúng sau khi nhận các gợi ý gợi mở của AI, thay vì bấm nút yêu cầu "Xem toàn bộ đáp án giải sẵn".
2. **Tỷ lệ tương tác sâu (Deep engagement metric):** Lượng ảnh chụp bài giải nháp viết tay tải lên ứng dụng vào khung giờ tối (20h - 23h) tăng trưởng đều đặn, cho thấy học sinh thực sự dùng app để rà soát lỗi sai tư duy chứ không chỉ dùng để quét đề bài lấy đáp số.

---

## Bước 10 — Liệt kê `Assumptions to Validate`

Job story chưa có research vẫn chỉ là **giả thuyết tốt hơn**, chưa phải sự thật.

### 5 assumption thường đáng kiểm

- Tôi đã chọn đúng `job executor`
- Pain này thật sự đủ đau và xảy ra đủ thường xuyên
- User sẽ đổi khỏi alternative hiện tại nếu có giải pháp tốt hơn
- AI thực sự tạo giá trị ở step tôi chọn
- User đủ tin kết quả AI để đưa vào workflow thật

### Bảng assumptions

| Assumption | Vì sao assumption này rủi ro? | Tôi đang có bằng chứng gì? | Cần validate bằng cách nào tiếp theo? |
|---|---|---|---|
| A1: Học sinh thực sự muốn hiểu bài để tự làm, chứ không chỉ muốn chép đáp án nhanh để đối phó nộp bài. | Nếu học sinh chỉ muốn chép bài đối phó, họ sẽ ghét tính năng "gợi ý tư duy" và quay lại sử dụng các app giải bài nhanh hoặc sách giải tĩnh. | Khảo sát nhanh nhóm học sinh học lực Khá-Giỏi cho thấy các em có nhu cầu hiểu cách làm để tự ôn thi đại học, nhưng nhóm Trung bình-Yếu có xu hướng muốn chép đáp án nhanh hơn. | Triển khai thử nghiệm A/B Testing trên một nhóm nhỏ user: Nhóm A nhận đáp án giải ngay, Nhóm B nhận gợi ý từng bước (Socratic). Đo lường tỷ lệ giữ chân (Retention Rate) và thời gian học tập thực tế của cả hai nhóm. |
| A2: AI có thể nhận diện chính xác nét chữ viết tay nháp của học sinh cấp 3 Việt Nam và chỉ ra đúng lỗi logic toán học mà không bị ảo giác. | Toán học yêu cầu độ chính xác 100%. Nếu AI chấm sai lời giải đúng hoặc khen một bài giải sai logic là đúng, học sinh sẽ mất hoàn toàn niềm tin và từ bỏ app. | Các LLM hàng đầu như GPT-4o, Claude 3.5 Sonnet giải toán rất tốt nhưng kỹ năng OCR chữ viết tay Tiếng Việt nghuệch ngoạc trên giấy nháp vẫn thường xuyên bị lỗi. | Xây dựng bộ dataset test gồm 200 ảnh chụp bài nháp thực tế của học sinh cấp 3 với các nét chữ viết tay và các lỗi sai toán học phổ biến. Chạy test và tối ưu Prompt/RAG cho đến khi đạt độ chính xác >95%. |
| A3: Phụ huynh sẵn sàng chi trả thuê bao tháng (subscription) cho app AI tự học của con thay vì nghĩ con dùng điện thoại để chơi game. | Phụ huynh là người trả tiền (Buyer). Nếu họ không tin tưởng phương pháp học qua màn hình điện thoại hoặc nghi ngờ hiệu quả của AI, mô hình doanh thu subscription sẽ sụp đổ. | Xu hướng chi tiêu cho EdTech tại Việt Nam tăng mạnh. Nhiều phụ huynh đã quen trả tiền cho các ứng dụng tiếng Anh (Elsa, Monkey Junior) hoặc khóa học trực tuyến. | Tiến hành phỏng vấn sâu (User Interview) với 20 phụ huynh học sinh cấp 3 để tìm hiểu mức độ sẵn sàng chi trả (Willingness to Pay) và các tính năng kiểm soát/báo cáo kết quả mà họ yêu cầu để tin tưởng app. |
| A4: Cách giải và hướng dẫn của AI tương thích hoàn toàn với chương trình học và barem chấm điểm của Bộ Giáo dục & Đào tạo Việt Nam. | Nếu AI hướng dẫn theo phương pháp quá nâng cao hoặc lạ (kiến thức đại học), giáo viên trên lớp sẽ không chấp nhận bài làm đó và học sinh sẽ không dùng app nữa. | LLM mặc định thường giải toán theo phương thức chung toàn cầu hoặc dùng các công cụ lập trình (Python) để giải quyết, đôi khi không giống phương pháp giảng dạy trong SGK Việt Nam. | Thực hiện kỹ thuật RAG (Retrieval-Augmented Generation) kết hợp đưa sách giáo khoa, sách giáo viên Toán cấp 3 và barem đề thi THPT Quốc gia làm tài liệu tham khảo cho AI khi tạo câu trả lời. |
| A5: Học sinh duy trì thói quen học tập với app AI hằng ngày lâu dài, thay vì chỉ hào hứng dùng thử vài ngày đầu rồi bỏ. | Nếu tỷ lệ quay lại thấp (Low retention), chi phí thu hút người dùng mới (CAC) sẽ vượt quá giá trị vòng đời khách hàng (LTV), khiến dự án không thể duy trì tài chính. | Chưa có dữ liệu thực tế cho app gia sư toán AI gợi mở tại Việt Nam. Các ứng dụng giải bài tập khác có lượng traffic lớn nhưng tỷ lệ active sâu thường thấp. | Phát triển phiên bản MVP cực nhanh tập trung vào đúng tính năng "quét bài nháp kiểm lỗi sai" và đo lường chỉ số Cohort Retention sau 7 ngày, 14 ngày, 30 ngày của nhóm người dùng thử nghiệm. |

### Assumption nguy hiểm nhất nếu tôi đang sai

> **Assumption A1 (Học sinh thực sự muốn hiểu bài để tự học chứ không phải chỉ muốn chép đáp án đối phó)** và **Assumption A2 (Độ chính xác của AI khi đọc chữ viết tay và chấm điểm logic toán học)**. Nếu học sinh chỉ muốn chép bài đối phó, hoặc nếu công nghệ AI chưa đủ chín muồi để đọc hiểu chữ nháp viết tay một cách chính xác tuyệt đối, sản phẩm sẽ ngay lập tức thất bại về cả mặt giá trị giáo dục lẫn lòng tin của người dùng.

---

## Bước 11 — Share trong bàn (3')

### Mỗi người / mỗi nhóm chỉ nói 4 thứ

1. **Job executor của bạn là ai**
2. **Core JTBD của bạn là gì**
3. **Step đau nhất đang nằm ở đâu**
4. **AI leverage point + assumption rủi ro nhất là gì**

### Nếu chưa biết hỏi ngược gì, dùng 4 câu này

1. **"Câu JTBD này có đang lỡ nhét solution vào không?"**
2. **"Alternative hiện tại của user là gì, và tại sao họ chưa bỏ nó?"**
3. **"Pain mạnh nhất nằm ở bước nào trong workflow, có chắc AI giải tốt được không?"**
4. **"Assumption nào nếu sai thì cả hypothesis sẽ sập?"**

### Ghi nhanh sau khi nghe bàn phản biện

| Ý phản biện tôi nghe được | Nó chạm vào phần nào? | Tôi sẽ giữ / sửa gì? |
|---|---|---|
| "Học sinh THPT có rất nhiều học lực khác nhau. Học sinh trung bình-yếu sẽ cảm thấy nản và bỏ app nếu app cứ bắt các em tự giải qua gợi ý mà không cho đáp án luôn." | Bước 8 (AI Leverage Point) và Assumption A1 | **Sửa nhẹ:** Thiết kế cơ chế "bảo hiểm" - nếu sau 3 lần gợi ý gợi mở học sinh vẫn bị tắc, app sẽ cho phép xem lời giải chi tiết nhưng kèm theo yêu cầu làm một bài tập tương tự ngay sau đó để kiểm tra mức độ hiểu bài. |
| "Năng lực giải toán của AI đôi khi có lỗi logic rất tinh vi. Làm sao để học sinh phát hiện ra nếu AI giải sai?" | Assumption A2 & Rủi ro dùng AI | **Giữ nguyên nhưng bổ sung giải pháp:** Đưa thêm nút "Báo cáo lỗi sai" hoặc "Yêu cầu gia sư con người trợ giúp" đối với các bài toán cực kỳ phức tạp để đảm bảo độ tin cậy của app. |
| "Phụ huynh là người trả tiền nhưng họ rất sợ con dùng điện thoại để chơi game lúc đêm muộn. Làm thế nào để họ tin tưởng?" | Assumption A3 | **Sửa nhẹ Product Hypothesis:** Bổ sung thêm giá trị cho phụ huynh bằng cách thiết lập tính năng gửi báo cáo tiến độ học tập tự động (Daily Study Report) qua Zalo/Email cho phụ huynh để họ thấy con mình thực sự học tập. |

---

## Bước 12 — Chốt version cuối sau thảo luận

### Sau khi nghe phản biện, tôi thay đổi gì?

- [x] Giữ nguyên `job executor`
- [ ] Sửa `job executor`
- [ ] Giữ nguyên `core JTBD`
- [x] Sửa `core JTBD`
- [ ] Giữ nguyên `AI leverage point`
- [x] Sửa `AI leverage point`
- [ ] Giữ nguyên `product hypothesis`
- [x] Sửa `product hypothesis`

### Vì sao tôi giữ / sửa?

> - **Sửa `core JTBD`:** Cụ thể hóa hơn mục tiêu học tập theo hướng giúp học sinh củng cố lỗ hổng kiến thức chủ động thay vì chỉ hoàn thành bài tập về nhà.
> - **Sửa `AI leverage point`:** Bổ sung cơ chế hybrid - cung cấp giải pháp toàn diện kèm bài tập tương ứng nếu học sinh thực sự bế tắc sau vài lượt gợi ý, tránh việc học sinh bỏ app vì nản lòng.
> - **Sửa `product hypothesis`:** Đưa thêm yếu tố báo cáo tiến độ cho phụ huynh để giải quyết triệt để rào cản chi trả của Buyer (phụ huynh).

### Version cuối cùng tôi nộp

**Job executor:**  
> Học sinh trung học phổ thông (lớp 10-12) tự học môn Toán tại nhà.

**Core JTBD:**  
> Hiểu bản chất cách giải các bài tập Toán khó tại nhà để tự củng cố lỗ hổng kiến thức, tự lực hoàn thành bài tập về nhà và đạt điểm số tốt trong các kỳ thi mà không phụ thuộc vào sự hỗ trợ trực tiếp 24/7 của gia sư hay giáo viên.

**2 bước đau nhất trong workflow:**  
> 1. **Confirm (Xác nhận hướng giải quyết đề bài)**  
> 2. **Monitor & Modify (Kiểm soát tiến trình giải và phát hiện, sửa lỗi sai trong bài nháp)**

**AI leverage point chính:**  
> 1. **Socratic AI Prompting:** Gợi mở tư duy hướng giải quyết thông qua ảnh chụp đề bài, nhắc công thức liên quan mà không giải hộ trực tiếp.
> 2. **Handwritten Error Analysis:** Đọc hiểu ảnh chụp bài nháp tự giải viết tay của học sinh để chỉ ra chính xác dòng bị lỗi tính toán/logic và hướng dẫn sửa đổi.
> 3. **Smart Fallback:** Cung cấp lời giải chi tiết từng bước kèm bài kiểm tra tương tự nếu học sinh thực sự bế tắc sau nhiều lần gợi ý.

**Product hypothesis:**  
> Nếu chúng ta giúp **học sinh trung học phổ thông (lớp 10-12)** làm **việc tự học Toán tại nhà vượt qua bế tắc trước các bài tập khó** tốt hơn ở bước **định hình hướng giải và sửa lỗi sai trong bài nháp**, bằng cách **cung cấp một ứng dụng Gia sư AI gợi mở (Socratic AI) tương tác qua ảnh chụp bài nháp cùng tính năng báo cáo tiến độ tự động cho phụ huynh**, thì họ sẽ chuyển từ **việc chép bài đối phó trên các trang web giải sẵn hoặc chờ đợi gia sư truyền thống tuần 2 buổi** sang **sử dụng ứng dụng Gia sư AI cá nhân hóa hằng ngày tại nhà**, vì **họ giải quyết được bế tắc học tập tức thì 24/7, thực sự tiến bộ học tập rõ rệt để đạt điểm cao và phụ huynh hoàn toàn an tâm chi trả chi phí subscription cực kỳ hợp lý.**

**Assumption cần validate đầu tiên:**  
> **Học sinh thực sự muốn hiểu bài để tự làm (chủ động tự học)** thay vì chỉ muốn chép đáp số nhanh đối phó, và **AI đạt độ chính xác >95% khi đọc hiểu bài nháp viết tay tiếng Việt để chỉ ra lỗi sai toán học**.

---

## Checklist trước khi nộp

- [x] Tôi đã khoanh đúng 1 lát cắt cụ thể của dự án.
- [x] Tôi đã phân biệt được `job executor` với buyer / influencer.
- [x] `Core JTBD` của tôi không nhét solution vào câu.
- [x] Tôi đã viết đủ 3 `job stories`.
- [x] Tôi đã điền `JTBD lite map` và khoanh ra 2 bước đau nhất.
- [x] Tôi đã chỉ ra `AI leverage point` thay vì nhảy thẳng vào feature list.
- [x] Tôi đã ghi rõ `assumptions to validate`.
- [x] Tôi đã sửa version cuối sau khi share trong bàn.

---

## Nếu còn thời gian / làm về nhà

- Phỏng vấn nhanh 1 người dùng thật để kiểm xem `job story` nào là sát nhất.
- So sánh `current alternatives` với project của nhóm theo 3 tiêu chí: nhanh hơn, rẻ hơn, tin hơn.
- Tự hỏi lại một câu khó: **nếu không dùng AI, project này còn tạo giá trị không?**
- Nếu câu trả lời là "không", hãy xem lại liệu nhóm đang giải **job thật** hay chỉ đang tìm chỗ để nhét AI.

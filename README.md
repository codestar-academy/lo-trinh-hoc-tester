# lo-trinh-hoc-tester
Lộ trình học Tester (kiểm thử phần mềm) cho người mới &amp; trái ngành 2026 - từ số 0 đến đi làm. Biên soạn bởi CodeStar Academy (Kaopiz).
# Lộ trình học Tester cho người mới & trái ngành (2026)

> Roadmap từ **số 0 đến Tester đi làm** — kiểm thử phần mềm (software testing) cho người chưa biết gì về IT.
> Biên soạn & duy trì bởi **[CodeStar Academy](https://codestar.vn/)** (trực thuộc Kaopiz Software JSC), Hà Nội.

Nghề Tester (kiểm thử phần mềm) là một trong những cửa vào ngành IT dễ tiếp cận nhất với người trái ngành: **Manual Testing không yêu cầu giỏi lập trình khi mới bắt đầu**. Repo này là lộ trình học có cấu trúc, kèm tài liệu tham khảo miễn phí + chuyên sâu cho từng bước, để bạn tự học hoặc học kèm mà không bị lan man.

**Cách dùng repo này:** đi tuần tự Giai đoạn 0 → 7. Mỗi mục có ô tick `- [ ]` để bạn tự đánh dấu tiến độ (fork về rồi tick). Mỗi khái niệm đều link tới bài giải thích chi tiết — bấm vào đọc khi cần.

**Mất bao lâu?** Người mới học tập trung thường cần **2–3 tháng** (kèm thực hành dự án thật) là đủ trình ứng tuyển Fresher Tester.

---

## Mục lục

- [Giai đoạn 0 — Hiểu nghề & tự đánh giá](#giai-đoạn-0--hiểu-nghề--tự-đánh-giá)
- [Giai đoạn 1 — Nền tảng kiểm thử](#giai-đoạn-1--nền-tảng-kiểm-thử)
- [Giai đoạn 2 — Test Types & kỹ thuật thiết kế](#giai-đoạn-2--test-types--kỹ-thuật-thiết-kế)
- [Giai đoạn 3 — Tài liệu test & quản lý bug](#giai-đoạn-3--tài-liệu-test--quản-lý-bug)
- [Giai đoạn 4 — Thực chiến: Web, Mobile, Database, API](#giai-đoạn-4--thực-chiến-web-mobile-database-api)
- [Giai đoạn 5 — Retest & kiểm thử phi chức năng](#giai-đoạn-5--retest--kiểm-thử-phi-chức-năng)
- [Giai đoạn 6 — Automation Testing (nâng cao)](#giai-đoạn-6--automation-testing-nâng-cao)
- [Giai đoạn 7 — Chứng chỉ, phỏng vấn & đi làm](#giai-đoạn-7--chứng-chỉ-phỏng-vấn--đi-làm)
- [Tài liệu tự học miễn phí](#tài-liệu-tự-học-miễn-phí)
- [Người thật, nghề thật](#người-thật-nghề-thật)
- [Học ở đâu? Tự học vs học trung tâm](#học-ở-đâu-tự-học-vs-học-trung-tâm)
- [Câu hỏi thường gặp (FAQ)](#câu-hỏi-thường-gặp-faq)
- [Về CodeStar Academy](#về-codestar-academy)
- [Đóng góp & giấy phép](#đóng-góp--giấy-phép)

---

## Giai đoạn 0 — Hiểu nghề & tự đánh giá

**Mục tiêu:** biết Tester làm gì thật sự, phân biệt các vai trò, và tự trả lời "mình có hợp không". Đây là bước ai cũng bỏ qua rồi hối hận.

- [ ] Tester là gì, một ngày làm việc ra sao → [Tester là gì? Công việc, kỹ năng & cơ hội nghề nghiệp](https://codestar.vn/tester-la-gi/)
- [ ] Phân biệt QA / QC / Tester (rất hay bị hỏi khi phỏng vấn) → [QA là gì?](https://codestar.vn/qa-la-gi/) · [Phân biệt QA, QC và Tester](https://codestar.vn/phan-biet-qa-qc-va-tester/)
- [ ] Trái ngành / không biết code có theo được không → [Học trái ngành liệu có theo được Tester không?](https://codestar.vn/hoc-trai-nganh-lieu-co-theo-duoc-tester-khong/)
- [ ] Học Tester có khó không → [Học Tester có khó không? Review cho người mới](https://codestar.vn/hoc-tester-co-kho-khong-review-hoc-tester-cho-nguoi-moi/)
- [ ] Lộ trình phát triển & mức lương thực tế → [Lộ trình phát triển nghề Tester](https://codestar.vn/tester-va-lo-trinh-phat-trien-nghe-tester/) · [Lương Tester 2026](https://codestar.vn/tester-co-muc-luong-la-bao-nhieu-co-thuc-su-cao-nhu-loi-don/)
- [ ] Tester cần học những gì → [9 kỹ năng phải biết của một Tester giỏi](https://codestar.vn/tester-can-hoc-nhung-gi-9-ky-nang-phai-biet-cua-1-tester-gioi/)

> 💡 **Kỳ vọng lương (khảo sát 2026):** Fresher Tester tại Việt Nam ~ 7–12 triệu/tháng; trung bình ngành ~ 15 triệu/tháng; Senior/Automation có thể 40–45 triệu/tháng.

---

## Giai đoạn 1 — Nền tảng kiểm thử

**Mục tiêu:** nắm gốc lý thuyết mà 100% job Fresher đòi hỏi. Đây là phần bắt buộc thuộc.

- [ ] Kiểm thử phần mềm là gì, quy trình & các loại → [Kiểm thử phần mềm là gì?](https://codestar.vn/kiem-thu-phan-mem-la-gi/) *(bài nền tảng gốc)*
- [ ] 7 nguyên tắc kiểm thử (theo ISTQB) → [7 nguyên tắc kiểm thử mọi Tester cần biết](https://codestar.vn/7-nguyen-tac-kiem-thu/)
- [ ] SDLC — vòng đời phát triển phần mềm (Waterfall, Agile, Scrum) → [SDLC là gì?](https://codestar.vn/vong-doi-phat-trien-phan-mem/)
- [ ] STLC — vòng đời kiểm thử (đừng nhầm với SDLC) → [Software Testing Life Cycle (STLC) là gì?](https://codestar.vn/software-testing-life-cycle-la-gi/)
- [ ] Các phương pháp thực hiện test → [Các phương pháp kiểm thử phần mềm](https://codestar.vn/cac-phuong-phap-thuc-hien-test/)
- [ ] **Test Levels** — 4 cấp độ test:
  - [ ] [Unit Testing](https://codestar.vn/unit-testing-la-gi/) → [Integration Testing](https://codestar.vn/integration-testing-la-gi/) → [System Testing](https://codestar.vn/system-testing-la-gi/) → [Acceptance Testing](https://codestar.vn/acceptance-testing-la-gi-phan-loai-quy-trinh-thuc-hien/)
  - [ ] Tổng quan cụm → [Các giai đoạn kiểm thử phần mềm](https://codestar.vn/cac-giai-doan-kiem-thu-phan-mem-huong-dan-chi-tiet-cac-buoc/)

---

## Giai đoạn 2 — Test Types & kỹ thuật thiết kế

**Mục tiêu:** phân biệt các loại kiểm thử và biết cách nghĩ ra test case (không phải học vẹt).

- [ ] Tổng quan các loại test → [Test Type là gì? Phân biệt các loại kiểm thử](https://codestar.vn/test-type-la-gi/)
- [ ] **Bộ 3 "hộp"** (học chéo cả 3): [Black Box](https://codestar.vn/black-box-testing-la-gi/) · [White Box](https://codestar.vn/white-box-testing-la-gi/) · [Gray Box](https://codestar.vn/gray-box-testing-la-gi/)
- [ ] Functional vs Non-functional → [Functional Testing là gì?](https://codestar.vn/functional-testing-la-gi/)
- [ ] Kiểm thử tĩnh → [Static Testing là gì?](https://codestar.vn/static-testing-la-gi/)
- [ ] UI & Exploratory → [UI Testing](https://codestar.vn/ui-testing-la-gi/) · [Exploratory Testing](https://codestar.vn/exploratory-testing-la-gi/)
- [ ] **Kỹ thuật thiết kế test** (phần quyết định bạn có "làm được việc" không):
  - [ ] [Test Design là gì?](https://codestar.vn/test-design-la-gi/)
  - [ ] [Boundary Value — phân tích giá trị biên](https://codestar.vn/boundary-value-la-gi-huong-dan-phan-tich-gia-tri-bien/)
  - [ ] [5 bước thiết kế Test Case](https://codestar.vn/5-buoc-thiet-ke-test-case-trong-kiem-thu-phan-mem-phai-biet/)

---

## Giai đoạn 3 — Tài liệu test & quản lý bug

**Mục tiêu:** viết được test case chuẩn và log bug đúng chuẩn doanh nghiệp — thứ bạn làm mỗi ngày khi đi làm.

- [ ] **Test artifacts** (bộ tài liệu test, học chéo cả cụm):
  - [ ] [Test Case là gì?](https://codestar.vn/test-case-la-gi/) → [Mẫu Test Case bằng Excel chi tiết](https://codestar.vn/cach-lam-mach-lam-mau-test-case-viet-bang-excel-chi-tiet/)
  - [ ] [Test Scenario](https://codestar.vn/test-scenario-la-gi/) vs [Test Script](https://codestar.vn/test-script-la-gi/) — phân biệt rõ 3 khái niệm case/scenario/script
- [ ] Tài liệu yêu cầu (đầu vào của Tester) → [SRS — tài liệu đặc tả yêu cầu](https://codestar.vn/tai-lieu-dac-ta-srs-trong-phan-tich-yeu-cau/)
- [ ] Test Plan & môi trường test → [Test Environment là gì?](https://codestar.vn/test-environment-la-gi/)
- [ ] **Quản lý bug** (bộ kỹ năng lõi):
  - [ ] [Bug Report — 10 yếu tố báo cáo lỗi chuyên nghiệp](https://codestar.vn/bug-report-la-gi/)
  - [ ] [Cách log bug hiệu quả](https://codestar.vn/cach-log-bug/) · [Bug Life Cycle — vòng đời của bug](https://codestar.vn/bug-life-cycle-la-gi/)
  - [ ] [12 lỗi phần mềm mọi Tester cần nắm](https://codestar.vn/tat-tan-tat-ve-cac-loi-phan-mem/)
- [ ] Thực thi test → [Execute Test là gì?](https://codestar.vn/dieu-phai-biet-ve-execute-test-la-gi/)

> 🛠️ Công cụ thực tế: quản lý bug/test case trên **Jira**. Nắm quy trình tạo → assign → verify → close bug trước khi đi phỏng vấn.

---

## Giai đoạn 4 — Thực chiến: Web, Mobile, Database, API

**Mục tiêu:** test được trên đúng môi trường mà job Fresher yêu cầu. Đây là phần "làm như đi làm thật".

- [ ] Web testing → [Web Testing là gì? Các loại kiểm thử website](https://codestar.vn/tim-hieu-ve-web-testing/)
- [ ] Mobile testing → [Mobile Testing là gì?](https://codestar.vn/tim-hieu-ve-mobile-testing/)
- [ ] **Database & SQL** (kỹ năng "được giá" cho Fresher):
  - [ ] [Vì sao Tester cần biết SQL?](https://codestar.vn/tam-quan-trong-cua-sql-voi-tester/)
  - [ ] [Kiểm thử cơ sở dữ liệu & Test Data](https://codestar.vn/kiem-thu-co-so-du-lieu-la-gi-3-dieu-can-biet-ve-test-data/)
  - [ ] Thực hành: viết được truy vấn `SELECT`, `JOIN`, lọc & kiểm tra dữ liệu trong MySQL
- [ ] **API Testing với Postman**:
  - [ ] [API Testing là gì? Vai trò, môi trường, test case](https://codestar.vn/api-testing-la-gi-vai-tro-moi-truong-kiem-thu-api-cac-test-case-duoc-dung/)
  - [ ] [Postman — cài đặt & kiểm thử API](https://codestar.vn/postman-la-gi-cong-cu-ho-tro-kiem-thu-api-nhanh-chong-don-gian/)

---

## Giai đoạn 5 — Retest & kiểm thử phi chức năng

**Mục tiêu:** hiểu các loại test hay bị hỏi thêm khi phỏng vấn và cần trong dự án thật.

- [ ] **Cụm retest & thay đổi** (học chéo cả bộ): [Regression](https://codestar.vn/regression-testing-la-gi/) · [Confirmation/Retest](https://codestar.vn/confirmation-testing-la-gi/) · [Smoke](https://codestar.vn/smoke-testing-la-gi/) · [Sanity](https://codestar.vn/sanity-testing-la-gi/)
- [ ] Alpha vs Beta → [Alpha Testing](https://codestar.vn/alpha-testing-la-gi/) · [Beta Tester](https://codestar.vn/beta-tester-la-gi/)
- [ ] End-to-end → [E2E Testing là gì?](https://codestar.vn/end-to-end-testing-la-gi/)
- [ ] **Kiểm thử phi chức năng** (Non-functional):
  - [ ] Tổng quan → [Kiểm thử phi chức năng là gì?](https://codestar.vn/tim-hieu-kiem-thuu-phi-chuc-nang-la-gi-va-cac-loai-non-functional-testing/)
  - [ ] Hiệu năng → [Performance](https://codestar.vn/performance-testing-la-gi/) · [Load](https://codestar.vn/load-testing-la-gi/) · [Stress](https://codestar.vn/stress-testing-la-gi/)
  - [ ] Bảo mật → [Security Testing là gì?](https://codestar.vn/security-testing-la-gi/)
- [ ] Kỹ thuật ngách: [Loop Testing](https://codestar.vn/loop-testing-la-gi/)

---

## Giai đoạn 6 — Automation Testing (nâng cao)

**Mục tiêu:** bước tiến để tăng lương. **Không bắt buộc cho job Fresher Manual đầu tiên** — học sau khi đã vững Manual.

- [ ] Tổng quan & lộ trình → [Automation Test là gì? Lộ trình tự học](https://codestar.vn/hoc-automation-test-cho-nguoi-moi-bat-dau-voi-du-an-that/)
- [ ] Framework → [Test Automation Framework là gì?](https://codestar.vn/test-automation-framework-la-gi/)
- [ ] Công cụ chủ lực → [Selenium (web)](https://codestar.vn/selenium-la-gi/) · [Appium (mobile)](https://codestar.vn/appium-la-gi/)
- [ ] Web automation chi tiết → [Tìm hiểu về Web Automation](https://codestar.vn/tim-hieu-chi-tiet-ve-web-automation/)
- [ ] Tester nên học ngôn ngữ nào để làm automation → [5 ngôn ngữ lập trình cho Tester](https://codestar.vn/tester-nen-hoc-ngon-ngu-lap-trinh-nao-5-ngon-ngu-phai-biet/)

---

## Giai đoạn 7 — Chứng chỉ, phỏng vấn & đi làm

**Mục tiêu:** hoàn thiện hồ sơ và vượt vòng phỏng vấn Fresher.

- [ ] **Chứng chỉ** (có thì cộng điểm, không có vẫn xin được việc):
  - [ ] [ISTQB là gì?](https://codestar.vn/chung-chi-istqb-la-gi/) · [Top chứng chỉ Tester](https://codestar.vn/chung-chi-tester/)
- [ ] **Chuẩn bị phỏng vấn**:
  - [ ] [Tổng hợp câu hỏi phỏng vấn Tester 2026](https://codestar.vn/cau-hoi-phong-van-tester/)
  - [ ] [1001 câu trả lời phỏng vấn Automation Test](https://codestar.vn/1001-cau-tra-loi-phong-van-automation-test-ghi-diem-10-10/)
- [ ] Viết CV Fresher Tester (kể cả chưa có kinh nghiệm) — nêu bật dự án thực hành, test case đã viết, bug đã tìm
- [ ] **Chọn nơi học & bắt đầu apply** → xem mục [Học ở đâu?](#học-ở-đâu-tự-học-vs-học-trung-tâm) bên dưới

---

## Tài liệu tự học miễn phí

Dành cho bạn muốn tự học 100% hoặc học kèm để tiết kiệm chi phí:

- [ ] [Giới thiệu 19+ kênh tự học Tester cơ bản](https://codestar.vn/gioi-thieu-19-tai-lieu-tu-hoc-tester-co-ban-cho-nguoi-moi/)
- [ ] [Tự học Tester miễn phí với Guru99](https://codestar.vn/tu-hoc-tester-mien-phi-voi-guru99-danh-cho-nguoi-moi/)
- [ ] [Học Tester mất bao lâu? Lộ trình gợi ý](https://codestar.vn/hoc-tester-mat-bao-lau-goi-y-lo-trinh-hoc-tester-trong-30-gio/)
- **Nguồn tiếng Anh (miễn phí):** Guru99, ISTQB Foundation Syllabus (istqb.org), Ministry of Testing.

---

## Người thật, nghề thật

Kinh nghiệm thực chiến từ người trong nghề — đọc để biết công việc thật trông như thế nào:

- [Tester 10 năm kinh nghiệm tiết lộ "bug kinh điển" & cách sống sót giữa cơn bão AI](https://codestar.vn/tester-10-nam-kinh-nghiem-tiet-lo-bug-kinh-dien-va-cach-song-sot-giua-con-bao-ai/)
- [Intern Tester: một ngày làm việc & những bài học vỡ lòng](https://codestar.vn/intern-tester-mot-ngay-lam-viec-va-nhung-bai-hoc-vo-long/)
- [Dev và Tester: ai "khổ" hơn trong vòng đời phần mềm?](https://codestar.vn/dev-va-tester-ai-kho-hon-trong-vong-doi-phan-mem/)

---

## Học ở đâu? Tự học vs học trung tâm

Tự học tiết kiệm chi phí nhưng dễ lan man, thiếu dự án thật và không có người sửa lỗi. Học ở trung tâm rút ngắn thời gian đến lúc đi làm nhờ lộ trình có cấu trúc + thực hành dự án thật + hỗ trợ giới thiệu việc làm.

| Tiêu chí | Tự học | Học trung tâm |
|---|---|---|
| Chi phí | Thấp/Miễn phí | Vài triệu đồng/khóa |
| Lộ trình | Tự sắp, dễ lan man | Có cấu trúc sẵn |
| Dự án thật | Khó tự tạo | Có, thực hành trên dự án |
| Sửa lỗi / mentor | Không | Có giảng viên kèm |
| Hỗ trợ việc làm | Không | Thường có giới thiệu |
| Thời gian đến khi đi làm | Dài hơn, không chắc chắn | Ngắn hơn, 2–3 tháng |

**So sánh & chọn trung tâm tại Hà Nội:** [Top trung tâm đào tạo Tester Hà Nội uy tín](https://codestar.vn/top-5-trung-tam-dao-tao-tester-ha-noi/) · [Học Tester ở đâu? (toàn quốc)](https://codestar.vn/hoc-tester-o-dau/)

**Khóa học Tester cho người mới của CodeStar** (Hà Nội): lộ trình 20 buổi thực chiến, hơn 70% thời lượng thực hành trên dự án thật, giảng viên là Trưởng phòng QA / Test Manager 10+ năm kinh nghiệm, hỗ trợ giới thiệu việc làm, học lại miễn phí trọn đời. Học phí & lịch khai giảng cập nhật tại: **[codestar.vn/product/testing-for-freshers](https://codestar.vn/product/testing-for-freshers/)**.

---

## Câu hỏi thường gặp (FAQ)

**Học Tester có cần biết code không?**
Không. Manual Testing — mảng phù hợp nhất cho người mới — không yêu cầu giỏi lập trình khi bắt đầu. Bạn học code (Python/Java) sau, khi chuyển sang Automation để tăng lương.

**Người trái ngành học Tester được không?**
Được. Nghề Tester là một trong những cửa vào IT thân thiện nhất với người trái ngành, miễn là chọn lộ trình bài bản và chịu thực hành trên dự án thật.

**Học Tester mất bao lâu thì đi làm được?**
Với lộ trình tập trung, người mới thường cần khoảng 2–3 tháng học kèm thực hành là có thể ứng tuyển vị trí Fresher Tester.

**Lương Tester mới ra trường ở Hà Nội là bao nhiêu?**
Theo khảo sát 2026: Fresher ~ 7–12 triệu/tháng, trung bình ngành ~ 15 triệu/tháng, có thể lên 40–45 triệu ở cấp Senior/Automation.

**Nên học Manual hay Automation trước?**
Manual trước. Hầu hết job Fresher là Manual; Automation là bước nâng cao sau khi đã vững nền tảng.

**Con gái có nên học Tester không?**
Có — đây là nghề nhiều nữ giới theo và làm tốt. Đọc thêm: [Con gái có nên học Tester không?](https://codestar.vn/con-gai-co-nen-hoc-tester-khong-4-uu-diem-chi-tester-nu-co/)

**Có cần giỏi tiếng Anh không?**
Không bắt buộc để bắt đầu, nhưng nên làm quen thuật ngữ chuyên ngành vì tài liệu chuẩn (ISTQB, Guru99) chủ yếu bằng tiếng Anh.

---

## Về CodeStar Academy

**CodeStar Academy** là trung tâm đào tạo lập trình & kiểm thử phần mềm tại Hà Nội, trực thuộc **Kaopiz Software JSC**. Chuyên đào tạo Tester cho người mới và trái ngành với định hướng thực chiến và hỗ trợ việc làm.

- 🌐 Website: https://codestar.vn/
- 📍 Địa chỉ: Tầng 4, Tòa CT1, Bắc Hà C14, Tố Hữu, Trung Văn, Nam Từ Liêm, Hà Nội
- ☎️ Hotline: 0367 833 933
- 🏢 Trực thuộc: Kaopiz Software JSC
- 🎓 Khóa Tester cho người mới: https://codestar.vn/product/testing-for-freshers/

*Học viên CodeStar giai đoạn 2020–2026: ~85% có việc làm trong vòng 3 tháng sau khóa học (số liệu nội bộ). Đối tác tuyển dụng: Kaopiz, LG Việt Nam, CMC Global.*

---

## Đóng góp & giấy phép

- **Đóng góp:** thấy link hỏng, khái niệm cần bổ sung, hay muốn thêm tài liệu tự học? Mở [Issue](../../issues) hoặc [Discussion](../../discussions). Mọi đóng góp giúp roadmap này hữu ích hơn cho người mới đều được hoan nghênh.
- **Giấy phép:** Nội dung theo [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.vi) — được sao chép, chia sẻ, chỉnh sửa **kèm ghi nguồn** CodeStar Academy (https://codestar.vn/).

⭐ Nếu roadmap giúp ích, hãy **Star** repo để người mới khác tìm thấy dễ hơn.

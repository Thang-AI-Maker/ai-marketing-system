# 🔍 AUDIT CHUỖI LOGIC TUẦN 2 — Rocket AI

> Kiểm tra: mỗi ngày nhận gì từ ngày trước → sản xuất gì → bàn giao gì cho ngày sau.
> Ký hiệu: ✅ Work · 🟡 Có rủi ro · 🔴 Đứt logic · ⚠️ Cần tùy chỉnh cho B2B

---

## A. VẾT TỪNG MỐI PHỤ THUỘC (TRACE TỪNG DÒNG OUTPUT)

### NGÀY 08 → NGÀY 09

| Output N08 | Dùng cho N09 | Khớp? | Ghi chú |
|---|---|---|---|
| T8.0 Brand Guideline (màu #E45714, giọng) | Đầu vào Brand Voice Guideline — N09 "THI HÀNH T8.0, không định nghĩa lại" | ✅ | T8.0 có đủ 5 phần: archetype, 3 màu hex, font, 5 nguyên tắc giọng, Do/Don't + từ cấm |
| 10 bài ⭐ (STT 1,2,3,6,9,13,16,20,23,25) | Chính là 10 bài Core viết trong N09 | ✅ | Phủ ≥3 pillar (P1: 5, P2: 2, P4: 2, P5: 1) · ≥2 BOF (bài 9,23,25) · ≥1 Journey ⚡ (bài 13 = J1⚡) |
| Content Research Sheet | Prompt 1 N09 yêu cầu dán khối `[GIỌNG]` + Brand Voice KB — đã có trong Research Sheet | ✅ | |
| FAQ Database Q31+ | Dùng trong bài xử lý phản đối — cần câu thật để viết | 🟡 | FAQ DB **chưa tồn tại**. N09 sẽ thiếu nguyên liệu cho 3 bài phản đối. Cần FAQ ít nhất 10 câu trước khi viết N09. |
| Sales Message Pack (N03) | N09 Cụm B "mở kho đạn" — hook/headline/CTA có sẵn | ⚠️ | Rocket AI chưa có Message Pack riêng. Cần trích từ 12-content-strategy (Hook Bank 25 câu + Angle Bank) để làm Message Pack tạm. |

### NGÀY 08 → NGÀY 10

| Output N08 | Dùng cho N10 | Khớp? | Ghi chú |
|---|---|---|---|
| T8.0: 3 màu hex + 2 font | Cài vào Canva Brand Kit — N10 "cấm chọn màu mới" | ✅ | `#E45714` · `#D8CFC0` · `#EDE7DD` đã có mã hex. Font Be Vietnam Pro đã kiểm tra dấu tiếng Việt ✅ |
| T8.0: 5 nguyên tắc giọng | Visual Brand Kit — phần phong cách ảnh "người thật, tông ấm" | ✅ | Photography style đã định nghĩa trong 03-brand-guideline mục 4 |
| Content Bank (sẽ có sau N09) | Chọn 6/10 bài để làm visual + 4 bài đánh dấu "ảnh thật" | 🔴 | **N10 làm SAU N09** — nhưng N09 chưa làm. N10 không thể chọn 6 bài nếu chưa có 10 bài hoàn chỉnh. Đây là dependency cứng. |
| Message Pack (N03) | "Nguồn duy nhất của CHỮ TRÊN ẢNH" — phải gạch chân được dòng Message Pack trước khi mở Canva | ⚠️ | Rocket AI chưa có Message Pack. N10 sẽ bị kẹt ở bước "gạch chân dòng Message Pack". |
| 2 video scripts (từ N11) | Làm 2 thumbnail cho video | 🔴 | **N10 yêu cầu thumbnail cho video N11, nhưng N11 làm SAU N10.** Logic ngược. Tuy nhiên, thumbnail là ảnh bìa — có thể làm từ ý tưởng video (không cần video hoàn chỉnh). Chấp nhận được nếu N10 chỉ cần biết chủ đề 2 video. |

### NGÀY 09 → NGÀY 10

| Output N09 | Dùng cho N10 | Khớp? | Ghi chú |
|---|---|---|---|
| 10 bài viết hoàn chỉnh | 6 bài gắn visual + 4 bài ảnh thật | 🔴 | Dependency cứng: N10 cần N09 xong. Không làm N09 = không có bài để gắn visual. |
| 3 quote/bài từ Repurpose Sheet | Nguyên liệu visual cho N10 | ✅ | Repurpose có sẵn quote ngắn — dùng làm chữ trên ảnh. |
| Brand Voice Guideline | Visual Brand Kit — giọng trên ảnh phải khớp | ✅ | |

### NGÀY 09 → NGÀY 11

| Output N09 | Dùng cho N11 | Khớp? | Ghi chú |
|---|---|---|---|
| 10 bài viết | Nguồn của 10 kịch bản video (1 bài → 1 script) | ✅ | |
| 3 script nháp (Repurpose Sheet) | Tiết kiệm 30% công sức viết script — chỉ nâng cấp | ✅ | |
| Brand Voice Guideline | Giọng thoại + chọn giọng AI khớp cá tính T8.0 | ✅ | |

### NGÀY 10 → NGÀY 11

| Output N10 | Dùng cho N11 | Khớp? | Ghi chú |
|---|---|---|---|
| 2 thumbnail (1080×1920) | Gắn vào đúng 2 video | ✅ | Thumbnail là ảnh tĩnh — làm được trước video. |

### NGÀY 08-11 → NGÀY 13

| Output các ngày trước | Slot trong lịch 14 ngày | Khớp? | Ghi chú |
|---|---|---|---|
| 10 bài viết (N9) | 10 slot FB | ✅ | |
| 2 video (N11) | 2 slot video | ✅ | |
| 2 Zalo broadcast (N9, từ Repurpose) | 2 slot Zalo | ✅ | |
| **Tổng: 14 nội dung** | **14 slot** | ✅ | Phép cộng khớp |

| Yêu cầu N13 | Nguồn | Khớp? |
|---|---|---|
| Baseline KPI từ Business Snapshot N1 | 01-business-brand-overview: DT ~1 tỷ/quý, chốt 12-20%, data sụp 3000→vài trăm | ✅ |
| Giờ vàng đăng bài (có LÝ DO) | 04-social-media: FB Thắng reach 20-67%, giờ đăng cần xác định từ thói quen ICP | 🟡 Cần xác nhận giờ cụ thể |
| CTA về form N12 | Form N12 phải tồn tại và link hoạt động | 🔴 Phụ thuộc N12 |

### NGÀY 12 → NGÀY 13

| Output N12 | Dùng cho N13 | Khớp? | Ghi chú |
|---|---|---|---|
| Form thu lead CHẠY THẬT + Sheet | Automation Layer 🟢 AUTO — Hermes đọc Sheet | 🔴 | Cần Hermes kết nối Zalo OA. Rocket AI cần xác nhận: đã có Zalo OA chưa? Hermes đã cài chưa? |
| Lead Flow Map (6 trạm) | Đầu vào Automation Layer N13 | ✅ | |
| Chuỗi nuôi dưỡng Zalo (Bonus) | Tầng 🟡 ASSISTED — người duyệt trước khi bật | 🟡 | |

### NGÀY 12 → NGÀY 14 (Marketing Gate)

| Output N12 | Dùng cho N14 | Khớp? | Ghi chú |
|---|---|---|---|
| Form → Sheet → Hermes → Zalo <2' | **Gate câu 3 (câu tử)** | 🔴 | Đây là mục quan trọng nhất. Nếu luồng vàng không thông → fail gate → không vào Tuần 3. Cần test kỹ. |
| Trường phân loại trong form | Mầm CRM Tuần 3 | ⚠️ | Cần thiết kế 5 lựa chọn phù hợp B2B: e.g. "Xây AI Agent" · "Tư vấn giải pháp" · "Học AI Marketing" · "Chuyển đổi số DN" · "Khác" |

---

## B. 5 ĐIỂM ĐỨT / RỦI RO LOGIC (cần xử lý trước)

### 🔴 #1 — N10 phụ thuộc N09, nhưng N10 làm cùng ngày hôm sau

**Vấn đề:** N10 yêu cầu chọn 6/10 bài từ Content Bank để làm visual. Nhưng Content Bank chỉ có SAU khi N09 hoàn thành. Nếu N09 trễ → N10 không có bài để làm visual.

**Đề xuất cho Rocket AI:** Làm N09 buổi sáng (3-4h), N10 buổi chiều (3-4h) cùng ngày. Hoặc làm gộp N09+N10 trong 2 ngày liên tiếp. **10 bài N09 không cần hoàn hảo 100% — chỉ cần đủ 6 bài chọn cho N10.**

### 🔴 #2 — Thiếu Sales Message Pack (N03)

**Vấn đề:** Cả N09 (cụm B "mở kho đạn") và N10 (nguồn chữ trên ảnh) đều yêu cầu Message Pack có sẵn. Rocket AI chưa có file này.

**Fix nhanh:** Trích từ 12-content-strategy (Hook Bank 25 câu + Angle Bank) + 08-product-offer-map (CTA/offer) → tạo Message Pack tạm trong 30 phút. Cấu trúc: 1 hook chủ đạo + 3 headline + 3 CTA + 5 angle + 5 câu ads.

### 🔴 #3 — Chưa có FAQ Database — ảnh hưởng dây chuyền

**Vấn đề:** FAQ DB là input cho:
- N08: R1 research (cần Q##)
- N09: 3 bài xử lý phản đối (cần Q## để viết)
- N12: Khối 9 landing page (FAQ lấy thẳng từ Q##)

**Fix nhanh:** Gom 15-20 câu hỏi thật từ inbox/zoom/workshop → tạo FAQ DB 20 câu trong 1 giờ. Em đã gợi ý sẵn 10 câu trong T8.1.

### 🟡 #4 — N12 cần Hermes kết nối Zalo OA

**Vấn đề:** Luồng vàng (form → Sheet → Hermes → Zalo <2 phút) là Gate câu 3. Nếu chưa cài Hermes hoặc chưa có Zalo OA → không pass gate.

**Fallback:** N12 cho phép "người trực gửi tay" thay vì Hermes. Nhưng cần có người thật cam kết trực Zalo trong giờ demo.

### ✅ #5 — Đã tách lead magnet theo hai phễu

**CEO:** AIOS Readiness Map 5 lớp/10 tiêu chí → Audit/Demo. **Builder:** Bản đồ 7 bước đóng gói sản phẩm số → workshop/Zoom. Form và Zalo gắn tag riêng; không còn dùng một lead magnet B2C/B2B chung.

---

## C. KIỂM TRA TOÀN CHUỖI THEO DÒNG THỜI GIAN

```
NGÀY 08 ────────────→ NGÀY 09 ────────→ NGÀY 10 ────────→ NGÀY 11
│                      │                   │                   │
│ T8.0 Brand           │ 10 bài (từ 10⭐)  │ 6 visual          │ 2 video
│ Research 3 mỏ        │ Brand Voice       │ (bài N09 +        │ (script N09 +
│ 5 Pillar + Funnel    │ Repurpose 3 bài   │  màu N08 +        │  thumbnail N10)
│ 60 ý + 10⭐          │ (trong đó 2 Zalo) │  Message Pack)    │
│                      │                   │                   │
└──────────────────────┴───────────────────┴───────────────────┤
                                                                │
NGÀY 12 ────────────────────────────────────────────────────────┤
│                                                               │
│ Form + LP + Lead Magnet                                       │
│ Hermes → Zalo (luồng vàng)                                    │
│                                                               │
└──────────────────────────────┬────────────────────────────────┘
                               │
                               ▼
                          NGÀY 13
                               │
                               │ Lịch 14 ngày = 10 bài + 2 video + 2 Zalo = 14 slot
                               │ 3 nội dung đã đăng THẬT
                               │ Automation 3 tầng
                               │
                               ▼
                          NGÀY 14
                               │
                               │ Demo luồng vàng (form → lead → Zalo)
                               │ Marketing Gate 5 câu
                               │ Pass → Tuần 3
```

**Kết luận chung:** Chuỗi logic **có work** — mỗi ngày có input rõ ràng từ ngày trước. Nhưng có **3 dependency cứng** không thể bỏ qua:

| Dependency cứng | Ngày ảnh hưởng | Hậu quả nếu đứt |
|---|---|---|
| FAQ Database phải có trước N09 | N08 → N09 | Thiếu nguyên liệu viết 3 bài phản đối |
| 10 bài N09 phải có trước N10 | N09 → N10 | Không có bài để chọn 6 visual |
| Form + Hermes phải chạy được trước N14 | N12 → N14 | Fail Gate câu 3 → không vào Tuần 3 |

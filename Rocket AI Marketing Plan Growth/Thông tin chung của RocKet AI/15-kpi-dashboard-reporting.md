# 15 — KPI Dashboard & Reporting: Rocket AI

> Không đo thì không tối ưu. Mỗi KPI đủ 6 thành phần (baseline · target · nguồn · người R · ngưỡng cảnh báo · hành động). Báo cáo cấm liệt kê số suông — kết bằng: nhận định → giả thuyết → hành động → người → deadline. Vòng lặp tuần/tháng/quý, phản hồi về 04 & 09.

---

## 1. Khung KPI — tách hai phễu

### Nhóm A — Chỉ số phủ toàn hệ

| KPI | Baseline | Target hiện có | Nguồn | Người R | Ngưỡng | Hành động |
|---|---|---|---|---|---|---|
| Reach/tháng | FB reach 20–67%/bài | Giữ và tăng dần | Insights | Anh Thư | Giảm >20% tuần/tuần | Đổi hook/format |
| Data mới toàn hệ | 3.000–4.000 cũ → vài trăm hiện tại | T7 ≥1.500 · T8 ~2.000 · T9 ~2.500 · T10 ~3.000 | CRM/Zalo | Media buyer + Cường | <80% target | Rà nguồn traffic |
| Tỷ lệ lead được gắn đúng tag | Chưa có | **100%** | CRM | Cường | <95% | Sửa form/router; không scale ads |

Data tổng chỉ đo sức khỏe đầu phễu; không dùng để tính close rate chung.

### Nhóm B — Phễu CEO-AIOS

| KPI | Baseline | Target | Nguồn | Người R | Ngưỡng | Hành động |
|---|---|---|---|---|---|---|
| **Lead CEO đủ điều kiện** ⭐ | `[CẦN BỔ SUNG]` | Chốt sau 2 tuần test | Form + CRM | Media buyer + sale | Lead tăng nhưng sai vai trò | Sửa tệp, copy và câu hỏi form |
| Qualified → Audit booked | `[CẦN BỔ SUNG]` | Chốt sau test | CRM/calendar | Sale CEO | Không có booking trong 7 ngày | Sửa CTA, SLA và nurture |
| Audit show rate | `[CẦN BỔ SUNG]` | Chốt sau test | Calendar/meeting log | Sale CEO | No-show tăng | Reminder + xác nhận agenda |
| Audit → Proposal | `[CẦN BỔ SUNG]` | Chốt sau test | CRM | Tony/Thắng | Audit nhiều, proposal ít | Rà qualification và discovery |
| Proposal → Won theo gói | `[CẦN BỔ SUNG]` | Tách Transfer/Installed/Managed/Enterprise | CRM + kế toán | Tony | Won thấp | Rà proof, scope, pricing, objection |
| Activation 28 ngày | `[CẦN BỔ SUNG]` | Theo gate chương trình | Demo Day/dashboard | Integrator | Hệ chưa chạy thật | Giảm scope, tăng hỗ trợ |
| Expansion/Referral 90 ngày | `[CẦN BỔ SUNG]` | Chốt sau cohort đầu | CRM | Customer Success | Không có review/case | Bắt buộc 90-day review |

### Nhóm C — Phễu DIGITAL-BUILDER

| KPI | Baseline | Target | Nguồn | Người R | Ngưỡng | Hành động |
|---|---|---|---|---|---|---|
| CPL Builder | Chưa có | ≤30k đẹp, trần 50k `[GIẢ ĐỊNH]` | Meta | Media buyer | >50k 5–7 ngày | Đổi creative/tệp/offer |
| Zalo → Workshop attended | 25% toàn hệ | ≥25%, phấn đấu 30% | Zalo + Zoom | Cường | <20% | Nurture + reminder |
| Workshop/Zoom → Bootcamp | 12–20% toàn hệ | Giữ ≥15% sau khi xác nhận tag | CRM | Thắng | <12% | Rà pitch, proof và offer |
| Activation Builder | `[CẦN BỔ SUNG]` | Offer/campaign chạy thật | Tracker/Demo | Integrator | Khách chỉ học, chưa launch | Gỡ scope, build sprint |
| Upsell/LTV Builder | `[CẦN BỔ SUNG]` | Chốt sau cohort đầu | CRM + Genful | Tony/Linh | Không có mua tiếp | Rà coaching/tool continuity |
| Case/Referral | `[CẦN BỔ SUNG]` | ≥3 case/cohort theo audit chương trình | CS tracker | Customer Success | Thiếu số trước/sau | Bắt baseline Ngày 0 |

### Nhóm D — Tài chính tách dòng

| KPI | Baseline | Target | Nguồn | Người R | Ngưỡng | Hành động |
|---|---|---|---|---|---|---|
| Doanh thu AIOS CEO | `[CẦN TÁCH]` | Theo kế hoạch tháng | CRM/kế toán | Tony | <85% target | Rà Audit→Proposal→Won |
| Doanh thu Builder | `[CẦN TÁCH]` | Theo kế hoạch tháng | CRM/kế toán | Thắng | <85% target | Rà Workshop→Won |
| Doanh thu Genful | ~15% doanh thu | T8 70–80 · T9 140–150 · T10 220–230tr | Genful | Linh | <80% target | Rà activation/usage/repeat |
| CAC/LTV theo nhánh | Chưa có | Không dùng blended | Ads + CRM + kế toán | Media buyer + Cường | Không nối được source→won | Dừng scale, sửa attribution |

**Điều kiện tiên quyết:** mỗi lead phải có `source`, `campaign`, `persona_tag`, `offer`, `stage`, `owner`, `next_action`, `outcome`. Chưa có tracking thì để `[CẦN BỔ SUNG]`, không bịa baseline.

## 2. Mẫu báo cáo TUẦN (kết bằng hành động — cấm liệt kê số suông)

> **Tuần: __ | Người tổng hợp: __ | Chỉ số sống còn: Qualified CEO + Builder attended**

**1. Đầu phễu:** Data tổng ___; gắn đúng tag ___%; CEO qualified ___; Builder leads ___; CPL từng nhánh ___.
→ *Nhận định:* … · *Giả thuyết:* … · *Hành động:* … · *Người:* … · *Deadline:* …

**2. CEO:** Audit booked ___; attended ___; proposal ___; won theo gói ___.
→ *Nhận định → giả thuyết → hành động → người → deadline.*

**3. Builder:** Workshop registered ___; attended ___%; Bootcamp won ___%; activation ___.
→ *Nhận định → giả thuyết → hành động → người → deadline.*

**4. Content:** Top 3 bài (reach/data) — ___. Flop 3 bài — ___.
→ *Phân loại Scale/Repurpose/Improve/Retest/Stop (mục 4) + hành động + người + deadline.*

**5. Ads:** Campaign thắng ___ (ROAS/CPL). Campaign cắt ___.
→ *Hành động ngân sách tuần tới + người + deadline.*

## 3. Mẫu báo cáo THÁNG

> **Tháng: __ | Doanh thu ___ / mục tiêu ___ (T8 700 / T9 1.000 / T10 1.300tr)**

1. **Kết quả vs mục tiêu:** doanh thu CEO, Builder, Genful; CAC/LTV từng nhánh.
2. **Hai phễu tháng:** CEO `Qualified→Audit→Proposal→Won→Activation`; Builder `Lead→Workshop→Bootcamp→Activation→Upsell`.
3. **Điểm rơi lớn nhất tháng:** … → *giả thuyết → hành động → người → deadline.*
4. **Quyết định tháng tới:** scale gì, dừng gì, thử gì (dựa mục 4).
5. **Ngân sách:** đã tiêu ___ / 100tr, dự phòng còn ___, ROAS blended ___.

## 4. Bảng phân loại nội dung (tiêu chí bằng SỐ)

| Loại | Tiêu chí số | Hành động |
|---|---|---|
| **Scale** | Reach ≥ 2× trung vị **và** data/đăng ký ≥ mục tiêu/bài | Dồn ads + nhân thành series, làm thêm biến thể |
| **Repurpose** | Reach tốt (≥ trung vị) nhưng ít data | Giữ nội dung, đổi CTA/lead magnet, đăng lại kênh khác |
| **Improve** | Gần ngưỡng (0,7–1× trung vị), có tiềm năng | Sửa hook/thumbnail/3 giây đầu, đăng lại |
| **Retest** | Mẫu nhỏ/kết quả không rõ | Chạy lại 1 biến thể trước khi kết luận |
| **Stop** | Reach < 0,5× trung vị **sau 2 lần** | Dừng series/format đó, dồn lực chỗ thắng |

*Trung vị tính trên chính dữ liệu Rocket AI sau khi có tracking — không so benchmark ngoài.*

## 5. Quy trình review QUÝ (vòng phản hồi về 04 & 09)

1. **Cập nhật baseline (→ 04):** thay số giả định bằng số thật riêng cho CEO-AIOS và DIGITAL-BUILDER: CAC, LTV, conversion từng bước, AOV, activation và expansion.
2. **Điều chỉnh chiến lược (→ 09):** nếu CPQL/Audit/Proposal của CEO hoặc CPL/Workshop/Won của Builder lệch giả định → chỉnh offer, ngân sách hoặc mục tiêu kỳ sau.
3. **Rà persona & offer (→ 07, 08):** nhánh nào (chuyên gia vs doanh nghiệp) ra tiền đúng dự đoán? Điều chỉnh tỷ trọng ngân sách 2 nhánh.
4. **Rà pillar (→ 12):** pillar nào Scale, pillar nào Stop theo số thật.

## Vòng lặp vận hành
**Tuần:** đọc KPI CEO và Builder riêng → hành động. **Tháng:** quyết định scale/stop từng nhánh. **Quý:** cập nhật baseline và phân bổ nguồn lực.

---

## Khối bàn giao
**`[CẦN BỔ SUNG]` (cài T7):** GA4/Pixel/CRM/chatbot Zalo/UTM + router `CEO-AIOS`/`DIGITAL-BUILDER` · CAC/LTV và conversion thật từng nhánh.
**`[CHỜ BOD]`:** ai nhập số hằng tuần (đề xuất Cường tổng hợp dashboard, Anh Thư phần content) · tần suất trình BOD (đề xuất: tuần cho đội, tháng cho BOD).
**Kết thúc bộ 15 tài liệu** — đây là vòng lặp vận hành liên tục, phản hồi ngược về 04 & 09.

*Tài liệu 15 · trạng thái: khung KPI đủ 6 thành phần, mẫu báo cáo kết bằng hành động, quy trình tối ưu & review quý sẵn sàng. HOÀN THÀNH bộ Marketing Growth OS.*

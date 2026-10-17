# Task Sprint 3 - Tuấn Anh

Tài liệu và sản phẩm báo cáo Sprint 3 (Phát triển ứng dụng Web - IS207).

## Sơ đồ đã hiệu chỉnh - 17/10/2026

Đã tái dựng ba Activity BKH và một State Machine TKT theo PDF yêu cầu (A1-A5, A7, A10, C5). Các sơ đồ có swimlane, điều kiện rẽ nhánh, ngoại lệ nét đứt đỏ, khung tên và bố cục A4 ngang. Tên file dùng đúng thứ tự mã `ACT-BKH-*` và `STM-TKT-*`.

| Sơ đồ | Xem ảnh | Mã Mermaid | Draw.io |
|---|---|---|---|
| ACT-BKH-01 - Đặt lịch tại viện | [PNG](<Tuấn Anh - Web - Sprint 3/BKH_ACT/ACT-BKH-01.png>) | [Mermaid](<Tuấn Anh - Web - Sprint 3/BKH_ACT/ACT-BKH-01.mmd>) | [Draw.io](<Tuấn Anh - Web - Sprint 3/BKH_ACT/ACT-BKH-01.drawio>) |
| ACT-BKH-02 - Check-in và ranh giới MedSi | [PNG](<Tuấn Anh - Web - Sprint 3/BKH_ACT/ACT-BKH-02.png>) | [Mermaid](<Tuấn Anh - Web - Sprint 3/BKH_ACT/ACT-BKH-02.mmd>) | [Draw.io](<Tuấn Anh - Web - Sprint 3/BKH_ACT/ACT-BKH-02.drawio>) |
| ACT-BKH-03 - Tra cứu lịch sử | [PNG](<Tuấn Anh - Web - Sprint 3/BKH_ACT/ACT-BKH-03.png>) | [Mermaid](<Tuấn Anh - Web - Sprint 3/BKH_ACT/ACT-BKH-03.mmd>) | [Draw.io](<Tuấn Anh - Web - Sprint 3/BKH_ACT/ACT-BKH-03.drawio>) |
| STM-TKT-01 - Vòng đời phiếu khám | [PNG](<Tuấn Anh - Web - Sprint 3/TKT_STM/STM-TKT-01.png>) | [Mermaid](<Tuấn Anh - Web - Sprint 3/TKT_STM/STM-TKT-01.mmd>) | [Draw.io](<Tuấn Anh - Web - Sprint 3/TKT_STM/STM-TKT-01.drawio>) |

- [PDF bốn sơ đồ và bảng chuyển trạng thái](<Tuấn Anh - Web - Sprint 3/sprint-3-diagrams.pdf>).
- [Bảng chuyển trạng thái sáu cột](<Tuấn Anh - Web - Sprint 3/TKT_STM/STM-TKT-01-transitions.csv>).
- [Bộ đầy đủ, kèm mã tái tạo](<Tuấn Anh - Web - Sprint 3/sprint-3-diagrams.zip>).
- [Giải thích từng hình, nguồn đối chiếu và hướng dẫn dùng](<Tuấn Anh - Web - Sprint 3/GUIDE.txt>).

A2 ưu tiên Mermaid trong Notion; bảng C5 vẫn đề cập Draw.io, nên cung cấp cả hai. PDF/PNG/Draw.io giữ bố cục A4; Mermaid tự sắp xếp lại. Bản [Mermaid có linkStyle](<Tuấn Anh - Web - Sprint 3/TKT_STM/STM-TKT-01-styled.mmd>) là lựa chọn khi nơi nhúng không hỗ trợ themeCSS của stateDiagram-v2.

Mốc hết hạn cuối ca +120 phút và nguồn xác nhận hoàn tất/HIS được đánh dấu cần nhóm xác nhận. Không đổi nghĩa các mã ngoại lệ cũ hoặc tự sửa bộ trạng thái chung. Các file `BKH_ACT/Code.docx` và `TKT_STM/TKT_STM.docx` được giữ làm tài liệu gốc; dùng các file Mermaid và bảng CSV liên kết ở trên cho phiên bản sơ đồ đã hiệu chỉnh.

## 📁 Cấu trúc thư mục

- **Tuấn Anh - Web - Sprint 3/**
  - **BKH_ACT/**: Biểu đồ hoạt động (Activity Diagrams) bao gồm các file `.drawio`, `.png` và tài liệu giải thích.
  - **TKT_STM/**: Biểu đồ trạng thái (State Machine Diagrams) bao gồm `.drawio`, `.png` và tài liệu giải thích.
  - **(7) PHÂN TÍCH THIẾT KẾ LẠI _ Notion.pdf**: Bản phân tích thiết kế chi tiết từ Notion.
  - **BKH_DD _ BKH_BR _ TKT_BR _ BKH_CMP _ BKH_OQ.xlsx**: Bảng từ điển dữ liệu (Data Dictionary), quy tắc nghiệp vụ (Business Rules) và các đặc tả liên quan.
  - **BKH_DOC _ TKT_SPEC.docx**: Tài liệu đặc tả chức năng và hệ thống.
  - **Resources.docx**: Tài nguyên và ghi chú tham khảo.
  - **Screenshot 2026-10-16 184042.png**: Hình ảnh minh chứng / chụp màn hình.

# 6451071073_Lab1 — Khai phá dữ liệu · Báo cáo thực hành Buổi 1

- **Sinh viên:** Phan Quốc Thắng — MSSV 6451071073 — Lớp CNTT-K64
- **GVHD:** ThS. Nguyễn Thiện Dương
- **Đơn vị:** Phân hiệu Trường ĐH Giao thông Vận tải tại TP. Hồ Chí Minh — Bộ môn Công nghệ Thông tin

## Cấu trúc

| Phần | Bài (số trang theo trình đọc PDF) | Nội dung | File mã nguồn |
|---|---|---|---|
| 1 | Bài 2 (Trang 15–17) | Khảo sát & tiền xử lý dữ liệu Titanic (8 yêu cầu) | [Phan1/6451071073_LAB1_Bai2_Trang15-17.ipynb](Phan1/6451071073_LAB1_Bai2_Trang15-17.ipynb) |
| 1 | Bài 2 (Trang 28) | Khảo sát & tiền xử lý dữ liệu Bank Marketing | [Phan1/6451071073_LAB1_Bai2_Trang28.ipynb](Phan1/6451071073_LAB1_Bai2_Trang28.ipynb) |
| 1 | Bài 2 (Trang 30) | Tiền xử lý dữ liệu môi trường `tb_tracking.xlsx` (a–d) | [Phan1/6451071073_LAB1_Bai2_Trang30.ipynb](Phan1/6451071073_LAB1_Bai2_Trang30.ipynb) |
| 2 | Bài 2 (Trang 37–38) | Apriori / FP-Growth trên Online Retail (UK, 12 yêu cầu) | [Phan2/6451071073_LAB1_Bai2_Trang37-38.ipynb](Phan2/6451071073_LAB1_Bai2_Trang37-38.ipynb) |
| 2 | Bài 5a (Trang 45) | Germany, min_sup = 5%, min_conf = 50% | [Phan2/6451071073_LAB1_Bai5a.ipynb](Phan2/6451071073_LAB1_Bai5a.ipynb) |
| 2 | Bài 5b (Trang 45) | France, min_sup = 7%, min_conf = 70% | [Phan2/6451071073_LAB1_Bai5b.ipynb](Phan2/6451071073_LAB1_Bai5b.ipynb) |
| 2 | Bài 6 (Trang 45) | So sánh thời gian Apriori và FP-Growth trên Groceries | [Phan2/6451071073_LAB1_Bai6.ipynb](Phan2/6451071073_LAB1_Bai6.ipynb) |

Mỗi notebook có ô khai báo họ tên – MSSV ở đầu, mỗi câu in ra họ tên – MSSV, kèm nhận xét sau mỗi kết quả.

## Dữ liệu (`data/`)

`titanic.csv`, `bank/bank-full.csv`, `tb_tracking.xlsx`, `Online Retail.xlsx`, `groceries.csv` — tải từ thư mục dataset của giảng viên.

## Chạy lại

```bash
pip install numpy pandas matplotlib seaborn scipy mlxtend openpyxl jupyter
cd Phan1   # hoặc Phan2
jupyter nbconvert --to notebook --execute --inplace *.ipynb
```

Đường dẫn dữ liệu trong notebook là tương đối (`../data/`), nên cần chạy notebook từ đúng thư mục của nó.

# vnstock-trading-tools

Phân tích dữ liệu chứng khoán Việt Nam với `vnstock` trong **GitHub Codespaces**.

## Tính năng
- Lấy dữ liệu giá & khối lượng.
- Tính EMA (9, 26, 100, 200) và RSI (9, 45).
- Đánh dấu giao cắt EMA, phân kỳ RSI.
- Vẽ biểu đồ nền sáng, font lớn.
- Xuất báo cáo PDF.

## Cách dùng (Codespaces)
1. Tải toàn bộ thư mục này lên GitHub.
2. Trên GitHub → nút **Code** → tab **Codespaces** → **Create codespace on main**.
3. Mở file `vnstock_demo.ipynb` → Run All.

## Cách chạy local
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook
```

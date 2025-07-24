# 📊 PHÂN TÍCH DỮ LIỆU CHUỖI THỜI GIAN THEO MÙA VÀ KHÔNG THEO MÙA BẰNG R

## 📝 Giới thiệu

Dự án này tập trung vào việc **phân tích chuỗi thời gian (time series)**, bao gồm:
- **Chuỗi có tính mùa vụ (seasonal)**
- **Chuỗi không có tính mùa vụ (non-seasonal)**

Phân tích được thực hiện bằng **ngôn ngữ R**, sử dụng các thư viện và kỹ thuật thống kê hiện đại để khám phá, mô hình hóa và dự đoán dữ liệu thực tế theo thời gian.

## 🎯 Mục tiêu

- Trực quan hóa và xử lý dữ liệu chuỗi thời gian
- Kiểm tra tính mùa vụ, xu hướng, độ trễ,...
- Ứng dụng các mô hình ARIMA, SARIMA, Holt-Winters,...
- Dự báo xu hướng tương lai và đánh giá mô hình

## 🔧 Công nghệ sử dụng

| Thư viện R       | Mục đích |
|------------------|---------|
| `forecast`       | Dự đoán chuỗi thời gian (ARIMA, ETS, Holt-Winters) |
| `tseries`        | Kiểm định dừng (ADF, KPSS), kiểm định Box-Ljung |
| `ggplot2`        | Vẽ biểu đồ trực quan |
| `readr`, `dplyr` | Đọc, xử lý và làm sạch dữ liệu |
| `stats`          | Phân tích thống kê cơ bản |

## 📁 Cấu trúc thư mục

```
project/
├── seasonal_analysis.R         # Phân tích chuỗi có mùa
├── nonseasonal_analysis.R      # Phân tích chuỗi không mùa
├── dataset/
│   ├── seasonal_data.csv
│   └── nonseasonal_data.csv
├── plots/
│   └── ... (biểu đồ đầu ra)
└── README.md
```

## 🚀 Hướng dẫn sử dụng

1. **Mở RStudio hoặc Terminal**
2. **Cài thư viện (nếu chưa có):**

```r
install.packages(c("forecast", "tseries", "ggplot2", "readr", "dplyr"))
```

3. **Chạy phân tích:**

```r
source("seasonal_analysis.R")
# hoặc
source("nonseasonal_analysis.R")
```

## 📈 Kết quả

- Biểu đồ xu hướng, mùa vụ, ACF/PACF
- Mô hình ARIMA/SARIMA, dự báo tương lai
- Đánh giá sai số bằng RMSE, MAE,...

## 👨‍🎓 Thông tin sinh viên

- **Họ tên:** Nguyễn Văn Nhân  
- **MSSV:** 2200002045  
- **Lớp:** 22DTH4C  
- **Trường:** Đại học Nguyễn Tất Thành  
- **Môn học:** Phân tích dữ liệu chuỗi thời gian

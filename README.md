# ETL_FROM_WEB
# ETL Project: Extracting Data from a Website using Python

## 📌 Overview
Đây là một project ETL (Extract - Transform - Load) sử dụng Python để lấy dữ liệu từ một trang web, xử lý dữ liệu và lưu vào cơ sở dữ liệu. Project này được thực hiện trong môi trường Jupyter Notebook.

## 🛠️ Technologies Used
- **Python**: Ngôn ngữ lập trình chính
- **Requests**: Thu thập dữ liệu từ website
- **BeautifulSoup**: Trích xuất và xử lý dữ liệu HTML
- **Pandas**: Chuyển đổi và xử lý dữ liệu
- **SQL (SQLite/PostgreSQL/MySQL)**: Lưu trữ dữ liệu sau khi xử lý

## 📌 Workflow
1. **Extract**: Sử dụng `requests` để lấy dữ liệu từ website.  
2. **Transform**: Dùng `BeautifulSoup` để trích xuất dữ liệu HTML và `pandas` để làm sạch dữ liệu.  
3. **Load**: Lưu dữ liệu vào database (SQLite).  

## 🚀 How to Run
1. **Clone repo**:
   ```bash
   git clone https://github.com/thaibeocaca/ETL_FROM_WEB.git
   cd ETL_FROM_WEB

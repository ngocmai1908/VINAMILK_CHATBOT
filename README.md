# 🐄 Vinamilk Chatbot

💬 **Trợ lý ảo hỗ trợ tra cứu thông tin nội bộ nhân viên, chính sách công ty và sản phẩm Vinamilk bằng AI**

---

## 📌 Giới Thiệu

**Vinamilk Chatbot** là ứng dụng chatbot được xây dựng bằng **Python** và **Streamlit**, tích hợp mô hình ngôn ngữ lớn (**LLM - VinaLLaMA 7B**) nhằm hỗ trợ người dùng tra cứu thông tin nhanh chóng bằng tiếng Việt.

Ứng dụng giúp:

- Tra cứu thông tin nhân viên từ dữ liệu Excel nội bộ  
- Trả lời câu hỏi liên quan đến chính sách, quy định, văn hóa công ty từ tài liệu PDF  
- Giới thiệu thông tin sản phẩm Vinamilk  
- Giao tiếp tự nhiên bằng ngôn ngữ tiếng Việt  

---

## 🎯 Mục Tiêu Dự Án

- Ứng dụng AI vào bài toán truy xuất thông tin doanh nghiệp  
- Tối ưu thời gian tìm kiếm dữ liệu nội bộ  
- Hỗ trợ nhân viên tiếp cận thông tin nhanh hơn  
- Xây dựng chatbot tiếng Việt phục vụ môi trường doanh nghiệp  

---

## 🛠️ Công Nghệ Sử Dụng

- Python  
- Streamlit  
- LangChain  
- FAISS Vector Database  
- Sentence Transformers / MiniLM  
- PyTorch  
- VinaLLaMA 7B  

---

## ⚙️ Tính Năng Chính

## 👨‍💼 1. Tra Cứu Thông Tin Nhân Viên

Chatbot có thể trả lời các câu hỏi như:

- “Mã nhân viên 606028 là ai?”  
- “Phòng ban của Hoàng Ngọc Vy là gì?”  
- “Đặng Thị Thảo còn bao nhiêu ngày nghỉ phép?”  

Nguồn dữ liệu: **File Excel nội bộ**

---

## 📄 2. Tra Cứu Chính Sách Công Ty

Chatbot sử dụng tài liệu `VINAMILK.pdf` để trả lời:

- Chính sách nghỉ phép  
- Lương thưởng  
- Đào tạo nội bộ  
- Làm việc linh hoạt  
- Quy định công ty  
- Cơ cấu tổ chức  
- Văn hóa doanh nghiệp  

---

## 🥛 3. Giới Thiệu Sản Phẩm Vinamilk

Chatbot có thể cung cấp thông tin về:

- Sữa tươi Vinamilk  
- Dielac  
- Sure Prevent  
- Probi  
- Và các dòng sản phẩm khác  

Bao gồm:

- Thành phần  
- Công dụng  
- Đối tượng sử dụng  

---

## 🧠 Cách Hoạt Động

1. Người dùng nhập câu hỏi bằng tiếng Việt  
2. Chatbot xác định nguồn dữ liệu phù hợp:
   - Excel nội bộ  
   - PDF tài liệu công ty  
3. Sử dụng Vector Search (FAISS) để tìm nội dung liên quan  
4. LLM tạo câu trả lời tự nhiên và dễ hiểu  

---

## 📁 Cấu Trúc Thư Mục

```bash
Vinamilk-Chatbot/
│── veny/
│   └── giaodien.py
│── VINAMILK.pdf
│── employee_data.xlsx
│── README.md

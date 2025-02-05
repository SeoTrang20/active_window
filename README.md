Active window:
irm https://get.activated.win | iex

Lệnh này chạy trên PowerShell và có thể tải xuống và thực thi một script từ internet. Hãy phân tích từng phần:

📌 Giải thích từng phần
irm https://get.activated.win | iex
1. irm (Invoke-RestMethod)
irm là viết tắt của Invoke-RestMethod trong PowerShell.
Nó dùng để gửi yêu cầu HTTP đến một URL và lấy dữ liệu trả về.
Ở đây, nó tải nội dung từ https://get.activated.win.
2. | (Pipeline)
Dấu | (pipe) dùng để truyền dữ liệu từ lệnh irm sang lệnh iex.
3. iex (Invoke-Expression)
iex là viết tắt của Invoke-Expression.
Nó thực thi nội dung nhận được từ irm như một lệnh PowerShell.

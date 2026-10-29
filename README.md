# LCS-ED
Cho hai chuỗi X (độ dài m) và Y (độ dài n). Tìm dãy con chung dài nhất (LCS) và khoảng cách chỉnh sửa Levenshtein (số phép chèn, xóa, thay thế ít nhất để biến X thành Y).  - Giải thuật tối thiểu: vét cạn O(2^m·n), đệ quy có ghi nhớ (top-down), quy hoạch động O(mn), quy hoạch động tiết kiệm bộ nhớ O(min(m,n)). 

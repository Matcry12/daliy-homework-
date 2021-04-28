2.1: Khi merge cần có commit, vậy commit merge này có được log trên nhánh được merge vào không (nhánh đích: branch A)?
2.2
- 2.2: Khi checkout branch B từ branch A, khi mà branch A có commit 1, sau đó 1 thơi gian branch A có 2 commit 
- (commit 1 - commit 2), branch B có 3 commit (commit 1 - commit 3 - commit 4), thế nếu merge B vào A xong.
- Git log ở A, thứ tự xuất hiện các commit có phụ thuộc vào thời gian commit của commit 2, 3, 4 không?
- trả lời
- 2.1: khi merge vào thì commit merge được log trên nhánh được merge 
- 2.2: thứ tự xuất hiện các commit có phụ thuộc vào thời gian commit 

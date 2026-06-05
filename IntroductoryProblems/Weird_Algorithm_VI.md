# Weird Algorithm

## Đề bài

Xét một thuật toán nhận đầu vào là một số nguyên dương `n`.

- Nếu `n` là số chẵn, thuật toán chia `n` cho `2`.
- Nếu `n` là số lẻ, thuật toán nhân `n` với `3` rồi cộng thêm `1`.

Thuật toán tiếp tục lặp lại quá trình này cho đến khi `n` bằng `1`.

Ví dụ, với `n = 3`, dãy giá trị thu được là:

$$3 \rightarrow 10 \rightarrow 5 \rightarrow 16 \rightarrow 8 \rightarrow 4 \rightarrow 2 \rightarrow 1$$

Nhiệm vụ của bạn là mô phỏng quá trình thực hiện thuật toán với giá trị `n` đã cho.

## Input

- Dòng duy nhất của input chứa một số nguyên `n`.

## Output

- In ra trên một dòng tất cả các giá trị của `n` xuất hiện trong quá trình thực hiện thuật toán.

## Ràng buộc

- $1 \le n \le 10^6$

## Ví dụ

### Input
```text
3
```

### Output
```text
3 10 5 16 8 4 2 1
```

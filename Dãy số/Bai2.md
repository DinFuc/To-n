(a_n) : a_n = (\sqrt2 + 1)^n\ .\text{Chứng minh } a_n = \sqrt m + \sqrt{m - 1} \\  
\textbf{Giải}\\
\exists\ (p_n),\ (q_n)\ \text{thỏa }\ a_n = p_n + q_n\ \sqrt{2}\\ 
\text{Quy nạp : với n = 1 đúng }.\ \text{Giả sử đúng tới n = k :}\ a_k = p_k + q_k\ \sqrt{2}\\ 
\text{Ta chứng minh với n = k+1, thật vậy}\ (\sqrt{2} + 1)^(k + 1) = (\sqrt{2} + 1)^k\ (\sqrt{2} +1)  = (p_k + q_k\ \sqrt{2})(\sqrt{2} + 1) = (p_k + 2q_k) + (p_k + q_k)\sqrt{2}\\ 
\text{Từ đây, ta xét dãy }(p_n), (q_n) \text{ thỏa } 
\left\{ \begin{array}{cl} 
p_1 = q_1 = 1 \\ 
p_{n + 1} = p_n + 2q_n\\ 
q_{n+1} = p_n + q_n 
\end{array} \right.\\ 
\text{Ta chứng minh được }\ p_n, q_n \in \mathrm{Z}\\ \text{Mà }\ a_n = p_n + q_n \sqrt{2} = \sqrt{(p_n)^2} + \sqrt{2(q_n)^2}\\ \text{Ta có thêm }\ |(p_n)^2 - 2(q_n)^2|=1\\ 
\text{Ta có }
2u_0 - 1 = (-1)^2,\ 2u_1 - 1 = 1^2,\ 2u_2 - 1 = 5^2,\ 2u_3 - 1 = 19^2,\ 2u_4 - 1 = 71^2,...\\
\text{Xét dãy }
\left\{ \begin{array}{cl}
b_0 = -1, b_1 = 1 \\
b_n = 4b_{n-1}-b_{n-2}
\end{array} \right.\\
\text{Quy nạp ta chứng minh được }\ 2u_{n-1}-1=(b_n)^2

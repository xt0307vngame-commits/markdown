**Linear Regression**:

$$
h_\theta(x) = \theta_0 + \theta_1x
$$


**Cost Function**:

$$
\mathcal{J}(\theta_0, \theta_1) = \frac{1}{2m}\sum_{i=1}^{m}(h_\theta(x^{(i)}) - y^{(i)})^2
$$

Trong đó:
- $m$: số lượng mẫu huấn luyện
- $x^{(i)}$: giá trị đầu vào của mẫu thứ $i$
- $y^{(i)}$: giá trị thực tế của mẫu thứ $i$
- $h_\theta(x^{(i)})$: giá trị dự đoán của mô hình
- $\theta_0, \theta_1$: các tham số (weights) của mô hình


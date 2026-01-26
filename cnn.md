# Convolutional Neural Network

## Activate function

**ReLU**:

$$
f(x) = max(0, x)
$$

Graph:
- x < 0 -> 0
- x >= 0 -> x

#### ⚡ Leaky ReLU

$$
f(x) = 
\begin{cases}
x     & x > 0 \\
0.01x & x \le 0
\end{cases}
$$

## 🌊 Sigmoid

Syntax:

$$
f(x) = \frac{1}{1 + e^{-x}}
$$

## 🔥 Softmax

Syntax:

$$
f(x_i) = \frac{e^{x_i}}{\sum_j e^{x_j}}
$$


## 🔁 Tanh

Syntax:

$$
f(x) = \frac{e_x - e_{-x}}{e_x + e_{-x}}
$$
























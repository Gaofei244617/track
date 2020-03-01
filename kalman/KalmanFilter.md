# Kalman滤波

## 预测方程

### (1) $\hat{x}_t^- = F\hat{x}_{t-1} + Bu_t$

### (2) $\Sigma_t^- = F\Sigma_{t-1}F^T + Q$

## 修正方程

### (3) $K_t = \Sigma_t^-H^T(H\Sigma_t^-H^T + R)^{-1}$

### (4) $\hat{x}_t = \hat{x}_t^- + K(y_t - H\hat{x}_t^-)$

### (5) $\Sigma_t = (I - KH)\Sigma_t^-$

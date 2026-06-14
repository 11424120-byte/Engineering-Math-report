# Engineering-Math-report
report
# RLC Series Circuit Transient Response Analysis

本專案針對開關電源輸出濾波中常見的 \(RLC\) 串聯電路進行暫態響應分析與數據化求解。

## 1. 問題描述與參數設定

在 \(t = 0\) 時刻接入直流電源 \(u_s = 12\text{V}\)，電路參數與初始條件如下：

### 電路參數
*   **電阻 (\(R\))**：\(8\,\Omega\)
*   **電感 (\(L\))**：\(1\text{H}\)
*   **電容 (\(C\))**：\(0.25\text{F}\)
*   **激勵電壓 (\(u_s\))**：\(12\text{V}\) (直流)

### 初始條件
*   **電容初始電壓 \(u_c(0)\)**：\(0\text{V}\)
*   **電感初始電流 \(i_L(0)\)**：\(0\text{A}\)
